---
title: TCS calculation on Sales and Receipt Transactions
description: TCS calculation on Sales and Receipt Transactions Transactions
author: v-debapd
ms.service: dynamics365-business-central
ms.topic: article
ms.devlang: na
ms.tgt_pltfrm: na
ms.workload: na
ms.search.keywords: India, local, IN, English
ms.date: 10/01/2020
ms.author: v-debapd
ms.openlocfilehash: 16ad10f5d3b01b8b27a48c794d686a213bba7820
ms.sourcegitcommit: ddbb5cede750df1baba4b3eab8fbed6744b5b9d6
ms.translationtype: HT
ms.contentlocale: en-IN
ms.lasthandoff: 10/01/2020
ms.locfileid: "3948613"
---
# <a name="tcs-calculation-on-sales-and-receipt-transactions"></a><span data-ttu-id="ddce3-103">TCS Calculation on Sales and Receipt Transactions</span><span class="sxs-lookup"><span data-stu-id="ddce3-103">TCS Calculation on Sales and Receipt Transactions</span></span>

[!INCLUDE[vnext_preview](../../includes/vnext_preview.md)]

<span data-ttu-id="ddce3-104">TCS can be collected on goods (Items) and services (G/L Account) transactions.</span><span class="sxs-lookup"><span data-stu-id="ddce3-104">TCS can be collected on goods (Items) and services (G/L Account) transactions.</span></span> <span data-ttu-id="ddce3-105">TCS calculations can be done through following documents:</span><span class="sxs-lookup"><span data-stu-id="ddce3-105">TCS calculations can be done through following documents:</span></span>

- <span data-ttu-id="ddce3-106">Sales Order</span><span class="sxs-lookup"><span data-stu-id="ddce3-106">Sales Order</span></span>
- <span data-ttu-id="ddce3-107">Sales Invoice</span><span class="sxs-lookup"><span data-stu-id="ddce3-107">Sales Invoice</span></span>
- <span data-ttu-id="ddce3-108">Sales Return Order</span><span class="sxs-lookup"><span data-stu-id="ddce3-108">Sales Return Order</span></span>
- <span data-ttu-id="ddce3-109">Sales Credit Memo</span><span class="sxs-lookup"><span data-stu-id="ddce3-109">Sales Credit Memo</span></span>
- <span data-ttu-id="ddce3-110">General Journal</span><span class="sxs-lookup"><span data-stu-id="ddce3-110">General Journal</span></span>
- <span data-ttu-id="ddce3-111">Sales Journal</span><span class="sxs-lookup"><span data-stu-id="ddce3-111">Sales Journal</span></span>
- <span data-ttu-id="ddce3-112">Cash Receipt Voucher</span><span class="sxs-lookup"><span data-stu-id="ddce3-112">Cash Receipt Voucher</span></span>
- <span data-ttu-id="ddce3-113">Bank Receipt Voucher</span><span class="sxs-lookup"><span data-stu-id="ddce3-113">Bank Receipt Voucher</span></span>

## <a name="tcs-calculation-on-general-journal-sales-journal-cash-receipt-journal-sales-invoice-sales-order-sales-return-order-sales-credit-memo"></a><span data-ttu-id="ddce3-114">TCS calculation on general journal, sales journal, cash receipt journal, sales invoice, sales order, sales return order, sales credit memo.</span><span class="sxs-lookup"><span data-stu-id="ddce3-114">TCS calculation on general journal, sales journal, cash receipt journal, sales invoice, sales order, sales return order, sales credit memo.</span></span>

- <span data-ttu-id="ddce3-115">Create General Journal, Sales Journal, Cash Receipt Journal or Bank Receipt Journal</span><span class="sxs-lookup"><span data-stu-id="ddce3-115">Create General Journal, Sales Journal, Cash Receipt Journal or Bank Receipt Journal</span></span>

  1.  <span data-ttu-id="ddce3-116">Choose the ![Search for Page or Report](image/search_small.png "Search for Page or Report icon") icon, enter **General Journal** , **Sales Journal** , **Cash Receipt Voucher** or **Bank Receipt Voucher** , and then choose the related link.</span><span class="sxs-lookup"><span data-stu-id="ddce3-116">Choose the ![Search for Page or Report](image/search_small.png "Search for Page or Report icon") icon, enter **General Journal** , **Sales Journal** , **Cash Receipt Voucher** or **Bank Receipt Voucher** , and then choose the related link.</span></span> 
  2. <span data-ttu-id="ddce3-117">Select **Customer** in Account Type and select relevant customer code in Account No. field.</span><span class="sxs-lookup"><span data-stu-id="ddce3-117">Select **Customer** in Account Type and select relevant customer code in Account No. field.</span></span> 
  3. <span data-ttu-id="ddce3-118">Select **G/L Account** or **Bank Account** in Bal. Account Type and select relevant expense account in Bal. Account.</span><span class="sxs-lookup"><span data-stu-id="ddce3-118">Select **G/L Account** or **Bank Account** in Bal. Account Type and select relevant expense account in Bal. Account.</span></span> <span data-ttu-id="ddce3-119">No.</span><span class="sxs-lookup"><span data-stu-id="ddce3-119">No.</span></span> <span data-ttu-id="ddce3-120">field.</span><span class="sxs-lookup"><span data-stu-id="ddce3-120">field.</span></span>
  4. <span data-ttu-id="ddce3-121">Select relevant **TCS Nature of Collection** in journal line.</span><span class="sxs-lookup"><span data-stu-id="ddce3-121">Select relevant **TCS Nature of Collection** in journal line.</span></span> <span data-ttu-id="ddce3-122">**Location Code** and **T.C.A.N No.**</span><span class="sxs-lookup"><span data-stu-id="ddce3-122">**Location Code** and **T.C.A.N No.**</span></span> <span data-ttu-id="ddce3-123">fields should not be blank.</span><span class="sxs-lookup"><span data-stu-id="ddce3-123">fields should not be blank.</span></span>

- <span data-ttu-id="ddce3-124">Create Sales Invoice or Sales Order</span><span class="sxs-lookup"><span data-stu-id="ddce3-124">Create Sales Invoice or Sales Order</span></span>

  1. <span data-ttu-id="ddce3-125">Choose the ![Search for Page or Report](image/search_small.png "Search for Page or Report icon") icon, enter **Sales Invoice** , **Sales Order** , **Sales Return Order** or **Sales Credit Memo** , and then choose the related link.</span><span class="sxs-lookup"><span data-stu-id="ddce3-125">Choose the ![Search for Page or Report](image/search_small.png "Search for Page or Report icon") icon, enter **Sales Invoice** , **Sales Order** , **Sales Return Order** or **Sales Credit Memo** , and then choose the related link.</span></span>
  2. <span data-ttu-id="ddce3-126">Select **Customer** , **Location Code** on **Sales Order** , **Sales Invoice** , **Sales Return Order** or **Sales Credit Memo** header.</span><span class="sxs-lookup"><span data-stu-id="ddce3-126">Select **Customer** , **Location Code** on **Sales Order** , **Sales Invoice** , **Sales Return Order** or **Sales Credit Memo** header.</span></span>
  3. <span data-ttu-id="ddce3-127">Select **G/L Account** or **Item Code** on **Sales Order** , **Sales Invoice** , **Sales Return Order** or **Sales Credit Memo** line.</span><span class="sxs-lookup"><span data-stu-id="ddce3-127">Select **G/L Account** or **Item Code** on **Sales Order** , **Sales Invoice** , **Sales Return Order** or **Sales Credit Memo** line.</span></span>
  4. <span data-ttu-id="ddce3-128">**TCS Nature of Collection** , **Location Code** and **T.C.A.N No.**</span><span class="sxs-lookup"><span data-stu-id="ddce3-128">**TCS Nature of Collection** , **Location Code** and **T.C.A.N No.**</span></span> <span data-ttu-id="ddce3-129">fields should not be blank.</span><span class="sxs-lookup"><span data-stu-id="ddce3-129">fields should not be blank.</span></span>

### <a name="tcs-to-be-calculated-on-customer-invoice-through-general-journal-sales-journal-sales-invoice-or-sales-order"></a><span data-ttu-id="ddce3-130">TCS to be calculated on customer invoice (through general journal, sales journal, sales invoice or sales order)</span><span class="sxs-lookup"><span data-stu-id="ddce3-130">TCS to be calculated on customer invoice (through general journal, sales journal, sales invoice or sales order)</span></span>

<span data-ttu-id="ddce3-131">For example, invoice has been issued to customer for INR 10,000 on which 1% TCS is applicable for Nature of Collection 'Scrap'.</span><span class="sxs-lookup"><span data-stu-id="ddce3-131">For example, invoice has been issued to customer for INR 10,000 on which 1% TCS is applicable for Nature of Collection 'Scrap'.</span></span>
  
  - <span data-ttu-id="ddce3-132">In this case TCS calculation will be as following:</span><span class="sxs-lookup"><span data-stu-id="ddce3-132">In this case TCS calculation will be as following:</span></span>

    |<span data-ttu-id="ddce3-133">Component</span><span class="sxs-lookup"><span data-stu-id="ddce3-133">Component</span></span>|<span data-ttu-id="ddce3-134">Value</span><span class="sxs-lookup"><span data-stu-id="ddce3-134">Value</span></span>|
    |----------------------------------|---------------------------------------|  
    |<span data-ttu-id="ddce3-135">**TCS Base Amount**</span><span class="sxs-lookup"><span data-stu-id="ddce3-135">**TCS Base Amount**</span></span>|<span data-ttu-id="ddce3-136">10000</span><span class="sxs-lookup"><span data-stu-id="ddce3-136">10000</span></span>|  
    |<span data-ttu-id="ddce3-137">**TCS Amount**</span><span class="sxs-lookup"><span data-stu-id="ddce3-137">**TCS Amount**</span></span>|<span data-ttu-id="ddce3-138">100 (10000\*1%)</span><span class="sxs-lookup"><span data-stu-id="ddce3-138">100 (10000\*1%)</span></span>|

  - <span data-ttu-id="ddce3-139">GL Entries will be as following:</span><span class="sxs-lookup"><span data-stu-id="ddce3-139">GL Entries will be as following:</span></span>
     
    |<span data-ttu-id="ddce3-140">Particulars</span><span class="sxs-lookup"><span data-stu-id="ddce3-140">Particulars</span></span>|<span data-ttu-id="ddce3-141">Amount</span><span class="sxs-lookup"><span data-stu-id="ddce3-141">Amount</span></span>|
    |----------------------------------|---------------------------------------|  
    |<span data-ttu-id="ddce3-142">**Customer Account**</span><span class="sxs-lookup"><span data-stu-id="ddce3-142">**Customer Account**</span></span>|<span data-ttu-id="ddce3-143">10100</span><span class="sxs-lookup"><span data-stu-id="ddce3-143">10100</span></span>|
    |<span data-ttu-id="ddce3-144">**TCS Payable Account**</span><span class="sxs-lookup"><span data-stu-id="ddce3-144">**TCS Payable Account**</span></span>|<span data-ttu-id="ddce3-145">-100</span><span class="sxs-lookup"><span data-stu-id="ddce3-145">-100</span></span>|
    |<span data-ttu-id="ddce3-146">**Sales Account**</span><span class="sxs-lookup"><span data-stu-id="ddce3-146">**Sales Account**</span></span>|<span data-ttu-id="ddce3-147">-10000</span><span class="sxs-lookup"><span data-stu-id="ddce3-147">-10000</span></span>|

## <a name="tcs-to-be-calculated-on-customer-advance-payment-through-general-journal-cash-receipt-journal"></a><span data-ttu-id="ddce3-148">TCS to be calculated on customer advance payment (through general journal, cash receipt journal)</span><span class="sxs-lookup"><span data-stu-id="ddce3-148">TCS to be calculated on customer advance payment (through general journal, cash receipt journal)</span></span>

<span data-ttu-id="ddce3-149">For example, advance payment received from customer for INR 10,000 on which 1% TCS is applicable for Nature of collection 'Scrap'</span><span class="sxs-lookup"><span data-stu-id="ddce3-149">For example, advance payment received from customer for INR 10,000 on which 1% TCS is applicable for Nature of collection 'Scrap'</span></span>

  - <span data-ttu-id="ddce3-150">In this case TCS calculation will be as following:</span><span class="sxs-lookup"><span data-stu-id="ddce3-150">In this case TCS calculation will be as following:</span></span>

    |<span data-ttu-id="ddce3-151">Component</span><span class="sxs-lookup"><span data-stu-id="ddce3-151">Component</span></span>|<span data-ttu-id="ddce3-152">Value</span><span class="sxs-lookup"><span data-stu-id="ddce3-152">Value</span></span>|
    |----------------------------------|---------------------------------------|  
    |<span data-ttu-id="ddce3-153">**TCS Base Amount**</span><span class="sxs-lookup"><span data-stu-id="ddce3-153">**TCS Base Amount**</span></span>|<span data-ttu-id="ddce3-154">10000</span><span class="sxs-lookup"><span data-stu-id="ddce3-154">10000</span></span>|  
    |<span data-ttu-id="ddce3-155">**TCS Amount**</span><span class="sxs-lookup"><span data-stu-id="ddce3-155">**TCS Amount**</span></span>|<span data-ttu-id="ddce3-156">99 (10000x1%/101)</span><span class="sxs-lookup"><span data-stu-id="ddce3-156">99 (10000x1%/101)</span></span>|

  - <span data-ttu-id="ddce3-157">GL Entries will be as following:</span><span class="sxs-lookup"><span data-stu-id="ddce3-157">GL Entries will be as following:</span></span>
     
    |<span data-ttu-id="ddce3-158">Particulars</span><span class="sxs-lookup"><span data-stu-id="ddce3-158">Particulars</span></span>|<span data-ttu-id="ddce3-159">Amount</span><span class="sxs-lookup"><span data-stu-id="ddce3-159">Amount</span></span>|
    |----------------------------------|---------------------------------------|  
    |<span data-ttu-id="ddce3-160">**Bank Account**</span><span class="sxs-lookup"><span data-stu-id="ddce3-160">**Bank Account**</span></span>|<span data-ttu-id="ddce3-161">10000</span><span class="sxs-lookup"><span data-stu-id="ddce3-161">10000</span></span>|
    |<span data-ttu-id="ddce3-162">**TCS Payable Account**</span><span class="sxs-lookup"><span data-stu-id="ddce3-162">**TCS Payable Account**</span></span>|<span data-ttu-id="ddce3-163">-99</span><span class="sxs-lookup"><span data-stu-id="ddce3-163">-99</span></span>|
    |<span data-ttu-id="ddce3-164">**Customer Account**</span><span class="sxs-lookup"><span data-stu-id="ddce3-164">**Customer Account**</span></span>|<span data-ttu-id="ddce3-165">-9901</span><span class="sxs-lookup"><span data-stu-id="ddce3-165">-9901</span></span>|

## <a name="adjustment-of-calculated-tcs-on-advance-payment-against-sales-invoice"></a><span data-ttu-id="ddce3-166">Adjustment of calculated TCS on advance payment against sales invoice</span><span class="sxs-lookup"><span data-stu-id="ddce3-166">Adjustment of calculated TCS on advance payment against sales invoice</span></span>

<span data-ttu-id="ddce3-167">TCS which has been calculated on advance payment can be adjusted while creating Sales Invoice against that advance payment.</span><span class="sxs-lookup"><span data-stu-id="ddce3-167">TCS which has been calculated on advance payment can be adjusted while creating Sales Invoice against that advance payment.</span></span> <span data-ttu-id="ddce3-168">TCS will not be calculated on Customer Invoices if advance payment, on which TCS has already been calculated, is applied to the invoice.</span><span class="sxs-lookup"><span data-stu-id="ddce3-168">TCS will not be calculated on Customer Invoices if advance payment, on which TCS has already been calculated, is applied to the invoice.</span></span> <span data-ttu-id="ddce3-169">System should check the TCS base amount upon which the TCS has been calculated on advance payments with the line amount of Sales Invoice and TCS will only be calculated on the line amount, which is more than the TCS base amount.</span><span class="sxs-lookup"><span data-stu-id="ddce3-169">System should check the TCS base amount on which TCS has been calculated on advance payment with the line amount of Sales Invoice and TCS will only be calculated on the line amount which is more than the TCS base amount.</span></span> <span data-ttu-id="ddce3-170">For example: If TCS base amount was 10,000.00 in advance payment and line amount is 20,000.00 on sales invoice, then TCS will be calculated on 10,000.00 on sales invoice.</span><span class="sxs-lookup"><span data-stu-id="ddce3-170">For example: If TCS base amount was 10,000.00 in advance payment and line amount is 20,000.00 on sales invoice, then TCS will be calculated on 10,000.00 on sales invoice.</span></span>

  - <span data-ttu-id="ddce3-171">GL Entries for TCS on Customer advance payment using Cash Receipt Journal, will be as following:</span><span class="sxs-lookup"><span data-stu-id="ddce3-171">GL Entries for TCS on Customer advance payment using Cash Receipt Journal, will be as following:</span></span>
     
    |<span data-ttu-id="ddce3-172">Particulars</span><span class="sxs-lookup"><span data-stu-id="ddce3-172">Particulars</span></span>|<span data-ttu-id="ddce3-173">Amount</span><span class="sxs-lookup"><span data-stu-id="ddce3-173">Amount</span></span>|
    |----------------------------------|---------------------------------------|  
    |<span data-ttu-id="ddce3-174">**Bank Account**</span><span class="sxs-lookup"><span data-stu-id="ddce3-174">**Bank Account**</span></span>|<span data-ttu-id="ddce3-175">10000</span><span class="sxs-lookup"><span data-stu-id="ddce3-175">10000</span></span>|
    |<span data-ttu-id="ddce3-176">**TCS Payable Account**</span><span class="sxs-lookup"><span data-stu-id="ddce3-176">**TCS Payable Account**</span></span>|<span data-ttu-id="ddce3-177">-99</span><span class="sxs-lookup"><span data-stu-id="ddce3-177">-99</span></span>|
    |<span data-ttu-id="ddce3-178">**Customer Account**</span><span class="sxs-lookup"><span data-stu-id="ddce3-178">**Customer Account**</span></span>|<span data-ttu-id="ddce3-179">-9901</span><span class="sxs-lookup"><span data-stu-id="ddce3-179">-9901</span></span>|

  - <span data-ttu-id="ddce3-180">GL Entries for TCS on Customer Invoice using Sales Invoice against advance payment, will be as following:</span><span class="sxs-lookup"><span data-stu-id="ddce3-180">GL Entries for TCS on Customer Invoice using Sales Invoice against advance payment, will be as following:</span></span>
     
    |<span data-ttu-id="ddce3-181">Particulars</span><span class="sxs-lookup"><span data-stu-id="ddce3-181">Particulars</span></span>|<span data-ttu-id="ddce3-182">Amount</span><span class="sxs-lookup"><span data-stu-id="ddce3-182">Amount</span></span>|
    |----------------------------------|---------------------------------------|  
    |<span data-ttu-id="ddce3-183">**Customer Account**</span><span class="sxs-lookup"><span data-stu-id="ddce3-183">**Customer Account**</span></span>|<span data-ttu-id="ddce3-184">20101</span><span class="sxs-lookup"><span data-stu-id="ddce3-184">20101</span></span>|
    |<span data-ttu-id="ddce3-185">**TCS Payable Account**</span><span class="sxs-lookup"><span data-stu-id="ddce3-185">**TCS Payable Account**</span></span>|<span data-ttu-id="ddce3-186">-101</span><span class="sxs-lookup"><span data-stu-id="ddce3-186">-101</span></span>|
    |<span data-ttu-id="ddce3-187">**Sales Account**</span><span class="sxs-lookup"><span data-stu-id="ddce3-187">**Sales Account**</span></span>|<span data-ttu-id="ddce3-188">-20000</span><span class="sxs-lookup"><span data-stu-id="ddce3-188">-20000</span></span>|

> [!NOTE]
> <span data-ttu-id="ddce3-189">TCS is calculated after adjusting the TCS amount which was earlier calculated on advance payment.</span><span class="sxs-lookup"><span data-stu-id="ddce3-189">TCS is calculated after adjusting the TCS amount which was earlier calculated on advance payment.</span></span>


## <a name="tcs-to-be-calculated-on-non-resident-customer-invoice-in-fcy"></a><span data-ttu-id="ddce3-190">TCS to be calculated on non-resident customer invoice in FCY</span><span class="sxs-lookup"><span data-stu-id="ddce3-190">TCS to be calculated on non-resident customer invoice in FCY</span></span>

<span data-ttu-id="ddce3-191">For example, the invoice has been raised to the foreign customer for USD 10,000, upon which 1% TCS is applicable for Nature of collection 'Scrap'.</span><span class="sxs-lookup"><span data-stu-id="ddce3-191">For example, invoice has been raised to foreign customer for USD 10,000 on which 1% TCS is applicable for Nature of collection 'Scrap'.</span></span> <span data-ttu-id="ddce3-192">All foreign currency amounts will get converted into INR based on currency exchange rates.</span><span class="sxs-lookup"><span data-stu-id="ddce3-192">All foreign currency amounts will get converted into INR based on currency exchange rates.</span></span> <span data-ttu-id="ddce3-193">The exchange rate applied in this example is 1 USD = 65 INR.</span><span class="sxs-lookup"><span data-stu-id="ddce3-193">Exchange rate considered for this example is 1 USD = 65 INR.</span></span>

  - <span data-ttu-id="ddce3-194">In this case TCS calculation will be as following:</span><span class="sxs-lookup"><span data-stu-id="ddce3-194">In this case TCS calculation will be as following:</span></span>

    |<span data-ttu-id="ddce3-195">Component</span><span class="sxs-lookup"><span data-stu-id="ddce3-195">Component</span></span>|<span data-ttu-id="ddce3-196">Value</span><span class="sxs-lookup"><span data-stu-id="ddce3-196">Value</span></span>|
    |----------------------------------|---------------------------------------|  
    |<span data-ttu-id="ddce3-197">**TCS Base Amount**</span><span class="sxs-lookup"><span data-stu-id="ddce3-197">**TCS Base Amount**</span></span>|<span data-ttu-id="ddce3-198">USD 10000 or INR 650000</span><span class="sxs-lookup"><span data-stu-id="ddce3-198">USD 10000 or INR 650000</span></span>|  
    |<span data-ttu-id="ddce3-199">**TCS Amount**</span><span class="sxs-lookup"><span data-stu-id="ddce3-199">**TCS Amount**</span></span>|<span data-ttu-id="ddce3-200">INR 6500(650000x1%)</span><span class="sxs-lookup"><span data-stu-id="ddce3-200">INR 6500(650000x1%)</span></span>|

  - <span data-ttu-id="ddce3-201">GL Entries will be as following:</span><span class="sxs-lookup"><span data-stu-id="ddce3-201">GL Entries will be as following:</span></span>
     
    |<span data-ttu-id="ddce3-202">Particulars</span><span class="sxs-lookup"><span data-stu-id="ddce3-202">Particulars</span></span>|<span data-ttu-id="ddce3-203">Amount</span><span class="sxs-lookup"><span data-stu-id="ddce3-203">Amount</span></span>|
    |----------------------------------|---------------------------------------|  
    |<span data-ttu-id="ddce3-204">**Customer Account**</span><span class="sxs-lookup"><span data-stu-id="ddce3-204">**Customer Account**</span></span>|<span data-ttu-id="ddce3-205">656500</span><span class="sxs-lookup"><span data-stu-id="ddce3-205">656500</span></span>|
    |<span data-ttu-id="ddce3-206">**TCS Payable Account**</span><span class="sxs-lookup"><span data-stu-id="ddce3-206">**TCS Payable Account**</span></span>|<span data-ttu-id="ddce3-207">-6500</span><span class="sxs-lookup"><span data-stu-id="ddce3-207">-6500</span></span>|
    |<span data-ttu-id="ddce3-208">**Sales Account**</span><span class="sxs-lookup"><span data-stu-id="ddce3-208">**Sales Account**</span></span>|<span data-ttu-id="ddce3-209">-650000</span><span class="sxs-lookup"><span data-stu-id="ddce3-209">-650000</span></span>|



## <a name="tcs-calculation-on-higher-rate-if-customer-is-not-having-pan"></a><span data-ttu-id="ddce3-210">TCS calculation on higher rate if customer is not having PAN</span><span class="sxs-lookup"><span data-stu-id="ddce3-210">TCS calculation on higher rate if customer is not having PAN</span></span>

<span data-ttu-id="ddce3-211">For example, invoice has been raised to customer for INR 50,000 on which 1% TCS is applicable for Nature of collection 'Scrap'.</span><span class="sxs-lookup"><span data-stu-id="ddce3-211">For example, invoice has been raised to customer for INR 50,000 on which 1% TCS is applicable for Nature of collection 'Scrap'.</span></span> <span data-ttu-id="ddce3-212">But if there is no PAN available for customer then higher TCS of 5% is applicable.</span><span class="sxs-lookup"><span data-stu-id="ddce3-212">But if there is no PAN available for customer then higher TCS of 5% is applicable.</span></span>

  - <span data-ttu-id="ddce3-213">In this case TCS calculation will be as following:</span><span class="sxs-lookup"><span data-stu-id="ddce3-213">In this case TCS calculation will be as following:</span></span>

    |<span data-ttu-id="ddce3-214">Component</span><span class="sxs-lookup"><span data-stu-id="ddce3-214">Component</span></span>|<span data-ttu-id="ddce3-215">Value</span><span class="sxs-lookup"><span data-stu-id="ddce3-215">Value</span></span>|
    |----------------------------------|---------------------------------------|  
    |<span data-ttu-id="ddce3-216">**TCS Base Amount**</span><span class="sxs-lookup"><span data-stu-id="ddce3-216">**TCS Base Amount**</span></span>|<span data-ttu-id="ddce3-217">50000</span><span class="sxs-lookup"><span data-stu-id="ddce3-217">50000</span></span>|  
    |<span data-ttu-id="ddce3-218">**TCS Amount**</span><span class="sxs-lookup"><span data-stu-id="ddce3-218">**TCS Amount**</span></span>|<span data-ttu-id="ddce3-219">2500(50000x5%)</span><span class="sxs-lookup"><span data-stu-id="ddce3-219">2500(50000x5%)</span></span>|

  - <span data-ttu-id="ddce3-220">GL Entries will be as following:</span><span class="sxs-lookup"><span data-stu-id="ddce3-220">GL Entries will be as following:</span></span>
     
    |<span data-ttu-id="ddce3-221">Particulars</span><span class="sxs-lookup"><span data-stu-id="ddce3-221">Particulars</span></span>|<span data-ttu-id="ddce3-222">Amount</span><span class="sxs-lookup"><span data-stu-id="ddce3-222">Amount</span></span>|
    |----------------------------------|---------------------------------------|  
    |<span data-ttu-id="ddce3-223">**Customer Account**</span><span class="sxs-lookup"><span data-stu-id="ddce3-223">**Customer Account**</span></span>|<span data-ttu-id="ddce3-224">52500</span><span class="sxs-lookup"><span data-stu-id="ddce3-224">52500</span></span>|
    |<span data-ttu-id="ddce3-225">**TCS Payable Account**</span><span class="sxs-lookup"><span data-stu-id="ddce3-225">**TCS Payable Account**</span></span>|<span data-ttu-id="ddce3-226">-2500</span><span class="sxs-lookup"><span data-stu-id="ddce3-226">-2500</span></span>|
    |<span data-ttu-id="ddce3-227">**Sales Account**</span><span class="sxs-lookup"><span data-stu-id="ddce3-227">**Sales Account**</span></span>|<span data-ttu-id="ddce3-228">-50000</span><span class="sxs-lookup"><span data-stu-id="ddce3-228">-50000</span></span>|

## <a name="tcs-calculation-on-multiple-nature-of-goods-in-single-invoice"></a><span data-ttu-id="ddce3-229">TCS calculation on multiple nature of goods in single invoice</span><span class="sxs-lookup"><span data-stu-id="ddce3-229">TCS calculation on multiple nature of goods in single invoice</span></span>

<span data-ttu-id="ddce3-230">For example, invoice has been raised to customer for INR 1,00,000.</span><span class="sxs-lookup"><span data-stu-id="ddce3-230">For example, invoice has been raised to customer for INR 1,00,000.</span></span> <span data-ttu-id="ddce3-231">INR 50,000 each towards two nature of goods 'Scrap' and 'Timber'.</span><span class="sxs-lookup"><span data-stu-id="ddce3-231">INR 50,000 each towards two nature of goods 'Scrap' and 'Timber'.</span></span>

  - <span data-ttu-id="ddce3-232">In this case TCS calculation will be as following:</span><span class="sxs-lookup"><span data-stu-id="ddce3-232">In this case TCS calculation will be as following:</span></span>

    |<span data-ttu-id="ddce3-233">Component</span><span class="sxs-lookup"><span data-stu-id="ddce3-233">Component</span></span>|<span data-ttu-id="ddce3-234">Value</span><span class="sxs-lookup"><span data-stu-id="ddce3-234">Value</span></span>|
    |----------------------------------|---------------------------------------|  
    |<span data-ttu-id="ddce3-235">**TCS Base Amount**</span><span class="sxs-lookup"><span data-stu-id="ddce3-235">**TCS Base Amount**</span></span>|<span data-ttu-id="ddce3-236">100000</span><span class="sxs-lookup"><span data-stu-id="ddce3-236">100000</span></span>|  
    |<span data-ttu-id="ddce3-237">**TCS Amount on Scrap**</span><span class="sxs-lookup"><span data-stu-id="ddce3-237">**TCS Amount on Scrap**</span></span>|<span data-ttu-id="ddce3-238">500(50000x1%)</span><span class="sxs-lookup"><span data-stu-id="ddce3-238">500(50000x1%)</span></span>|
    |<span data-ttu-id="ddce3-239">**TCS Amount on Timber**</span><span class="sxs-lookup"><span data-stu-id="ddce3-239">**TCS Amount on Timber**</span></span>|<span data-ttu-id="ddce3-240">2500(50000x5%)</span><span class="sxs-lookup"><span data-stu-id="ddce3-240">2500(50000x5%)</span></span>

  - <span data-ttu-id="ddce3-241">GL Entries will be as following:</span><span class="sxs-lookup"><span data-stu-id="ddce3-241">GL Entries will be as following:</span></span>
     
    |<span data-ttu-id="ddce3-242">Particulars</span><span class="sxs-lookup"><span data-stu-id="ddce3-242">Particulars</span></span>|<span data-ttu-id="ddce3-243">Amount</span><span class="sxs-lookup"><span data-stu-id="ddce3-243">Amount</span></span>|
    |----------------------------------|---------------------------------------|  
    |<span data-ttu-id="ddce3-244">**Customer Account**</span><span class="sxs-lookup"><span data-stu-id="ddce3-244">**Customer Account**</span></span>|<span data-ttu-id="ddce3-245">103000</span><span class="sxs-lookup"><span data-stu-id="ddce3-245">103000</span></span>|
    |<span data-ttu-id="ddce3-246">**TCS Payable Account - Scrap**</span><span class="sxs-lookup"><span data-stu-id="ddce3-246">**TCS Payable Account - Scrap**</span></span>|<span data-ttu-id="ddce3-247">-500</span><span class="sxs-lookup"><span data-stu-id="ddce3-247">-500</span></span>|
    |<span data-ttu-id="ddce3-248">**TCS Payable Account - Timber**</span><span class="sxs-lookup"><span data-stu-id="ddce3-248">**TCS Payable Account - Timber**</span></span>|<span data-ttu-id="ddce3-249">-2500</span><span class="sxs-lookup"><span data-stu-id="ddce3-249">-2500</span></span>|
    |<span data-ttu-id="ddce3-250">**Sales Account - Scrap**</span><span class="sxs-lookup"><span data-stu-id="ddce3-250">**Sales Account - Scrap**</span></span>|<span data-ttu-id="ddce3-251">-50000</span><span class="sxs-lookup"><span data-stu-id="ddce3-251">-50000</span></span>|
    |<span data-ttu-id="ddce3-252">**Sales Account - Timber**</span><span class="sxs-lookup"><span data-stu-id="ddce3-252">**Sales Account - Timber**</span></span>|<span data-ttu-id="ddce3-253">-50000</span><span class="sxs-lookup"><span data-stu-id="ddce3-253">-50000</span></span>|

## <a name="tcs-on-sale-of-scrap--lower-rate"></a><span data-ttu-id="ddce3-254">TCS on sale of scrap @ lower rate</span><span class="sxs-lookup"><span data-stu-id="ddce3-254">TCS on sale of scrap @ lower rate</span></span>

<span data-ttu-id="ddce3-255">For example, invoice has been raised to customer for INR 1,00,000 towards sale of Scrap.</span><span class="sxs-lookup"><span data-stu-id="ddce3-255">For example, invoice has been raised to customer for INR 1,00,000 towards sale of Scrap.</span></span> <span data-ttu-id="ddce3-256">Customer has a certificate of income tax at Lower rate @ 0.5% on Scrap instead of normal rate.</span><span class="sxs-lookup"><span data-stu-id="ddce3-256">Customer has a certificate of income tax at Lower rate @ 0.5% on Scrap instead of normal rate.</span></span>

  - <span data-ttu-id="ddce3-257">In this case TCS calculation will be as following:</span><span class="sxs-lookup"><span data-stu-id="ddce3-257">In this case TCS calculation will be as following:</span></span>

    |<span data-ttu-id="ddce3-258">Component</span><span class="sxs-lookup"><span data-stu-id="ddce3-258">Component</span></span>|<span data-ttu-id="ddce3-259">Value</span><span class="sxs-lookup"><span data-stu-id="ddce3-259">Value</span></span>|
    |----------------------------------|---------------------------------------|  
    |<span data-ttu-id="ddce3-260">**TCS Base Amount**</span><span class="sxs-lookup"><span data-stu-id="ddce3-260">**TCS Base Amount**</span></span>|<span data-ttu-id="ddce3-261">100000</span><span class="sxs-lookup"><span data-stu-id="ddce3-261">100000</span></span>|  
    |<span data-ttu-id="ddce3-262">**TCS Amount**</span><span class="sxs-lookup"><span data-stu-id="ddce3-262">**TCS Amount**</span></span>|<span data-ttu-id="ddce3-263">500(100000x0.5%)</span><span class="sxs-lookup"><span data-stu-id="ddce3-263">500(100000x0.5%)</span></span>|
    
  - <span data-ttu-id="ddce3-264">GL Entries will be as following:</span><span class="sxs-lookup"><span data-stu-id="ddce3-264">GL Entries will be as following:</span></span>
     
    |<span data-ttu-id="ddce3-265">Particulars</span><span class="sxs-lookup"><span data-stu-id="ddce3-265">Particulars</span></span>|<span data-ttu-id="ddce3-266">Amount</span><span class="sxs-lookup"><span data-stu-id="ddce3-266">Amount</span></span>|
    |----------------------------------|---------------------------------------|  
    |<span data-ttu-id="ddce3-267">**Customer Account**</span><span class="sxs-lookup"><span data-stu-id="ddce3-267">**Customer Account**</span></span>|<span data-ttu-id="ddce3-268">103000</span><span class="sxs-lookup"><span data-stu-id="ddce3-268">103000</span></span>|
    |<span data-ttu-id="ddce3-269">**TCS Payable Account**</span><span class="sxs-lookup"><span data-stu-id="ddce3-269">**TCS Payable Account**</span></span>|<span data-ttu-id="ddce3-270">-500</span><span class="sxs-lookup"><span data-stu-id="ddce3-270">-500</span></span>|
    |<span data-ttu-id="ddce3-271">**Sales Account**</span><span class="sxs-lookup"><span data-stu-id="ddce3-271">**Sales Account**</span></span>|<span data-ttu-id="ddce3-272">-100000</span><span class="sxs-lookup"><span data-stu-id="ddce3-272">-100000</span></span>|

## <a name="tcs-on-sale-of-scrap--zero-rate"></a><span data-ttu-id="ddce3-273">TCS on sale of scrap @ zero rate</span><span class="sxs-lookup"><span data-stu-id="ddce3-273">TCS on sale of scrap @ zero rate</span></span>

<span data-ttu-id="ddce3-274">For example, invoice has been raised to customer for INR 1,00,000 towards sale of Scrap.</span><span class="sxs-lookup"><span data-stu-id="ddce3-274">For example, invoice has been raised to customer for INR 1,00,000 towards sale of Scrap.</span></span> <span data-ttu-id="ddce3-275">Customer has a certificate of income tax at Zero rate @ 0% on Scrap instead of normal rate.</span><span class="sxs-lookup"><span data-stu-id="ddce3-275">Customer has a certificate of income tax at Zero rate @ 0% on Scrap instead of normal rate.</span></span>

  - <span data-ttu-id="ddce3-276">In this case TCS calculation will be as following:</span><span class="sxs-lookup"><span data-stu-id="ddce3-276">In this case TCS calculation will be as following:</span></span>

    |<span data-ttu-id="ddce3-277">Component</span><span class="sxs-lookup"><span data-stu-id="ddce3-277">Component</span></span>|<span data-ttu-id="ddce3-278">Value</span><span class="sxs-lookup"><span data-stu-id="ddce3-278">Value</span></span>|
    |----------------------------------|---------------------------------------|  
    |<span data-ttu-id="ddce3-279">**TCS Base Amount**</span><span class="sxs-lookup"><span data-stu-id="ddce3-279">**TCS Base Amount**</span></span>|<span data-ttu-id="ddce3-280">100000</span><span class="sxs-lookup"><span data-stu-id="ddce3-280">100000</span></span>|  
    |<span data-ttu-id="ddce3-281">**TCS Amount**</span><span class="sxs-lookup"><span data-stu-id="ddce3-281">**TCS Amount**</span></span>|<span data-ttu-id="ddce3-282">0(100000x0%)</span><span class="sxs-lookup"><span data-stu-id="ddce3-282">0(100000x0%)</span></span>|
    
  - <span data-ttu-id="ddce3-283">GL Entries will be as following:</span><span class="sxs-lookup"><span data-stu-id="ddce3-283">GL Entries will be as following:</span></span>
     
    |<span data-ttu-id="ddce3-284">Particulars</span><span class="sxs-lookup"><span data-stu-id="ddce3-284">Particulars</span></span>|<span data-ttu-id="ddce3-285">Amount</span><span class="sxs-lookup"><span data-stu-id="ddce3-285">Amount</span></span>|
    |----------------------------------|---------------------------------------|  
    |<span data-ttu-id="ddce3-286">**Customer Account**</span><span class="sxs-lookup"><span data-stu-id="ddce3-286">**Customer Account**</span></span>|<span data-ttu-id="ddce3-287">100000</span><span class="sxs-lookup"><span data-stu-id="ddce3-287">100000</span></span>|
    |<span data-ttu-id="ddce3-288">**Sales Account**</span><span class="sxs-lookup"><span data-stu-id="ddce3-288">**Sales Account**</span></span>|<span data-ttu-id="ddce3-289">-100000</span><span class="sxs-lookup"><span data-stu-id="ddce3-289">-100000</span></span>|

## <a name="tcs-to-be-calculated-on-sales-return-sales-return-order-or-sales-credit-memo"></a><span data-ttu-id="ddce3-290">TCS to be calculated on sales return (sales return order or sales credit memo)</span><span class="sxs-lookup"><span data-stu-id="ddce3-290">TCS to be calculated on sales return (sales return order or sales credit memo)</span></span>

<span data-ttu-id="ddce3-291">For example, sales return from customer for INR 10,000 on which 1% TCS is applicable for Nature of collection “Scrap”.</span><span class="sxs-lookup"><span data-stu-id="ddce3-291">For example, sales return from customer for INR 10,000 on which 1% TCS is applicable for Nature of collection “Scrap”.</span></span>

  - <span data-ttu-id="ddce3-292">In this case TCS calculation will be as following:</span><span class="sxs-lookup"><span data-stu-id="ddce3-292">In this case TCS calculation will be as following:</span></span>

    |<span data-ttu-id="ddce3-293">Component</span><span class="sxs-lookup"><span data-stu-id="ddce3-293">Component</span></span>|<span data-ttu-id="ddce3-294">Value</span><span class="sxs-lookup"><span data-stu-id="ddce3-294">Value</span></span>|
    |----------------------------------|---------------------------------------|  
    |<span data-ttu-id="ddce3-295">**TCS Base Amount**</span><span class="sxs-lookup"><span data-stu-id="ddce3-295">**TCS Base Amount**</span></span>|<span data-ttu-id="ddce3-296">10000</span><span class="sxs-lookup"><span data-stu-id="ddce3-296">10000</span></span>|  
    |<span data-ttu-id="ddce3-297">**TCS Amount**</span><span class="sxs-lookup"><span data-stu-id="ddce3-297">**TCS Amount**</span></span>|<span data-ttu-id="ddce3-298">100(10000x1%)</span><span class="sxs-lookup"><span data-stu-id="ddce3-298">100(10000x1%)</span></span>|
    
  - <span data-ttu-id="ddce3-299">GL Entries will be as following:</span><span class="sxs-lookup"><span data-stu-id="ddce3-299">GL Entries will be as following:</span></span>
     
    |<span data-ttu-id="ddce3-300">Particulars</span><span class="sxs-lookup"><span data-stu-id="ddce3-300">Particulars</span></span>|<span data-ttu-id="ddce3-301">Amount</span><span class="sxs-lookup"><span data-stu-id="ddce3-301">Amount</span></span>|
    |----------------------------------|---------------------------------------|  
    |<span data-ttu-id="ddce3-302">**Sales Account**</span><span class="sxs-lookup"><span data-stu-id="ddce3-302">**Sales Account**</span></span>|<span data-ttu-id="ddce3-303">10000</span><span class="sxs-lookup"><span data-stu-id="ddce3-303">10000</span></span>|
    |<span data-ttu-id="ddce3-304">**TCS Payable Account**</span><span class="sxs-lookup"><span data-stu-id="ddce3-304">**TCS Payable Account**</span></span>|<span data-ttu-id="ddce3-305">100</span><span class="sxs-lookup"><span data-stu-id="ddce3-305">100</span></span>|
    |<span data-ttu-id="ddce3-306">**Customer Account**</span><span class="sxs-lookup"><span data-stu-id="ddce3-306">**Customer Account**</span></span>|<span data-ttu-id="ddce3-307">-10100</span><span class="sxs-lookup"><span data-stu-id="ddce3-307">-10100</span></span>|

> [!NOTE]
> <span data-ttu-id="ddce3-308">If Credit Memo is created before remittance of Tax to government, then TCS entries will get reversed proportionately, on the basis of the quantity returned.</span><span class="sxs-lookup"><span data-stu-id="ddce3-308">If Credit Memo is created before remittance of Tax to government, then TCS entries will get reversed proportionately, on the basis of the quantity returned.</span></span> <span data-ttu-id="ddce3-309">In case TCS amount has been remitted to Income Tax department, TCS Payable account will not be reversed.</span><span class="sxs-lookup"><span data-stu-id="ddce3-309">In case TCS amount has been remitted to Income Tax department, TCS Payable account will not be reversed.</span></span>
