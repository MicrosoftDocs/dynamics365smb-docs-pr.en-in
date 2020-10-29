---
title: Tax Engine - Design Consideration
description: Tax Engine - Design Consideration
author: v-debapd
ms.service: dynamics365-business-central
ms.topic: article
ms.devlang: na
ms.tgt_pltfrm: na
ms.workload: na
ms.search.keywords: India, local, IN, English
ms.date: 10/01/2020
ms.author: v-debapd
ms.openlocfilehash: e0342e7d8bc2af3c94d1172e2319b2824b6ba419
ms.sourcegitcommit: ddbb5cede750df1baba4b3eab8fbed6744b5b9d6
ms.translationtype: HT
ms.contentlocale: en-IN
ms.lasthandoff: 10/01/2020
ms.locfileid: "3948597"
---
# <a name="tax-engine---design-consideration"></a><span data-ttu-id="401d0-103">Tax Engine - Design Consideration</span><span class="sxs-lookup"><span data-stu-id="401d0-103">Tax Engine - Design Consideration</span></span>

[!INCLUDE[vnext_preview](../../includes/vnext_preview.md)]

<span data-ttu-id="401d0-104">This section contains the factors that shall be considered while configuring Taxes using tax engine.</span><span class="sxs-lookup"><span data-stu-id="401d0-104">This section contains the factors that shall be considered while configuring Taxes using tax engine.</span></span>

## <a name="tax-type"></a><span data-ttu-id="401d0-105">Tax type</span><span class="sxs-lookup"><span data-stu-id="401d0-105">Tax type</span></span>

<span data-ttu-id="401d0-106">A new tax type should be created if it has unique attributes which are used in definition of conditions and computation logic.</span><span class="sxs-lookup"><span data-stu-id="401d0-106">A new tax type should be created if it has unique attributes which are used in definition of conditions and computation logic.</span></span> <span data-ttu-id="401d0-107">For example, GST and TDS are defined as different tax types.</span><span class="sxs-lookup"><span data-stu-id="401d0-107">For example, GST and TDS are defined as different tax types.</span></span> 

## <a name="tax-attributes"></a><span data-ttu-id="401d0-108">Tax attributes</span><span class="sxs-lookup"><span data-stu-id="401d0-108">Tax attributes</span></span>
 - <span data-ttu-id="401d0-109">When to create an Attribute as Generic?</span><span class="sxs-lookup"><span data-stu-id="401d0-109">When to create an Attribute as Generic?</span></span>
 
   <span data-ttu-id="401d0-110">Generic attributes are used in the same way as item attributes are managed in Business Central.</span><span class="sxs-lookup"><span data-stu-id="401d0-110">Generic attributes are used in the same way as item attributes are managed in Business Central.</span></span> <span data-ttu-id="401d0-111">If the attribute is not linked to a field in an existing table then it is generic in nature.</span><span class="sxs-lookup"><span data-stu-id="401d0-111">If the attribute is not linked to a field in an existing table then it is generic in nature.</span></span>
 - <span data-ttu-id="401d0-112">When to map a tax attribute with a table field?</span><span class="sxs-lookup"><span data-stu-id="401d0-112">When to map a tax attribute with a table field?</span></span>
 
   <span data-ttu-id="401d0-113">In case field is already available in the table which is being mapped then it can be linked to that attribute.</span><span class="sxs-lookup"><span data-stu-id="401d0-113">In case field is already available in the table which is being mapped then it can be linked to that attribute.</span></span> <span data-ttu-id="401d0-114">This means that field data will be used as attribute value.</span><span class="sxs-lookup"><span data-stu-id="401d0-114">This means that field data will be used as attribute value.</span></span> 

## <a name="generic-tax-rate-setup"></a><span data-ttu-id="401d0-115">Generic tax rate setup</span><span class="sxs-lookup"><span data-stu-id="401d0-115">Generic tax rate setup</span></span>
- <span data-ttu-id="401d0-116">Rate Setup for Different Tax Type</span><span class="sxs-lookup"><span data-stu-id="401d0-116">Rate Setup for Different Tax Type</span></span>
  
  <span data-ttu-id="401d0-117">Tax Rate Setup of each tax type is configured separately but the User Interface is same.</span><span class="sxs-lookup"><span data-stu-id="401d0-117">Tax Rate Setup of each tax type is configured separately but the User Interface is same.</span></span> <span data-ttu-id="401d0-118">Fields in tax rate setup are dynamic and based on the tax rate column setup.</span><span class="sxs-lookup"><span data-stu-id="401d0-118">Fields in tax rate setup are dynamic and based on the tax rate column setup.</span></span> <span data-ttu-id="401d0-119">User can define what columns are needed for a tax rate setup.</span><span class="sxs-lookup"><span data-stu-id="401d0-119">User can define what columns are needed for a tax rate setup.</span></span> <span data-ttu-id="401d0-120">For example ‘GST' tax type would require ‘HSN Code’ where as 'TDS' tax type is not dependent on HSN code.</span><span class="sxs-lookup"><span data-stu-id="401d0-120">For example ‘GST' tax type would require ‘HSN Code’ where as 'TDS' tax type is not dependent on HSN code.</span></span>

- <span data-ttu-id="401d0-121">Generic Table for Tax Rate Setup</span><span class="sxs-lookup"><span data-stu-id="401d0-121">Generic Table for Tax Rate Setup</span></span>
  
  <span data-ttu-id="401d0-122">Use generic table for tax rate setup for all Tax types.</span><span class="sxs-lookup"><span data-stu-id="401d0-122">Use generic table for tax rate setup for all Tax types.</span></span> <span data-ttu-id="401d0-123">It enables to handling any new components introduced by government related to the tax rate.</span><span class="sxs-lookup"><span data-stu-id="401d0-123">It enables to handling any new components introduced by government related to the tax rate.</span></span>
  
  <span data-ttu-id="401d0-124">Example: If there is a regulatory change in which ‘Threshold Limit’ is removed then it can be managed by removing it from the tax rate column setup.</span><span class="sxs-lookup"><span data-stu-id="401d0-124">Example: If there is a regulatory change in which ‘Threshold Limit’ is removed then it can be managed by removing it from the tax rate column setup.</span></span>

## <a name="generic-metadata"></a><span data-ttu-id="401d0-125">Generic metadata</span><span class="sxs-lookup"><span data-stu-id="401d0-125">Generic metadata</span></span>
- <span data-ttu-id="401d0-126">Tax Transaction Values Data pertaining to tax calculation regarding a said transaction is stored in a common table.</span><span class="sxs-lookup"><span data-stu-id="401d0-126">Tax Transaction Values Data pertaining to tax calculation regarding a said transaction is stored in a common table.</span></span> <span data-ttu-id="401d0-127">If the transaction record is deleted then related tax transaction value also gets deleted.</span><span class="sxs-lookup"><span data-stu-id="401d0-127">If the transaction record is deleted then related tax transaction value also gets deleted.</span></span>
  
  <span data-ttu-id="401d0-128">Example: If transaction involves ‘Purchase Line’ then all information related to tax calculation will be stored in tax transaction value.</span><span class="sxs-lookup"><span data-stu-id="401d0-128">Example: If transaction involves ‘Purchase Line’ then all information related to tax calculation will be stored in tax transaction value.</span></span> <span data-ttu-id="401d0-129">If purchase line is deleted, then tax transaction value record related to that purchase line will also be deleted.</span><span class="sxs-lookup"><span data-stu-id="401d0-129">If purchase line is deleted, then tax transaction value record related to that purchase line will also be deleted.</span></span>
  
  <span data-ttu-id="401d0-130">Information stored in ‘tax transaction value’ is shown in the ‘tax information’ and ‘tax component’ fact boxes related to that transaction.</span><span class="sxs-lookup"><span data-stu-id="401d0-130">Information stored in ‘tax transaction value’ is shown in the ‘tax information’ and ‘tax component’ fact boxes related to that transaction.</span></span> <span data-ttu-id="401d0-131">Attributes which have “visible on interface” as true will be visible in the fact box.</span><span class="sxs-lookup"><span data-stu-id="401d0-131">Attributes which have “visible on interface” as true will be visible in the fact box.</span></span>

 - <span data-ttu-id="401d0-132">Tax Rate Configuration Value</span><span class="sxs-lookup"><span data-stu-id="401d0-132">Tax Rate Configuration Value</span></span>
 
  <span data-ttu-id="401d0-133">This table contains information of tax rate setup.</span><span class="sxs-lookup"><span data-stu-id="401d0-133">This table contains information of tax rate setup.</span></span> <span data-ttu-id="401d0-134">Tax engine uses common tax rate setup for different types of taxes.</span><span class="sxs-lookup"><span data-stu-id="401d0-134">Tax engine uses common tax rate setup for different types of taxes.</span></span>

## <a name="use-case-execution"></a><span data-ttu-id="401d0-135">Use case execution</span><span class="sxs-lookup"><span data-stu-id="401d0-135">Use case execution</span></span>

- <span data-ttu-id="401d0-136">Only Child Use Cases are Executed for output</span><span class="sxs-lookup"><span data-stu-id="401d0-136">Only Child Use Cases are Executed for output</span></span>

  <span data-ttu-id="401d0-137">There can be a parent child relation between use cases.</span><span class="sxs-lookup"><span data-stu-id="401d0-137">There can be a parent child relation between use cases.</span></span> <span data-ttu-id="401d0-138">Parent use cases are used for defining attribute mapping which is common for one or more use cases.</span><span class="sxs-lookup"><span data-stu-id="401d0-138">Parent use cases are used for defining attribute mapping which is common for one or more use cases.</span></span>
  
  <span data-ttu-id="401d0-139">A child use case is mapped in the use case tree.</span><span class="sxs-lookup"><span data-stu-id="401d0-139">A child use case is mapped in the use case tree.</span></span> <span data-ttu-id="401d0-140">Before execution of the use case, conditions of use case tree should be passed.</span><span class="sxs-lookup"><span data-stu-id="401d0-140">Before execution of the use case, conditions of use case tree should be passed.</span></span>
  
- <span data-ttu-id="401d0-141">Sequencing of Use Case Execution</span><span class="sxs-lookup"><span data-stu-id="401d0-141">Sequencing of Use Case Execution</span></span>

  <span data-ttu-id="401d0-142">The sequence of use case execution depends on the sequencing defined in the use case tree.</span><span class="sxs-lookup"><span data-stu-id="401d0-142">The sequence of use case execution depends on the sequencing defined in the use case tree.</span></span>

- <span data-ttu-id="401d0-143">Execution of multiple Use Cases for a tax type</span><span class="sxs-lookup"><span data-stu-id="401d0-143">Execution of multiple Use Cases for a tax type</span></span>

  <span data-ttu-id="401d0-144">If there are more than one use cases for a tax type, then execution will be done sequentially which means that second use case will execute only after completion of first use case.</span><span class="sxs-lookup"><span data-stu-id="401d0-144">If there are more than one use cases for a tax type, then execution will be done sequentially which means that second use case will execute only after completion of first use case.</span></span>

- <span data-ttu-id="401d0-145">Execution Flow of Tax Engine</span><span class="sxs-lookup"><span data-stu-id="401d0-145">Execution Flow of Tax Engine</span></span>

  ![img](image/executionflow.png)

## <a name="deployment"></a><span data-ttu-id="401d0-147">Deployment</span><span class="sxs-lookup"><span data-stu-id="401d0-147">Deployment</span></span>

- <span data-ttu-id="401d0-148">Configuration Files</span><span class="sxs-lookup"><span data-stu-id="401d0-148">Configuration Files</span></span>
 
  <span data-ttu-id="401d0-149">Every use case configured in tax engine is a Json file which can be exported and imported from a Business Central tenant.</span><span class="sxs-lookup"><span data-stu-id="401d0-149">Every use case configured in tax engine is a Json file which can be exported and imported from a Business Central tenant.</span></span> <span data-ttu-id="401d0-150">These configurations are deployed individually for each company.</span><span class="sxs-lookup"><span data-stu-id="401d0-150">These configurations are deployed individually for each company.</span></span>

- <span data-ttu-id="401d0-151">Deployment of Configuration</span><span class="sxs-lookup"><span data-stu-id="401d0-151">Deployment of Configuration</span></span>

  <span data-ttu-id="401d0-152">Default configurations that are provided in the system will be available as part of demo data.</span><span class="sxs-lookup"><span data-stu-id="401d0-152">Default configurations that are provided in the system will be available as part of demo data.</span></span> <span data-ttu-id="401d0-153">In case if a new production company is created then the configuration can be imported from assisted setup, where system will pick the json based on the function of a codeunit.</span><span class="sxs-lookup"><span data-stu-id="401d0-153">In case if a new production company is created then the configuration can be imported from assisted setup, where system will pick the json based on the function of a codeunit.</span></span> <span data-ttu-id="401d0-154">Json for standard configuration is available in a translation file for there related extensions like GST, TDS and TCS which are updated when the codeunit function is called.</span><span class="sxs-lookup"><span data-stu-id="401d0-154">Json for standard configuration is available in a translation file for there related extensions like GST, TDS and TCS which are updated when the codeunit function is called.</span></span> <span data-ttu-id="401d0-155">In case users have changed any standard configuration or created a new configuration then they can use the export and import function available on tax types and use cases page.</span><span class="sxs-lookup"><span data-stu-id="401d0-155">In case users have changed any standard configuration or created a new configuration then they can use the export and import function available on tax types and use cases page.</span></span>

- <span data-ttu-id="401d0-156">Change in Configuration</span><span class="sxs-lookup"><span data-stu-id="401d0-156">Change in Configuration</span></span>

  <span data-ttu-id="401d0-157">If any update is done on a use case then the version of the use case will be higher than the one which is already deployed.</span><span class="sxs-lookup"><span data-stu-id="401d0-157">If any update is done on a use case then the version of the use case will be higher than the one which is already deployed.</span></span> <span data-ttu-id="401d0-158">System will archive the old one and update the new use case based on the jeson.</span><span class="sxs-lookup"><span data-stu-id="401d0-158">System will archive the old one and update the new use case based on the jeson.</span></span>

   
- <span data-ttu-id="401d0-159">Change in Configuration by user</span><span class="sxs-lookup"><span data-stu-id="401d0-159">Change in Configuration by user</span></span>

  <span data-ttu-id="401d0-160">In case of any change done in any use case to fix a bug or handle regulatory change, the updated configuration should be imported again in each company individually.</span><span class="sxs-lookup"><span data-stu-id="401d0-160">In case of any change done in any use case to fix a bug or handle regulatory change, the updated configuration should be imported again in each company individually.</span></span>

- <span data-ttu-id="401d0-161">Version Management</span><span class="sxs-lookup"><span data-stu-id="401d0-161">Version Management</span></span>

  <span data-ttu-id="401d0-162">In case of any change done in any use case the current active version of the use case is archived and new use case version becomes active.</span><span class="sxs-lookup"><span data-stu-id="401d0-162">In case of any change done in any use case the current active version of the use case is archived and new use case version becomes active.</span></span>

## <a name="enabling-and-disabling-configuration"></a><span data-ttu-id="401d0-163">Enabling and disabling configuration</span><span class="sxs-lookup"><span data-stu-id="401d0-163">Enabling and disabling configuration</span></span>

- <span data-ttu-id="401d0-164">Enable or Disable Use Case</span><span class="sxs-lookup"><span data-stu-id="401d0-164">Enable or Disable Use Case</span></span>

  <span data-ttu-id="401d0-165">By default, a Use case is enabled.</span><span class="sxs-lookup"><span data-stu-id="401d0-165">By default, a Use case is enabled.</span></span> <span data-ttu-id="401d0-166">If a use case is not applicable, then it can be disabled and that use case will not get executed.</span><span class="sxs-lookup"><span data-stu-id="401d0-166">If a use case is not applicable, then it can be disabled and that use case will not get executed.</span></span>
