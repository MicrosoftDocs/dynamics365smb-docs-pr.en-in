---
title: Transaction on Voucher Interface
description: Transaction on Voucher Interface
author: v-debapd
ms.service: dynamics365-business-central
ms.topic: article
ms.devlang: na
ms.tgt_pltfrm: na
ms.workload: na
ms.search.keywords: India, local, IN, English
ms.date: 10/01/2020
ms.author: v-debapd
ms.openlocfilehash: d86591a63dd81ba2c678c072f9b1b3d8e1af00f4
ms.sourcegitcommit: ddbb5cede750df1baba4b3eab8fbed6744b5b9d6
ms.translationtype: HT
ms.contentlocale: en-IN
ms.lasthandoff: 10/01/2020
ms.locfileid: "3948595"
---
# <a name="voucher-transaction"></a><span data-ttu-id="fc5a5-103">Voucher Transaction</span><span class="sxs-lookup"><span data-stu-id="fc5a5-103">Voucher Transaction</span></span>

[!INCLUDE[vnext_preview](../../includes/vnext_preview.md)]

<span data-ttu-id="fc5a5-104">This topic explains the process of recording day-to-day transactions through voucher interface.</span><span class="sxs-lookup"><span data-stu-id="fc5a5-104">This topic explains the process of recording day-to-day transactions through voucher interface.</span></span>

## <a name="type-of-vouchers-and-transactions"></a><span data-ttu-id="fc5a5-105">Type of vouchers and transactions</span><span class="sxs-lookup"><span data-stu-id="fc5a5-105">Type of vouchers and transactions</span></span>

<span data-ttu-id="fc5a5-106">Following are the vouchers needed to record the transactions like Cash, Bank, and Journals for this functionality:</span><span class="sxs-lookup"><span data-stu-id="fc5a5-106">Following are the vouchers needed to record the transactions like Cash, Bank, and Journals for this functionality:</span></span>
- <span data-ttu-id="fc5a5-107">Cash Receipt Voucher: Entries which affect the Cash accounts while receiving cash payments from customers or refund from vendor.</span><span class="sxs-lookup"><span data-stu-id="fc5a5-107">Cash Receipt Voucher: Entries which affect the Cash accounts while receiving cash payments from customers or refund from vendor.</span></span> 
- <span data-ttu-id="fc5a5-108">Cash Payment Voucher: Entries which affect the Cash accounts while making cash payments to vendors or refund to customer</span><span class="sxs-lookup"><span data-stu-id="fc5a5-108">Cash Payment Voucher: Entries which affect the Cash accounts while making cash payments to vendors or refund to customer</span></span> 
- <span data-ttu-id="fc5a5-109">Bank Receipt Voucher: Entries which affect the Bank accounts while receiving payments from customers or refund from vendor.</span><span class="sxs-lookup"><span data-stu-id="fc5a5-109">Bank Receipt Voucher: Entries which affect the Bank accounts while receiving payments from customers or refund from vendor.</span></span> 
- <span data-ttu-id="fc5a5-110">Bank Payment Voucher: Entries which affect the Bank accounts while making payments to vendors or refund to customer.</span><span class="sxs-lookup"><span data-stu-id="fc5a5-110">Bank Payment Voucher: Entries which affect the Bank accounts while making payments to vendors or refund to customer.</span></span> 
- <span data-ttu-id="fc5a5-111">Contra Voucher: Entries which affect the Cash and Bank Account together are termed as Contra Vouchers.</span><span class="sxs-lookup"><span data-stu-id="fc5a5-111">Contra Voucher: Entries which affect the Cash and Bank Account together are termed as Contra Vouchers.</span></span> <span data-ttu-id="fc5a5-112">For example, withdrawal from bank is one such transaction.</span><span class="sxs-lookup"><span data-stu-id="fc5a5-112">For example, withdrawal from bank is one such transaction.</span></span> 
- <span data-ttu-id="fc5a5-113">Journal Voucher: Entries which are affecting neither the Cash Account nor the Bank account are termed as Journal Vouchers.</span><span class="sxs-lookup"><span data-stu-id="fc5a5-113">Journal Voucher: Entries which are affecting neither the Cash Account nor the Bank account are termed as Journal Vouchers.</span></span> 


## <a name="mandatory-fields-for-voucher-entries-through-voucher-interface"></a><span data-ttu-id="fc5a5-114">Mandatory fields for voucher entries through voucher interface</span><span class="sxs-lookup"><span data-stu-id="fc5a5-114">Mandatory fields for voucher entries through voucher interface</span></span>

1. <span data-ttu-id="fc5a5-115">Choose the ![Search for Page or Report](image/search_small.png "Search for Page or Report icon") icon, enter **Cash Receipt Voucher** , **Cash Payment Voucher** , **Bank Receipt Voucher** , **Bank Payment Voucher** , **Contra Voucher** or **Journal Voucher** , and then choose the related link.</span><span class="sxs-lookup"><span data-stu-id="fc5a5-115">Choose the ![Search for Page or Report](image/search_small.png "Search for Page or Report icon") icon, enter **Cash Receipt Voucher** , **Cash Payment Voucher** , **Bank Receipt Voucher** , **Bank Payment Voucher** , **Contra Voucher** or **Journal Voucher** , and then choose the related link.</span></span> 
2. <span data-ttu-id="fc5a5-116">Following are the mandatory fields for any type of voucher entry:</span><span class="sxs-lookup"><span data-stu-id="fc5a5-116">Following are the mandatory fields for any type of voucher entry:</span></span>

    |<span data-ttu-id="fc5a5-117">Field</span><span class="sxs-lookup"><span data-stu-id="fc5a5-117">Field</span></span>|<span data-ttu-id="fc5a5-118">Description</span><span class="sxs-lookup"><span data-stu-id="fc5a5-118">Description</span></span>|
    |----------------------------------|---------------------------------------|  
    |<span data-ttu-id="fc5a5-119">**Posting Date**</span><span class="sxs-lookup"><span data-stu-id="fc5a5-119">**Posting Date**</span></span>|<span data-ttu-id="fc5a5-120">Specify the posting date.</span><span class="sxs-lookup"><span data-stu-id="fc5a5-120">Specify the posting date.</span></span>|  
    |<span data-ttu-id="fc5a5-121">**Document Type**</span><span class="sxs-lookup"><span data-stu-id="fc5a5-121">**Document Type**</span></span>|<span data-ttu-id="fc5a5-122">Specify document type as per transaction requirement i.e. Payment, Refund etc.</span><span class="sxs-lookup"><span data-stu-id="fc5a5-122">Specify document type as per transaction requirement i.e. Payment, Refund etc.</span></span>|
    |<span data-ttu-id="fc5a5-123">**Document Number**</span><span class="sxs-lookup"><span data-stu-id="fc5a5-123">**Document Number**</span></span>|<span data-ttu-id="fc5a5-124">Specifies the document number, this can be manually entered or auto populated from general journal template or batch.</span><span class="sxs-lookup"><span data-stu-id="fc5a5-124">Specifies the document number, this can be manually entered or auto populated from general journal template or batch.</span></span>|
    |<span data-ttu-id="fc5a5-125">**Account Type**</span><span class="sxs-lookup"><span data-stu-id="fc5a5-125">**Account Type**</span></span>|<span data-ttu-id="fc5a5-126">Select relevant account type, i.e. Customer, Vendor, G/L Account, Bank etc.</span><span class="sxs-lookup"><span data-stu-id="fc5a5-126">Select relevant account type, i.e. Customer, Vendor, G/L Account, Bank etc.</span></span>|
    |<span data-ttu-id="fc5a5-127">**Account No.**</span><span class="sxs-lookup"><span data-stu-id="fc5a5-127">**Account No.**</span></span>|<span data-ttu-id="fc5a5-128">Select the relevant account number</span><span class="sxs-lookup"><span data-stu-id="fc5a5-128">Select the relevant account number</span></span>|
    |<span data-ttu-id="fc5a5-129">**Debit Amount**</span><span class="sxs-lookup"><span data-stu-id="fc5a5-129">**Debit Amount**</span></span>|<span data-ttu-id="fc5a5-130">Specify the debit amount</span><span class="sxs-lookup"><span data-stu-id="fc5a5-130">Specify the debit amount</span></span>|
    |<span data-ttu-id="fc5a5-131">**Credit Amount**</span><span class="sxs-lookup"><span data-stu-id="fc5a5-131">**Credit Amount**</span></span>|<span data-ttu-id="fc5a5-132">Specify the credit amount</span><span class="sxs-lookup"><span data-stu-id="fc5a5-132">Specify the credit amount</span></span>|
    |<span data-ttu-id="fc5a5-133">**Balance Account Type**</span><span class="sxs-lookup"><span data-stu-id="fc5a5-133">**Balance Account Type**</span></span>|<span data-ttu-id="fc5a5-134">Select relevant account type, i.e. Customer, Vendor, G/L Account, Bank etc.</span><span class="sxs-lookup"><span data-stu-id="fc5a5-134">Select relevant account type, i.e. Customer, Vendor, G/L Account, Bank etc.</span></span>|
    |<span data-ttu-id="fc5a5-135">**Balance Account No.**</span><span class="sxs-lookup"><span data-stu-id="fc5a5-135">**Balance Account No.**</span></span>|<span data-ttu-id="fc5a5-136">Select the relevant account number</span><span class="sxs-lookup"><span data-stu-id="fc5a5-136">Select the relevant account number</span></span>|
    |<span data-ttu-id="fc5a5-137">**Cheque No.**</span><span class="sxs-lookup"><span data-stu-id="fc5a5-137">**Cheque No.**</span></span>|<span data-ttu-id="fc5a5-138">Specify the cheque number, only applicable for bank payment and receipt voucher.</span><span class="sxs-lookup"><span data-stu-id="fc5a5-138">Specify the cheque number, only applicable for bank payment and receipt voucher.</span></span>|
    |<span data-ttu-id="fc5a5-139">**Cheque Date**</span><span class="sxs-lookup"><span data-stu-id="fc5a5-139">**Cheque Date**</span></span>|<span data-ttu-id="fc5a5-140">Specify the cheque date, only applicable for bank payment and receipt voucher.</span><span class="sxs-lookup"><span data-stu-id="fc5a5-140">Specify the cheque date, only applicable for bank payment and receipt voucher.</span></span>|
    |<span data-ttu-id="fc5a5-141">**Line Narration**</span><span class="sxs-lookup"><span data-stu-id="fc5a5-141">**Line Narration**</span></span>|<span data-ttu-id="fc5a5-142">Specify the line narration of the journal lines, can be provided for each line.</span><span class="sxs-lookup"><span data-stu-id="fc5a5-142">Specify the line narration of the journal lines, can be provided for each line.</span></span>|
    |<span data-ttu-id="fc5a5-143">**Voucher Narration**</span><span class="sxs-lookup"><span data-stu-id="fc5a5-143">**Voucher Narration**</span></span>|<span data-ttu-id="fc5a5-144">Specify the voucher narration, this will be a single narration for the whole document.</span><span class="sxs-lookup"><span data-stu-id="fc5a5-144">Specify the voucher narration, this will be a single narration for the whole document.</span></span>|
   

### <a name="posted-general-ledger-entries-for-each-voucher"></a><span data-ttu-id="fc5a5-145">Posted general ledger entries for each voucher</span><span class="sxs-lookup"><span data-stu-id="fc5a5-145">Posted general ledger entries for each voucher</span></span>

- <span data-ttu-id="fc5a5-146">Payment received in cash from customer for INR 10,000 through Cash Receipt Voucher.</span><span class="sxs-lookup"><span data-stu-id="fc5a5-146">Payment received in cash from customer for INR 10,000 through Cash Receipt Voucher.</span></span> 

  <span data-ttu-id="fc5a5-147">GL Entries will be as following:</span><span class="sxs-lookup"><span data-stu-id="fc5a5-147">GL Entries will be as following:</span></span>
     
    |<span data-ttu-id="fc5a5-148">Particulars</span><span class="sxs-lookup"><span data-stu-id="fc5a5-148">Particulars</span></span>|<span data-ttu-id="fc5a5-149">Amount</span><span class="sxs-lookup"><span data-stu-id="fc5a5-149">Amount</span></span>|
    |----------------------------------|---------------------------------------|  
    |<span data-ttu-id="fc5a5-150">**Cash Account**</span><span class="sxs-lookup"><span data-stu-id="fc5a5-150">**Cash Account**</span></span>|<span data-ttu-id="fc5a5-151">10000</span><span class="sxs-lookup"><span data-stu-id="fc5a5-151">10000</span></span>|
    |<span data-ttu-id="fc5a5-152">**Customer Account**</span><span class="sxs-lookup"><span data-stu-id="fc5a5-152">**Customer Account**</span></span>|<span data-ttu-id="fc5a5-153">-10000</span><span class="sxs-lookup"><span data-stu-id="fc5a5-153">-10000</span></span>|

> [!TIP]
> <span data-ttu-id="fc5a5-154">Cash will always be debited in Cash receipt voucher.</span><span class="sxs-lookup"><span data-stu-id="fc5a5-154">Cash will always be debited in Cash receipt voucher.</span></span>

- <span data-ttu-id="fc5a5-155">Payment made in cash to vendor for INR 10,000 through Cash Payment Voucher.</span><span class="sxs-lookup"><span data-stu-id="fc5a5-155">Payment made in cash to vendor for INR 10,000 through Cash Payment Voucher.</span></span> 

  <span data-ttu-id="fc5a5-156">GL Entries will be as following:</span><span class="sxs-lookup"><span data-stu-id="fc5a5-156">GL Entries will be as following:</span></span>
     
    |<span data-ttu-id="fc5a5-157">Particulars</span><span class="sxs-lookup"><span data-stu-id="fc5a5-157">Particulars</span></span>|<span data-ttu-id="fc5a5-158">Amount</span><span class="sxs-lookup"><span data-stu-id="fc5a5-158">Amount</span></span>|
    |----------------------------------|---------------------------------------|  
    |<span data-ttu-id="fc5a5-159">**Cash Account**</span><span class="sxs-lookup"><span data-stu-id="fc5a5-159">**Cash Account**</span></span>|<span data-ttu-id="fc5a5-160">-10000</span><span class="sxs-lookup"><span data-stu-id="fc5a5-160">-10000</span></span>|
    |<span data-ttu-id="fc5a5-161">**Vendor Account**</span><span class="sxs-lookup"><span data-stu-id="fc5a5-161">**Vendor Account**</span></span>|<span data-ttu-id="fc5a5-162">10000</span><span class="sxs-lookup"><span data-stu-id="fc5a5-162">10000</span></span>|

> [!TIP]
> <span data-ttu-id="fc5a5-163">Cash will always be credited in Cash payment voucher.</span><span class="sxs-lookup"><span data-stu-id="fc5a5-163">Cash will always be credited in Cash payment voucher.</span></span>

- <span data-ttu-id="fc5a5-164">Payment received by cheque from customer for INR 10,000 through Bank Receipt Voucher.</span><span class="sxs-lookup"><span data-stu-id="fc5a5-164">Payment received by cheque from customer for INR 10,000 through Bank Receipt Voucher.</span></span> 

  <span data-ttu-id="fc5a5-165">GL Entries will be as following:</span><span class="sxs-lookup"><span data-stu-id="fc5a5-165">GL Entries will be as following:</span></span>
     
    |<span data-ttu-id="fc5a5-166">Particulars</span><span class="sxs-lookup"><span data-stu-id="fc5a5-166">Particulars</span></span>|<span data-ttu-id="fc5a5-167">Amount</span><span class="sxs-lookup"><span data-stu-id="fc5a5-167">Amount</span></span>|
    |----------------------------------|---------------------------------------|  
    |<span data-ttu-id="fc5a5-168">**Bank Account**</span><span class="sxs-lookup"><span data-stu-id="fc5a5-168">**Bank Account**</span></span>|<span data-ttu-id="fc5a5-169">10000</span><span class="sxs-lookup"><span data-stu-id="fc5a5-169">10000</span></span>|
    |<span data-ttu-id="fc5a5-170">**Customer Account**</span><span class="sxs-lookup"><span data-stu-id="fc5a5-170">**Customer Account**</span></span>|<span data-ttu-id="fc5a5-171">-10000</span><span class="sxs-lookup"><span data-stu-id="fc5a5-171">-10000</span></span>|

> [!TIP]
> <span data-ttu-id="fc5a5-172">Bank will always be debited in Bank receipt voucher.</span><span class="sxs-lookup"><span data-stu-id="fc5a5-172">Bank will always be debited in Bank receipt voucher.</span></span>

- <span data-ttu-id="fc5a5-173">Payment made by cheque to vendor for INR 10,000 through Bank Payment Voucher.</span><span class="sxs-lookup"><span data-stu-id="fc5a5-173">Payment made by cheque to vendor for INR 10,000 through Bank Payment Voucher.</span></span> 

  <span data-ttu-id="fc5a5-174">GL Entries will be as following:</span><span class="sxs-lookup"><span data-stu-id="fc5a5-174">GL Entries will be as following:</span></span>
     
    |<span data-ttu-id="fc5a5-175">Particulars</span><span class="sxs-lookup"><span data-stu-id="fc5a5-175">Particulars</span></span>|<span data-ttu-id="fc5a5-176">Amount</span><span class="sxs-lookup"><span data-stu-id="fc5a5-176">Amount</span></span>|
    |----------------------------------|---------------------------------------|  
    |<span data-ttu-id="fc5a5-177">**Bank Account**</span><span class="sxs-lookup"><span data-stu-id="fc5a5-177">**Bank Account**</span></span>|<span data-ttu-id="fc5a5-178">-10000</span><span class="sxs-lookup"><span data-stu-id="fc5a5-178">-10000</span></span>|
    |<span data-ttu-id="fc5a5-179">**Vendor Account**</span><span class="sxs-lookup"><span data-stu-id="fc5a5-179">**Vendor Account**</span></span>|<span data-ttu-id="fc5a5-180">10000</span><span class="sxs-lookup"><span data-stu-id="fc5a5-180">10000</span></span>|

> [!TIP]
> <span data-ttu-id="fc5a5-181">Bank will always be credited in Bank payment voucher.</span><span class="sxs-lookup"><span data-stu-id="fc5a5-181">Bank will always be credited in Bank payment voucher.</span></span>

- <span data-ttu-id="fc5a5-182">Payment made by cheque to vendor for INR 12,000 and INR 200 as Bank Charges through Bank Payment Voucher.</span><span class="sxs-lookup"><span data-stu-id="fc5a5-182">Payment made by cheque to vendor for INR 12,000 and INR 200 as Bank Charges through Bank Payment Voucher.</span></span> 

  <span data-ttu-id="fc5a5-183">GL Entries will be as following:</span><span class="sxs-lookup"><span data-stu-id="fc5a5-183">GL Entries will be as following:</span></span>
     
    |<span data-ttu-id="fc5a5-184">Particulars</span><span class="sxs-lookup"><span data-stu-id="fc5a5-184">Particulars</span></span>|<span data-ttu-id="fc5a5-185">Amount</span><span class="sxs-lookup"><span data-stu-id="fc5a5-185">Amount</span></span>|
    |----------------------------------|---------------------------------------|  
    |<span data-ttu-id="fc5a5-186">**Bank Account**</span><span class="sxs-lookup"><span data-stu-id="fc5a5-186">**Bank Account**</span></span>|<span data-ttu-id="fc5a5-187">-12200</span><span class="sxs-lookup"><span data-stu-id="fc5a5-187">-12200</span></span>|
    |<span data-ttu-id="fc5a5-188">**Vendor Account**</span><span class="sxs-lookup"><span data-stu-id="fc5a5-188">**Vendor Account**</span></span>|<span data-ttu-id="fc5a5-189">12000</span><span class="sxs-lookup"><span data-stu-id="fc5a5-189">12000</span></span>|
    |<span data-ttu-id="fc5a5-190">**Bank Charges Account**</span><span class="sxs-lookup"><span data-stu-id="fc5a5-190">**Bank Charges Account**</span></span>|<span data-ttu-id="fc5a5-191">200</span><span class="sxs-lookup"><span data-stu-id="fc5a5-191">200</span></span>|

> [!TIP]
> <span data-ttu-id="fc5a5-192">Bank will always be credited in Bank payment voucher.</span><span class="sxs-lookup"><span data-stu-id="fc5a5-192">Bank will always be credited in Bank payment voucher.</span></span>

- <span data-ttu-id="fc5a5-193">Cash Withdrawn/deposited or Transfer between bank accounts through Contra Voucher, for example Cash Withdrawn from Bank for INR 10,000.</span><span class="sxs-lookup"><span data-stu-id="fc5a5-193">Cash Withdrawn/deposited or Transfer between bank accounts through Contra Voucher, for example Cash Withdrawn from Bank for INR 10,000.</span></span> 

  <span data-ttu-id="fc5a5-194">GL Entries will be as following:</span><span class="sxs-lookup"><span data-stu-id="fc5a5-194">GL Entries will be as following:</span></span>
     
    |<span data-ttu-id="fc5a5-195">Particulars</span><span class="sxs-lookup"><span data-stu-id="fc5a5-195">Particulars</span></span>|<span data-ttu-id="fc5a5-196">Amount</span><span class="sxs-lookup"><span data-stu-id="fc5a5-196">Amount</span></span>|
    |----------------------------------|---------------------------------------|  
    |<span data-ttu-id="fc5a5-197">**Bank Account**</span><span class="sxs-lookup"><span data-stu-id="fc5a5-197">**Bank Account**</span></span>|<span data-ttu-id="fc5a5-198">-10000</span><span class="sxs-lookup"><span data-stu-id="fc5a5-198">-10000</span></span>|
    |<span data-ttu-id="fc5a5-199">**Cash Account**</span><span class="sxs-lookup"><span data-stu-id="fc5a5-199">**Cash Account**</span></span>|<span data-ttu-id="fc5a5-200">10000</span><span class="sxs-lookup"><span data-stu-id="fc5a5-200">10000</span></span>|

> [!TIP]
> <span data-ttu-id="fc5a5-201">Only Bank or Cash accounts can be allowed in Contra Voucher.</span><span class="sxs-lookup"><span data-stu-id="fc5a5-201">Only Bank or Cash accounts can be allowed in Contra Voucher.</span></span>

- <span data-ttu-id="fc5a5-202">Expense booked for INR 10,000 and crediting Vendor through Journal Voucher.</span><span class="sxs-lookup"><span data-stu-id="fc5a5-202">Expense booked for INR 10,000 and crediting Vendor through Journal Voucher.</span></span>

  <span data-ttu-id="fc5a5-203">GL Entries will be as following:</span><span class="sxs-lookup"><span data-stu-id="fc5a5-203">GL Entries will be as following:</span></span>
     
    |<span data-ttu-id="fc5a5-204">Particulars</span><span class="sxs-lookup"><span data-stu-id="fc5a5-204">Particulars</span></span>|<span data-ttu-id="fc5a5-205">Amount</span><span class="sxs-lookup"><span data-stu-id="fc5a5-205">Amount</span></span>|
    |----------------------------------|---------------------------------------|  
    |<span data-ttu-id="fc5a5-206">**Expenses Account**</span><span class="sxs-lookup"><span data-stu-id="fc5a5-206">**Expenses Account**</span></span>|<span data-ttu-id="fc5a5-207">10000</span><span class="sxs-lookup"><span data-stu-id="fc5a5-207">10000</span></span>|
    |<span data-ttu-id="fc5a5-208">**Vendor Account**</span><span class="sxs-lookup"><span data-stu-id="fc5a5-208">**Vendor Account**</span></span>|<span data-ttu-id="fc5a5-209">-10000</span><span class="sxs-lookup"><span data-stu-id="fc5a5-209">-10000</span></span>|

> [!TIP]
> <span data-ttu-id="fc5a5-210">Bank and Cash accounts are not allowed in Journal Voucher.</span><span class="sxs-lookup"><span data-stu-id="fc5a5-210">Bank and Cash accounts are not allowed in Journal Voucher.</span></span>

## <a name="opening-balances-for-gst"></a><span data-ttu-id="fc5a5-211">Opening balances for GST</span><span class="sxs-lookup"><span data-stu-id="fc5a5-211">Opening balances for GST</span></span>

<span data-ttu-id="fc5a5-212">GST opening balances shall be created in Business Central.</span><span class="sxs-lookup"><span data-stu-id="fc5a5-212">GST opening balances shall be created in Business Central.</span></span> <span data-ttu-id="fc5a5-213">In Journal Voucher, options available to provide the opening balances for –</span><span class="sxs-lookup"><span data-stu-id="fc5a5-213">In Journal Voucher, options available to provide the opening balances for –</span></span> 
    
-   <span data-ttu-id="fc5a5-214">GST Credit</span><span class="sxs-lookup"><span data-stu-id="fc5a5-214">GST Credit</span></span>
-   <span data-ttu-id="fc5a5-215">GST Liability</span><span class="sxs-lookup"><span data-stu-id="fc5a5-215">GST Liability</span></span>
-   <span data-ttu-id="fc5a5-216">GST TDS Credit</span><span class="sxs-lookup"><span data-stu-id="fc5a5-216">GST TDS Credit</span></span>
-   <span data-ttu-id="fc5a5-217">GST TCS Credit</span><span class="sxs-lookup"><span data-stu-id="fc5a5-217">GST TCS Credit</span></span>

> [!NOTE]
> <span data-ttu-id="fc5a5-218">Only positive amounts are allowed for GST Credit opening balances.</span><span class="sxs-lookup"><span data-stu-id="fc5a5-218">Only positive amounts are allowed for GST Credit opening balances.</span></span>
>
> <span data-ttu-id="fc5a5-219">Only negative amounts are allowed for GST Liability opening balances.</span><span class="sxs-lookup"><span data-stu-id="fc5a5-219">Only negative amounts are allowed for GST Liability opening balances.</span></span>
>
> <span data-ttu-id="fc5a5-220">System should record the values in GST Sub-Ledger.</span><span class="sxs-lookup"><span data-stu-id="fc5a5-220">System should record the values in GST Sub-Ledger.</span></span>


## <a name="tds-and-tcs-payment-to-government"></a><span data-ttu-id="fc5a5-221">TDS and TCS payment to government</span><span class="sxs-lookup"><span data-stu-id="fc5a5-221">TDS and TCS payment to government</span></span>

<span data-ttu-id="fc5a5-222">It is required to pay the TDS and TCS to government authorities through Bank/Cash Payment Vouchers.</span><span class="sxs-lookup"><span data-stu-id="fc5a5-222">It is required to pay the TDS and TCS to government authorities through Bank/Cash Payment Vouchers.</span></span> <span data-ttu-id="fc5a5-223">Provision is available to select the TDS and TCS sub-ledger entries by applying filters like Companies/Non-Companies, etc. and on the basis of TAN and TCAN Numbers.</span><span class="sxs-lookup"><span data-stu-id="fc5a5-223">Provision is available to select the TDS and TCS sub-ledger entries by applying filters like Companies/Non-Companies, etc. and on the basis of TAN and TCAN Numbers.</span></span> 

> [!NOTE]
> <span data-ttu-id="fc5a5-224">Details are available in respective TDS and TCS documents.</span><span class="sxs-lookup"><span data-stu-id="fc5a5-224">Details are available in respective TDS and TCS documents.</span></span>