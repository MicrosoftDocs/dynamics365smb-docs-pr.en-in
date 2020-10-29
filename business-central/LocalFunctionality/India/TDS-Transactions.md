---
title: TDS calculation on Purchase and Payment Transactions
description: TDS calculation on Purchase and Payment Transactions
author: v-debapd
ms.service: dynamics365-business-central
ms.topic: article
ms.devlang: na
ms.tgt_pltfrm: na
ms.workload: na
ms.search.keywords: India, local, IN, English
ms.date: 10/01/2020
ms.author: v-debapd
ms.openlocfilehash: bc4f93952ca52b80cd3401fd1cb4767dcdb6c89f
ms.sourcegitcommit: ddbb5cede750df1baba4b3eab8fbed6744b5b9d6
ms.translationtype: HT
ms.contentlocale: en-IN
ms.lasthandoff: 10/01/2020
ms.locfileid: "3948605"
---
# <a name="tds-calculation-on-purchase-and-payment-transactions"></a><span data-ttu-id="661e3-103">TDS calculation on Purchase and Payment Transactions</span><span class="sxs-lookup"><span data-stu-id="661e3-103">TDS calculation on Purchase and Payment Transactions</span></span>

[!INCLUDE[vnext_preview](../../includes/vnext_preview.md)]

<span data-ttu-id="661e3-104">TDS can be deducted on expenses (GL Account) transactions.</span><span class="sxs-lookup"><span data-stu-id="661e3-104">TDS can be deducted on expenses (GL Account) transactions.</span></span> <span data-ttu-id="661e3-105">TDS can be deducted on purchase order, invoice received from vendor or advance payment made to vendor.</span><span class="sxs-lookup"><span data-stu-id="661e3-105">TDS can be deducted on purchase order, invoice received from vendor or advance payment made to vendor.</span></span> <span data-ttu-id="661e3-106">TDS calculations can be done on following document types:</span><span class="sxs-lookup"><span data-stu-id="661e3-106">TDS calculations can be done on following document types:</span></span>

- <span data-ttu-id="661e3-107">Purchase Order</span><span class="sxs-lookup"><span data-stu-id="661e3-107">Purchase Order</span></span>
- <span data-ttu-id="661e3-108">Purchase Invoice</span><span class="sxs-lookup"><span data-stu-id="661e3-108">Purchase Invoice</span></span>
- <span data-ttu-id="661e3-109">General Journal</span><span class="sxs-lookup"><span data-stu-id="661e3-109">General Journal</span></span>
- <span data-ttu-id="661e3-110">Purchase Journal</span><span class="sxs-lookup"><span data-stu-id="661e3-110">Purchase Journal</span></span>

## <a name="mandatory-fields-for-tds-calculation-on-general-journal-purchase-journal-purchase-invoice-purchase-order"></a><span data-ttu-id="661e3-111">Mandatory fields for TDS calculation on general journal, purchase journal, purchase invoice, purchase order.</span><span class="sxs-lookup"><span data-stu-id="661e3-111">Mandatory fields for TDS calculation on general journal, purchase journal, purchase invoice, purchase order.</span></span>

- <span data-ttu-id="661e3-112">Create General Journal or Purchase Journal</span><span class="sxs-lookup"><span data-stu-id="661e3-112">Create General Journal or Purchase Journal</span></span>

  1.  <span data-ttu-id="661e3-113">Choose the ![Search for Page or Report](image/search_small.png "Search for Page or Report icon") icon, enter **General Journal** or **Purchase Journal** , and then choose the related link.</span><span class="sxs-lookup"><span data-stu-id="661e3-113">Choose the ![Search for Page or Report](image/search_small.png "Search for Page or Report icon") icon, enter **General Journal** or **Purchase Journal** , and then choose the related link.</span></span> 
  2. <span data-ttu-id="661e3-114">Select **Vendor** in Account Type and select relevant vendor code in Account No. field.</span><span class="sxs-lookup"><span data-stu-id="661e3-114">Select **Vendor** in Account Type and select relevant vendor code in Account No. field.</span></span> <span data-ttu-id="661e3-115">Select **G/L Account** in Bal. Account Type and select relevant expense account in Bal. Account No. field.</span><span class="sxs-lookup"><span data-stu-id="661e3-115">Select **G/L Account** in Bal. Account Type and select relevant expense account in Bal. Account No. field.</span></span>
  3. <span data-ttu-id="661e3-116">Select relevant **TDS Section** on journal line.</span><span class="sxs-lookup"><span data-stu-id="661e3-116">Select relevant **TDS Section** on journal line.</span></span>  <span data-ttu-id="661e3-117">**Location Code** and **T.A.N No.**</span><span class="sxs-lookup"><span data-stu-id="661e3-117">**Location Code** and **T.A.N No.**</span></span> <span data-ttu-id="661e3-118">fields should not be blank.</span><span class="sxs-lookup"><span data-stu-id="661e3-118">fields should not be blank.</span></span>

- <span data-ttu-id="661e3-119">Create Purchase Invoice or Purchase Order</span><span class="sxs-lookup"><span data-stu-id="661e3-119">Create Purchase Invoice or Purchase Order</span></span>

  1.  <span data-ttu-id="661e3-120">Choose the ![Search for Page or Report](image/search_small.png "Search for Page or Report icon") icon, enter **Purchase Invoice** or **Purchase Order** , and then choose the related link.</span><span class="sxs-lookup"><span data-stu-id="661e3-120">Choose the ![Search for Page or Report](image/search_small.png "Search for Page or Report icon") icon, enter **Purchase Invoice** or **Purchase Order** , and then choose the related link.</span></span>
  2. <span data-ttu-id="661e3-121">Select **Vendor** , **Location Code** on **Purchase Order** or **Purchase Invoice** header</span><span class="sxs-lookup"><span data-stu-id="661e3-121">Select **Vendor** , **Location Code** on **Purchase Order** or **Purchase Invoice** header</span></span>
  3. <span data-ttu-id="661e3-122">Select **G/L Account** on **Purchase Order** or **Purchase Invoice** line.</span><span class="sxs-lookup"><span data-stu-id="661e3-122">Select **G/L Account** on **Purchase Order** or **Purchase Invoice** line.</span></span>
  <span data-ttu-id="661e3-123">s4.</span><span class="sxs-lookup"><span data-stu-id="661e3-123">s4.</span></span> <span data-ttu-id="661e3-124">**TDS Section** , **Location Code** and **T.A.N No.**</span><span class="sxs-lookup"><span data-stu-id="661e3-124">**TDS Section** , **Location Code** and **T.A.N No.**</span></span> <span data-ttu-id="661e3-125">fields should not be blank.</span><span class="sxs-lookup"><span data-stu-id="661e3-125">fields should not be blank.</span></span>

### <a name="tds-to-be-calculated-on-vendor-invoice-through-general-journal-purchase-journal-purchase-invoice-or-purchase-order"></a><span data-ttu-id="661e3-126">TDS to be calculated on vendor invoice (through general journal, purchase journal, purchase invoice or purchase order)</span><span class="sxs-lookup"><span data-stu-id="661e3-126">TDS to be calculated on vendor invoice (through general journal, purchase journal, purchase invoice or purchase order)</span></span>

<span data-ttu-id="661e3-127">In the given scenario, vendor has issued an invoice for INR 50,000 on which 2% TDS is applicable under TDS Section 194C.</span><span class="sxs-lookup"><span data-stu-id="661e3-127">In the given scenario, vendor has issued an invoice for INR 50,000 on which 2% TDS is applicable under TDS Section 194C.</span></span>
  
  - <span data-ttu-id="661e3-128">In this case TDS calculation will be as following:</span><span class="sxs-lookup"><span data-stu-id="661e3-128">In this case TDS calculation will be as following:</span></span>

    |<span data-ttu-id="661e3-129">Component</span><span class="sxs-lookup"><span data-stu-id="661e3-129">Component</span></span>|<span data-ttu-id="661e3-130">Value</span><span class="sxs-lookup"><span data-stu-id="661e3-130">Value</span></span>|
    |----------------------------------|---------------------------------------|  
    |<span data-ttu-id="661e3-131">**TDS Base Amount**</span><span class="sxs-lookup"><span data-stu-id="661e3-131">**TDS Base Amount**</span></span>|<span data-ttu-id="661e3-132">50000</span><span class="sxs-lookup"><span data-stu-id="661e3-132">50000</span></span>|  
    |<span data-ttu-id="661e3-133">**TDS Amount**</span><span class="sxs-lookup"><span data-stu-id="661e3-133">**TDS Amount**</span></span>|<span data-ttu-id="661e3-134">1000 (50000\*2%)</span><span class="sxs-lookup"><span data-stu-id="661e3-134">1000 (50000\*2%)</span></span>|

  - <span data-ttu-id="661e3-135">On posting of invoice, GL Entries will be as following:</span><span class="sxs-lookup"><span data-stu-id="661e3-135">On posting of invoice, GL Entries will be as following:</span></span>
     
    |<span data-ttu-id="661e3-136">Particulars</span><span class="sxs-lookup"><span data-stu-id="661e3-136">Particulars</span></span>|<span data-ttu-id="661e3-137">Amount</span><span class="sxs-lookup"><span data-stu-id="661e3-137">Amount</span></span>|
    |----------------------------------|---------------------------------------|  
    |<span data-ttu-id="661e3-138">**Expense Account**</span><span class="sxs-lookup"><span data-stu-id="661e3-138">**Expense Account**</span></span>|<span data-ttu-id="661e3-139">50000</span><span class="sxs-lookup"><span data-stu-id="661e3-139">50000</span></span>| 
    |<span data-ttu-id="661e3-140">**TDS Payable Account**</span><span class="sxs-lookup"><span data-stu-id="661e3-140">**TDS Payable Account**</span></span>|<span data-ttu-id="661e3-141">-1000</span><span class="sxs-lookup"><span data-stu-id="661e3-141">-1000</span></span>| 
    |<span data-ttu-id="661e3-142">**Vendor Account**</span><span class="sxs-lookup"><span data-stu-id="661e3-142">**Vendor Account**</span></span>|<span data-ttu-id="661e3-143">-49000</span><span class="sxs-lookup"><span data-stu-id="661e3-143">-49000</span></span>|

### <a name="tds-to-be-calculated-on-vendor-advance-payment-through-general-journal-or-payment-journal"></a><span data-ttu-id="661e3-144">TDS to be calculated on vendor advance payment (through general journal or payment journal)</span><span class="sxs-lookup"><span data-stu-id="661e3-144">TDS to be calculated on vendor advance payment (through general journal or payment journal)</span></span>

<span data-ttu-id="661e3-145">In the given scenario, advance payment made to vendor for INR 50,000 on which 2% TDS is applicable under TDS Section 194C.</span><span class="sxs-lookup"><span data-stu-id="661e3-145">In the given scenario, advance payment made to vendor for INR 50,000 on which 2% TDS is applicable under TDS Section 194C.</span></span>

  - <span data-ttu-id="661e3-146">In this case TDS calculation will be as following:</span><span class="sxs-lookup"><span data-stu-id="661e3-146">In this case TDS calculation will be as following:</span></span>

    |<span data-ttu-id="661e3-147">Component</span><span class="sxs-lookup"><span data-stu-id="661e3-147">Component</span></span>|<span data-ttu-id="661e3-148">Value</span><span class="sxs-lookup"><span data-stu-id="661e3-148">Value</span></span>|
    |----------------------------------|---------------------------------------|  
    |<span data-ttu-id="661e3-149">**TDS Base Amount**</span><span class="sxs-lookup"><span data-stu-id="661e3-149">**TDS Base Amount**</span></span>|<span data-ttu-id="661e3-150">50000</span><span class="sxs-lookup"><span data-stu-id="661e3-150">50000</span></span>|  
    |<span data-ttu-id="661e3-151">**TDS Amount**</span><span class="sxs-lookup"><span data-stu-id="661e3-151">**TDS Amount**</span></span>|<span data-ttu-id="661e3-152">1000 (50000\*2%)</span><span class="sxs-lookup"><span data-stu-id="661e3-152">1000 (50000\*2%)</span></span>|

  - <span data-ttu-id="661e3-153">On posting of advance payment, GL Entries will be as following:</span><span class="sxs-lookup"><span data-stu-id="661e3-153">On posting of advance payment, GL Entries will be as following:</span></span>
     
    |<span data-ttu-id="661e3-154">Particulars</span><span class="sxs-lookup"><span data-stu-id="661e3-154">Particulars</span></span>|<span data-ttu-id="661e3-155">Amount</span><span class="sxs-lookup"><span data-stu-id="661e3-155">Amount</span></span>|
    |----------------------------------|---------------------------------------|  
    |<span data-ttu-id="661e3-156">**Expense Account**</span><span class="sxs-lookup"><span data-stu-id="661e3-156">**Expense Account**</span></span>|<span data-ttu-id="661e3-157">50000</span><span class="sxs-lookup"><span data-stu-id="661e3-157">50000</span></span>|
    |<span data-ttu-id="661e3-158">**TDS Payable Account**</span><span class="sxs-lookup"><span data-stu-id="661e3-158">**TDS Payable Account**</span></span>|<span data-ttu-id="661e3-159">-1000</span><span class="sxs-lookup"><span data-stu-id="661e3-159">-1000</span></span>|
    |<span data-ttu-id="661e3-160">**Bank Account**</span><span class="sxs-lookup"><span data-stu-id="661e3-160">**Bank Account**</span></span>|<span data-ttu-id="661e3-161">-49000</span><span class="sxs-lookup"><span data-stu-id="661e3-161">-49000</span></span>|

<span data-ttu-id="661e3-162">On receiving the invoice from the vendor, TDS will be calculated on the differential amount.</span><span class="sxs-lookup"><span data-stu-id="661e3-162">On receiving the invoice from the vendor, TDS will be calculated on the differential amount.</span></span> <span data-ttu-id="661e3-163">Suppose vendor sent an invoice of INR 120000.</span><span class="sxs-lookup"><span data-stu-id="661e3-163">Suppose vendor sent an invoice of INR 120000.</span></span> <span data-ttu-id="661e3-164">Since TDS has already been calculated at the time of payment, at the time of invoicing TDS will be calculated on the remaining amount i.e. INR 70000 (1200000 - 50000).</span><span class="sxs-lookup"><span data-stu-id="661e3-164">Since TDS has already been calculated at the time of payment, at the time of invoicing TDS will be calculated on the remaining amount i.e. INR 70000 (1200000 - 50000).</span></span>

> [!NOTE]
> <span data-ttu-id="661e3-165">Advance payment needs to be applied with the invoice before posting.</span><span class="sxs-lookup"><span data-stu-id="661e3-165">Advance payment needs to be applied with the invoice before posting.</span></span> <span data-ttu-id="661e3-166">Otherwise TDS will be calculated on the whole invoice amount.</span><span class="sxs-lookup"><span data-stu-id="661e3-166">Otherwise TDS will be calculated on the whole invoice amount.</span></span>

### <a name="tds-to-be-calculated-on-non-resident-vendor-invoice-in-fcy"></a><span data-ttu-id="661e3-167">TDS to be calculated on non-resident vendor invoice in FCY</span><span class="sxs-lookup"><span data-stu-id="661e3-167">TDS to be calculated on non-resident vendor invoice in FCY</span></span>

<span data-ttu-id="661e3-168">In the given scenario, the vendor issued an invoice for USD 10000, upon which 2% TDS is applicable under TDS Section 195.</span><span class="sxs-lookup"><span data-stu-id="661e3-168">In the given scenario, vendor issued an invoice for USD 10000 on which 2% TDS is applicable under TDS Section 195.</span></span> <span data-ttu-id="661e3-169">All USD amounts will get converted into INR based on currency exchange rates.</span><span class="sxs-lookup"><span data-stu-id="661e3-169">All USD amounts will get converted into INR based on currency exchange rates.</span></span> <span data-ttu-id="661e3-170">For this example, the exchange rate was calculated at USD 1 = INR 65.</span><span class="sxs-lookup"><span data-stu-id="661e3-170">For this example exchange rate has been considered as USD 1 = INR 65.</span></span>

  - <span data-ttu-id="661e3-171">In this case TDS calculation will be as following:</span><span class="sxs-lookup"><span data-stu-id="661e3-171">In this case TDS calculation will be as following:</span></span>

    |<span data-ttu-id="661e3-172">Component</span><span class="sxs-lookup"><span data-stu-id="661e3-172">Component</span></span>|<span data-ttu-id="661e3-173">Value</span><span class="sxs-lookup"><span data-stu-id="661e3-173">Value</span></span>|
    |----------------------------------|---------------------------------------|  
    |<span data-ttu-id="661e3-174">**TDS Base Amount**</span><span class="sxs-lookup"><span data-stu-id="661e3-174">**TDS Base Amount**</span></span>|<span data-ttu-id="661e3-175">USD 10000 or INR 650000</span><span class="sxs-lookup"><span data-stu-id="661e3-175">USD 10000 or INR 650000</span></span>|  
    |<span data-ttu-id="661e3-176">**TDS Amount**</span><span class="sxs-lookup"><span data-stu-id="661e3-176">**TDS Amount**</span></span>|<span data-ttu-id="661e3-177">INR 13000 (INR 650000\*2%)</span><span class="sxs-lookup"><span data-stu-id="661e3-177">INR 13000 (INR 650000\*2%)</span></span>|

  - <span data-ttu-id="661e3-178">On posting invoice, GL Entries, will be as following:</span><span class="sxs-lookup"><span data-stu-id="661e3-178">On posting invoice, GL Entries, will be as following:</span></span>
     
    |<span data-ttu-id="661e3-179">Particulars</span><span class="sxs-lookup"><span data-stu-id="661e3-179">Particulars</span></span>|<span data-ttu-id="661e3-180">Amount</span><span class="sxs-lookup"><span data-stu-id="661e3-180">Amount</span></span>|
    |----------------------------------|---------------------------------------|  
    |<span data-ttu-id="661e3-181">**Expense Account**</span><span class="sxs-lookup"><span data-stu-id="661e3-181">**Expense Account**</span></span>|<span data-ttu-id="661e3-182">650000</span><span class="sxs-lookup"><span data-stu-id="661e3-182">650000</span></span>|
    |<span data-ttu-id="661e3-183">**TDS Payable Account**</span><span class="sxs-lookup"><span data-stu-id="661e3-183">**TDS Payable Account**</span></span>|<span data-ttu-id="661e3-184">-13000</span><span class="sxs-lookup"><span data-stu-id="661e3-184">-13000</span></span>|
    |<span data-ttu-id="661e3-185">**Vendor Account**</span><span class="sxs-lookup"><span data-stu-id="661e3-185">**Vendor Account**</span></span>|<span data-ttu-id="661e3-186">-637000</span><span class="sxs-lookup"><span data-stu-id="661e3-186">-637000</span></span>|

> [!TIP]
> <span data-ttu-id="661e3-187">Nature of Remittance and Act Applicable are mandatory for NRI Payments.</span><span class="sxs-lookup"><span data-stu-id="661e3-187">Nature of Remittance and Act Applicable are mandatory for NRI Payments.</span></span>

### <a name="tds-calculation-on-higher-rate-if-vendor-is-not-having-pan"></a><span data-ttu-id="661e3-188">TDS calculation on higher rate if vendor is not having PAN</span><span class="sxs-lookup"><span data-stu-id="661e3-188">TDS calculation on higher rate if vendor is not having PAN</span></span>

<span data-ttu-id="661e3-189">PAN of vendor is mandatory for TDS calculation, but in case PAN is not available, higher rate of TDS will be deducted from the vendor.</span><span class="sxs-lookup"><span data-stu-id="661e3-189">PAN of vendor is mandatory for TDS calculation, but in case PAN is not available, higher rate of TDS will be deducted from the vendor.</span></span>

<span data-ttu-id="661e3-190">In the given scenario, vendor issued an invoice for INR 50000 on which 2% TDS is applicable under TDS section 194C, but PAN is not available for vendor.</span><span class="sxs-lookup"><span data-stu-id="661e3-190">In the given scenario, vendor issued an invoice for INR 50000 on which 2% TDS is applicable under TDS section 194C, but PAN is not available for vendor.</span></span> <span data-ttu-id="661e3-191">In such a case 20% TDS will be charged as a higher rate.</span><span class="sxs-lookup"><span data-stu-id="661e3-191">In such a case 20% TDS will be charged as a higher rate.</span></span>

  - <span data-ttu-id="661e3-192">In this case TDS calculation will be as following:</span><span class="sxs-lookup"><span data-stu-id="661e3-192">In this case TDS calculation will be as following:</span></span>

    |<span data-ttu-id="661e3-193">Component</span><span class="sxs-lookup"><span data-stu-id="661e3-193">Component</span></span>|<span data-ttu-id="661e3-194">Value</span><span class="sxs-lookup"><span data-stu-id="661e3-194">Value</span></span>|
    |----------------------------------|---------------------------------------|  
    |<span data-ttu-id="661e3-195">**TDS Base Amount**</span><span class="sxs-lookup"><span data-stu-id="661e3-195">**TDS Base Amount**</span></span>|<span data-ttu-id="661e3-196">50000</span><span class="sxs-lookup"><span data-stu-id="661e3-196">50000</span></span>|  
    |<span data-ttu-id="661e3-197">**TDS Amount**</span><span class="sxs-lookup"><span data-stu-id="661e3-197">**TDS Amount**</span></span>|<span data-ttu-id="661e3-198">10000 (50000\*20%)</span><span class="sxs-lookup"><span data-stu-id="661e3-198">10000 (50000\*20%)</span></span>|

  - <span data-ttu-id="661e3-199">On posting invoice, GL Entries, will be as following:</span><span class="sxs-lookup"><span data-stu-id="661e3-199">On posting invoice, GL Entries, will be as following:</span></span>
     
    |<span data-ttu-id="661e3-200">Particulars</span><span class="sxs-lookup"><span data-stu-id="661e3-200">Particulars</span></span>|<span data-ttu-id="661e3-201">Amount</span><span class="sxs-lookup"><span data-stu-id="661e3-201">Amount</span></span>|
    |----------------------------------|---------------------------------------|  
    |<span data-ttu-id="661e3-202">**Expense Account**</span><span class="sxs-lookup"><span data-stu-id="661e3-202">**Expense Account**</span></span>|<span data-ttu-id="661e3-203">50000</span><span class="sxs-lookup"><span data-stu-id="661e3-203">50000</span></span>|
    |<span data-ttu-id="661e3-204">**TDS Payable Account**</span><span class="sxs-lookup"><span data-stu-id="661e3-204">**TDS Payable Account**</span></span>|<span data-ttu-id="661e3-205">-10000</span><span class="sxs-lookup"><span data-stu-id="661e3-205">-10000</span></span>|
    |<span data-ttu-id="661e3-206">**Vendor Account**</span><span class="sxs-lookup"><span data-stu-id="661e3-206">**Vendor Account**</span></span>|<span data-ttu-id="661e3-207">-40000</span><span class="sxs-lookup"><span data-stu-id="661e3-207">-40000</span></span>|

### <a name="expenses-partially-subject-to-tds"></a><span data-ttu-id="661e3-208">Expenses partially subject to TDS</span><span class="sxs-lookup"><span data-stu-id="661e3-208">Expenses partially subject to TDS</span></span>

- <span data-ttu-id="661e3-209">In the given scenario, vendor issued an invoice for INR 112360, out of which INR 100000 is for auditing service on which 10% TDS will be applicable under Section 194J.</span><span class="sxs-lookup"><span data-stu-id="661e3-209">In the given scenario, vendor issued an invoice for INR 112360, out of which INR 100000 is for auditing service on which 10% TDS will be applicable under Section 194J.</span></span> <span data-ttu-id="661e3-210">INR 12360 is for other charges on which TDS is not applicable.</span><span class="sxs-lookup"><span data-stu-id="661e3-210">INR 12360 is for other charges on which TDS is not applicable.</span></span>
    
    <span data-ttu-id="661e3-211">In this case TDS calculation will be as following:</span><span class="sxs-lookup"><span data-stu-id="661e3-211">In this case TDS calculation will be as following:</span></span>

    |<span data-ttu-id="661e3-212">Component</span><span class="sxs-lookup"><span data-stu-id="661e3-212">Component</span></span>|<span data-ttu-id="661e3-213">Value</span><span class="sxs-lookup"><span data-stu-id="661e3-213">Value</span></span>|
    |----------------------------------|---------------------------------------|  
    |<span data-ttu-id="661e3-214">**TDS Base Amount**</span><span class="sxs-lookup"><span data-stu-id="661e3-214">**TDS Base Amount**</span></span>|<span data-ttu-id="661e3-215">100000</span><span class="sxs-lookup"><span data-stu-id="661e3-215">100000</span></span>|  
    |<span data-ttu-id="661e3-216">**TDS Amount**</span><span class="sxs-lookup"><span data-stu-id="661e3-216">**TDS Amount**</span></span>|<span data-ttu-id="661e3-217">10000 (100000\*10%)</span><span class="sxs-lookup"><span data-stu-id="661e3-217">10000 (100000\*10%)</span></span>|

  <span data-ttu-id="661e3-218">On posting invoice, GL Entries will be as following:</span><span class="sxs-lookup"><span data-stu-id="661e3-218">On posting invoice, GL Entries will be as following:</span></span>
     
    |<span data-ttu-id="661e3-219">Particulars</span><span class="sxs-lookup"><span data-stu-id="661e3-219">Particulars</span></span>|<span data-ttu-id="661e3-220">Amount</span><span class="sxs-lookup"><span data-stu-id="661e3-220">Amount</span></span>|
    |----------------------------------|---------------------------------------|  
    |<span data-ttu-id="661e3-221">**Expense Account**</span><span class="sxs-lookup"><span data-stu-id="661e3-221">**Expense Account**</span></span>|<span data-ttu-id="661e3-222">112360</span><span class="sxs-lookup"><span data-stu-id="661e3-222">112360</span></span>|
    |<span data-ttu-id="661e3-223">**TDS Payable Account**</span><span class="sxs-lookup"><span data-stu-id="661e3-223">**TDS Payable Account**</span></span>|<span data-ttu-id="661e3-224">-10000</span><span class="sxs-lookup"><span data-stu-id="661e3-224">-10000</span></span>|
    |<span data-ttu-id="661e3-225">**Vendor Account**</span><span class="sxs-lookup"><span data-stu-id="661e3-225">**Vendor Account**</span></span>|<span data-ttu-id="661e3-226">-102360</span><span class="sxs-lookup"><span data-stu-id="661e3-226">-102360</span></span>|

### <a name="tds-calculation-on-multiple-expenses-in-a-single-invoice"></a><span data-ttu-id="661e3-227">TDS calculation on multiple expenses in a single invoice</span><span class="sxs-lookup"><span data-stu-id="661e3-227">TDS calculation on multiple expenses in a single invoice</span></span>

<span data-ttu-id="661e3-228">A single invoice can be raised by the vendor for multiple expenses.</span><span class="sxs-lookup"><span data-stu-id="661e3-228">A single invoice can be raised by the vendor for multiple expenses.</span></span> <span data-ttu-id="661e3-229">For example, vendor issued a single invoice for INR 100000; INR 50000 each towards two services under TDS Section 194C and 194J.</span><span class="sxs-lookup"><span data-stu-id="661e3-229">For example, vendor issued a single invoice for INR 100000; INR 50000 each towards two services under TDS Section 194C and 194J.</span></span>

  - <span data-ttu-id="661e3-230">In this case TDS calculation will be as following:</span><span class="sxs-lookup"><span data-stu-id="661e3-230">In this case TDS calculation will be as following:</span></span>

    |<span data-ttu-id="661e3-231">Component</span><span class="sxs-lookup"><span data-stu-id="661e3-231">Component</span></span>|<span data-ttu-id="661e3-232">Value</span><span class="sxs-lookup"><span data-stu-id="661e3-232">Value</span></span>|
    |----------------------------------|---------------------------------------|  
    |<span data-ttu-id="661e3-233">**TDS Base Amount**</span><span class="sxs-lookup"><span data-stu-id="661e3-233">**TDS Base Amount**</span></span>|<span data-ttu-id="661e3-234">100000</span><span class="sxs-lookup"><span data-stu-id="661e3-234">100000</span></span>|  
    |<span data-ttu-id="661e3-235">**TDS percent for 194C**</span><span class="sxs-lookup"><span data-stu-id="661e3-235">**TDS percent for 194C**</span></span>|<span data-ttu-id="661e3-236">1000 (50,000x2%)</span><span class="sxs-lookup"><span data-stu-id="661e3-236">1000 (50,000x2%)</span></span>|
    |<span data-ttu-id="661e3-237">**TDS percent for 194J**</span><span class="sxs-lookup"><span data-stu-id="661e3-237">**TDS percent for 194J**</span></span>|<span data-ttu-id="661e3-238">5000 (50,000x10%)</span><span class="sxs-lookup"><span data-stu-id="661e3-238">5000 (50,000x10%)</span></span>|

  - <span data-ttu-id="661e3-239">On posting invoice, GL Entries will be as following:</span><span class="sxs-lookup"><span data-stu-id="661e3-239">On posting invoice, GL Entries will be as following:</span></span>
     
    |<span data-ttu-id="661e3-240">Particulars</span><span class="sxs-lookup"><span data-stu-id="661e3-240">Particulars</span></span>|<span data-ttu-id="661e3-241">Amount</span><span class="sxs-lookup"><span data-stu-id="661e3-241">Amount</span></span>|
    |----------------------------------|---------------------------------------|  
    |<span data-ttu-id="661e3-242">**Expense Account (194C)**</span><span class="sxs-lookup"><span data-stu-id="661e3-242">**Expense Account (194C)**</span></span>|<span data-ttu-id="661e3-243">50000</span><span class="sxs-lookup"><span data-stu-id="661e3-243">50000</span></span>|
    |<span data-ttu-id="661e3-244">**Expense Account (194J)**</span><span class="sxs-lookup"><span data-stu-id="661e3-244">**Expense Account (194J)**</span></span>|<span data-ttu-id="661e3-245">50000</span><span class="sxs-lookup"><span data-stu-id="661e3-245">50000</span></span>|
    |<span data-ttu-id="661e3-246">**TDS Payable Account (194C)**</span><span class="sxs-lookup"><span data-stu-id="661e3-246">**TDS Payable Account (194C)**</span></span>|<span data-ttu-id="661e3-247">-1000</span><span class="sxs-lookup"><span data-stu-id="661e3-247">-1000</span></span>|
    |<span data-ttu-id="661e3-248">**TDS Payable Account (194J)**</span><span class="sxs-lookup"><span data-stu-id="661e3-248">**TDS Payable Account (194J)**</span></span>|<span data-ttu-id="661e3-249">-5000</span><span class="sxs-lookup"><span data-stu-id="661e3-249">-5000</span></span>|
    |<span data-ttu-id="661e3-250">**Vendor Account**</span><span class="sxs-lookup"><span data-stu-id="661e3-250">**Vendor Account**</span></span>|<span data-ttu-id="661e3-251">-94000</span><span class="sxs-lookup"><span data-stu-id="661e3-251">-94000</span></span>|


### <a name="tds-on-expenses-at-lower-rate-or-zero-rate"></a><span data-ttu-id="661e3-252">TDS on expenses at lower rate or zero rate</span><span class="sxs-lookup"><span data-stu-id="661e3-252">TDS on expenses at lower rate or zero rate</span></span>

<span data-ttu-id="661e3-253">If a vendor has a certificate of concessional rate instead of normal rate then to handle that scenario, concessional codes can be configured and attached to those vendors.</span><span class="sxs-lookup"><span data-stu-id="661e3-253">If a vendor has a certificate of concessional rate instead of normal rate then to handle that scenario, concessional codes can be configured and attached to those vendors.</span></span>

<span data-ttu-id="661e3-254">In the given scenario, vendor issued an invoice for INR 100000 towards professional services.</span><span class="sxs-lookup"><span data-stu-id="661e3-254">In the given scenario, vendor issued an invoice for INR 100000 towards professional services.</span></span> <span data-ttu-id="661e3-255">Vendor has a certificate of income tax at Lower rate @ 5% on professional services instead of normal rate.</span><span class="sxs-lookup"><span data-stu-id="661e3-255">Vendor has a certificate of income tax at Lower rate @ 5% on professional services instead of normal rate.</span></span>

  - <span data-ttu-id="661e3-256">In this case TDS calculation will be as following:</span><span class="sxs-lookup"><span data-stu-id="661e3-256">In this case TDS calculation will be as following:</span></span>

    |<span data-ttu-id="661e3-257">Component</span><span class="sxs-lookup"><span data-stu-id="661e3-257">Component</span></span>|<span data-ttu-id="661e3-258">Value</span><span class="sxs-lookup"><span data-stu-id="661e3-258">Value</span></span>|
    |----------------------------------|---------------------------------------|  
    |<span data-ttu-id="661e3-259">**TDS Base Amount**</span><span class="sxs-lookup"><span data-stu-id="661e3-259">**TDS Base Amount**</span></span>|<span data-ttu-id="661e3-260">100000</span><span class="sxs-lookup"><span data-stu-id="661e3-260">100000</span></span>|  
    |<span data-ttu-id="661e3-261">**TDS Amount**</span><span class="sxs-lookup"><span data-stu-id="661e3-261">**TDS Amount**</span></span>|<span data-ttu-id="661e3-262">5000 (100000\*5%)</span><span class="sxs-lookup"><span data-stu-id="661e3-262">5000 (100000\*5%)</span></span>|

  - <span data-ttu-id="661e3-263">On posting invoice, GL Entries will be as following:</span><span class="sxs-lookup"><span data-stu-id="661e3-263">On posting invoice, GL Entries will be as following:</span></span>
     
    |<span data-ttu-id="661e3-264">Particulars</span><span class="sxs-lookup"><span data-stu-id="661e3-264">Particulars</span></span>|<span data-ttu-id="661e3-265">Amount</span><span class="sxs-lookup"><span data-stu-id="661e3-265">Amount</span></span>|
    |----------------------------------|---------------------------------------|  
    |<span data-ttu-id="661e3-266">**Expense Account**</span><span class="sxs-lookup"><span data-stu-id="661e3-266">**Expense Account**</span></span>|<span data-ttu-id="661e3-267">100000</span><span class="sxs-lookup"><span data-stu-id="661e3-267">100000</span></span>|
    |<span data-ttu-id="661e3-268">**TDS Payable Account**</span><span class="sxs-lookup"><span data-stu-id="661e3-268">**TDS Payable Account**</span></span>|<span data-ttu-id="661e3-269">-5000</span><span class="sxs-lookup"><span data-stu-id="661e3-269">-5000</span></span>|
    |<span data-ttu-id="661e3-270">**Vendor Account**</span><span class="sxs-lookup"><span data-stu-id="661e3-270">**Vendor Account**</span></span>|<span data-ttu-id="661e3-271">-95000</span><span class="sxs-lookup"><span data-stu-id="661e3-271">-95000</span></span>|

<span data-ttu-id="661e3-272">In this scenario, vendor issued an invoice for INR 100000 towards professional services.</span><span class="sxs-lookup"><span data-stu-id="661e3-272">In this scenario, vendor issued an invoice for INR 100000 towards professional services.</span></span> <span data-ttu-id="661e3-273">vendor has a certificate of income tax at Zero rate @ 0% on professional services instead of normal rate.</span><span class="sxs-lookup"><span data-stu-id="661e3-273">vendor has a certificate of income tax at Zero rate @ 0% on professional services instead of normal rate.</span></span>

  - <span data-ttu-id="661e3-274">In this case TDS calculation will be as following:</span><span class="sxs-lookup"><span data-stu-id="661e3-274">In this case TDS calculation will be as following:</span></span>

    |<span data-ttu-id="661e3-275">Component</span><span class="sxs-lookup"><span data-stu-id="661e3-275">Component</span></span>|<span data-ttu-id="661e3-276">Value</span><span class="sxs-lookup"><span data-stu-id="661e3-276">Value</span></span>|
    |----------------------------------|---------------------------------------|  
    |<span data-ttu-id="661e3-277">**TDS Base Amount**</span><span class="sxs-lookup"><span data-stu-id="661e3-277">**TDS Base Amount**</span></span>|<span data-ttu-id="661e3-278">100000</span><span class="sxs-lookup"><span data-stu-id="661e3-278">100000</span></span>|  
    |<span data-ttu-id="661e3-279">**TDS Amount**</span><span class="sxs-lookup"><span data-stu-id="661e3-279">**TDS Amount**</span></span>|<span data-ttu-id="661e3-280">0 (100000\*0%)</span><span class="sxs-lookup"><span data-stu-id="661e3-280">0 (100000\*0%)</span></span>|

  - <span data-ttu-id="661e3-281">On posting invoice, GL Entries will be as following:</span><span class="sxs-lookup"><span data-stu-id="661e3-281">On posting invoice, GL Entries will be as following:</span></span>
     
    |<span data-ttu-id="661e3-282">Particulars</span><span class="sxs-lookup"><span data-stu-id="661e3-282">Particulars</span></span>|<span data-ttu-id="661e3-283">Amount</span><span class="sxs-lookup"><span data-stu-id="661e3-283">Amount</span></span>|
    |----------------------------------|---------------------------------------|  
    |<span data-ttu-id="661e3-284">**Expense Account**</span><span class="sxs-lookup"><span data-stu-id="661e3-284">**Expense Account**</span></span>|<span data-ttu-id="661e3-285">100000</span><span class="sxs-lookup"><span data-stu-id="661e3-285">100000</span></span>|
    |<span data-ttu-id="661e3-286">**Vendor Account**</span><span class="sxs-lookup"><span data-stu-id="661e3-286">**Vendor Account**</span></span>|<span data-ttu-id="661e3-287">-100000</span><span class="sxs-lookup"><span data-stu-id="661e3-287">-100000</span></span>|

> [!NOTE]
> <span data-ttu-id="661e3-288">Concession Code must be selected on vendor master for lower or zero rated TDS transactions.</span><span class="sxs-lookup"><span data-stu-id="661e3-288">Concession Code must be selected on vendor master for lower or zero rated TDS transactions.</span></span>






































