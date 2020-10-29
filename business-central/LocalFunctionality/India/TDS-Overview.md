---
title: Setting up Tax Deducted at Source, as per the provisions of the Income Tax Act, 1961
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
ms.openlocfilehash: 9ac211ae0f4b283a44849e9545a8d300c9c0fbd0
ms.sourcegitcommit: ddbb5cede750df1baba4b3eab8fbed6744b5b9d6
ms.translationtype: HT
ms.contentlocale: en-IN
ms.lasthandoff: 10/01/2020
ms.locfileid: "3948609"
---
# <a name="setting-up-tax-deducted-at-source-tds-as-per-the-provisions-of-the-income-tax-act-1961"></a><span data-ttu-id="3714c-103">Setting Up Tax Deducted at Source (TDS), as per the Provisions of the Income Tax Act, 1961</span><span class="sxs-lookup"><span data-stu-id="3714c-103">Setting Up Tax Deducted at Source (TDS), as per the Provisions of the Income Tax Act, 1961</span></span>

[!INCLUDE[vnext_preview](../../includes/vnext_preview.md)]

<span data-ttu-id="3714c-104">Business Central has included Tax Deducted at Source (TDS) Feature to Indian Localisation.</span><span class="sxs-lookup"><span data-stu-id="3714c-104">Business Central has included Tax Deducted at Source (TDS) Feature to Indian Localization.</span></span>

<span data-ttu-id="3714c-105">**TDS** means **Tax Deducted at Source** .</span><span class="sxs-lookup"><span data-stu-id="3714c-105">**TDS** means **Tax Deducted at Source** .</span></span> <span data-ttu-id="3714c-106">The concept of TDS was introduced with an aim to collect tax from the very source of income.</span><span class="sxs-lookup"><span data-stu-id="3714c-106">The concept of TDS was introduced with an aim to collect tax from the very source of income.</span></span> <span data-ttu-id="3714c-107">As per this concept, a person (deductor) who is liable to make payment of specified nature to any other person (deductee) shall deduct tax at source and remit the same into the account of the Central Government</span><span class="sxs-lookup"><span data-stu-id="3714c-107">As per this concept, a person (deductor) who is liable to make payment of specified nature to any other person (deductee) shall deduct tax at source and remit the same into the account of the Central Government</span></span>

<span data-ttu-id="3714c-108">Income from several sources is subjected to TDS.</span><span class="sxs-lookup"><span data-stu-id="3714c-108">Income from several sources is subjected to TDS.</span></span> <span data-ttu-id="3714c-109">Presently this concept of TDS is also used as an instrument in enlarging the tax base.</span><span class="sxs-lookup"><span data-stu-id="3714c-109">Presently this concept of TDS is also used as an instrument in enlarging the tax base.</span></span> <span data-ttu-id="3714c-110">Some of such incomes subjected to TDS are salary, interest, dividend, interest on securities, winnings from lottery, horse races, commission and brokerage, rent, fees for professional and technical services, and payments to non-residents.</span><span class="sxs-lookup"><span data-stu-id="3714c-110">Some of such incomes subjected to TDS are salary, interest, dividend, interest on securities, winnings from lottery, horse races, commission and brokerage, rent, fees for professional and technical services, and payments to non-residents.</span></span>

<span data-ttu-id="3714c-111">The Income Tax Act, 1961 specifies that tax deduction is to be made, for the specified incomes, on credit or on payment, whichever is earlier.</span><span class="sxs-lookup"><span data-stu-id="3714c-111">The Income Tax Act, 1961 specifies that tax deduction is to be made, for the specified incomes, on credit or on payment, whichever is earlier.</span></span>

## <a name="setting-up-tds"></a><span data-ttu-id="3714c-112">Setting Up TDS</span><span class="sxs-lookup"><span data-stu-id="3714c-112">Setting Up TDS</span></span>

### <a name="tds-has-two-different-types-of-setups"></a><span data-ttu-id="3714c-113">TDS has two different types of setups</span><span class="sxs-lookup"><span data-stu-id="3714c-113">TDS has two different types of setups</span></span>

- <span data-ttu-id="3714c-114">Automatic - These setup are done through Tax Engine.</span><span class="sxs-lookup"><span data-stu-id="3714c-114">Automatic - These setup are done through Tax Engine.</span></span>
- <span data-ttu-id="3714c-115">Manual - These setups are done manually by the business users.</span><span class="sxs-lookup"><span data-stu-id="3714c-115">Manual - These setups are done manually by the business users.</span></span>

#### <a name="following-is-the-list-of-setups-which-will-be-pre-configured-with-help-of-tax-engine"></a><span data-ttu-id="3714c-116">Following is the list of Setups which will be pre-configured with help of **Tax Engine**</span><span class="sxs-lookup"><span data-stu-id="3714c-116">Following is the list of Setups which will be pre-configured with help of **Tax Engine**</span></span>

- <span data-ttu-id="3714c-117">Tax Types</span><span class="sxs-lookup"><span data-stu-id="3714c-117">Tax Types</span></span>
- <span data-ttu-id="3714c-118">Tax Entities</span><span class="sxs-lookup"><span data-stu-id="3714c-118">Tax Entities</span></span>
- <span data-ttu-id="3714c-119">Components</span><span class="sxs-lookup"><span data-stu-id="3714c-119">Components</span></span>
- <span data-ttu-id="3714c-120">Attributes</span><span class="sxs-lookup"><span data-stu-id="3714c-120">Attributes</span></span>
- <span data-ttu-id="3714c-121">Rate Setup</span><span class="sxs-lookup"><span data-stu-id="3714c-121">Rate Setup</span></span>

<span data-ttu-id="3714c-122">For more information about Automatic Setup, see **Tax Engine** Information.</span><span class="sxs-lookup"><span data-stu-id="3714c-122">For more information about Automatic Setup, see **Tax Engine** Information.</span></span>

#### <a name="the-following-are-required-to-be-setup-manually"></a><span data-ttu-id="3714c-123">The following are required to be setup manually</span><span class="sxs-lookup"><span data-stu-id="3714c-123">The following are required to be setup manually</span></span>

- [<span data-ttu-id="3714c-124">TDS Rate</span><span class="sxs-lookup"><span data-stu-id="3714c-124">TDS Rate</span></span>](tds-overview.md#to-set-up-tds-rates)
- [<span data-ttu-id="3714c-125">Tax Accounting Period</span><span class="sxs-lookup"><span data-stu-id="3714c-125">Tax Accounting Period</span></span>](tds-overview.md#to-set-up-tax-accounting-period)
- [<span data-ttu-id="3714c-126">T.A.N</span><span class="sxs-lookup"><span data-stu-id="3714c-126">T.A.N</span></span>](tds-overview.md#to-set-up-tan)
- [<span data-ttu-id="3714c-127">Assessee Code</span><span class="sxs-lookup"><span data-stu-id="3714c-127">Assessee Code</span></span>](tds-overview.md#to-set-up-assessee-code)
- [<span data-ttu-id="3714c-128">TDS Section</span><span class="sxs-lookup"><span data-stu-id="3714c-128">TDS Section</span></span>](tds-overview.md#to-set-up-tds-section)
- [<span data-ttu-id="3714c-129">Concessional Code</span><span class="sxs-lookup"><span data-stu-id="3714c-129">Concessional Code</span></span>](tds-overview.md#to-set-up-concessional-codes)
- [<span data-ttu-id="3714c-130">TDS Nature of Remittances</span><span class="sxs-lookup"><span data-stu-id="3714c-130">TDS Nature of Remittances</span></span>](tds-overview.md#to-set-up-tds-nature-of-remittances)
- [<span data-ttu-id="3714c-131">Act Applicable</span><span class="sxs-lookup"><span data-stu-id="3714c-131">Act Applicable</span></span>](tds-overview.md#to-set-up-act-applicable)
- [<span data-ttu-id="3714c-132">TDS Posting Setup</span><span class="sxs-lookup"><span data-stu-id="3714c-132">TDS Posting Setup</span></span>](tds-overview.md#to-set-up-tds-posting-setup)
- [<span data-ttu-id="3714c-133">TDS Rounding Precision</span><span class="sxs-lookup"><span data-stu-id="3714c-133">TDS Rounding Precision</span></span>](tds-overview.md#to-set-up-tds-rounding-precision)
- [<span data-ttu-id="3714c-134">TDS in Vendor Master</span><span class="sxs-lookup"><span data-stu-id="3714c-134">TDS in Vendor Master</span></span>](tds-overview.md#to-set-up-tds-in-vendor-master)
- [<span data-ttu-id="3714c-135">TDS in Location Master</span><span class="sxs-lookup"><span data-stu-id="3714c-135">TDS in Location Master</span></span>](tds-overview.md#to-set-up-tds-in-location-master)
- [<span data-ttu-id="3714c-136">TDS in Company Information</span><span class="sxs-lookup"><span data-stu-id="3714c-136">TDS in Company Information</span></span>](tds-overview.md#to-set-up-tds-in-company-information)
- [<span data-ttu-id="3714c-137">TDS in State Code</span><span class="sxs-lookup"><span data-stu-id="3714c-137">TDS in State Code</span></span>](tds-overview.md#to-set-up-tds-in-state-code)

## <a name="to-set-up-tds-rates"></a><span data-ttu-id="3714c-138">To set up TDS rates</span><span class="sxs-lookup"><span data-stu-id="3714c-138">To set up TDS rates</span></span>

<span data-ttu-id="3714c-139">Rate of TDS is defined in combination of TDS section and assessee code.</span><span class="sxs-lookup"><span data-stu-id="3714c-139">Rate of TDS is defined in combination of TDS section and assessee code.</span></span>

1. <span data-ttu-id="3714c-140">Choose the ![Search for Page or Report](image/search_small.png "Search for Page or Report icon") icon, enter **Tax Type** -> **TDS** -> **Action** -> **Tax Rates** , and then choose the related link.</span><span class="sxs-lookup"><span data-stu-id="3714c-140">Choose the ![Search for Page or Report](image/search_small.png "Search for Page or Report icon") icon, enter **Tax Type** -> **TDS** -> **Action** -> **Tax Rates** , and then choose the related link.</span></span>
2. <span data-ttu-id="3714c-141">Fill in the fields as described in the following table.</span><span class="sxs-lookup"><span data-stu-id="3714c-141">Fill in the fields as described in the following table.</span></span>

    |<span data-ttu-id="3714c-142">Field</span><span class="sxs-lookup"><span data-stu-id="3714c-142">Field</span></span>|<span data-ttu-id="3714c-143">Description</span><span class="sxs-lookup"><span data-stu-id="3714c-143">Description</span></span>|  
    |---------------------------------|---------------------------------------|  
    |<span data-ttu-id="3714c-144">**Section Code**</span><span class="sxs-lookup"><span data-stu-id="3714c-144">**Section Code**</span></span>|<span data-ttu-id="3714c-145">Specifies the TDS section code.</span><span class="sxs-lookup"><span data-stu-id="3714c-145">Specifies the TDS section code.</span></span>|
    |<span data-ttu-id="3714c-146">**Assessee Code**</span><span class="sxs-lookup"><span data-stu-id="3714c-146">**Assessee Code**</span></span>|<span data-ttu-id="3714c-147">Specifies the assessee code.</span><span class="sxs-lookup"><span data-stu-id="3714c-147">Specifies the assessee code.</span></span>|
    |<span data-ttu-id="3714c-148">**Effective Date**</span><span class="sxs-lookup"><span data-stu-id="3714c-148">**Effective Date**</span></span>|<span data-ttu-id="3714c-149">Specifies the date from which rate will be effective.</span><span class="sxs-lookup"><span data-stu-id="3714c-149">Specifies the date from which rate will be effective.</span></span>|
    |<span data-ttu-id="3714c-150">**Concessional Code**</span><span class="sxs-lookup"><span data-stu-id="3714c-150">**Concessional Code**</span></span>|<span data-ttu-id="3714c-151">Specifies the concessional code.</span><span class="sxs-lookup"><span data-stu-id="3714c-151">Specifies the concessional code.</span></span>|
    |<span data-ttu-id="3714c-152">**Nature of Remittance**</span><span class="sxs-lookup"><span data-stu-id="3714c-152">**Nature of Remittance**</span></span>|<span data-ttu-id="3714c-153">Specifies whether the nature of remittance is applicable or not.</span><span class="sxs-lookup"><span data-stu-id="3714c-153">Specifies whether the nature of remittance is applicable or not.</span></span>|
    |<span data-ttu-id="3714c-154">**Act Applicable**</span><span class="sxs-lookup"><span data-stu-id="3714c-154">**Act Applicable**</span></span>|<span data-ttu-id="3714c-155">Specifies the applicable act.</span><span class="sxs-lookup"><span data-stu-id="3714c-155">Specifies the applicable act.</span></span>|
    |<span data-ttu-id="3714c-156">**Currency Code**</span><span class="sxs-lookup"><span data-stu-id="3714c-156">**Currency Code**</span></span>|<span data-ttu-id="3714c-157">Specifies the currency code.</span><span class="sxs-lookup"><span data-stu-id="3714c-157">Specifies the currency code.</span></span>|
    |<span data-ttu-id="3714c-158">**TDS %**</span><span class="sxs-lookup"><span data-stu-id="3714c-158">**TDS %**</span></span>|<span data-ttu-id="3714c-159">Specifies the TDS rate.</span><span class="sxs-lookup"><span data-stu-id="3714c-159">Specifies the TDS rate.</span></span>|
    |<span data-ttu-id="3714c-160">**Non PAN TDS %**</span><span class="sxs-lookup"><span data-stu-id="3714c-160">**Non PAN TDS %**</span></span>|<span data-ttu-id="3714c-161">Specifies the TDS rate in case of non availability of PAN.</span><span class="sxs-lookup"><span data-stu-id="3714c-161">Specifies the TDS rate in case of non availability of PAN.</span></span>|
    |<span data-ttu-id="3714c-162">**Surcharge %**</span><span class="sxs-lookup"><span data-stu-id="3714c-162">**Surcharge %**</span></span>|<span data-ttu-id="3714c-163">Specifies the surcharge rate.</span><span class="sxs-lookup"><span data-stu-id="3714c-163">Specifies the surcharge rate.</span></span>|
    |<span data-ttu-id="3714c-164">**eCESS %**</span><span class="sxs-lookup"><span data-stu-id="3714c-164">**eCESS %**</span></span>|<span data-ttu-id="3714c-165">Specifies the eCess rate.</span><span class="sxs-lookup"><span data-stu-id="3714c-165">Specifies the eCess rate.</span></span>|
    |<span data-ttu-id="3714c-166">**SHE Cess %**</span><span class="sxs-lookup"><span data-stu-id="3714c-166">**SHE Cess %**</span></span>|<span data-ttu-id="3714c-167">Specifies the SHE Cess rate.</span><span class="sxs-lookup"><span data-stu-id="3714c-167">Specifies the SHE Cess rate.</span></span>|
    |<span data-ttu-id="3714c-168">**Surcharge Threshold Amount**</span><span class="sxs-lookup"><span data-stu-id="3714c-168">**Surcharge Threshold Amount**</span></span>|<span data-ttu-id="3714c-169">Specifies the threshold amount applicable for surcharge.</span><span class="sxs-lookup"><span data-stu-id="3714c-169">Specifies the threshold amount applicable for surcharge.</span></span>|
    |<span data-ttu-id="3714c-170">**TDS Threshold Amount**</span><span class="sxs-lookup"><span data-stu-id="3714c-170">**TDS Threshold Amount**</span></span>|<span data-ttu-id="3714c-171">Specifies the threshold amount applicable for TDS.</span><span class="sxs-lookup"><span data-stu-id="3714c-171">Specifies the threshold amount applicable for TDS.</span></span>|
    |<span data-ttu-id="3714c-172">**Per Contract Value**</span><span class="sxs-lookup"><span data-stu-id="3714c-172">**Per Contract Value**</span></span>|<span data-ttu-id="3714c-173">Specifies the per contract value.</span><span class="sxs-lookup"><span data-stu-id="3714c-173">Specifies the per contract value.</span></span>|


## <a name="to-set-up-tax-accounting-period"></a><span data-ttu-id="3714c-174">To set up tax accounting period.</span><span class="sxs-lookup"><span data-stu-id="3714c-174">To set up tax accounting period.</span></span>

<span data-ttu-id="3714c-175">Tax Accounting period and quarters need to be defined for TDS calculation.</span><span class="sxs-lookup"><span data-stu-id="3714c-175">Tax Accounting period and quarters need to be defined for TDS calculation.</span></span>

1. <span data-ttu-id="3714c-176">Choose the ![Search for Page or Report](image/search_small.png "Search for Page or Report icon") icon, enter **Tax Acc. Period Setup** , and then choose the related link.</span><span class="sxs-lookup"><span data-stu-id="3714c-176">Choose the ![Search for Page or Report](image/search_small.png "Search for Page or Report icon") icon, enter **Tax Acc. Period Setup** , and then choose the related link.</span></span> 
2. <span data-ttu-id="3714c-177">Fill in the fields as described in the following table.</span><span class="sxs-lookup"><span data-stu-id="3714c-177">Fill in the fields as described in the following table.</span></span>   

    |<span data-ttu-id="3714c-178">Field</span><span class="sxs-lookup"><span data-stu-id="3714c-178">Field</span></span>|<span data-ttu-id="3714c-179">Description</span><span class="sxs-lookup"><span data-stu-id="3714c-179">Description</span></span>|  
    |---------------------------------|---------------------------------------|   
    |<span data-ttu-id="3714c-180">**Code**</span><span class="sxs-lookup"><span data-stu-id="3714c-180">**Code**</span></span>|<span data-ttu-id="3714c-181">Enter the valid tax type.</span><span class="sxs-lookup"><span data-stu-id="3714c-181">Enter the valid tax type.</span></span>|  
    |<span data-ttu-id="3714c-182">**Description**</span><span class="sxs-lookup"><span data-stu-id="3714c-182">**Description**</span></span>|<span data-ttu-id="3714c-183">Specify the description of the tax type.</span><span class="sxs-lookup"><span data-stu-id="3714c-183">Specify the description of the tax type.</span></span>|

3. <span data-ttu-id="3714c-184">Select the Tax Type -> Action -> Tax Accounting Period -> Create Year, fill the following information and accounting period will be created.</span><span class="sxs-lookup"><span data-stu-id="3714c-184">Select the Tax Type -> Action -> Tax Accounting Period -> Create Year, fill the following information and accounting period will be created.</span></span>
    
    |<span data-ttu-id="3714c-185">Field</span><span class="sxs-lookup"><span data-stu-id="3714c-185">Field</span></span>|<span data-ttu-id="3714c-186">Description</span><span class="sxs-lookup"><span data-stu-id="3714c-186">Description</span></span>|  
    |---------------------------------|---------------------------------------|   
    |<span data-ttu-id="3714c-187">**Tax Type**</span><span class="sxs-lookup"><span data-stu-id="3714c-187">**Tax Type**</span></span>|<span data-ttu-id="3714c-188">Select the valid tax type.</span><span class="sxs-lookup"><span data-stu-id="3714c-188">Select the valid tax type.</span></span>|  
    |<span data-ttu-id="3714c-189">**Starting Date**</span><span class="sxs-lookup"><span data-stu-id="3714c-189">**Starting Date**</span></span>|<span data-ttu-id="3714c-190">Specify the starting date of the accounting period.</span><span class="sxs-lookup"><span data-stu-id="3714c-190">Specify the starting date of the accounting period.</span></span>|
    |<span data-ttu-id="3714c-191">**No. of Periods**</span><span class="sxs-lookup"><span data-stu-id="3714c-191">**No. of Periods**</span></span>|<span data-ttu-id="3714c-192">Specify the number of periods.</span><span class="sxs-lookup"><span data-stu-id="3714c-192">Specify the number of periods.</span></span>|
    |<span data-ttu-id="3714c-193">**Period Length**</span><span class="sxs-lookup"><span data-stu-id="3714c-193">**Period Length**</span></span>|<span data-ttu-id="3714c-194">Specify the length of the period.</span><span class="sxs-lookup"><span data-stu-id="3714c-194">Specify the length of the period.</span></span>|

## <a name="to-set-up-tan"></a><span data-ttu-id="3714c-195">To set up T.A.N</span><span class="sxs-lookup"><span data-stu-id="3714c-195">To set up T.A.N</span></span>

<span data-ttu-id="3714c-196">Tax Deduction Account Number (T.A.N) allotted to a company can be more than one, depending on the number of branch locations from where the company files its returns.</span><span class="sxs-lookup"><span data-stu-id="3714c-196">Tax Deduction Account Number (T.A.N) allotted to a company can be more than one, depending on the number of branch locations from where the company files its returns.</span></span> <span data-ttu-id="3714c-197">All the account numbers allotted to a company need to capture here.</span><span class="sxs-lookup"><span data-stu-id="3714c-197">All the account numbers allotted to a company need to capture here.</span></span>

1. <span data-ttu-id="3714c-198">Choose the ![Search for Page or Report](image/search_small.png "Search for Page or Report icon") icon, enter **T.A.N Nos.** , and then choose the related link.</span><span class="sxs-lookup"><span data-stu-id="3714c-198">Choose the ![Search for Page or Report](image/search_small.png "Search for Page or Report icon") icon, enter **T.A.N Nos.** , and then choose the related link.</span></span> 
2. <span data-ttu-id="3714c-199">Fill in the fields as described in the following table.</span><span class="sxs-lookup"><span data-stu-id="3714c-199">Fill in the fields as described in the following table.</span></span>   

    |<span data-ttu-id="3714c-200">Field</span><span class="sxs-lookup"><span data-stu-id="3714c-200">Field</span></span>|<span data-ttu-id="3714c-201">Description</span><span class="sxs-lookup"><span data-stu-id="3714c-201">Description</span></span>|  
    |---------------------------------|---------------------------------------|   
    |<span data-ttu-id="3714c-202">**Code**</span><span class="sxs-lookup"><span data-stu-id="3714c-202">**Code**</span></span>|<span data-ttu-id="3714c-203">Enter the valid registration number provided by authority.</span><span class="sxs-lookup"><span data-stu-id="3714c-203">Enter the valid registration number provided by authority.</span></span>|  
    |<span data-ttu-id="3714c-204">**Description**</span><span class="sxs-lookup"><span data-stu-id="3714c-204">**Description**</span></span>|<span data-ttu-id="3714c-205">Specify the description of the registration number.</span><span class="sxs-lookup"><span data-stu-id="3714c-205">Specify the description of the registration number.</span></span>|
    

> [!TIP]
>
> <span data-ttu-id="3714c-206">It is mandatory to enter the T.A.N, on all TDS Transactions.</span><span class="sxs-lookup"><span data-stu-id="3714c-206">It is mandatory to enter the T.A.N, on all TDS Transactions.</span></span>

## <a name="to-set-up-assessee-code"></a><span data-ttu-id="3714c-207">To set up assessee code</span><span class="sxs-lookup"><span data-stu-id="3714c-207">To set up assessee code</span></span>

<span data-ttu-id="3714c-208">Income Tax Act 1961 defines 'Assessee' as a person by whom any tax or any other sum of money is payable under this Act. The rates of TDS are different for different types of Assessee.</span><span class="sxs-lookup"><span data-stu-id="3714c-208">Income Tax Act 1961 defines 'Assessee' as a person by whom any tax or any other sum of money is payable under this Act. The rates of TDS are different for different types of Assessee.</span></span>

1. <span data-ttu-id="3714c-209">Choose the ![Search for Page or Report](image/search_small.png "Search for Page or Report icon") icon, enter **Assessee Codes** , and then choose the related link.</span><span class="sxs-lookup"><span data-stu-id="3714c-209">Choose the ![Search for Page or Report](image/search_small.png "Search for Page or Report icon") icon, enter **Assessee Codes** , and then choose the related link.</span></span> 
2. <span data-ttu-id="3714c-210">Fill in the fields as described in the following table.</span><span class="sxs-lookup"><span data-stu-id="3714c-210">Fill in the fields as described in the following table.</span></span>   

    |<span data-ttu-id="3714c-211">Field</span><span class="sxs-lookup"><span data-stu-id="3714c-211">Field</span></span>|<span data-ttu-id="3714c-212">Description</span><span class="sxs-lookup"><span data-stu-id="3714c-212">Description</span></span>|  
    |---------------------------------|---------------------------------------|   
    |<span data-ttu-id="3714c-213">**Code**</span><span class="sxs-lookup"><span data-stu-id="3714c-213">**Code**</span></span>|<span data-ttu-id="3714c-214">Enter the valid Assessee Code, for example, IND, COM.</span><span class="sxs-lookup"><span data-stu-id="3714c-214">Enter the valid Assessee Code, for example, IND, COM.</span></span>|  
    |<span data-ttu-id="3714c-215">**Description**</span><span class="sxs-lookup"><span data-stu-id="3714c-215">**Description**</span></span>|<span data-ttu-id="3714c-216">Enter the description of the assessee code.</span><span class="sxs-lookup"><span data-stu-id="3714c-216">Enter the description of the assessee code.</span></span>|
    |<span data-ttu-id="3714c-217">**Type**</span><span class="sxs-lookup"><span data-stu-id="3714c-217">**Type**</span></span>|<span data-ttu-id="3714c-218">Select the type of the assessee from drop down list as Company or Others.</span><span class="sxs-lookup"><span data-stu-id="3714c-218">Select the type of the assessee from drop down list as Company or Others.</span></span>|

> [!TIP]
>
> <span data-ttu-id="3714c-219">Type should be selected correctly while creating Assessee codes as it will reflect in eTDS returns.</span><span class="sxs-lookup"><span data-stu-id="3714c-219">Type should be selected correctly while creating Assessee codes as it will reflect in eTDS returns.</span></span>

## <a name="to-set-up-tds-section"></a><span data-ttu-id="3714c-220">To set up TDS section</span><span class="sxs-lookup"><span data-stu-id="3714c-220">To set up TDS section</span></span>

<span data-ttu-id="3714c-221">TDS Section represents the various sections under which tax deduction takes place as per the Income Tax Act 1961.</span><span class="sxs-lookup"><span data-stu-id="3714c-221">TDS Section represents the various sections under which tax deduction takes place as per the Income Tax Act 1961.</span></span>

1. <span data-ttu-id="3714c-222">Choose the ![Search for Page or Report](image/search_small.png "Search for Page or Report icon") icon, enter **TDS Sections** , and then choose the related link.</span><span class="sxs-lookup"><span data-stu-id="3714c-222">Choose the ![Search for Page or Report](image/search_small.png "Search for Page or Report icon") icon, enter **TDS Sections** , and then choose the related link.</span></span>
2. <span data-ttu-id="3714c-223">Fill in the fields as described in the following table.</span><span class="sxs-lookup"><span data-stu-id="3714c-223">Fill in the fields as described in the following table.</span></span>

    |<span data-ttu-id="3714c-224">Field</span><span class="sxs-lookup"><span data-stu-id="3714c-224">Field</span></span>|<span data-ttu-id="3714c-225">Description</span><span class="sxs-lookup"><span data-stu-id="3714c-225">Description</span></span>|  
    |---------------------------------|---------------------------------------|   
    |<span data-ttu-id="3714c-226">**Code**</span><span class="sxs-lookup"><span data-stu-id="3714c-226">**Code**</span></span>|<span data-ttu-id="3714c-227">Enter the valid TDS Section applicable as per the Income Tax Act, 1961.</span><span class="sxs-lookup"><span data-stu-id="3714c-227">Enter the valid TDS Section applicable as per the Income Tax Act, 1961.</span></span>|  
    |<span data-ttu-id="3714c-228">**Description**</span><span class="sxs-lookup"><span data-stu-id="3714c-228">**Description**</span></span>|<span data-ttu-id="3714c-229">Enter the description of the mentioned TDS Section.</span><span class="sxs-lookup"><span data-stu-id="3714c-229">Enter the description of the mentioned TDS Section.</span></span>|
    |<span data-ttu-id="3714c-230">**e-TDS**</span><span class="sxs-lookup"><span data-stu-id="3714c-230">**e-TDS**</span></span>|<span data-ttu-id="3714c-231">Specifies the section code to be used in the TDS return.</span><span class="sxs-lookup"><span data-stu-id="3714c-231">Specifies the section code to be used in the TDS return.</span></span>|

## <a name="to-set-up-concessional-codes"></a><span data-ttu-id="3714c-232">To set up concessional codes</span><span class="sxs-lookup"><span data-stu-id="3714c-232">To set up concessional codes</span></span>

<span data-ttu-id="3714c-233">Concessional codes are used for cases authorised for concessional rates exclusively defined by the government.</span><span class="sxs-lookup"><span data-stu-id="3714c-233">Concessional codes are used for cases authorized for concessional rates exclusively defined by the government.</span></span>

1. <span data-ttu-id="3714c-234">Choose the ![Search for Page or Report](image/search_small.png "Search for Page or Report icon") icon, enter **Concessional Codes** , and then choose the related link.</span><span class="sxs-lookup"><span data-stu-id="3714c-234">Choose the ![Search for Page or Report](image/search_small.png "Search for Page or Report icon") icon, enter **Concessional Codes** , and then choose the related link.</span></span>
2. <span data-ttu-id="3714c-235">Fill in the fields as described in the following table.</span><span class="sxs-lookup"><span data-stu-id="3714c-235">Fill in the fields as described in the following table.</span></span>

    |<span data-ttu-id="3714c-236">Field</span><span class="sxs-lookup"><span data-stu-id="3714c-236">Field</span></span>|<span data-ttu-id="3714c-237">Description</span><span class="sxs-lookup"><span data-stu-id="3714c-237">Description</span></span>|  
    |---------------------------------|---------------------------------------|   
    |<span data-ttu-id="3714c-238">**Code**</span><span class="sxs-lookup"><span data-stu-id="3714c-238">**Code**</span></span>|<span data-ttu-id="3714c-239">Enter the valid Concessional Codes applicable as per the Income Tax Act.</span><span class="sxs-lookup"><span data-stu-id="3714c-239">Enter the valid Concessional Codes applicable as per the Income Tax Act.</span></span>|  
    |<span data-ttu-id="3714c-240">**Description**</span><span class="sxs-lookup"><span data-stu-id="3714c-240">**Description**</span></span>|<span data-ttu-id="3714c-241">Enter the description of the mentioned Concessional Codes.</span><span class="sxs-lookup"><span data-stu-id="3714c-241">Enter the description of the mentioned Concessional Codes.</span></span>|

## <a name="to-set-up-tds-nature-of-remittances"></a><span data-ttu-id="3714c-242">To set up TDS nature of remittances</span><span class="sxs-lookup"><span data-stu-id="3714c-242">To set up TDS nature of remittances</span></span>

<span data-ttu-id="3714c-243">Specifies the type of remittance.</span><span class="sxs-lookup"><span data-stu-id="3714c-243">Specifies the type of remittance.</span></span>

1. <span data-ttu-id="3714c-244">Choose the ![Search for Page or Report](image/search_small.png "Search for Page or Report icon") icon, enter **Nature of Remittances** , and then choose the related link.</span><span class="sxs-lookup"><span data-stu-id="3714c-244">Choose the ![Search for Page or Report](image/search_small.png "Search for Page or Report icon") icon, enter **Nature of Remittances** , and then choose the related link.</span></span>
2. <span data-ttu-id="3714c-245">Fill in the fields as described in the following table.</span><span class="sxs-lookup"><span data-stu-id="3714c-245">Fill in the fields as described in the following table.</span></span>

    |<span data-ttu-id="3714c-246">Field</span><span class="sxs-lookup"><span data-stu-id="3714c-246">Field</span></span>|<span data-ttu-id="3714c-247">Description</span><span class="sxs-lookup"><span data-stu-id="3714c-247">Description</span></span>|  
    |---------------------------------|---------------------------------------|   
    |<span data-ttu-id="3714c-248">**Code**</span><span class="sxs-lookup"><span data-stu-id="3714c-248">**Code**</span></span>|<span data-ttu-id="3714c-249">Enter the valid nature of remittance code applicable.</span><span class="sxs-lookup"><span data-stu-id="3714c-249">Enter the valid nature of remittance code applicable.</span></span>|
    |<span data-ttu-id="3714c-250">**Description**</span><span class="sxs-lookup"><span data-stu-id="3714c-250">**Description**</span></span>|<span data-ttu-id="3714c-251">Enter the description of the code.</span><span class="sxs-lookup"><span data-stu-id="3714c-251">Enter the description of the code.</span></span>|

## <a name="to-set-up-act-applicable"></a><span data-ttu-id="3714c-252">To set up act applicable</span><span class="sxs-lookup"><span data-stu-id="3714c-252">To set up act applicable</span></span>

<span data-ttu-id="3714c-253">Specifies the Act under which income from Non-resident Indians will be taxed either the Income Tax Act (IT-Act), or as per the relevant rates prescribed in the relevant Double Tax Avoidance Agreement (DTAA).</span><span class="sxs-lookup"><span data-stu-id="3714c-253">Specifies the Act under which income from Non-resident Indians will be taxed either the Income Tax Act (IT-Act), or as per the relevant rates prescribed in the relevant Double Tax Avoidance Agreement (DTAA).</span></span>

1. <span data-ttu-id="3714c-254">Choose the ![Search for Page or Report](image/search_small.png "Search for Page or Report icon") icon, enter **Act Applicable** , and then choose the related link.</span><span class="sxs-lookup"><span data-stu-id="3714c-254">Choose the ![Search for Page or Report](image/search_small.png "Search for Page or Report icon") icon, enter **Act Applicable** , and then choose the related link.</span></span>
2. <span data-ttu-id="3714c-255">Fill in the fields as described in the following table.</span><span class="sxs-lookup"><span data-stu-id="3714c-255">Fill in the fields as described in the following table.</span></span>

    |<span data-ttu-id="3714c-256">Field</span><span class="sxs-lookup"><span data-stu-id="3714c-256">Field</span></span>|<span data-ttu-id="3714c-257">Description</span><span class="sxs-lookup"><span data-stu-id="3714c-257">Description</span></span>|  
    |---------------------------------|---------------------------------------|   
    |<span data-ttu-id="3714c-258">**Code**</span><span class="sxs-lookup"><span data-stu-id="3714c-258">**Code**</span></span>|<span data-ttu-id="3714c-259">Enter the valid Concessional Codes applicable as per the Income Tax Act, 1961.</span><span class="sxs-lookup"><span data-stu-id="3714c-259">Enter the valid Concessional Codes applicable as per the Income Tax Act, 1961.</span></span>| 

## <a name="to-set-up-tds-posting-setup"></a><span data-ttu-id="3714c-260">To set up TDS posting setup</span><span class="sxs-lookup"><span data-stu-id="3714c-260">To set up TDS posting setup</span></span>

<span data-ttu-id="3714c-261">Specifies the general ledger account for each TDS Section defined in the system.</span><span class="sxs-lookup"><span data-stu-id="3714c-261">Specifies the general ledger account for each TDS Section defined in the system.</span></span> <span data-ttu-id="3714c-262">System will update the TDS payable amount in the defined general ledger account.</span><span class="sxs-lookup"><span data-stu-id="3714c-262">System will update the TDS payable amount in the defined general ledger account.</span></span>

1. <span data-ttu-id="3714c-263">Choose the ![Search for Page or Report](image/search_small.png "Search for Page or Report icon") icon, enter **TDS Posting Setup** , and then choose the related link.</span><span class="sxs-lookup"><span data-stu-id="3714c-263">Choose the ![Search for Page or Report](image/search_small.png "Search for Page or Report icon") icon, enter **TDS Posting Setup** , and then choose the related link.</span></span>
2. <span data-ttu-id="3714c-264">Fill in the fields as described in the following table.</span><span class="sxs-lookup"><span data-stu-id="3714c-264">Fill in the fields as described in the following table.</span></span>

    |<span data-ttu-id="3714c-265">Field</span><span class="sxs-lookup"><span data-stu-id="3714c-265">Field</span></span>|<span data-ttu-id="3714c-266">Description</span><span class="sxs-lookup"><span data-stu-id="3714c-266">Description</span></span>|  
    |---------------------------------|---------------------------------------|   
    |<span data-ttu-id="3714c-267">**TDS Section**</span><span class="sxs-lookup"><span data-stu-id="3714c-267">**TDS Section**</span></span>|<span data-ttu-id="3714c-268">Enter the valid TDS Section.</span><span class="sxs-lookup"><span data-stu-id="3714c-268">Enter the valid TDS Section.</span></span>|
    |<span data-ttu-id="3714c-269">**Effective Date**</span><span class="sxs-lookup"><span data-stu-id="3714c-269">**Effective Date**</span></span>|<span data-ttu-id="3714c-270">Specifies the starting date.</span><span class="sxs-lookup"><span data-stu-id="3714c-270">Specifies the starting date.</span></span>|
    |<span data-ttu-id="3714c-271">**TDS Account**</span><span class="sxs-lookup"><span data-stu-id="3714c-271">**TDS Account**</span></span>|<span data-ttu-id="3714c-272">Specifies the general ledger account for posting of TDS payable amount.</span><span class="sxs-lookup"><span data-stu-id="3714c-272">Specifies the general ledger account for posting of TDS payable amount.</span></span>|

## <a name="to-set-up-tds-rounding-precision"></a><span data-ttu-id="3714c-273">To set up TDS rounding precision</span><span class="sxs-lookup"><span data-stu-id="3714c-273">To set up TDS rounding precision</span></span>

<span data-ttu-id="3714c-274">Rounding precision for each and every component can be defined in system.</span><span class="sxs-lookup"><span data-stu-id="3714c-274">Rounding precision for each and every component can be defined in system.</span></span>

1. <span data-ttu-id="3714c-275">Choose the ![Search for Page or Report](image/search_small.png "Search for Page or Report icon") icon, enter **Tax Type** -> Select **TDS** -> **Tax Component** , and then choose the related link.</span><span class="sxs-lookup"><span data-stu-id="3714c-275">Choose the ![Search for Page or Report](image/search_small.png "Search for Page or Report icon") icon, enter **Tax Type** -> Select **TDS** -> **Tax Component** , and then choose the related link.</span></span> 

2. <span data-ttu-id="3714c-276">Define the relevant rounding precision against each tax components.</span><span class="sxs-lookup"><span data-stu-id="3714c-276">Define the relevant rounding precision against each tax components.</span></span>


## <a name="to-set-up-tds-in-vendor-master"></a><span data-ttu-id="3714c-277">To set up TDS in vendor master</span><span class="sxs-lookup"><span data-stu-id="3714c-277">To set up TDS in vendor master</span></span>

<span data-ttu-id="3714c-278">TDS Section and concessional codes need to be defined for each vendor that is liable to TDS.</span><span class="sxs-lookup"><span data-stu-id="3714c-278">TDS Section and concessional codes need to be defined for each vendor that is liable to TDS.</span></span> <span data-ttu-id="3714c-279">Multiple TDS sections can be attached to one vendor.</span><span class="sxs-lookup"><span data-stu-id="3714c-279">Multiple TDS sections can be attached to one vendor.</span></span>

- <span data-ttu-id="3714c-280">To define the TDS Sections in the Vendor Card</span><span class="sxs-lookup"><span data-stu-id="3714c-280">To define the TDS Sections in the Vendor Card</span></span>

  1. <span data-ttu-id="3714c-281">Choose the ![Search for Page or Report](image/search_small.png "Search for Page or Report icon") icon, enter **Vendors** -> **Navigate** -> **Allowed Sections** and then choose the related link.</span><span class="sxs-lookup"><span data-stu-id="3714c-281">Choose the ![Search for Page or Report](image/search_small.png "Search for Page or Report icon") icon, enter **Vendors** -> **Navigate** -> **Allowed Sections** and then choose the related link.</span></span>
  2. <span data-ttu-id="3714c-282">**Assessee Code** needs to be filled on the vendor master.</span><span class="sxs-lookup"><span data-stu-id="3714c-282">**Assessee Code** needs to be filled on the vendor master.</span></span>
  3. <span data-ttu-id="3714c-283">**PAN** needs to be filled on vendor master, in case of no PAN is provided, higher rate of TDS will be deducted.</span><span class="sxs-lookup"><span data-stu-id="3714c-283">**PAN** needs to be filled on vendor master, in case of no PAN is provided, higher rate of TDS will be deducted.</span></span>
  4. <span data-ttu-id="3714c-284">Fill in the fields as described in the following table.</span><span class="sxs-lookup"><span data-stu-id="3714c-284">Fill in the fields as described in the following table.</span></span>

      |<span data-ttu-id="3714c-285">Field</span><span class="sxs-lookup"><span data-stu-id="3714c-285">Field</span></span>|<span data-ttu-id="3714c-286">Description</span><span class="sxs-lookup"><span data-stu-id="3714c-286">Description</span></span>|  
      |---------------------------------|---------------------------------------|
      |<span data-ttu-id="3714c-287">**TDS Section**</span><span class="sxs-lookup"><span data-stu-id="3714c-287">**TDS Section**</span></span>|<span data-ttu-id="3714c-288">Select the valid section from lookup depending on the kind of services provided by the vendor.</span><span class="sxs-lookup"><span data-stu-id="3714c-288">Select the valid section from lookup depending on the kind of services provided by the vendor.</span></span>|
      |<span data-ttu-id="3714c-289">**TDS Section Description**</span><span class="sxs-lookup"><span data-stu-id="3714c-289">**TDS Section Description**</span></span>|<span data-ttu-id="3714c-290">Enter the description of the selected section.</span><span class="sxs-lookup"><span data-stu-id="3714c-290">Enter the description of the selected section.</span></span>|
      |<span data-ttu-id="3714c-291">**Default Section**</span><span class="sxs-lookup"><span data-stu-id="3714c-291">**Default Section**</span></span>|<span data-ttu-id="3714c-292">Mark true if the section needs to be defined as default section.</span><span class="sxs-lookup"><span data-stu-id="3714c-292">Mark true if the section needs to be defined as default section.</span></span>|
      |<span data-ttu-id="3714c-293">**Threshold Overlook**</span><span class="sxs-lookup"><span data-stu-id="3714c-293">**Threshold Overlook**</span></span>|<span data-ttu-id="3714c-294">Place a check mark in this field to overlook the TDS Threshold amount defined in 'Tax Rates'</span><span class="sxs-lookup"><span data-stu-id="3714c-294">Place a check mark in this field to overlook the TDS Threshold amount defined in 'Tax Rates'</span></span>|
      |<span data-ttu-id="3714c-295">**Surcharge Overlook**</span><span class="sxs-lookup"><span data-stu-id="3714c-295">**Surcharge Overlook**</span></span>|<span data-ttu-id="3714c-296">Place a check mark in this field to overlook the Surcharge Threshold amount defined in 'Tax Rates'</span><span class="sxs-lookup"><span data-stu-id="3714c-296">Place a check mark in this field to overlook the Surcharge Threshold amount defined in 'Tax Rates'</span></span>|
      |<span data-ttu-id="3714c-297">**Non Resident Payment**</span><span class="sxs-lookup"><span data-stu-id="3714c-297">**Non Resident Payment**</span></span>|<span data-ttu-id="3714c-298">Identify if the TDS Section deals with non-resident.</span><span class="sxs-lookup"><span data-stu-id="3714c-298">Identify if the TDS Section deals with non-resident.</span></span> <span data-ttu-id="3714c-299">This identification will help the system to generate eTDS for Non-Residents.</span><span class="sxs-lookup"><span data-stu-id="3714c-299">This identification will help the system to generate eTDS for Non-Residents.</span></span>|
      |<span data-ttu-id="3714c-300">**Nature of Remittance**</span><span class="sxs-lookup"><span data-stu-id="3714c-300">**Nature of Remittance**</span></span>|<span data-ttu-id="3714c-301">Select the Nature of Remittance.</span><span class="sxs-lookup"><span data-stu-id="3714c-301">Select the Nature of Remittance.</span></span>|
      |<span data-ttu-id="3714c-302">**Act Applicable**</span><span class="sxs-lookup"><span data-stu-id="3714c-302">**Act Applicable**</span></span>|<span data-ttu-id="3714c-303">Select  applicable act for generating in eTDS returns.</span><span class="sxs-lookup"><span data-stu-id="3714c-303">Select  applicable act for generating in eTDS returns.</span></span>|

- <span data-ttu-id="3714c-304">To define the concessional code in vendor card</span><span class="sxs-lookup"><span data-stu-id="3714c-304">To define the concessional code in vendor card</span></span>

  1. <span data-ttu-id="3714c-305">Choose the ![Search for Page or Report](image/search_small.png "Search for Page or Report icon") icon, enter **Vendors** -> **Navigate** -> **TDS Concessional Codes** and then choose the related link.</span><span class="sxs-lookup"><span data-stu-id="3714c-305">Choose the ![Search for Page or Report](image/search_small.png "Search for Page or Report icon") icon, enter **Vendors** -> **Navigate** -> **TDS Concessional Codes** and then choose the related link.</span></span>
  2. <span data-ttu-id="3714c-306">Fill in the fields as described in the following table.</span><span class="sxs-lookup"><span data-stu-id="3714c-306">Fill in the fields as described in the following table.</span></span>

      |<span data-ttu-id="3714c-307">Field</span><span class="sxs-lookup"><span data-stu-id="3714c-307">Field</span></span>|<span data-ttu-id="3714c-308">Description</span><span class="sxs-lookup"><span data-stu-id="3714c-308">Description</span></span>|  
      |---------------------------------|---------------------------------------|
      |<span data-ttu-id="3714c-309">**Section**</span><span class="sxs-lookup"><span data-stu-id="3714c-309">**Section**</span></span>|<span data-ttu-id="3714c-310">Select the valid section from lookup depending on the kind of services provided by vendor.</span><span class="sxs-lookup"><span data-stu-id="3714c-310">Select the valid section from lookup depending on the kind of services provided by vendor.</span></span>|
      |<span data-ttu-id="3714c-311">**Concessional Code**</span><span class="sxs-lookup"><span data-stu-id="3714c-311">**Concessional Code**</span></span>|<span data-ttu-id="3714c-312">Select the valid concessional code from lookup depending on the kind of services provided by vendor.</span><span class="sxs-lookup"><span data-stu-id="3714c-312">Select the valid concessional code from lookup depending on the kind of services provided by vendor.</span></span>|
      |<span data-ttu-id="3714c-313">**Certificate No.**</span><span class="sxs-lookup"><span data-stu-id="3714c-313">**Certificate No.**</span></span>|<span data-ttu-id="3714c-314">Certificate number provided by the vendor can be defined to justify the lower tax deduction.</span><span class="sxs-lookup"><span data-stu-id="3714c-314">Certificate number provided by the vendor can be defined to justify the lower tax deduction.</span></span>|
      
## <a name="to-set-up-tds-in-location-master"></a><span data-ttu-id="3714c-315">To set up TDS in location master</span><span class="sxs-lookup"><span data-stu-id="3714c-315">To set up TDS in location master</span></span>

<span data-ttu-id="3714c-316">**T.A.N** needs to be defined on locations from where the company files its returns.</span><span class="sxs-lookup"><span data-stu-id="3714c-316">**T.A.N** needs to be defined on locations from where the company files its returns.</span></span>

## <a name="to-set-up-tds-in-company-information"></a><span data-ttu-id="3714c-317">To set up TDS in company information</span><span class="sxs-lookup"><span data-stu-id="3714c-317">To set up TDS in company information</span></span>

-  <span data-ttu-id="3714c-318">Following information needs to be defined in company information.</span><span class="sxs-lookup"><span data-stu-id="3714c-318">Following information needs to be defined in company information.</span></span>

      |<span data-ttu-id="3714c-319">Field</span><span class="sxs-lookup"><span data-stu-id="3714c-319">Field</span></span>|<span data-ttu-id="3714c-320">Description</span><span class="sxs-lookup"><span data-stu-id="3714c-320">Description</span></span>|  
      |---------------------------------|---------------------------------------|
      |<span data-ttu-id="3714c-321">**T.A.N No.**</span><span class="sxs-lookup"><span data-stu-id="3714c-321">**T.A.N No.**</span></span>|<span data-ttu-id="3714c-322">Specifies the TAN of the legal entity.</span><span class="sxs-lookup"><span data-stu-id="3714c-322">Specifies the TAN of the legal entity.</span></span>|
      |<span data-ttu-id="3714c-323">**P.A.N No.**</span><span class="sxs-lookup"><span data-stu-id="3714c-323">**P.A.N No.**</span></span>|<span data-ttu-id="3714c-324">Specifies the PAN of the legal entity.</span><span class="sxs-lookup"><span data-stu-id="3714c-324">Specifies the PAN of the legal entity.</span></span>|
      |<span data-ttu-id="3714c-325">**Deductor Category**</span><span class="sxs-lookup"><span data-stu-id="3714c-325">**Deductor Category**</span></span>|<span data-ttu-id="3714c-326">Specifies the deductor category of the legal entity.</span><span class="sxs-lookup"><span data-stu-id="3714c-326">Specifies the deductor category of the legal entity.</span></span>|
      |<span data-ttu-id="3714c-327">**PAO Code**</span><span class="sxs-lookup"><span data-stu-id="3714c-327">**PAO Code**</span></span>|<span data-ttu-id="3714c-328">Specifies the PAO code.</span><span class="sxs-lookup"><span data-stu-id="3714c-328">Specifies the PAO code.</span></span>|
      |<span data-ttu-id="3714c-329">**PAO Registration No.**</span><span class="sxs-lookup"><span data-stu-id="3714c-329">**PAO Registration No.**</span></span>|<span data-ttu-id="3714c-330">Specifies PAO registration number.</span><span class="sxs-lookup"><span data-stu-id="3714c-330">Specifies PAO registration number.</span></span>|
      |<span data-ttu-id="3714c-331">**DDO Code**</span><span class="sxs-lookup"><span data-stu-id="3714c-331">**DDO Code**</span></span>|<span data-ttu-id="3714c-332">Specifies DDO code.</span><span class="sxs-lookup"><span data-stu-id="3714c-332">Specifies DDO code.</span></span>|
      |<span data-ttu-id="3714c-333">**DDO Registration No.**</span><span class="sxs-lookup"><span data-stu-id="3714c-333">**DDO Registration No.**</span></span>|<span data-ttu-id="3714c-334">Specifies the DDO registration number.</span><span class="sxs-lookup"><span data-stu-id="3714c-334">Specifies the DDO registration number.</span></span>|
      |<span data-ttu-id="3714c-335">**Ministry Type**</span><span class="sxs-lookup"><span data-stu-id="3714c-335">**Ministry Type**</span></span>|<span data-ttu-id="3714c-336">Specifies the Ministry type.</span><span class="sxs-lookup"><span data-stu-id="3714c-336">Specifies the Ministry type.</span></span>|
      |<span data-ttu-id="3714c-337">**Ministry Code**</span><span class="sxs-lookup"><span data-stu-id="3714c-337">**Ministry Code**</span></span>|<span data-ttu-id="3714c-338">Specifies the Ministry code.</span><span class="sxs-lookup"><span data-stu-id="3714c-338">Specifies the Ministry code.</span></span>|

## <a name="to-set-up-tds-in-state-code"></a><span data-ttu-id="3714c-339">To set up TDS in state code</span><span class="sxs-lookup"><span data-stu-id="3714c-339">To set up TDS in state code</span></span>

<span data-ttu-id="3714c-340">**State Code for eTDS/TCS** needs to be defined on States master.</span><span class="sxs-lookup"><span data-stu-id="3714c-340">**State Code for eTDS/TCS** needs to be defined on States master.</span></span>




















