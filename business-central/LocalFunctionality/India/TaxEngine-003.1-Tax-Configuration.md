---
title: Tax Engine - Tax Configuration 02
description: Tax Engine - Tax Configuration
author: v-debapd
ms.service: dynamics365-business-central
ms.topic: article
ms.devlang: na
ms.tgt_pltfrm: na
ms.workload: na
ms.search.keywords: India, local, IN, English
ms.date: 10/01/2020
ms.author: v-debapd
ms.openlocfilehash: 13e2d6b6e520ee3d0f894f2b054ee18bd7a9c186
ms.sourcegitcommit: ddbb5cede750df1baba4b3eab8fbed6744b5b9d6
ms.translationtype: HT
ms.contentlocale: en-IN
ms.lasthandoff: 10/01/2020
ms.locfileid: "3948607"
---
# <a name="tax-engine---use-case-configuration"></a><span data-ttu-id="73b17-103">Tax Engine - Use Case Configuration</span><span class="sxs-lookup"><span data-stu-id="73b17-103">Tax Engine - Use Case Configuration</span></span>

[!INCLUDE[vnext_preview](../../includes/vnext_preview.md)]

<span data-ttu-id="73b17-104">This topic provides information about use case configuration.</span><span class="sxs-lookup"><span data-stu-id="73b17-104">This topic provides information about use case configuration.</span></span>

## <a name="use-cases"></a><span data-ttu-id="73b17-105">Use cases</span><span class="sxs-lookup"><span data-stu-id="73b17-105">Use cases</span></span>
<span data-ttu-id="73b17-106">Use case describes a business scenario, conditions which need to be met and event which will trigger the calculation of tax.</span><span class="sxs-lookup"><span data-stu-id="73b17-106">Use case describes a business scenario, conditions which need to be met and event which will trigger the calculation of tax.</span></span> <span data-ttu-id="73b17-107">A use case can be enabled or disabled as per the business need.</span><span class="sxs-lookup"><span data-stu-id="73b17-107">A use case can be enabled or disabled as per the business need.</span></span>  

<span data-ttu-id="73b17-108">Use Case consist of following stages for calculation:</span><span class="sxs-lookup"><span data-stu-id="73b17-108">Use Case consist of following stages for calculation:</span></span>

  - <span data-ttu-id="73b17-109">**Condition** :</span><span class="sxs-lookup"><span data-stu-id="73b17-109">**Condition** :</span></span>

    <span data-ttu-id="73b17-110">Condition which determine whether the use case should be executed or not.</span><span class="sxs-lookup"><span data-stu-id="73b17-110">Condition which determine whether the use case should be executed or not.</span></span>

    <span data-ttu-id="73b17-111">Example of Condition:</span><span class="sxs-lookup"><span data-stu-id="73b17-111">Example of Condition:</span></span>

     |<span data-ttu-id="73b17-112">Operator</span><span class="sxs-lookup"><span data-stu-id="73b17-112">Operator</span></span>|<span data-ttu-id="73b17-113">Value</span><span class="sxs-lookup"><span data-stu-id="73b17-113">Value</span></span>|<span data-ttu-id="73b17-114">Condition</span><span class="sxs-lookup"><span data-stu-id="73b17-114">Condition</span></span>|<span data-ttu-id="73b17-115">Value 2</span><span class="sxs-lookup"><span data-stu-id="73b17-115">Value 2</span></span>|
     |--------------------|-----------------------|-----------------|----------|  
     |    |<span data-ttu-id="73b17-116">"Applies-to Doc No."</span><span class="sxs-lookup"><span data-stu-id="73b17-116">"Applies-to Doc No."</span></span>|<span data-ttu-id="73b17-117">Not Equals</span><span class="sxs-lookup"><span data-stu-id="73b17-117">Not Equals</span></span>|<span data-ttu-id="73b17-118">''</span><span class="sxs-lookup"><span data-stu-id="73b17-118">''</span></span>
     |<span data-ttu-id="73b17-119">or</span><span class="sxs-lookup"><span data-stu-id="73b17-119">or</span></span>|<span data-ttu-id="73b17-120">"Applies-to ID"</span><span class="sxs-lookup"><span data-stu-id="73b17-120">"Applies-to ID"</span></span>|<span data-ttu-id="73b17-121">Not Equals</span><span class="sxs-lookup"><span data-stu-id="73b17-121">Not Equals</span></span>|<span data-ttu-id="73b17-122">''</span><span class="sxs-lookup"><span data-stu-id="73b17-122">''</span></span>
     |<span data-ttu-id="73b17-123">and</span><span class="sxs-lookup"><span data-stu-id="73b17-123">and</span></span>|<span data-ttu-id="73b17-124">"GST Vendor Type"</span><span class="sxs-lookup"><span data-stu-id="73b17-124">"GST Vendor Type"</span></span>|<span data-ttu-id="73b17-125">Equals</span><span class="sxs-lookup"><span data-stu-id="73b17-125">Equals</span></span>|<span data-ttu-id="73b17-126">'Unregistered'</span><span class="sxs-lookup"><span data-stu-id="73b17-126">'Unregistered'</span></span>
     |<span data-ttu-id="73b17-127">and</span><span class="sxs-lookup"><span data-stu-id="73b17-127">and</span></span>|<span data-ttu-id="73b17-128">"Account Type"</span><span class="sxs-lookup"><span data-stu-id="73b17-128">"Account Type"</span></span>|<span data-ttu-id="73b17-129">Equals</span><span class="sxs-lookup"><span data-stu-id="73b17-129">Equals</span></span>|<span data-ttu-id="73b17-130">'Vendor'</span><span class="sxs-lookup"><span data-stu-id="73b17-130">'Vendor'</span></span>
     |<span data-ttu-id="73b17-131">and</span><span class="sxs-lookup"><span data-stu-id="73b17-131">and</span></span>|<span data-ttu-id="73b17-132">"Document Type"</span><span class="sxs-lookup"><span data-stu-id="73b17-132">"Document Type"</span></span>|<span data-ttu-id="73b17-133">Equals</span><span class="sxs-lookup"><span data-stu-id="73b17-133">Equals</span></span>|<span data-ttu-id="73b17-134">'Invoice'</span><span class="sxs-lookup"><span data-stu-id="73b17-134">'Invoice'</span></span>
     |<span data-ttu-id="73b17-135">and</span><span class="sxs-lookup"><span data-stu-id="73b17-135">and</span></span>|<span data-ttu-id="73b17-136">"GST Bill-to/Buy-from State Code"</span><span class="sxs-lookup"><span data-stu-id="73b17-136">"GST Bill-to/Buy-from State Code"</span></span>|<span data-ttu-id="73b17-137">Equals</span><span class="sxs-lookup"><span data-stu-id="73b17-137">Equals</span></span>|<span data-ttu-id="73b17-138">'Location State Code'</span><span class="sxs-lookup"><span data-stu-id="73b17-138">'Location State Code'</span></span>
     |<span data-ttu-id="73b17-139">and</span><span class="sxs-lookup"><span data-stu-id="73b17-139">and</span></span>|<span data-ttu-id="73b17-140">"GST Group Code"</span><span class="sxs-lookup"><span data-stu-id="73b17-140">"GST Group Code"</span></span>|<span data-ttu-id="73b17-141">Not Equals</span><span class="sxs-lookup"><span data-stu-id="73b17-141">Not Equals</span></span>|<span data-ttu-id="73b17-142">''</span><span class="sxs-lookup"><span data-stu-id="73b17-142">''</span></span>
     |<span data-ttu-id="73b17-143">and</span><span class="sxs-lookup"><span data-stu-id="73b17-143">and</span></span>|<span data-ttu-id="73b17-144">"HSN/SAC Code"</span><span class="sxs-lookup"><span data-stu-id="73b17-144">"HSN/SAC Code"</span></span>|<span data-ttu-id="73b17-145">Not Equals</span><span class="sxs-lookup"><span data-stu-id="73b17-145">Not Equals</span></span>|<span data-ttu-id="73b17-146">''</span><span class="sxs-lookup"><span data-stu-id="73b17-146">''</span></span>
     |<span data-ttu-id="73b17-147">and</span><span class="sxs-lookup"><span data-stu-id="73b17-147">and</span></span>|<span data-ttu-id="73b17-148">"GST Reverse Charge"</span><span class="sxs-lookup"><span data-stu-id="73b17-148">"GST Reverse Charge"</span></span>|<span data-ttu-id="73b17-149">Equals</span><span class="sxs-lookup"><span data-stu-id="73b17-149">Equals</span></span>|<span data-ttu-id="73b17-150">'Yes'</span><span class="sxs-lookup"><span data-stu-id="73b17-150">'Yes'</span></span>


   - <span data-ttu-id="73b17-151">**Attribute Mapping** :</span><span class="sxs-lookup"><span data-stu-id="73b17-151">**Attribute Mapping** :</span></span>

     <span data-ttu-id="73b17-152">This is defined to map the required attributes with their source of value.</span><span class="sxs-lookup"><span data-stu-id="73b17-152">This is defined to map the required attributes with their source of value.</span></span>
     <span data-ttu-id="73b17-153">Example : In case, GST is to be calculated on Sales Line and value of field ‘Type’ on General Journal Line is ‘G/L Account’ then, HSN Code will flow from G/L Account table.</span><span class="sxs-lookup"><span data-stu-id="73b17-153">Example : In case, GST is to be calculated on Sales Line and value of field ‘Type’ on General Journal Line is ‘G/L Account’ then, HSN Code will flow from G/L Account table.</span></span>

   - <span data-ttu-id="73b17-154">**Rate Parameter Mapping** :</span><span class="sxs-lookup"><span data-stu-id="73b17-154">**Rate Parameter Mapping** :</span></span>

     <span data-ttu-id="73b17-155">Rate parameter needs to be mapped with their source, but this mapping will be done only for column types ‘Range’ and ‘Value’.</span><span class="sxs-lookup"><span data-stu-id="73b17-155">Rate parameter needs to be mapped with their source, but this mapping will be done only for column types ‘Range’ and ‘Value’.</span></span> <span data-ttu-id="73b17-156">If an applicable tax rate is found, then system will return ‘component percent’ defined for that tax rate.</span><span class="sxs-lookup"><span data-stu-id="73b17-156">If an applicable tax rate is found, then system will return ‘component percent’ defined for that tax rate.</span></span> <span data-ttu-id="73b17-157">Example:</span><span class="sxs-lookup"><span data-stu-id="73b17-157">Example:</span></span>

      |<span data-ttu-id="73b17-158">Type</span><span class="sxs-lookup"><span data-stu-id="73b17-158">Type</span></span>  |<span data-ttu-id="73b17-159">Description</span><span class="sxs-lookup"><span data-stu-id="73b17-159">Description</span></span>  |
      |---------|---------|
      |<span data-ttu-id="73b17-160">**Date**</span><span class="sxs-lookup"><span data-stu-id="73b17-160">**Date**</span></span>|<span data-ttu-id="73b17-161">This column will be mapped with a posting date of sales header and the system will analyse whether the posting date falls within the ‘Date from’ to ‘Date To’ range.</span><span class="sxs-lookup"><span data-stu-id="73b17-161">This column will be mapped with posting date of sales header and system will analyze whether the posting date comes in the range of ‘Date from’ and ‘Date To’.</span></span>|
      |<span data-ttu-id="73b17-162">**From State**</span><span class="sxs-lookup"><span data-stu-id="73b17-162">**From State**</span></span>|<span data-ttu-id="73b17-163">In case of sales, parameter 'From State' needs to be mapped with state of location code.</span><span class="sxs-lookup"><span data-stu-id="73b17-163">In case of sales, parameter 'From State' needs to be mapped with state of location code.</span></span>|
      |<span data-ttu-id="73b17-164">**To State**</span><span class="sxs-lookup"><span data-stu-id="73b17-164">**To State**</span></span>|<span data-ttu-id="73b17-165">In case of Sales, parameter 'To State' needs to be mapped with state of customer code.</span><span class="sxs-lookup"><span data-stu-id="73b17-165">In case of Sales, parameter 'To State' needs to be mapped with state of customer code.</span></span>|


   - <span data-ttu-id="73b17-166">**Use Case Variables** :</span><span class="sxs-lookup"><span data-stu-id="73b17-166">**Use Case Variables** :</span></span>

     <span data-ttu-id="73b17-167">Variables can be used at the time of computation of an intermediate value or defining validations in a use case.</span><span class="sxs-lookup"><span data-stu-id="73b17-167">Variables can be used at the time of computation of an intermediate value or defining validations in a use case.</span></span> <span data-ttu-id="73b17-168">Example: showing alert message on tax execution.</span><span class="sxs-lookup"><span data-stu-id="73b17-168">Example: showing alert message on tax execution.</span></span>


  - <span data-ttu-id="73b17-169">**Computation Script** :</span><span class="sxs-lookup"><span data-stu-id="73b17-169">**Computation Script** :</span></span>

     <span data-ttu-id="73b17-170">This is an optional step, which will be used to store values in variables.</span><span class="sxs-lookup"><span data-stu-id="73b17-170">This is an optional step, which will be used to store values in variables.</span></span>
     <span data-ttu-id="73b17-171">Example: storing value of TDS Amount and adding INR 1000 freight to get the final amount.</span><span class="sxs-lookup"><span data-stu-id="73b17-171">Example: storing value of TDS Amount and adding INR 1000 freight to get the final amount.</span></span>


   - <span data-ttu-id="73b17-172">**Component Formula** :</span><span class="sxs-lookup"><span data-stu-id="73b17-172">**Component Formula** :</span></span>

     <span data-ttu-id="73b17-173">Define ‘Component formula’ for the components which are specific to the use case.</span><span class="sxs-lookup"><span data-stu-id="73b17-173">Define ‘Component formula’ for the components which are specific to the use case.</span></span> <span data-ttu-id="73b17-174">Example: CGST = {“Line Amount” from “Sales Line”} \* {CGST %} /100</span><span class="sxs-lookup"><span data-stu-id="73b17-174">Example: CGST = {“Line Amount” from “Sales Line”} \* {CGST %} /100</span></span>


  - <span data-ttu-id="73b17-175">**Use Case Posting** :</span><span class="sxs-lookup"><span data-stu-id="73b17-175">**Use Case Posting** :</span></span>

    <span data-ttu-id="73b17-176">There is a posting entity where the 'G/L Accounts' are configured for the specific 'tax type'.</span><span class="sxs-lookup"><span data-stu-id="73b17-176">There is a posting entity where the 'G/L Accounts' are configured for the specific 'tax type'.</span></span> <span data-ttu-id="73b17-177">Based on the filters applied on the posting entity, tax engine points to the record from which components can be mapped to posting accounts.</span><span class="sxs-lookup"><span data-stu-id="73b17-177">Based on the filters applied on the posting entity, tax engine points to the record from which components can be mapped to posting accounts.</span></span> <span data-ttu-id="73b17-178">In case of reverse charge, same component is adjusted with its payable or receivable account.</span><span class="sxs-lookup"><span data-stu-id="73b17-178">In case of reverse charge, same component is adjusted with its payable or receivable account.</span></span> <span data-ttu-id="73b17-179">Configuration will have “Reverse Charge” flag as true and account can be mapped for same to “Reverse Charge G/L Field Name”.</span><span class="sxs-lookup"><span data-stu-id="73b17-179">Configuration will have “Reverse Charge” flag as true and account can be mapped for same to “Reverse Charge G/L Field Name”.</span></span>


  - <span data-ttu-id="73b17-180">**Tax Ledger Mapping** :</span><span class="sxs-lookup"><span data-stu-id="73b17-180">**Tax Ledger Mapping** :</span></span>

    <span data-ttu-id="73b17-181">Calculated tax, which is an output of a use case needs to be mapped to a tax ledger table.</span><span class="sxs-lookup"><span data-stu-id="73b17-181">Calculated tax, which is an output of a use case needs to be mapped to a tax ledger table.</span></span> <span data-ttu-id="73b17-182">Example: On posting of general ledger entry for GST, there will be a new GST Entry created as a tax ledger for the posted transaction.</span><span class="sxs-lookup"><span data-stu-id="73b17-182">Example: On posting of general ledger entry for GST, there will be a new GST Entry created as a tax ledger for the posted transaction.</span></span>


## <a name="how-to-check-tax-information-for-a-transaction"></a><span data-ttu-id="73b17-183">How to check tax information for a transaction</span><span class="sxs-lookup"><span data-stu-id="73b17-183">How to check tax information for a transaction</span></span>

<span data-ttu-id="73b17-184">There are two fact boxes available on transaction page to view calculated tax</span><span class="sxs-lookup"><span data-stu-id="73b17-184">There are two fact boxes available on transaction page to view calculated tax</span></span>

- <span data-ttu-id="73b17-185">Tax Information</span><span class="sxs-lookup"><span data-stu-id="73b17-185">Tax Information</span></span> 
- <span data-ttu-id="73b17-186">Tax Component</span><span class="sxs-lookup"><span data-stu-id="73b17-186">Tax Component</span></span>

<span data-ttu-id="73b17-187">Statistics Page, will show the tax information in Tax Summary Tab.</span><span class="sxs-lookup"><span data-stu-id="73b17-187">Statistics Page, will show the tax information in Tax Summary Tab.</span></span>









































