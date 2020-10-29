---
title: TDS on Provisional Entries
description: TDS on Provisional Entries
author: v-debapd
ms.service: dynamics365-business-central
ms.topic: article
ms.devlang: na
ms.tgt_pltfrm: na
ms.workload: na
ms.search.keywords: India, local, IN, English
ms.date: 10/01/2020
ms.author: v-debapd
ms.openlocfilehash: 7a73ddfc692ea12e61df211889aa1712dd84c1f7
ms.sourcegitcommit: ddbb5cede750df1baba4b3eab8fbed6744b5b9d6
ms.translationtype: HT
ms.contentlocale: en-IN
ms.lasthandoff: 10/01/2020
ms.locfileid: "3948606"
---
# <a name="tds-on-provisional-entries"></a><span data-ttu-id="94b73-103">TDS on Provisional Entries</span><span class="sxs-lookup"><span data-stu-id="94b73-103">TDS on Provisional Entries</span></span>

[!INCLUDE[vnext_preview](../../includes/vnext_preview.md)]

<span data-ttu-id="94b73-104">As per TDS rules, tax (TDS) has to be deducted at source, when amount is paid or credited to the account of the payee whichever is earlier.</span><span class="sxs-lookup"><span data-stu-id="94b73-104">As per TDS rules, tax (TDS) has to be deducted at source, when amount is paid or credited to the account of the payee whichever is earlier.</span></span> <span data-ttu-id="94b73-105">When the amount is credited to suspense account or any provisional account, then it is treated as amount is credited to the account of the payee and tax has to be deducted at source.</span><span class="sxs-lookup"><span data-stu-id="94b73-105">When the amount is credited to suspense account or any provisional account, then it is treated as amount is credited to the account of the payee and tax has to be deducted at source.</span></span> <span data-ttu-id="94b73-106">Hence, Tax has to be deducted at source even on provisions made in the books of accounts to which TDS provisions are applicable.</span><span class="sxs-lookup"><span data-stu-id="94b73-106">Hence, Tax has to be deducted at source even on provisions made in the books of accounts to which TDS provisions are applicable.</span></span>

<span data-ttu-id="94b73-107">A provisional entry should be posted before posting an actual entry, on posting of actual entry, provisional entry will be reversed.</span><span class="sxs-lookup"><span data-stu-id="94b73-107">A provisional entry should be posted before posting an actual entry, on posting of actual entry, provisional entry will be reversed.</span></span> <span data-ttu-id="94b73-108">As per requirement, TDS to be calculated on provisional entry and on posting of actual entry, system should not calculate TDS as it is deducted in provisional entry.</span><span class="sxs-lookup"><span data-stu-id="94b73-108">As per requirement, TDS to be calculated on provisional entry and on posting of actual entry, system should not calculate TDS as it is deducted in provisional entry.</span></span> 

<span data-ttu-id="94b73-109">For example, provisional expense journal has to be created and posted for INR 10000 against professional expense and 10% TDS to be calculated on the expense amount.</span><span class="sxs-lookup"><span data-stu-id="94b73-109">For example, provisional expense journal has to be created and posted for INR 10000 against professional expense and 10% TDS to be calculated on the expense amount.</span></span>

1.  <span data-ttu-id="94b73-110">Choose the ![Search for Page or Report](image/search_small.png "Search for Page or Report icon") icon, enter **Purchase Journal** , and then choose the related link.</span><span class="sxs-lookup"><span data-stu-id="94b73-110">Choose the ![Search for Page or Report](image/search_small.png "Search for Page or Report icon") icon, enter **Purchase Journal** , and then choose the related link.</span></span>
2.  <span data-ttu-id="94b73-111">Fill in the fields as described in the following table.</span><span class="sxs-lookup"><span data-stu-id="94b73-111">Fill in the fields as described in the following table.</span></span>

    |<span data-ttu-id="94b73-112">Field</span><span class="sxs-lookup"><span data-stu-id="94b73-112">Field</span></span>|<span data-ttu-id="94b73-113">Description</span><span class="sxs-lookup"><span data-stu-id="94b73-113">Description</span></span>|
    |----------------------------------|---------------------------------------|  
    |<span data-ttu-id="94b73-114">**Posting Date**</span><span class="sxs-lookup"><span data-stu-id="94b73-114">**Posting Date**</span></span>|<span data-ttu-id="94b73-115">Specify the date of entry.</span><span class="sxs-lookup"><span data-stu-id="94b73-115">Specify the date of entry.</span></span>|  
    |<span data-ttu-id="94b73-116">**Document Type**</span><span class="sxs-lookup"><span data-stu-id="94b73-116">**Document Type**</span></span>|<span data-ttu-id="94b73-117">Select Invoice as document type.</span><span class="sxs-lookup"><span data-stu-id="94b73-117">Select Invoice as document type.</span></span>|
    |<span data-ttu-id="94b73-118">**Document No.**</span><span class="sxs-lookup"><span data-stu-id="94b73-118">**Document No.**</span></span>|<span data-ttu-id="94b73-119">Specify the document number.</span><span class="sxs-lookup"><span data-stu-id="94b73-119">Specify the document number.</span></span>|
    |<span data-ttu-id="94b73-120">**Party Type**</span><span class="sxs-lookup"><span data-stu-id="94b73-120">**Party Type**</span></span>|<span data-ttu-id="94b73-121">Select Vendor as party type.</span><span class="sxs-lookup"><span data-stu-id="94b73-121">Select Vendor as party type.</span></span>|
    |<span data-ttu-id="94b73-122">**Party Code**</span><span class="sxs-lookup"><span data-stu-id="94b73-122">**Party Code**</span></span>|<span data-ttu-id="94b73-123">Select relevant vendor code.</span><span class="sxs-lookup"><span data-stu-id="94b73-123">Select relevant vendor code.</span></span>|
    |<span data-ttu-id="94b73-124">**Account Type**</span><span class="sxs-lookup"><span data-stu-id="94b73-124">**Account Type**</span></span>|<span data-ttu-id="94b73-125">Select G/L Account.</span><span class="sxs-lookup"><span data-stu-id="94b73-125">Select G/L Account.</span></span>| 
    |<span data-ttu-id="94b73-126">**Account No**</span><span class="sxs-lookup"><span data-stu-id="94b73-126">**Account No**</span></span>|<span data-ttu-id="94b73-127">Select relevant account number for provision entry.</span><span class="sxs-lookup"><span data-stu-id="94b73-127">Select relevant account number for provision entry.</span></span>|
    |<span data-ttu-id="94b73-128">**Amount**</span><span class="sxs-lookup"><span data-stu-id="94b73-128">**Amount**</span></span>|<span data-ttu-id="94b73-129">Amount should be negative.</span><span class="sxs-lookup"><span data-stu-id="94b73-129">Amount should be negative.</span></span>|
    |<span data-ttu-id="94b73-130">**TDS Section**</span><span class="sxs-lookup"><span data-stu-id="94b73-130">**TDS Section**</span></span>|<span data-ttu-id="94b73-131">Select relevant TDS Section.</span><span class="sxs-lookup"><span data-stu-id="94b73-131">Select relevant TDS Section.</span></span>|
    |<span data-ttu-id="94b73-132">**Bal. Account Type**</span><span class="sxs-lookup"><span data-stu-id="94b73-132">**Bal. Account Type**</span></span>|<span data-ttu-id="94b73-133">Select G/L Account as balance account type.</span><span class="sxs-lookup"><span data-stu-id="94b73-133">Select G/L Account as balance account type.</span></span>|
    |<span data-ttu-id="94b73-134">**Bal. Account No.**</span><span class="sxs-lookup"><span data-stu-id="94b73-134">**Bal. Account No.**</span></span>|<span data-ttu-id="94b73-135">Select the relevant expanse account.</span><span class="sxs-lookup"><span data-stu-id="94b73-135">Select the relevant expanse account.</span></span>|
    |<span data-ttu-id="94b73-136">**Provisional Entry**</span><span class="sxs-lookup"><span data-stu-id="94b73-136">**Provisional Entry**</span></span>|<span data-ttu-id="94b73-137">Mark true.</span><span class="sxs-lookup"><span data-stu-id="94b73-137">Mark true.</span></span>|

    <span data-ttu-id="94b73-138">In this case TDS calculation will be as following:</span><span class="sxs-lookup"><span data-stu-id="94b73-138">In this case TDS calculation will be as following:</span></span>

    |<span data-ttu-id="94b73-139">Component</span><span class="sxs-lookup"><span data-stu-id="94b73-139">Component</span></span>|<span data-ttu-id="94b73-140">Value</span><span class="sxs-lookup"><span data-stu-id="94b73-140">Value</span></span>|
    |----------------------------------|---------------------------------------|  
    |<span data-ttu-id="94b73-141">**TDS Base Amount**</span><span class="sxs-lookup"><span data-stu-id="94b73-141">**TDS Base Amount**</span></span>|<span data-ttu-id="94b73-142">10000</span><span class="sxs-lookup"><span data-stu-id="94b73-142">10000</span></span>|  
    |<span data-ttu-id="94b73-143">**TDS Amount**</span><span class="sxs-lookup"><span data-stu-id="94b73-143">**TDS Amount**</span></span>|<span data-ttu-id="94b73-144">1000 (10000\*1%)</span><span class="sxs-lookup"><span data-stu-id="94b73-144">1000 (10000\*1%)</span></span>|

    <span data-ttu-id="94b73-145">GL Entries for Provisional Entry, will be as following:</span><span class="sxs-lookup"><span data-stu-id="94b73-145">GL Entries for Provisional Entry, will be as following:</span></span>

    |<span data-ttu-id="94b73-146">Particulars</span><span class="sxs-lookup"><span data-stu-id="94b73-146">Particulars</span></span>|<span data-ttu-id="94b73-147">Amount</span><span class="sxs-lookup"><span data-stu-id="94b73-147">Amount</span></span>|
    |----------------------------------|---------------------------------------|  
    |<span data-ttu-id="94b73-148">**Expense Account**</span><span class="sxs-lookup"><span data-stu-id="94b73-148">**Expense Account**</span></span>|<span data-ttu-id="94b73-149">10000</span><span class="sxs-lookup"><span data-stu-id="94b73-149">10000</span></span>| 
    |<span data-ttu-id="94b73-150">**Provisional Account**</span><span class="sxs-lookup"><span data-stu-id="94b73-150">**Provisional Account**</span></span>|<span data-ttu-id="94b73-151">-10000</span><span class="sxs-lookup"><span data-stu-id="94b73-151">-10000</span></span>|
    |<span data-ttu-id="94b73-152">**TDS Payable Account**</span><span class="sxs-lookup"><span data-stu-id="94b73-152">**TDS Payable Account**</span></span>|<span data-ttu-id="94b73-153">-1000</span><span class="sxs-lookup"><span data-stu-id="94b73-153">-1000</span></span>|
    |<span data-ttu-id="94b73-154">**Vendor Account**</span><span class="sxs-lookup"><span data-stu-id="94b73-154">**Vendor Account**</span></span>|<span data-ttu-id="94b73-155">1000</span><span class="sxs-lookup"><span data-stu-id="94b73-155">1000</span></span>|

<span data-ttu-id="94b73-156">•   Later invoice created against the provisional entry.</span><span class="sxs-lookup"><span data-stu-id="94b73-156">•   Later invoice created against the provisional entry.</span></span>

1.  <span data-ttu-id="94b73-157">Choose the ![Search for Page or Report](image/search_small.png "Search for Page or Report icon") icon, enter **Purchase Journal** , and then choose the related link.</span><span class="sxs-lookup"><span data-stu-id="94b73-157">Choose the ![Search for Page or Report](image/search_small.png "Search for Page or Report icon") icon, enter **Purchase Journal** , and then choose the related link.</span></span>
2.  <span data-ttu-id="94b73-158">Fill in the fields as described in the following table.</span><span class="sxs-lookup"><span data-stu-id="94b73-158">Fill in the fields as described in the following table.</span></span>

    |<span data-ttu-id="94b73-159">Field</span><span class="sxs-lookup"><span data-stu-id="94b73-159">Field</span></span>|<span data-ttu-id="94b73-160">Description</span><span class="sxs-lookup"><span data-stu-id="94b73-160">Description</span></span>|
    |----------------------------------|---------------------------------------|  
    |<span data-ttu-id="94b73-161">**Posting Date**</span><span class="sxs-lookup"><span data-stu-id="94b73-161">**Posting Date**</span></span>|<span data-ttu-id="94b73-162">Specify the date of entry.</span><span class="sxs-lookup"><span data-stu-id="94b73-162">Specify the date of entry.</span></span>|  
    |<span data-ttu-id="94b73-163">**Document Type**</span><span class="sxs-lookup"><span data-stu-id="94b73-163">**Document Type**</span></span>|<span data-ttu-id="94b73-164">Select Invoice as document type.</span><span class="sxs-lookup"><span data-stu-id="94b73-164">Select Invoice as document type.</span></span>|
    |<span data-ttu-id="94b73-165">**Document No.**</span><span class="sxs-lookup"><span data-stu-id="94b73-165">**Document No.**</span></span>|<span data-ttu-id="94b73-166">Specify the document number.</span><span class="sxs-lookup"><span data-stu-id="94b73-166">Specify the document number.</span></span>|
    |<span data-ttu-id="94b73-167">**Party Type**</span><span class="sxs-lookup"><span data-stu-id="94b73-167">**Party Type**</span></span>|<span data-ttu-id="94b73-168">Select Vendor as party type.</span><span class="sxs-lookup"><span data-stu-id="94b73-168">Select Vendor as party type.</span></span>|
    |<span data-ttu-id="94b73-169">**Party Code**</span><span class="sxs-lookup"><span data-stu-id="94b73-169">**Party Code**</span></span>|<span data-ttu-id="94b73-170">Select relevant vendor code.</span><span class="sxs-lookup"><span data-stu-id="94b73-170">Select relevant vendor code.</span></span>|
    |<span data-ttu-id="94b73-171">**Account Type**</span><span class="sxs-lookup"><span data-stu-id="94b73-171">**Account Type**</span></span>|<span data-ttu-id="94b73-172">Select Vendor.</span><span class="sxs-lookup"><span data-stu-id="94b73-172">Select Vendor.</span></span>| 
    |<span data-ttu-id="94b73-173">**Account No**</span><span class="sxs-lookup"><span data-stu-id="94b73-173">**Account No**</span></span>|<span data-ttu-id="94b73-174">Select relevant vendor code.</span><span class="sxs-lookup"><span data-stu-id="94b73-174">Select relevant vendor code.</span></span>|
    |<span data-ttu-id="94b73-175">**Amount**</span><span class="sxs-lookup"><span data-stu-id="94b73-175">**Amount**</span></span>|<span data-ttu-id="94b73-176">Amount should be negative.</span><span class="sxs-lookup"><span data-stu-id="94b73-176">Amount should be negative.</span></span>|
    |<span data-ttu-id="94b73-177">**Bal. Account Type**</span><span class="sxs-lookup"><span data-stu-id="94b73-177">**Bal. Account Type**</span></span>|<span data-ttu-id="94b73-178">Select G/L Account as balance account type.</span><span class="sxs-lookup"><span data-stu-id="94b73-178">Select G/L Account as balance account type.</span></span>|
    |<span data-ttu-id="94b73-179">**Bal. Account No.**</span><span class="sxs-lookup"><span data-stu-id="94b73-179">**Bal. Account No.**</span></span>|<span data-ttu-id="94b73-180">Select the relevant expanse account.</span><span class="sxs-lookup"><span data-stu-id="94b73-180">Select the relevant expanse account.</span></span>|
    

3. <span data-ttu-id="94b73-181">Select Apply Provisional Entry and select the relevant provision entry posted for the vendor.</span><span class="sxs-lookup"><span data-stu-id="94b73-181">Select Apply Provisional Entry and select the relevant provision entry posted for the vendor.</span></span>

   <span data-ttu-id="94b73-182">GL Entries for purchase invoice against provisional entry, will be as following:</span><span class="sxs-lookup"><span data-stu-id="94b73-182">GL Entries for purchase invoice against provisional entry, will be as following:</span></span>

    |<span data-ttu-id="94b73-183">Particulars</span><span class="sxs-lookup"><span data-stu-id="94b73-183">Particulars</span></span>|<span data-ttu-id="94b73-184">Amount</span><span class="sxs-lookup"><span data-stu-id="94b73-184">Amount</span></span>|
    |----------------------------------|---------------------------------------|  
    |<span data-ttu-id="94b73-185">**Vendor Account**</span><span class="sxs-lookup"><span data-stu-id="94b73-185">**Vendor Account**</span></span>|<span data-ttu-id="94b73-186">-10000</span><span class="sxs-lookup"><span data-stu-id="94b73-186">-10000</span></span>|
    |<span data-ttu-id="94b73-187">**Provisional Account**</span><span class="sxs-lookup"><span data-stu-id="94b73-187">**Provisional Account**</span></span>|<span data-ttu-id="94b73-188">10000</span><span class="sxs-lookup"><span data-stu-id="94b73-188">10000</span></span>|

4.  <span data-ttu-id="94b73-189">On posting of provisional entry Provisional Entries will be created, and once the invoice is applied with the entry Applied Invoice No. field will be updated with the invoice number.</span><span class="sxs-lookup"><span data-stu-id="94b73-189">On posting of provisional entry Provisional Entries will be created, and once the invoice is applied with the entry Applied Invoice No. field will be updated with the invoice number.</span></span>

<span data-ttu-id="94b73-190">•   If this is found that the provisional entry needs to be reversed, then option of **Reverse Transaction** and **Reverse Without TDS** are available in Provisional Entries.</span><span class="sxs-lookup"><span data-stu-id="94b73-190">•   If this is found that the provisional entry needs to be reversed, then option of **Reverse Transaction** and **Reverse Without TDS** are available in Provisional Entries.</span></span>
1.  <span data-ttu-id="94b73-191">Reverse Transaction will reverse all the posted entries of the selected transaction.</span><span class="sxs-lookup"><span data-stu-id="94b73-191">Reverse Transaction will reverse all the posted entries of the selected transaction.</span></span>
2.  <span data-ttu-id="94b73-192">Reverse Without TDS will reverse all the posted entries of the selected transaction other than the TDS entry.</span><span class="sxs-lookup"><span data-stu-id="94b73-192">Reverse Without TDS will reverse all the posted entries of the selected transaction other than the TDS entry.</span></span>
3.  <span data-ttu-id="94b73-193">System will mark the reverse transaction as **Reversed After TDS Paid** if TDS is paid to the government for the selected transaction.</span><span class="sxs-lookup"><span data-stu-id="94b73-193">System will mark the reverse transaction as **Reversed After TDS Paid** if TDS is paid to the government for the selected transaction.</span></span>



























