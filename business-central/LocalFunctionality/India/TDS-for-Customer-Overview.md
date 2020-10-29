---
title: Setting up Tax Deducted at Source by Customer, as per the provisions of the Income Tax Act, 1961
description: Specifies Basic Setups required, as per the provisions of the Income Tax Act, 1961
author: v-debapd
ms.service: dynamics365-business-central
ms.topic: article
ms.devlang: na
ms.tgt_pltfrm: na
ms.workload: na
ms.search.keywords: India, local, IN, English
ms.date: 10/01/2020
ms.author: v-debapd
ms.openlocfilehash: 0ab5faed5174caa32971a6f8cf6e17d3022e73a2
ms.sourcegitcommit: ddbb5cede750df1baba4b3eab8fbed6744b5b9d6
ms.translationtype: HT
ms.contentlocale: en-IN
ms.lasthandoff: 10/01/2020
ms.locfileid: "3948602"
---
# <a name="setting-up-tax-deducted-at-source-tds-by-customer-as-per-the-provisions-of-the-income-tax-act-1961"></a><span data-ttu-id="690a6-103">Setting Up Tax Deducted at Source (TDS) by Customer, as per the Provisions of the Income Tax Act, 1961</span><span class="sxs-lookup"><span data-stu-id="690a6-103">Setting Up Tax Deducted at Source (TDS) by Customer, as per the Provisions of the Income Tax Act, 1961</span></span>

[!INCLUDE[vnext_preview](../../includes/vnext_preview.md)]

<span data-ttu-id="690a6-104">Business Central has included Tax Deducted at Source (TDS) by Customer Feature to Indian Localisation.</span><span class="sxs-lookup"><span data-stu-id="690a6-104">Business Central has included Tax Deducted at Source (TDS) by Customer Feature to Indian Localization.</span></span>

<span data-ttu-id="690a6-105">TDS is a withholding tax, where tax is deducted by the customer, at the time of making the payment or booking of the invoice, whichever is earlier.</span><span class="sxs-lookup"><span data-stu-id="690a6-105">TDS is a withholding tax, where tax is deducted by the customer, at the time of making the payment or booking of the invoice, whichever is earlier.</span></span> <span data-ttu-id="690a6-106">As per the Income Tax Act, 1961, tax needs to be deducted by the payer, when the payment is of a specific nature.</span><span class="sxs-lookup"><span data-stu-id="690a6-106">As per the Income Tax Act, 1961, tax needs to be deducted by the payer, when the payment is of a specific nature.</span></span>
<span data-ttu-id="690a6-107">If the TDS is deducted by the customer (deductor), then the user (deductee) has to calculate TDS on the invoice or revenue and keep a track of TDS deducted.</span><span class="sxs-lookup"><span data-stu-id="690a6-107">If the TDS is deducted by the customer (deductor), then the user (deductee) has to calculate TDS on the invoice or revenue and keep a track of TDS deducted.</span></span> <span data-ttu-id="690a6-108">The deductor has to provide the deductee a TDS certificate.</span><span class="sxs-lookup"><span data-stu-id="690a6-108">The deductor has to provide the deductee a TDS certificate.</span></span>


## <a name="setting-up-tds"></a><span data-ttu-id="690a6-109">Setting Up TDS</span><span class="sxs-lookup"><span data-stu-id="690a6-109">Setting Up TDS</span></span>

### <a name="tds-has-two-types-of-setup"></a><span data-ttu-id="690a6-110">TDS has two types of setup.</span><span class="sxs-lookup"><span data-stu-id="690a6-110">TDS has two types of setup.</span></span>

- <span data-ttu-id="690a6-111">Automatic - These setup are done through Tax Engine.</span><span class="sxs-lookup"><span data-stu-id="690a6-111">Automatic - These setup are done through Tax Engine.</span></span>
- <span data-ttu-id="690a6-112">Manual - These setups are done manually by the business users.</span><span class="sxs-lookup"><span data-stu-id="690a6-112">Manual - These setups are done manually by the business users.</span></span>

### <a name="following-is-the-list-of-setups-which-will-be-pre-configured-with-help-of-tax-engine"></a><span data-ttu-id="690a6-113">Following is the list of setups which will be pre-configured with help of **Tax Engine**</span><span class="sxs-lookup"><span data-stu-id="690a6-113">Following is the list of setups which will be pre-configured with help of **Tax Engine**</span></span>

- <span data-ttu-id="690a6-114">Tax Types</span><span class="sxs-lookup"><span data-stu-id="690a6-114">Tax Types</span></span>
- <span data-ttu-id="690a6-115">Tax Entities</span><span class="sxs-lookup"><span data-stu-id="690a6-115">Tax Entities</span></span>
- <span data-ttu-id="690a6-116">Components</span><span class="sxs-lookup"><span data-stu-id="690a6-116">Components</span></span>
- <span data-ttu-id="690a6-117">Attributes</span><span class="sxs-lookup"><span data-stu-id="690a6-117">Attributes</span></span>
- <span data-ttu-id="690a6-118">Rate Setup</span><span class="sxs-lookup"><span data-stu-id="690a6-118">Rate Setup</span></span>


<span data-ttu-id="690a6-119">For more information about Automatic Setup, see **Tax Engine** Information.</span><span class="sxs-lookup"><span data-stu-id="690a6-119">For more information about Automatic Setup, see **Tax Engine** Information.</span></span>

### <a name="the-following-are-required-to-be-setup-manually"></a><span data-ttu-id="690a6-120">The following are required to be setup manually</span><span class="sxs-lookup"><span data-stu-id="690a6-120">The following are required to be setup manually</span></span>

- [<span data-ttu-id="690a6-121">TDS Rate</span><span class="sxs-lookup"><span data-stu-id="690a6-121">TDS Rate</span></span>](tds-for-customer-overview.md#to-set-up-tds-rates)
- [<span data-ttu-id="690a6-122">Tax Accounting Period</span><span class="sxs-lookup"><span data-stu-id="690a6-122">Tax Accounting Period</span></span>](tds-for-customer-overview.md#to-set-up-tax-accounting-period)
- [<span data-ttu-id="690a6-123">T.A.N</span><span class="sxs-lookup"><span data-stu-id="690a6-123">T.A.N</span></span>](tds-for-customer-overview.md#to-set-up-tan)
- [<span data-ttu-id="690a6-124">Assessee Code</span><span class="sxs-lookup"><span data-stu-id="690a6-124">Assessee Code</span></span>](tds-for-customer-overview.md#to-set-up-assessee-code)
- [<span data-ttu-id="690a6-125">TDS Section</span><span class="sxs-lookup"><span data-stu-id="690a6-125">TDS Section</span></span>](tds-for-customer-overview.md#to-set-up-tds-section)
- [<span data-ttu-id="690a6-126">Concessional Code</span><span class="sxs-lookup"><span data-stu-id="690a6-126">Concessional Code</span></span>](tds-for-customer-overview.md#to-set-up-concessional-codes)
- [<span data-ttu-id="690a6-127">TDS Posting Setup</span><span class="sxs-lookup"><span data-stu-id="690a6-127">TDS Posting Setup</span></span>](tds-for-customer-overview.md#to-set-up-tds-posting-setup)
- [<span data-ttu-id="690a6-128">TDS on Customer Master</span><span class="sxs-lookup"><span data-stu-id="690a6-128">TDS on Customer Master</span></span>](tds-for-customer-overview.md#to-set-up-tds-on-customer-master)
- [<span data-ttu-id="690a6-129">TDS on Location Master</span><span class="sxs-lookup"><span data-stu-id="690a6-129">TDS on Location Master</span></span>](tds-for-customer-overview.md#to-set-up-tds-on-location-master)
- [<span data-ttu-id="690a6-130">TDS on Company Information</span><span class="sxs-lookup"><span data-stu-id="690a6-130">TDS on Company Information</span></span>](tds-for-customer-overview.md#to-set-up-tds-on-company-information)
- [<span data-ttu-id="690a6-131">TDS on State Code</span><span class="sxs-lookup"><span data-stu-id="690a6-131">TDS on State Code</span></span>](tds-for-customer-overview.md#to-set-up-tds-on-state-code)

## <a name="to-set-up-tds-rates"></a><span data-ttu-id="690a6-132">To set up TDS rates</span><span class="sxs-lookup"><span data-stu-id="690a6-132">To set up TDS rates</span></span>

<span data-ttu-id="690a6-133">Rate of TDS is defined in combination of TDS section and assessee code.</span><span class="sxs-lookup"><span data-stu-id="690a6-133">Rate of TDS is defined in combination of TDS section and assessee code.</span></span>

1. <span data-ttu-id="690a6-134">Choose the ![Search for Page or Report](image/search_small.png "Search for Page or Report icon") icon, enter **Tax Type** -> **TDS** -> **Action** -> **Tax Rates** , and then choose the related link.</span><span class="sxs-lookup"><span data-stu-id="690a6-134">Choose the ![Search for Page or Report](image/search_small.png "Search for Page or Report icon") icon, enter **Tax Type** -> **TDS** -> **Action** -> **Tax Rates** , and then choose the related link.</span></span>
2. <span data-ttu-id="690a6-135">Fill in the fields as described in the following table.</span><span class="sxs-lookup"><span data-stu-id="690a6-135">Fill in the fields as described in the following table.</span></span>

    |<span data-ttu-id="690a6-136">Field</span><span class="sxs-lookup"><span data-stu-id="690a6-136">Field</span></span>|<span data-ttu-id="690a6-137">Description</span><span class="sxs-lookup"><span data-stu-id="690a6-137">Description</span></span>|  
    |---------------------------------|---------------------------------------|  
    |<span data-ttu-id="690a6-138">**Section Code**</span><span class="sxs-lookup"><span data-stu-id="690a6-138">**Section Code**</span></span>|<span data-ttu-id="690a6-139">Specifies the TDS section code.</span><span class="sxs-lookup"><span data-stu-id="690a6-139">Specifies the TDS section code.</span></span>|
    |<span data-ttu-id="690a6-140">**Assessee Code**</span><span class="sxs-lookup"><span data-stu-id="690a6-140">**Assessee Code**</span></span>|<span data-ttu-id="690a6-141">Specifies the assessee code.</span><span class="sxs-lookup"><span data-stu-id="690a6-141">Specifies the assessee code.</span></span>|
    |<span data-ttu-id="690a6-142">**Effective Date**</span><span class="sxs-lookup"><span data-stu-id="690a6-142">**Effective Date**</span></span>|<span data-ttu-id="690a6-143">Specifies the date from which rate will be effective.</span><span class="sxs-lookup"><span data-stu-id="690a6-143">Specifies the date from which rate will be effective.</span></span>|
    |<span data-ttu-id="690a6-144">**Concessional Code**</span><span class="sxs-lookup"><span data-stu-id="690a6-144">**Concessional Code**</span></span>|<span data-ttu-id="690a6-145">Specifies the concessional code.</span><span class="sxs-lookup"><span data-stu-id="690a6-145">Specifies the concessional code.</span></span>|
    |<span data-ttu-id="690a6-146">**Nature of Remittance**</span><span class="sxs-lookup"><span data-stu-id="690a6-146">**Nature of Remittance**</span></span>|<span data-ttu-id="690a6-147">Specifies whether the nature of remittance is applicable or not.</span><span class="sxs-lookup"><span data-stu-id="690a6-147">Specifies whether the nature of remittance is applicable or not.</span></span>|
    |<span data-ttu-id="690a6-148">**Act Applicable**</span><span class="sxs-lookup"><span data-stu-id="690a6-148">**Act Applicable**</span></span>|<span data-ttu-id="690a6-149">Specifies the applicable act.</span><span class="sxs-lookup"><span data-stu-id="690a6-149">Specifies the applicable act.</span></span>|
    |<span data-ttu-id="690a6-150">**Currency Code**</span><span class="sxs-lookup"><span data-stu-id="690a6-150">**Currency Code**</span></span>|<span data-ttu-id="690a6-151">Specifies the currency code.</span><span class="sxs-lookup"><span data-stu-id="690a6-151">Specifies the currency code.</span></span>|
    |<span data-ttu-id="690a6-152">**TDS %**</span><span class="sxs-lookup"><span data-stu-id="690a6-152">**TDS %**</span></span>|<span data-ttu-id="690a6-153">Specifies the TDS rate.</span><span class="sxs-lookup"><span data-stu-id="690a6-153">Specifies the TDS rate.</span></span>|
    |<span data-ttu-id="690a6-154">**Non PAN TDS %**</span><span class="sxs-lookup"><span data-stu-id="690a6-154">**Non PAN TDS %**</span></span>|<span data-ttu-id="690a6-155">Specifies the TDS rate in case of non availability of PAN.</span><span class="sxs-lookup"><span data-stu-id="690a6-155">Specifies the TDS rate in case of non availability of PAN.</span></span>|
    |<span data-ttu-id="690a6-156">**Surcharge %**</span><span class="sxs-lookup"><span data-stu-id="690a6-156">**Surcharge %**</span></span>|<span data-ttu-id="690a6-157">Specifies the surcharge rate.</span><span class="sxs-lookup"><span data-stu-id="690a6-157">Specifies the surcharge rate.</span></span>|
    |<span data-ttu-id="690a6-158">**eCESS %**</span><span class="sxs-lookup"><span data-stu-id="690a6-158">**eCESS %**</span></span>|<span data-ttu-id="690a6-159">Specifies the eCess rate.</span><span class="sxs-lookup"><span data-stu-id="690a6-159">Specifies the eCess rate.</span></span>|
    |<span data-ttu-id="690a6-160">**SHE Cess %**</span><span class="sxs-lookup"><span data-stu-id="690a6-160">**SHE Cess %**</span></span>|<span data-ttu-id="690a6-161">Specifies the SHE Cess rate.</span><span class="sxs-lookup"><span data-stu-id="690a6-161">Specifies the SHE Cess rate.</span></span>|
    |<span data-ttu-id="690a6-162">**Surcharge Threshold Amount**</span><span class="sxs-lookup"><span data-stu-id="690a6-162">**Surcharge Threshold Amount**</span></span>|<span data-ttu-id="690a6-163">Specifies the threshold amount applicable for surcharge.</span><span class="sxs-lookup"><span data-stu-id="690a6-163">Specifies the threshold amount applicable for surcharge.</span></span>|
    |<span data-ttu-id="690a6-164">**TDS Threshold Amount**</span><span class="sxs-lookup"><span data-stu-id="690a6-164">**TDS Threshold Amount**</span></span>|<span data-ttu-id="690a6-165">Specifies the threshold amount applicable for TDS.</span><span class="sxs-lookup"><span data-stu-id="690a6-165">Specifies the threshold amount applicable for TDS.</span></span>|
    |<span data-ttu-id="690a6-166">**Per Contract Value**</span><span class="sxs-lookup"><span data-stu-id="690a6-166">**Per Contract Value**</span></span>|<span data-ttu-id="690a6-167">Specifies the per contract value.</span><span class="sxs-lookup"><span data-stu-id="690a6-167">Specifies the per contract value.</span></span>

## <a name="to-set-up-tax-accounting-period"></a><span data-ttu-id="690a6-168">To set up tax accounting period</span><span class="sxs-lookup"><span data-stu-id="690a6-168">To set up tax accounting period</span></span>

<span data-ttu-id="690a6-169">Tax Accounting period and quarters need to be defined for TDS calculation.</span><span class="sxs-lookup"><span data-stu-id="690a6-169">Tax Accounting period and quarters need to be defined for TDS calculation.</span></span>

1. <span data-ttu-id="690a6-170">Choose the ![Search for Page or Report](image/search_small.png "Search for Page or Report icon") icon, enter **Tax Acc. Period Setup** , and then choose the related link.</span><span class="sxs-lookup"><span data-stu-id="690a6-170">Choose the ![Search for Page or Report](image/search_small.png "Search for Page or Report icon") icon, enter **Tax Acc. Period Setup** , and then choose the related link.</span></span> 
2. <span data-ttu-id="690a6-171">Fill in the fields as described in the following table.</span><span class="sxs-lookup"><span data-stu-id="690a6-171">Fill in the fields as described in the following table.</span></span>   

    |<span data-ttu-id="690a6-172">Field</span><span class="sxs-lookup"><span data-stu-id="690a6-172">Field</span></span>|<span data-ttu-id="690a6-173">Description</span><span class="sxs-lookup"><span data-stu-id="690a6-173">Description</span></span>|  
    |---------------------------------|---------------------------------------|   
    |<span data-ttu-id="690a6-174">**Code**</span><span class="sxs-lookup"><span data-stu-id="690a6-174">**Code**</span></span>|<span data-ttu-id="690a6-175">Enter the valid tax type.</span><span class="sxs-lookup"><span data-stu-id="690a6-175">Enter the valid tax type.</span></span>|  
    |<span data-ttu-id="690a6-176">**Description**</span><span class="sxs-lookup"><span data-stu-id="690a6-176">**Description**</span></span>|<span data-ttu-id="690a6-177">Specify the description of the tax type.</span><span class="sxs-lookup"><span data-stu-id="690a6-177">Specify the description of the tax type.</span></span>|

3. <span data-ttu-id="690a6-178">Select the Tax Type -> Action -> Tax Accounting Period -> Create Year, fill the following information and accounting period will be created.</span><span class="sxs-lookup"><span data-stu-id="690a6-178">Select the Tax Type -> Action -> Tax Accounting Period -> Create Year, fill the following information and accounting period will be created.</span></span>
    
    |<span data-ttu-id="690a6-179">Field</span><span class="sxs-lookup"><span data-stu-id="690a6-179">Field</span></span>|<span data-ttu-id="690a6-180">Description</span><span class="sxs-lookup"><span data-stu-id="690a6-180">Description</span></span>|  
    |---------------------------------|---------------------------------------|   
    |<span data-ttu-id="690a6-181">**Tax Type**</span><span class="sxs-lookup"><span data-stu-id="690a6-181">**Tax Type**</span></span>|<span data-ttu-id="690a6-182">Select the valid tax type.</span><span class="sxs-lookup"><span data-stu-id="690a6-182">Select the valid tax type.</span></span>|  
    |<span data-ttu-id="690a6-183">**Starting Date**</span><span class="sxs-lookup"><span data-stu-id="690a6-183">**Starting Date**</span></span>|<span data-ttu-id="690a6-184">Specify the starting date of the accounting period.</span><span class="sxs-lookup"><span data-stu-id="690a6-184">Specify the starting date of the accounting period.</span></span>|
    |<span data-ttu-id="690a6-185">**No. of Periods**</span><span class="sxs-lookup"><span data-stu-id="690a6-185">**No. of Periods**</span></span>|<span data-ttu-id="690a6-186">Specify the number of periods.</span><span class="sxs-lookup"><span data-stu-id="690a6-186">Specify the number of periods.</span></span>|
    |<span data-ttu-id="690a6-187">**Period Length**</span><span class="sxs-lookup"><span data-stu-id="690a6-187">**Period Length**</span></span>|<span data-ttu-id="690a6-188">Specify the length of the period.</span><span class="sxs-lookup"><span data-stu-id="690a6-188">Specify the length of the period.</span></span>|

## <a name="to-set-up-tan"></a><span data-ttu-id="690a6-189">To set up T.A.N.</span><span class="sxs-lookup"><span data-stu-id="690a6-189">To set up T.A.N.</span></span>

<span data-ttu-id="690a6-190">Tax Deduction Account Number (T.A.N) allotted to a legal entity can be more than one, depending on the number of branch locations from where the legal entity files its TDs returns.</span><span class="sxs-lookup"><span data-stu-id="690a6-190">Tax Deduction Account Number (T.A.N) allotted to a legal entity can be more than one, depending on the number of branch locations from where the legal entity files its TDs returns.</span></span> <span data-ttu-id="690a6-191">All the account numbers allotted to a legal entity need to be captured here.</span><span class="sxs-lookup"><span data-stu-id="690a6-191">All the account numbers allotted to a legal entity need to be captured here.</span></span>

1. <span data-ttu-id="690a6-192">Choose the ![Search for Page or Report](image/search_small.png "Search for Page or Report icon") icon, enter **T.A.N Nos.** , and then choose the related link.</span><span class="sxs-lookup"><span data-stu-id="690a6-192">Choose the ![Search for Page or Report](image/search_small.png "Search for Page or Report icon") icon, enter **T.A.N Nos.** , and then choose the related link.</span></span> 
2. <span data-ttu-id="690a6-193">Fill in the fields as described in the following table.</span><span class="sxs-lookup"><span data-stu-id="690a6-193">Fill in the fields as described in the following table.</span></span>   

    |<span data-ttu-id="690a6-194">Field</span><span class="sxs-lookup"><span data-stu-id="690a6-194">Field</span></span>|<span data-ttu-id="690a6-195">Description</span><span class="sxs-lookup"><span data-stu-id="690a6-195">Description</span></span>|  
    |---------------------------------|---------------------------------------|
    |<span data-ttu-id="690a6-196">**Code**</span><span class="sxs-lookup"><span data-stu-id="690a6-196">**Code**</span></span>|<span data-ttu-id="690a6-197">Enter the valid registration number provided by authority.</span><span class="sxs-lookup"><span data-stu-id="690a6-197">Enter the valid registration number provided by authority.</span></span>|  
    |<span data-ttu-id="690a6-198">**Description**</span><span class="sxs-lookup"><span data-stu-id="690a6-198">**Description**</span></span>|<span data-ttu-id="690a6-199">Specify the description of the registration number.</span><span class="sxs-lookup"><span data-stu-id="690a6-199">Specify the description of the registration number.</span></span>|
    

## <a name="to-set-up-assessee-code"></a><span data-ttu-id="690a6-200">To set up assessee code</span><span class="sxs-lookup"><span data-stu-id="690a6-200">To set up assessee code</span></span>

<span data-ttu-id="690a6-201">Income Tax Act 1961 defines 'Assessee' as a person by whom any tax or any other sum of money is payable under this Act. The rates of TDS are different for different types of Assessee.</span><span class="sxs-lookup"><span data-stu-id="690a6-201">Income Tax Act 1961 defines 'Assessee' as a person by whom any tax or any other sum of money is payable under this Act. The rates of TDS are different for different types of Assessee.</span></span>

1. <span data-ttu-id="690a6-202">Choose the ![Search for Page or Report](image/search_small.png "Search for Page or Report icon") icon, enter **Assessee Codes** , and then choose the related link.</span><span class="sxs-lookup"><span data-stu-id="690a6-202">Choose the ![Search for Page or Report](image/search_small.png "Search for Page or Report icon") icon, enter **Assessee Codes** , and then choose the related link.</span></span> 
2. <span data-ttu-id="690a6-203">Fill in the fields as described in the following table.</span><span class="sxs-lookup"><span data-stu-id="690a6-203">Fill in the fields as described in the following table.</span></span>   

    |<span data-ttu-id="690a6-204">Field</span><span class="sxs-lookup"><span data-stu-id="690a6-204">Field</span></span>|<span data-ttu-id="690a6-205">Description</span><span class="sxs-lookup"><span data-stu-id="690a6-205">Description</span></span>|  
    |---------------------------------|---------------------------------------|   
    |<span data-ttu-id="690a6-206">**Code**</span><span class="sxs-lookup"><span data-stu-id="690a6-206">**Code**</span></span>|<span data-ttu-id="690a6-207">Enter the valid Assessee Code, for example, IND, COM.</span><span class="sxs-lookup"><span data-stu-id="690a6-207">Enter the valid Assessee Code, for example, IND, COM.</span></span>|  
    |<span data-ttu-id="690a6-208">**Description**</span><span class="sxs-lookup"><span data-stu-id="690a6-208">**Description**</span></span>|<span data-ttu-id="690a6-209">Enter the description of the assessee code.</span><span class="sxs-lookup"><span data-stu-id="690a6-209">Enter the description of the assessee code.</span></span>|
    |<span data-ttu-id="690a6-210">**Type**</span><span class="sxs-lookup"><span data-stu-id="690a6-210">**Type**</span></span>|<span data-ttu-id="690a6-211">Select the type of the assessee from drop down list as Company or Others.</span><span class="sxs-lookup"><span data-stu-id="690a6-211">Select the type of the assessee from drop down list as Company or Others.</span></span>|


## <a name="to-set-up-tds-section"></a><span data-ttu-id="690a6-212">To set up TDS section</span><span class="sxs-lookup"><span data-stu-id="690a6-212">To set up TDS section</span></span>

<span data-ttu-id="690a6-213">TDS Section represents the various sections under which tax deduction takes place as per the Income Tax Act 1961.</span><span class="sxs-lookup"><span data-stu-id="690a6-213">TDS Section represents the various sections under which tax deduction takes place as per the Income Tax Act 1961.</span></span>

1. <span data-ttu-id="690a6-214">Choose the ![Search for Page or Report](image/search_small.png "Search for Page or Report icon") icon, enter **TDS Sections** , and then choose the related link.</span><span class="sxs-lookup"><span data-stu-id="690a6-214">Choose the ![Search for Page or Report](image/search_small.png "Search for Page or Report icon") icon, enter **TDS Sections** , and then choose the related link.</span></span>
2. <span data-ttu-id="690a6-215">Fill in the fields as described in the following table.</span><span class="sxs-lookup"><span data-stu-id="690a6-215">Fill in the fields as described in the following table.</span></span>

    |<span data-ttu-id="690a6-216">Field</span><span class="sxs-lookup"><span data-stu-id="690a6-216">Field</span></span>|<span data-ttu-id="690a6-217">Description</span><span class="sxs-lookup"><span data-stu-id="690a6-217">Description</span></span>|  
    |---------------------------------|---------------------------------------|   
    |<span data-ttu-id="690a6-218">**Code**</span><span class="sxs-lookup"><span data-stu-id="690a6-218">**Code**</span></span>|<span data-ttu-id="690a6-219">Enter the valid TDS Section applicable as per the Income Tax Act, 1961</span><span class="sxs-lookup"><span data-stu-id="690a6-219">Enter the valid TDS Section applicable as per the Income Tax Act, 1961</span></span>|  
    |<span data-ttu-id="690a6-220">**Description**</span><span class="sxs-lookup"><span data-stu-id="690a6-220">**Description**</span></span>|<span data-ttu-id="690a6-221">Enter the description of the mentioned TDS Section.</span><span class="sxs-lookup"><span data-stu-id="690a6-221">Enter the description of the mentioned TDS Section.</span></span>|
    |<span data-ttu-id="690a6-222">**e-TDS**</span><span class="sxs-lookup"><span data-stu-id="690a6-222">**e-TDS**</span></span>|<span data-ttu-id="690a6-223">Specifies the section code to be used in the tds return.</span><span class="sxs-lookup"><span data-stu-id="690a6-223">Specifies the section code to be used in the tds return.</span></span>|

## <a name="to-set-up-concessional-codes"></a><span data-ttu-id="690a6-224">To set up concessional codes</span><span class="sxs-lookup"><span data-stu-id="690a6-224">To set up concessional codes</span></span>

<span data-ttu-id="690a6-225">Concessional codes are used for cases authorised for concessional rates exclusively defined by the government.</span><span class="sxs-lookup"><span data-stu-id="690a6-225">Concessional codes are used for cases authorized for concessional rates exclusively defined by the government.</span></span> 

1. <span data-ttu-id="690a6-226">Choose the ![Search for Page or Report](image/search_small.png "Search for Page or Report icon") icon, enter **Concessional Codes** , and then choose the related link.</span><span class="sxs-lookup"><span data-stu-id="690a6-226">Choose the ![Search for Page or Report](image/search_small.png "Search for Page or Report icon") icon, enter **Concessional Codes** , and then choose the related link.</span></span>
2. <span data-ttu-id="690a6-227">Fill in the fields as described in the following table.</span><span class="sxs-lookup"><span data-stu-id="690a6-227">Fill in the fields as described in the following table.</span></span>

    |<span data-ttu-id="690a6-228">Field</span><span class="sxs-lookup"><span data-stu-id="690a6-228">Field</span></span>|<span data-ttu-id="690a6-229">Description</span><span class="sxs-lookup"><span data-stu-id="690a6-229">Description</span></span>|  
    |---------------------------------|---------------------------------------|   
    |<span data-ttu-id="690a6-230">**Code**</span><span class="sxs-lookup"><span data-stu-id="690a6-230">**Code**</span></span>|<span data-ttu-id="690a6-231">Enter the valid Concessional Codes applicable as per the Income Tax Act</span><span class="sxs-lookup"><span data-stu-id="690a6-231">Enter the valid Concessional Codes applicable as per the Income Tax Act</span></span>|  
    |<span data-ttu-id="690a6-232">**Description**</span><span class="sxs-lookup"><span data-stu-id="690a6-232">**Description**</span></span>|<span data-ttu-id="690a6-233">Enter the description of the mentioned Concessional Codes</span><span class="sxs-lookup"><span data-stu-id="690a6-233">Enter the description of the mentioned Concessional Codes</span></span>|

## <a name="to-set-up-tds-posting-setup"></a><span data-ttu-id="690a6-234">To set up TDS posting setup</span><span class="sxs-lookup"><span data-stu-id="690a6-234">To set up TDS posting setup</span></span>

<span data-ttu-id="690a6-235">Specifies the general ledger account for each TDS Section defined in the system.</span><span class="sxs-lookup"><span data-stu-id="690a6-235">Specifies the general ledger account for each TDS Section defined in the system.</span></span> <span data-ttu-id="690a6-236">System will update the tds receivable amount in the defined general ledger account.</span><span class="sxs-lookup"><span data-stu-id="690a6-236">System will update the tds receivable amount in the defined general ledger account.</span></span>

1. <span data-ttu-id="690a6-237">Choose the ![Search for Page or Report](image/search_small.png "Search for Page or Report icon") icon, enter **TDS Posting Setup** , and then choose the related link.</span><span class="sxs-lookup"><span data-stu-id="690a6-237">Choose the ![Search for Page or Report](image/search_small.png "Search for Page or Report icon") icon, enter **TDS Posting Setup** , and then choose the related link.</span></span>
2. <span data-ttu-id="690a6-238">Fill in the fields as described in the following table.</span><span class="sxs-lookup"><span data-stu-id="690a6-238">Fill in the fields as described in the following table.</span></span>

    |<span data-ttu-id="690a6-239">Field</span><span class="sxs-lookup"><span data-stu-id="690a6-239">Field</span></span>|<span data-ttu-id="690a6-240">Description</span><span class="sxs-lookup"><span data-stu-id="690a6-240">Description</span></span>|  
    |---------------------------------|---------------------------------------|   
    |<span data-ttu-id="690a6-241">**TDS Section**</span><span class="sxs-lookup"><span data-stu-id="690a6-241">**TDS Section**</span></span>|<span data-ttu-id="690a6-242">Specifies the relevant TDS section</span><span class="sxs-lookup"><span data-stu-id="690a6-242">Specifies the relevant TDS section</span></span>|  
    |<span data-ttu-id="690a6-243">**Effective Date**</span><span class="sxs-lookup"><span data-stu-id="690a6-243">**Effective Date**</span></span>|<span data-ttu-id="690a6-244">Specifies the start date of the setup line</span><span class="sxs-lookup"><span data-stu-id="690a6-244">Specifies the start date of the setup line</span></span>|
    |<span data-ttu-id="690a6-245">**TDS Receivable Account**</span><span class="sxs-lookup"><span data-stu-id="690a6-245">**TDS Receivable Account**</span></span>|<span data-ttu-id="690a6-246">Specifies the general ledger account in which receivable account will be posted.</span><span class="sxs-lookup"><span data-stu-id="690a6-246">Specifies the general ledger account in which receivable account will be posted.</span></span>|

## <a name="to-set-up-tds-on-customer-master"></a><span data-ttu-id="690a6-247">To set up TDS on customer master</span><span class="sxs-lookup"><span data-stu-id="690a6-247">To set up TDS on customer master</span></span>

<span data-ttu-id="690a6-248">TDS Section and concessional codes need to be defined for each customer, who is liable to deduct TDS.</span><span class="sxs-lookup"><span data-stu-id="690a6-248">TDS Section and concessional codes need to be defined for each customer, who is liable to deduct TDS.</span></span> <span data-ttu-id="690a6-249">Multiple TDS sections can be configured for one customer.</span><span class="sxs-lookup"><span data-stu-id="690a6-249">Multiple TDS sections can be configured for one customer.</span></span>

- <span data-ttu-id="690a6-250">To define the TDS Sections on the Customer Card.</span><span class="sxs-lookup"><span data-stu-id="690a6-250">To define the TDS Sections on the Customer Card.</span></span>

  1. <span data-ttu-id="690a6-251">Choose the ![Search for Page or Report](image/search_small.png "Search for Page or Report icon") icon, enter **Customer** -> **Customer** -> **Customer Allowed Sections** and then choose the related link.</span><span class="sxs-lookup"><span data-stu-id="690a6-251">Choose the ![Search for Page or Report](image/search_small.png "Search for Page or Report icon") icon, enter **Customer** -> **Customer** -> **Customer Allowed Sections** and then choose the related link.</span></span>
  2. <span data-ttu-id="690a6-252">**Assessee Code** needs to be filled on the customer master.</span><span class="sxs-lookup"><span data-stu-id="690a6-252">**Assessee Code** needs to be filled on the customer master.</span></span>
  3. <span data-ttu-id="690a6-253">**PAN** needs to be filled on customer master, PAN is mandatory for TDS calculation for customer.</span><span class="sxs-lookup"><span data-stu-id="690a6-253">**PAN** needs to be filled on customer master, PAN is mandatory for TDS calculation for customer.</span></span>
  4. <span data-ttu-id="690a6-254">Fill in the fields as described in the following table.</span><span class="sxs-lookup"><span data-stu-id="690a6-254">Fill in the fields as described in the following table.</span></span>

      |<span data-ttu-id="690a6-255">Field</span><span class="sxs-lookup"><span data-stu-id="690a6-255">Field</span></span>|<span data-ttu-id="690a6-256">Description</span><span class="sxs-lookup"><span data-stu-id="690a6-256">Description</span></span>|  
      |---------------------------------|---------------------------------------|
      |<span data-ttu-id="690a6-257">**TDS Section**</span><span class="sxs-lookup"><span data-stu-id="690a6-257">**TDS Section**</span></span>|<span data-ttu-id="690a6-258">Select the valid section from lookup list depending on the kind of services provided by the customer.</span><span class="sxs-lookup"><span data-stu-id="690a6-258">Select the valid section from lookup list depending on the kind of services provided by the customer.</span></span>|
      |<span data-ttu-id="690a6-259">**TDS Section Description**</span><span class="sxs-lookup"><span data-stu-id="690a6-259">**TDS Section Description**</span></span>|<span data-ttu-id="690a6-260">Enter the description of the selected section.</span><span class="sxs-lookup"><span data-stu-id="690a6-260">Enter the description of the selected section.</span></span>|
      |<span data-ttu-id="690a6-261">**TDS Certificate Receivable**</span><span class="sxs-lookup"><span data-stu-id="690a6-261">**TDS Certificate Receivable**</span></span>|<span data-ttu-id="690a6-262">This field should be marked as true.</span><span class="sxs-lookup"><span data-stu-id="690a6-262">This field should be marked as true.</span></span>|
      |<span data-ttu-id="690a6-263">**Threshold Overlook**</span><span class="sxs-lookup"><span data-stu-id="690a6-263">**Threshold Overlook**</span></span>|<span data-ttu-id="690a6-264">Place a check mark in this field to overlook the TDS Threshold amount defined in 'Tax Rates'</span><span class="sxs-lookup"><span data-stu-id="690a6-264">Place a check mark in this field to overlook the TDS Threshold amount defined in 'Tax Rates'</span></span>|
      |<span data-ttu-id="690a6-265">**Surcharge Overlook**</span><span class="sxs-lookup"><span data-stu-id="690a6-265">**Surcharge Overlook**</span></span>|<span data-ttu-id="690a6-266">Place a check mark in this field to overlook the Surcharge Threshold amount defined in 'Tax Rates'</span><span class="sxs-lookup"><span data-stu-id="690a6-266">Place a check mark in this field to overlook the Surcharge Threshold amount defined in 'Tax Rates'</span></span>|

- <span data-ttu-id="690a6-267">To define the concessional code on customer card</span><span class="sxs-lookup"><span data-stu-id="690a6-267">To define the concessional code on customer card</span></span>

  1. <span data-ttu-id="690a6-268">Choose the ![Search for Page or Report](image/search_small.png "Search for Page or Report icon") icon, enter **Customer** -> **Customer** -> **TDS Customer Concessional Codes** and then choose the related link.</span><span class="sxs-lookup"><span data-stu-id="690a6-268">Choose the ![Search for Page or Report](image/search_small.png "Search for Page or Report icon") icon, enter **Customer** -> **Customer** -> **TDS Customer Concessional Codes** and then choose the related link.</span></span>
  2. <span data-ttu-id="690a6-269">Fill in the fields as described in the following table.</span><span class="sxs-lookup"><span data-stu-id="690a6-269">Fill in the fields as described in the following table.</span></span>

      |<span data-ttu-id="690a6-270">Field</span><span class="sxs-lookup"><span data-stu-id="690a6-270">Field</span></span>|<span data-ttu-id="690a6-271">Description</span><span class="sxs-lookup"><span data-stu-id="690a6-271">Description</span></span>|  
      |---------------------------------|---------------------------------------|
      |<span data-ttu-id="690a6-272">**Section**</span><span class="sxs-lookup"><span data-stu-id="690a6-272">**Section**</span></span>|<span data-ttu-id="690a6-273">Select the valid section from lookup list depending on the kind of services provided by customer.</span><span class="sxs-lookup"><span data-stu-id="690a6-273">Select the valid section from lookup list depending on the kind of services provided by customer.</span></span>|
      |<span data-ttu-id="690a6-274">**Concessional Code**</span><span class="sxs-lookup"><span data-stu-id="690a6-274">**Concessional Code**</span></span>|<span data-ttu-id="690a6-275">Select the valid concessional code from lookup list depending on the kind of services provided by customer.</span><span class="sxs-lookup"><span data-stu-id="690a6-275">Select the valid concessional code from lookup list depending on the kind of services provided by customer.</span></span>|
      |<span data-ttu-id="690a6-276">**Certificate No.**</span><span class="sxs-lookup"><span data-stu-id="690a6-276">**Certificate No.**</span></span>|<span data-ttu-id="690a6-277">Certificate number provided by the customer can be defined to justify the lower tax deduction.</span><span class="sxs-lookup"><span data-stu-id="690a6-277">Certificate number provided by the customer can be defined to justify the lower tax deduction.</span></span>  |
      

## <a name="to-set-up-tds-on-location-master"></a><span data-ttu-id="690a6-278">To set up TDS on location master</span><span class="sxs-lookup"><span data-stu-id="690a6-278">To set up TDS on location master</span></span>

<span data-ttu-id="690a6-279">**T.A.N** needs to be defined in locations from where the company files its returns.</span><span class="sxs-lookup"><span data-stu-id="690a6-279">**T.A.N** needs to be defined in locations from where the company files its returns.</span></span>

## <a name="to-set-up-tds-on-company-information"></a><span data-ttu-id="690a6-280">To set up TDS on company information</span><span class="sxs-lookup"><span data-stu-id="690a6-280">To set up TDS on company information</span></span>

-  <span data-ttu-id="690a6-281">Following information need to be defined in company information.</span><span class="sxs-lookup"><span data-stu-id="690a6-281">Following information need to be defined in company information.</span></span>

      |<span data-ttu-id="690a6-282">Field</span><span class="sxs-lookup"><span data-stu-id="690a6-282">Field</span></span>|<span data-ttu-id="690a6-283">Description</span><span class="sxs-lookup"><span data-stu-id="690a6-283">Description</span></span>|  
      |---------------------------------|---------------------------------------|
      |<span data-ttu-id="690a6-284">**T.A.N. No.**</span><span class="sxs-lookup"><span data-stu-id="690a6-284">**T.A.N. No.**</span></span>|<span data-ttu-id="690a6-285">Specifies the TAN No.</span><span class="sxs-lookup"><span data-stu-id="690a6-285">Specifies the TAN No.</span></span> <span data-ttu-id="690a6-286">of the legal entity.</span><span class="sxs-lookup"><span data-stu-id="690a6-286">of the legal entity.</span></span>|
      |<span data-ttu-id="690a6-287">**P.A.N No.**</span><span class="sxs-lookup"><span data-stu-id="690a6-287">**P.A.N No.**</span></span>|<span data-ttu-id="690a6-288">Specifies the PAN of the legal entity.</span><span class="sxs-lookup"><span data-stu-id="690a6-288">Specifies the PAN of the legal entity.</span></span>|
      |<span data-ttu-id="690a6-289">**Deductor Category**</span><span class="sxs-lookup"><span data-stu-id="690a6-289">**Deductor Category**</span></span>|<span data-ttu-id="690a6-290">Specifies the deductor category of the legal entity.</span><span class="sxs-lookup"><span data-stu-id="690a6-290">Specifies the deductor category of the legal entity.</span></span>|
      |<span data-ttu-id="690a6-291">**PAO Code**</span><span class="sxs-lookup"><span data-stu-id="690a6-291">**PAO Code**</span></span>|<span data-ttu-id="690a6-292">Specifies the PAO code.</span><span class="sxs-lookup"><span data-stu-id="690a6-292">Specifies the PAO code.</span></span>|
      |<span data-ttu-id="690a6-293">**PAO Registration No.**</span><span class="sxs-lookup"><span data-stu-id="690a6-293">**PAO Registration No.**</span></span>|<span data-ttu-id="690a6-294">Specifies PAO registration number.</span><span class="sxs-lookup"><span data-stu-id="690a6-294">Specifies PAO registration number.</span></span>|
      |<span data-ttu-id="690a6-295">**DDO Code**</span><span class="sxs-lookup"><span data-stu-id="690a6-295">**DDO Code**</span></span>|<span data-ttu-id="690a6-296">Specifies DDO code.</span><span class="sxs-lookup"><span data-stu-id="690a6-296">Specifies DDO code.</span></span>|
      |<span data-ttu-id="690a6-297">**DDO Registration No.**</span><span class="sxs-lookup"><span data-stu-id="690a6-297">**DDO Registration No.**</span></span>|<span data-ttu-id="690a6-298">Specifies the DDO registration number.</span><span class="sxs-lookup"><span data-stu-id="690a6-298">Specifies the DDO registration number.</span></span>|
      |<span data-ttu-id="690a6-299">**Ministry Type**</span><span class="sxs-lookup"><span data-stu-id="690a6-299">**Ministry Type**</span></span>|<span data-ttu-id="690a6-300">Specifies the Ministry type.</span><span class="sxs-lookup"><span data-stu-id="690a6-300">Specifies the Ministry type.</span></span>|
      |<span data-ttu-id="690a6-301">**Ministry Code**</span><span class="sxs-lookup"><span data-stu-id="690a6-301">**Ministry Code**</span></span>|<span data-ttu-id="690a6-302">Specifies the Ministry code.</span><span class="sxs-lookup"><span data-stu-id="690a6-302">Specifies the Ministry code.</span></span>|

## <a name="to-set-up-tds-on-state-code"></a><span data-ttu-id="690a6-303">To set up TDS on state code</span><span class="sxs-lookup"><span data-stu-id="690a6-303">To set up TDS on state code</span></span>

<span data-ttu-id="690a6-304">**State Code for eTDS/TCS** needs to be defined in States master.</span><span class="sxs-lookup"><span data-stu-id="690a6-304">**State Code for eTDS/TCS** needs to be defined in States master.</span></span>

















