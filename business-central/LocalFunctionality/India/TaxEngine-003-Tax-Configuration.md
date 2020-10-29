---
title: Tax Engine - Tax Configuration 01
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
ms.openlocfilehash: 0c6f110e26b66131303c35ade9b51a5cbabd4810
ms.sourcegitcommit: ddbb5cede750df1baba4b3eab8fbed6744b5b9d6
ms.translationtype: HT
ms.contentlocale: en-IN
ms.lasthandoff: 10/01/2020
ms.locfileid: "3948600"
---
# <a name="tax-engine---configuration-of-tax-type-and-tax-rates"></a><span data-ttu-id="c2d66-103">Tax Engine - Configuration of Tax Type and Tax Rates</span><span class="sxs-lookup"><span data-stu-id="c2d66-103">Tax Engine - Configuration of Tax Type and Tax Rates</span></span>

[!INCLUDE[vnext_preview](../../includes/vnext_preview.md)]

<span data-ttu-id="c2d66-104">This topic provides information about tax types that a tax authority can levy in the same jurisdiction or a different jurisdiction.</span><span class="sxs-lookup"><span data-stu-id="c2d66-104">This topic provides information about tax types that a tax authority can levy in the same jurisdiction or a different jurisdiction.</span></span> <span data-ttu-id="c2d66-105">Calculation and posting of this type of tax to G/L Accounts.</span><span class="sxs-lookup"><span data-stu-id="c2d66-105">Calculation and posting of this type of tax to G/L Accounts.</span></span>

## <a name="tax-types"></a><span data-ttu-id="c2d66-106">Tax types</span><span class="sxs-lookup"><span data-stu-id="c2d66-106">Tax types</span></span>

<span data-ttu-id="c2d66-107">There can be various type of taxes applicable for a company.</span><span class="sxs-lookup"><span data-stu-id="c2d66-107">There can be various type of taxes applicable for a company.</span></span> <span data-ttu-id="c2d66-108">Examples:</span><span class="sxs-lookup"><span data-stu-id="c2d66-108">Examples:</span></span>

- <span data-ttu-id="c2d66-109">**GST** : Goods and Services Tax.</span><span class="sxs-lookup"><span data-stu-id="c2d66-109">**GST** : Goods and Services Tax.</span></span>
- <span data-ttu-id="c2d66-110">**TDS** : Tax deducted at source.</span><span class="sxs-lookup"><span data-stu-id="c2d66-110">**TDS** : Tax deducted at source.</span></span>
- <span data-ttu-id="c2d66-111">**TCS** : Tax collected at source.</span><span class="sxs-lookup"><span data-stu-id="c2d66-111">**TCS** : Tax collected at source.</span></span>
- <span data-ttu-id="c2d66-112">**WHT** : Withholding Tax.</span><span class="sxs-lookup"><span data-stu-id="c2d66-112">**WHT** : Withholding Tax.</span></span>


## <a name="tax-entities"></a><span data-ttu-id="c2d66-113">Tax entities</span><span class="sxs-lookup"><span data-stu-id="c2d66-113">Tax entities</span></span>

<span data-ttu-id="c2d66-114">These are tables which are specific to a Tax Type.</span><span class="sxs-lookup"><span data-stu-id="c2d66-114">These are tables which are specific to a Tax Type.</span></span> <span data-ttu-id="c2d66-115">This is defined to restrict the list of tables in a lookup.</span><span class="sxs-lookup"><span data-stu-id="c2d66-115">This is defined to restrict the list of tables in a lookup.</span></span> <span data-ttu-id="c2d66-116">A Tax Entity can be of type ‘Master’ or ‘Transaction’.</span><span class="sxs-lookup"><span data-stu-id="c2d66-116">A Tax Entity can be of type ‘Master’ or ‘Transaction’.</span></span>

- <span data-ttu-id="c2d66-117">Example of Master: Customer, Vendor, Location, Item etc.</span><span class="sxs-lookup"><span data-stu-id="c2d66-117">Example of Master: Customer, Vendor, Location, Item etc.</span></span>
- <span data-ttu-id="c2d66-118">Example of Transaction: Purchase Line, Sales Line, Transfer Line, Gen.</span><span class="sxs-lookup"><span data-stu-id="c2d66-118">Example of Transaction: Purchase Line, Sales Line, Transfer Line, Gen.</span></span> <span data-ttu-id="c2d66-119">Journal Line etc.</span><span class="sxs-lookup"><span data-stu-id="c2d66-119">Journal Line etc.</span></span>


## <a name="input-parameters"></a><span data-ttu-id="c2d66-120">Input parameters</span><span class="sxs-lookup"><span data-stu-id="c2d66-120">Input parameters</span></span>

<span data-ttu-id="c2d66-121">Attributes of tax type that can be used as a parameter in tax calculation or reporting.</span><span class="sxs-lookup"><span data-stu-id="c2d66-121">Attributes of tax type that can be used as a parameter in tax calculation or reporting.</span></span> <span data-ttu-id="c2d66-122">For example :</span><span class="sxs-lookup"><span data-stu-id="c2d66-122">For example :</span></span>

<span data-ttu-id="c2d66-123">**HSN Code** : It is a parameter to find GST rate of an item and it can also be used as a parameter for filing of online tax to the government.</span><span class="sxs-lookup"><span data-stu-id="c2d66-123">**HSN Code** : It is a parameter to find GST rate of an item and it can also be used as a parameter for filing of online tax to the government.</span></span>

<span data-ttu-id="c2d66-124">An attribute can be either linked to a field of an existing table or can be mapped to an existing table as an attribute.</span><span class="sxs-lookup"><span data-stu-id="c2d66-124">An attribute can be either linked to a field of an existing table or can be mapped to an existing table as an attribute.</span></span> <span data-ttu-id="c2d66-125">(In the same way as Item Attributes are define in item table)</span><span class="sxs-lookup"><span data-stu-id="c2d66-125">(In the same way as Item Attributes are define in item table)</span></span>

<span data-ttu-id="c2d66-126">Header contains following information</span><span class="sxs-lookup"><span data-stu-id="c2d66-126">Header contains following information</span></span>  

- <span data-ttu-id="c2d66-127">Attribute Name.</span><span class="sxs-lookup"><span data-stu-id="c2d66-127">Attribute Name.</span></span>
- <span data-ttu-id="c2d66-128">Datatype of Attribute.</span><span class="sxs-lookup"><span data-stu-id="c2d66-128">Datatype of Attribute.</span></span>
- <span data-ttu-id="c2d66-129">Visible on Interface (Yes/No)</span><span class="sxs-lookup"><span data-stu-id="c2d66-129">Visible on Interface (Yes/No)</span></span> 
- <span data-ttu-id="c2d66-130">Blocked (Yes/No)</span><span class="sxs-lookup"><span data-stu-id="c2d66-130">Blocked (Yes/No)</span></span>

<span data-ttu-id="c2d66-131">In case the attribute needs to be mapped to a field of a table, then the field needs to be entered in 'Mapping Field Name' else it will be created as an attribute for that entity record.</span><span class="sxs-lookup"><span data-stu-id="c2d66-131">In case the attribute needs to be mapped to a field of a table, then the field needs to be entered in 'Mapping Field Name' else it will be created as an attribute for that entity record.</span></span> <span data-ttu-id="c2d66-132">Attribute values can be added or viewed in case the type of attribute is an ‘option’.</span><span class="sxs-lookup"><span data-stu-id="c2d66-132">Attribute values can be added or viewed in case the type of attribute is an ‘option’.</span></span>


## <a name="component"></a><span data-ttu-id="c2d66-133">Component</span><span class="sxs-lookup"><span data-stu-id="c2d66-133">Component</span></span>

<span data-ttu-id="c2d66-134">Certain tax type may have components that need to be computed as part of tax calculation.</span><span class="sxs-lookup"><span data-stu-id="c2d66-134">Certain tax type may have components that need to be computed as part of tax calculation.</span></span> <span data-ttu-id="c2d66-135">Following are some examples of tax components:</span><span class="sxs-lookup"><span data-stu-id="c2d66-135">Following are some examples of tax components:</span></span>

- <span data-ttu-id="c2d66-136">CGST: is a component of Tax Type GST.</span><span class="sxs-lookup"><span data-stu-id="c2d66-136">CGST: is a component of Tax Type GST.</span></span>
- <span data-ttu-id="c2d66-137">SGST: is a component of Tax Type GST.</span><span class="sxs-lookup"><span data-stu-id="c2d66-137">SGST: is a component of Tax Type GST.</span></span>
- <span data-ttu-id="c2d66-138">TDS: is a component of Tax Type TDS.</span><span class="sxs-lookup"><span data-stu-id="c2d66-138">TDS: is a component of Tax Type TDS.</span></span>
- <span data-ttu-id="c2d66-139">E-Cess: is a component of Tax Type TDS.</span><span class="sxs-lookup"><span data-stu-id="c2d66-139">E-Cess: is a component of Tax Type TDS.</span></span>


## <a name="rate-setup"></a><span data-ttu-id="c2d66-140">Rate setup</span><span class="sxs-lookup"><span data-stu-id="c2d66-140">Rate setup</span></span>
<span data-ttu-id="c2d66-141">For each tax type, parameters are defined basis which rate is specified in the setup.</span><span class="sxs-lookup"><span data-stu-id="c2d66-141">For each tax type, parameters are defined basis which rate is specified in the setup.</span></span>

<span data-ttu-id="c2d66-142">These Parameters can be of following types:</span><span class="sxs-lookup"><span data-stu-id="c2d66-142">These Parameters can be of following types:</span></span>

|<span data-ttu-id="c2d66-143">Type</span><span class="sxs-lookup"><span data-stu-id="c2d66-143">Type</span></span>  |<span data-ttu-id="c2d66-144">Description</span><span class="sxs-lookup"><span data-stu-id="c2d66-144">Description</span></span>  |
|---------|---------|
|<span data-ttu-id="c2d66-145">**Tax Attributes**</span><span class="sxs-lookup"><span data-stu-id="c2d66-145">**Tax Attributes**</span></span>|<span data-ttu-id="c2d66-146">When a tax attribute is used as a parameter for tax rate configuration.</span><span class="sxs-lookup"><span data-stu-id="c2d66-146">When a tax attribute is used as a parameter for tax rate configuration.</span></span> <span data-ttu-id="c2d66-147">(example – HSN Code, GST Group Code etc.)</span><span class="sxs-lookup"><span data-stu-id="c2d66-147">(example – HSN Code, GST Group Code etc.)</span></span>|
|<span data-ttu-id="c2d66-148">**Value**</span><span class="sxs-lookup"><span data-stu-id="c2d66-148">**Value**</span></span>|<span data-ttu-id="c2d66-149">This will be used where we want to use a value in the tax rate configuration that is not mapped with a table as an attribute.</span><span class="sxs-lookup"><span data-stu-id="c2d66-149">This will be used where we want to use a value in the tax rate configuration that is not mapped with a table as an attribute.</span></span> <span data-ttu-id="c2d66-150">(example – From State, To State etc.)</span><span class="sxs-lookup"><span data-stu-id="c2d66-150">(example – From State, To State etc.)</span></span>|
|<span data-ttu-id="c2d66-151">**Range**</span><span class="sxs-lookup"><span data-stu-id="c2d66-151">**Range**</span></span>|<span data-ttu-id="c2d66-152">This is used to define slabs in a tax rate setup, such as ‘Date from’ and ‘Date To’.</span><span class="sxs-lookup"><span data-stu-id="c2d66-152">This is used to define slabs in a tax rate setup, such as ‘Date from’ and ‘Date To’.</span></span> <span data-ttu-id="c2d66-153">When tax type is defined as 'range', system will create two parameters in tax rate configuration.</span><span class="sxs-lookup"><span data-stu-id="c2d66-153">When tax type is defined as 'range', system will create two parameters in tax rate configuration.</span></span>|
|<span data-ttu-id="c2d66-154">**Component**</span><span class="sxs-lookup"><span data-stu-id="c2d66-154">**Component**</span></span>|<span data-ttu-id="c2d66-155">Components are used to define distribution of tax calculated.</span><span class="sxs-lookup"><span data-stu-id="c2d66-155">Components are used to define distribution of tax calculated.</span></span> <span data-ttu-id="c2d66-156">For example, 50% of GST will go to CGST and remaining will be SGST.</span><span class="sxs-lookup"><span data-stu-id="c2d66-156">For example, 50% of GST will go to CGST and remaining will be SGST.</span></span>|
|<span data-ttu-id="c2d66-157">**Output Information**</span><span class="sxs-lookup"><span data-stu-id="c2d66-157">**Output Information**</span></span>|<span data-ttu-id="c2d66-158">Numeric values that are part of rate setup.</span><span class="sxs-lookup"><span data-stu-id="c2d66-158">Numeric values that are part of rate setup.</span></span> <span data-ttu-id="c2d66-159">(Example – Threshold Amount)</span><span class="sxs-lookup"><span data-stu-id="c2d66-159">(Example – Threshold Amount)</span></span>|



## <a name="tax-rates"></a><span data-ttu-id="c2d66-160">Tax rates</span><span class="sxs-lookup"><span data-stu-id="c2d66-160">Tax rates</span></span>
<span data-ttu-id="c2d66-161">Tax rates can be defined for a combination of tax parameters defined as part of 'Rate Setup' for a 'Tax type'.</span><span class="sxs-lookup"><span data-stu-id="c2d66-161">Tax rates can be defined for a combination of tax parameters defined as part of 'Rate Setup' for a 'Tax type'.</span></span> <span data-ttu-id="c2d66-162">Rate defined for a combination cannot be repeated.</span><span class="sxs-lookup"><span data-stu-id="c2d66-162">Rate defined for a combination cannot be repeated.</span></span>



















