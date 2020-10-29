---
title: GST on Bank Charges Transaction
description: GST on Bank Charges Transaction
author: v-debapd
ms.service: dynamics365-business-central
ms.topic: article
ms.devlang: na
ms.tgt_pltfrm: na
ms.workload: na
ms.search.keywords: India, local, IN, English
ms.date: 10/01/2020
ms.author: v-debapd
ms.openlocfilehash: b817e6521e50322dc9985c728d7fde78a3c62591
ms.sourcegitcommit: ddbb5cede750df1baba4b3eab8fbed6744b5b9d6
ms.translationtype: HT
ms.contentlocale: en-IN
ms.lasthandoff: 10/01/2020
ms.locfileid: "3948655"
---
# <a name="gst-on-bank-charges-transaction"></a><span data-ttu-id="63099-103">GST on Bank Charges Transaction</span><span class="sxs-lookup"><span data-stu-id="63099-103">GST on Bank Charges Transaction</span></span>

[!INCLUDE[vnext_preview](../../includes/vnext_preview.md)]

<span data-ttu-id="63099-104">As per Rule 54(2) of CGST Rules, 2017, Banks shall issue a tax invoice or any other document in lieu of tax invoice.</span><span class="sxs-lookup"><span data-stu-id="63099-104">As per Rule 54(2) of CGST Rules, 2017, Banks shall issue a tax invoice or any other document in lieu of tax invoice.</span></span> <span data-ttu-id="63099-105">In case if an invoice is not provided by the bank, then the bank statement shall be deemed to be an invoice.</span><span class="sxs-lookup"><span data-stu-id="63099-105">In case if an invoice is not provided by the bank, then the bank statement shall be deemed to be an invoice.</span></span> <span data-ttu-id="63099-106">Such document shall be construed as Tax invoice even if it is not serially numbered and whether or not it contains the address of recipient of taxable service.</span><span class="sxs-lookup"><span data-stu-id="63099-106">Such document shall be construed as Tax invoice even if it is not serially numbered and whether or not it contains the address of recipient of taxable service.</span></span>

<span data-ttu-id="63099-107">Process for GST calculation on bank charges has been explained in this document.</span><span class="sxs-lookup"><span data-stu-id="63099-107">Process for GST calculation on bank charges has been explained in this document.</span></span>

### <a name="gst-calculation-on-bank-charges"></a><span data-ttu-id="63099-108">GST calculation on bank charges</span><span class="sxs-lookup"><span data-stu-id="63099-108">GST calculation on bank charges</span></span>

1. <span data-ttu-id="63099-109">Choose the ![Search for Page or Report](image/search_small.png "Search for Page or Report icon") icon, enter **Bank Payment Voucher** , and then choose the related link.</span><span class="sxs-lookup"><span data-stu-id="63099-109">Choose the ![Search for Page or Report](image/search_small.png "Search for Page or Report icon") icon, enter **Bank Payment Voucher** , and then choose the related link.</span></span>
2. <span data-ttu-id="63099-110">Select **G/L Account** in **Account Type** field and select relevant general ledger account in **Account No.** field.</span><span class="sxs-lookup"><span data-stu-id="63099-110">Select **G/L Account** in **Account Type** field and select relevant general ledger account in **Account No.** field.</span></span>
3. <span data-ttu-id="63099-111">Select **Bank Account** in **Bal. Account Type** field and select relevant bank account in **Bal. Account No.** field.</span><span class="sxs-lookup"><span data-stu-id="63099-111">Select **Bank Account** in **Bal. Account Type** field and select relevant bank account in **Bal. Account No.** field.</span></span>
4. <span data-ttu-id="63099-112">**GST Registration No.** and **GST Registration Status** fields should not be blank on **Bank Account** .</span><span class="sxs-lookup"><span data-stu-id="63099-112">**GST Registration No.** and **GST Registration Status** fields should not be blank on **Bank Account** .</span></span>
5. <span data-ttu-id="63099-113">**Location Code** should not be blank on **Bank Payment Voucher** .</span><span class="sxs-lookup"><span data-stu-id="63099-113">**Location Code** should not be blank on **Bank Payment Voucher** .</span></span>
6. <span data-ttu-id="63099-114">**Bank Charge** field should be marked true, select **Process** on the ribbon and click on **Bank Charges** -> select **Bank Charge** code and system will calculate the GST on bank charge amount.</span><span class="sxs-lookup"><span data-stu-id="63099-114">**Bank Charge** field should be marked true, select **Process** on the ribbon and click on **Bank Charges** -> select **Bank Charge** code and system will calculate the GST on bank charge amount.</span></span> <span data-ttu-id="63099-115">**GST Credit** , **GST Group Code** and **HSN/SAC Code** should not be blank on **Bank Charge** Code.</span><span class="sxs-lookup"><span data-stu-id="63099-115">**GST Credit** , **GST Group Code** and **HSN/SAC Code** should not be blank on **Bank Charge** Code.</span></span>

### <a name="gst-on-bank-charges"></a><span data-ttu-id="63099-116">GST on bank charges</span><span class="sxs-lookup"><span data-stu-id="63099-116">GST on bank charges</span></span>

<span data-ttu-id="63099-117">Intra-State Bank Payment with GST on Bank Charges where Input Tax Credit is available, for example bank charge of INR 10000 to be paid to bank and GST (9% CGST and 9% SGST) has to be calculated on bank charges amount.</span><span class="sxs-lookup"><span data-stu-id="63099-117">Intra-State Bank Payment with GST on Bank Charges where Input Tax Credit is available, for example bank charge of INR 10000 to be paid to bank and GST (9% CGST and 9% SGST) has to be calculated on bank charges amount.</span></span>
    
  - <span data-ttu-id="63099-118">GST calculation will appear in the Fact Box, as following:</span><span class="sxs-lookup"><span data-stu-id="63099-118">GST calculation will appear in the Fact Box, as following:</span></span>

       |<span data-ttu-id="63099-119">Component</span><span class="sxs-lookup"><span data-stu-id="63099-119">Component</span></span>|<span data-ttu-id="63099-120">Amount</span><span class="sxs-lookup"><span data-stu-id="63099-120">Amount</span></span>|
       |----------------------------------|---------------------------------------|  
       |<span data-ttu-id="63099-121">**Bank Charge Amount**</span><span class="sxs-lookup"><span data-stu-id="63099-121">**Bank Charge Amount**</span></span>|<span data-ttu-id="63099-122">10,000</span><span class="sxs-lookup"><span data-stu-id="63099-122">10,000</span></span>|  
       |<span data-ttu-id="63099-123">**CGST**</span><span class="sxs-lookup"><span data-stu-id="63099-123">**CGST**</span></span>|<span data-ttu-id="63099-124">900</span><span class="sxs-lookup"><span data-stu-id="63099-124">900</span></span>|  
       |<span data-ttu-id="63099-125">**SGST**</span><span class="sxs-lookup"><span data-stu-id="63099-125">**SGST**</span></span>|<span data-ttu-id="63099-126">900</span><span class="sxs-lookup"><span data-stu-id="63099-126">900</span></span>|
    

  - <span data-ttu-id="63099-127">Once posted the bank payment GL entries for Intra-state bank charges with GST where Input Tax Credit is available, will be as following:</span><span class="sxs-lookup"><span data-stu-id="63099-127">Once posted the bank payment GL entries for Intra-state bank charges with GST where Input Tax Credit is available, will be as following:</span></span>
    
     |<span data-ttu-id="63099-128">Particulars</span><span class="sxs-lookup"><span data-stu-id="63099-128">Particulars</span></span>|<span data-ttu-id="63099-129">Amount</span><span class="sxs-lookup"><span data-stu-id="63099-129">Amount</span></span>|
     |----------------------------------|---------------------------------------|  
     |<span data-ttu-id="63099-130">**Bank Charges**</span><span class="sxs-lookup"><span data-stu-id="63099-130">**Bank Charges**</span></span>|<span data-ttu-id="63099-131">10000</span><span class="sxs-lookup"><span data-stu-id="63099-131">10000</span></span>|  
     |<span data-ttu-id="63099-132">**CGST Receivable Account**</span><span class="sxs-lookup"><span data-stu-id="63099-132">**CGST Receivable Account**</span></span>|<span data-ttu-id="63099-133">900</span><span class="sxs-lookup"><span data-stu-id="63099-133">900</span></span>|
     |<span data-ttu-id="63099-134">**SGST/UTGST Receivable Account**</span><span class="sxs-lookup"><span data-stu-id="63099-134">**SGST/UTGST Receivable Account**</span></span>|<span data-ttu-id="63099-135">900</span><span class="sxs-lookup"><span data-stu-id="63099-135">900</span></span>|
     |<span data-ttu-id="63099-136">**Bank Account**</span><span class="sxs-lookup"><span data-stu-id="63099-136">**Bank Account**</span></span>|<span data-ttu-id="63099-137">-11800</span><span class="sxs-lookup"><span data-stu-id="63099-137">-11800</span></span>|

<span data-ttu-id="63099-138">Inter-State Bank Payment with GST on Bank Charges where Input Tax Credit is available, for example bank charge of INR 10000 to be paid to bank and 18% IGST has to be calculated on bank charges amount.</span><span class="sxs-lookup"><span data-stu-id="63099-138">Inter-State Bank Payment with GST on Bank Charges where Input Tax Credit is available, for example bank charge of INR 10000 to be paid to bank and 18% IGST has to be calculated on bank charges amount.</span></span>
    
  - <span data-ttu-id="63099-139">GST calculation will appear in the Fact Box, as following:</span><span class="sxs-lookup"><span data-stu-id="63099-139">GST calculation will appear in the Fact Box, as following:</span></span>

      |<span data-ttu-id="63099-140">Component</span><span class="sxs-lookup"><span data-stu-id="63099-140">Component</span></span>|<span data-ttu-id="63099-141">Amount</span><span class="sxs-lookup"><span data-stu-id="63099-141">Amount</span></span>|
      |----------------------------------|---------------------------------------|  
      |<span data-ttu-id="63099-142">**Bank Charge Amount**</span><span class="sxs-lookup"><span data-stu-id="63099-142">**Bank Charge Amount**</span></span>|<span data-ttu-id="63099-143">10,000</span><span class="sxs-lookup"><span data-stu-id="63099-143">10,000</span></span>|  
      |<span data-ttu-id="63099-144">**IGST**</span><span class="sxs-lookup"><span data-stu-id="63099-144">**IGST**</span></span>|<span data-ttu-id="63099-145">1800</span><span class="sxs-lookup"><span data-stu-id="63099-145">1800</span></span>|  
       

  - <span data-ttu-id="63099-146">Once posted the bank payment GL entries for Inter-state bank charges with GST where Input Tax Credit is available, will be as following:</span><span class="sxs-lookup"><span data-stu-id="63099-146">Once posted the bank payment GL entries for Inter-state bank charges with GST where Input Tax Credit is available, will be as following:</span></span>

      |<span data-ttu-id="63099-147">Particulars</span><span class="sxs-lookup"><span data-stu-id="63099-147">Particulars</span></span>|<span data-ttu-id="63099-148">Amount</span><span class="sxs-lookup"><span data-stu-id="63099-148">Amount</span></span>|
      |----------------------------------|----------------------------------|  
      |<span data-ttu-id="63099-149">**Bank Charges**</span><span class="sxs-lookup"><span data-stu-id="63099-149">**Bank Charges**</span></span>|<span data-ttu-id="63099-150">10000</span><span class="sxs-lookup"><span data-stu-id="63099-150">10000</span></span>|  
      |<span data-ttu-id="63099-151">**IGST Receivable Account**</span><span class="sxs-lookup"><span data-stu-id="63099-151">**IGST Receivable Account**</span></span>|<span data-ttu-id="63099-152">1800</span><span class="sxs-lookup"><span data-stu-id="63099-152">1800</span></span>|
      |<span data-ttu-id="63099-153">**Bank Account**</span><span class="sxs-lookup"><span data-stu-id="63099-153">**Bank Account**</span></span>|<span data-ttu-id="63099-154">-11800</span><span class="sxs-lookup"><span data-stu-id="63099-154">-11800</span></span>| 

<span data-ttu-id="63099-155">Intra-State Bank Payment with GST on Bank Charges where Input Tax Credit is not available, for example bank charge of INR 10000 to be paid to bank and GST (9% CGST and 9% SGST) has to be calculated on bank charges amount.</span><span class="sxs-lookup"><span data-stu-id="63099-155">Intra-State Bank Payment with GST on Bank Charges where Input Tax Credit is not available, for example bank charge of INR 10000 to be paid to bank and GST (9% CGST and 9% SGST) has to be calculated on bank charges amount.</span></span>

  - <span data-ttu-id="63099-156">GST calculation will appear in the Fact Box, as following:</span><span class="sxs-lookup"><span data-stu-id="63099-156">GST calculation will appear in the Fact Box, as following:</span></span>

      |<span data-ttu-id="63099-157">Component</span><span class="sxs-lookup"><span data-stu-id="63099-157">Component</span></span>|<span data-ttu-id="63099-158">Amount</span><span class="sxs-lookup"><span data-stu-id="63099-158">Amount</span></span>|
      |----------------------------------|---------------------------------------|  
      |<span data-ttu-id="63099-159">**Bank Charge Amount**</span><span class="sxs-lookup"><span data-stu-id="63099-159">**Bank Charge Amount**</span></span>|<span data-ttu-id="63099-160">10,000</span><span class="sxs-lookup"><span data-stu-id="63099-160">10,000</span></span>|  
      |<span data-ttu-id="63099-161">**CGST**</span><span class="sxs-lookup"><span data-stu-id="63099-161">**CGST**</span></span>|<span data-ttu-id="63099-162">900</span><span class="sxs-lookup"><span data-stu-id="63099-162">900</span></span>|  
      |<span data-ttu-id="63099-163">**SGST**</span><span class="sxs-lookup"><span data-stu-id="63099-163">**SGST**</span></span>|<span data-ttu-id="63099-164">900</span><span class="sxs-lookup"><span data-stu-id="63099-164">900</span></span>|
    

  - <span data-ttu-id="63099-165">Once posted the bank payment GL entries for Intra-state bank charges with GST where Input Tax Credit is not available, will be as following:</span><span class="sxs-lookup"><span data-stu-id="63099-165">Once posted the bank payment GL entries for Intra-state bank charges with GST where Input Tax Credit is not available, will be as following:</span></span>
    
      |<span data-ttu-id="63099-166">Particulars</span><span class="sxs-lookup"><span data-stu-id="63099-166">Particulars</span></span>|<span data-ttu-id="63099-167">Amount</span><span class="sxs-lookup"><span data-stu-id="63099-167">Amount</span></span>|
      |----------------------------------|---------------------------------------|  
      |<span data-ttu-id="63099-168">**Bank Charges**</span><span class="sxs-lookup"><span data-stu-id="63099-168">**Bank Charges**</span></span>|<span data-ttu-id="63099-169">11800</span><span class="sxs-lookup"><span data-stu-id="63099-169">11800</span></span>|  
      |<span data-ttu-id="63099-170">**Bank Account**</span><span class="sxs-lookup"><span data-stu-id="63099-170">**Bank Account**</span></span>|<span data-ttu-id="63099-171">-11800</span><span class="sxs-lookup"><span data-stu-id="63099-171">-11800</span></span>|

<span data-ttu-id="63099-172">Inter-State Bank Payment with GST on Bank Charges where Input Tax Credit is not available, for example bank charge of INR 10000 to be paid to bank and 18% IGST has to be calculated on bank charges amount.</span><span class="sxs-lookup"><span data-stu-id="63099-172">Inter-State Bank Payment with GST on Bank Charges where Input Tax Credit is not available, for example bank charge of INR 10000 to be paid to bank and 18% IGST has to be calculated on bank charges amount.</span></span>
    
  - <span data-ttu-id="63099-173">GST calculation will appear in the Fact Box, as following:</span><span class="sxs-lookup"><span data-stu-id="63099-173">GST calculation will appear in the Fact Box, as following:</span></span>

      |<span data-ttu-id="63099-174">Component</span><span class="sxs-lookup"><span data-stu-id="63099-174">Component</span></span>|<span data-ttu-id="63099-175">Amount</span><span class="sxs-lookup"><span data-stu-id="63099-175">Amount</span></span>|
      |----------------------------------|---------------------------------------|  
      |<span data-ttu-id="63099-176">**Bank Charge Amount**</span><span class="sxs-lookup"><span data-stu-id="63099-176">**Bank Charge Amount**</span></span>|<span data-ttu-id="63099-177">10,000</span><span class="sxs-lookup"><span data-stu-id="63099-177">10,000</span></span>|  
      |<span data-ttu-id="63099-178">**IGST**</span><span class="sxs-lookup"><span data-stu-id="63099-178">**IGST**</span></span>|<span data-ttu-id="63099-179">1800</span><span class="sxs-lookup"><span data-stu-id="63099-179">1800</span></span>|  
       

  - <span data-ttu-id="63099-180">Once posted the bank payment GL entries for Inter-state bank charges with GST where Input Tax Credit is not available, will be as following:</span><span class="sxs-lookup"><span data-stu-id="63099-180">Once posted the bank payment GL entries for Inter-state bank charges with GST where Input Tax Credit is not available, will be as following:</span></span>
    
      |<span data-ttu-id="63099-181">Particulars</span><span class="sxs-lookup"><span data-stu-id="63099-181">Particulars</span></span>|<span data-ttu-id="63099-182">Amount</span><span class="sxs-lookup"><span data-stu-id="63099-182">Amount</span></span>|
      |----------------------------------|---------------------------------------|  
      |<span data-ttu-id="63099-183">**Bank Charges**</span><span class="sxs-lookup"><span data-stu-id="63099-183">**Bank Charges**</span></span>|<span data-ttu-id="63099-184">11800</span><span class="sxs-lookup"><span data-stu-id="63099-184">11800</span></span>|  
      |<span data-ttu-id="63099-185">**Bank Account**</span><span class="sxs-lookup"><span data-stu-id="63099-185">**Bank Account**</span></span>|<span data-ttu-id="63099-186">-11800</span><span class="sxs-lookup"><span data-stu-id="63099-186">-11800</span></span>| 


## <a name="deemed-value-calculation-for-gst-base-amount-in-foreign-exchange-transactions"></a><span data-ttu-id="63099-187">Deemed value calculation for GST base amount in foreign exchange transactions</span><span class="sxs-lookup"><span data-stu-id="63099-187">Deemed value calculation for GST base amount in foreign exchange transactions</span></span>

<span data-ttu-id="63099-188">As per GST law, A person supplying the services of exchange of foreign currency may exercise option to ascertain value in terms of Rule 32(2)b for a financial Year.</span><span class="sxs-lookup"><span data-stu-id="63099-188">As per GST law, A person supplying the services of exchange of foreign currency may exercise option to ascertain value in terms of Rule 32(2)b for a financial Year.</span></span> <span data-ttu-id="63099-189">In service related to supply of foreign currency, including money changing, the problem of valuation always arises, therefore the Rule states that, consideration should be taken to the difference in the buying rate or the selling rate.</span><span class="sxs-lookup"><span data-stu-id="63099-189">In service related to supply of foreign currency, including money changing, the problem of valuation always arises, therefore the Rule states that, consideration should be taken to the difference in the buying rate or the selling rate.</span></span>

### <a name="gst-calculation-on-bank-charges-for-bank-payment"></a><span data-ttu-id="63099-190">GST calculation on bank charges for bank payment</span><span class="sxs-lookup"><span data-stu-id="63099-190">GST calculation on bank charges for bank payment</span></span>

   1. <span data-ttu-id="63099-191">Choose the ![Search for Page or Report](image/search_small.png "Search for Page or Report icon") icon, enter **Bank Receipt Voucher** , and then choose the related link.</span><span class="sxs-lookup"><span data-stu-id="63099-191">Choose the ![Search for Page or Report](image/search_small.png "Search for Page or Report icon") icon, enter **Bank Receipt Voucher** , and then choose the related link.</span></span>
   2. <span data-ttu-id="63099-192">Select **G/L Account** in Account Type field and select relevant **Vendor** or **Customer** account in Account No. field.</span><span class="sxs-lookup"><span data-stu-id="63099-192">Select **G/L Account** in Account Type field and select relevant **Vendor** or **Customer** account in Account No. field.</span></span>
   3. <span data-ttu-id="63099-193">Select **Bank Account** in Bal. Account Type field and select relevant bank account in Bal. Account No. field.</span><span class="sxs-lookup"><span data-stu-id="63099-193">Select **Bank Account** in Bal. Account Type field and select relevant bank account in Bal. Account No. field.</span></span>
   4. <span data-ttu-id="63099-194">**GST Registration No.** and **GST Registration Status** fields should not be blank on Bank Account.</span><span class="sxs-lookup"><span data-stu-id="63099-194">**GST Registration No.** and **GST Registration Status** fields should not be blank on Bank Account.</span></span>
   5. <span data-ttu-id="63099-195">Select Process on the ribbon and click on Bank Charges -> select Bank Charge code and system will calculate the GST on bank charge amount.</span><span class="sxs-lookup"><span data-stu-id="63099-195">Select Process on the ribbon and click on Bank Charges -> select Bank Charge code and system will calculate the GST on bank charge amount.</span></span> <span data-ttu-id="63099-196">**External Document No.** and **GST Document Type** fields should not be blank on **Journal Bank Charges** line.</span><span class="sxs-lookup"><span data-stu-id="63099-196">**External Document No.** and **GST Document Type** fields should not be blank on **Journal Bank Charges** line.</span></span>
   6. <span data-ttu-id="63099-197">GST Credit, GST Group Code and HSN/SAC Code should not be blank on Bank Charge Code.</span><span class="sxs-lookup"><span data-stu-id="63099-197">GST Credit, GST Group Code and HSN/SAC Code should not be blank on Bank Charge Code.</span></span>

<span data-ttu-id="63099-198">Let us take the following example and check the GL entries of the posted transactions for different scenarios.</span><span class="sxs-lookup"><span data-stu-id="63099-198">Let us take the following example and check the GL entries of the posted transactions for different scenarios.</span></span>

|<span data-ttu-id="63099-199">Bank Charge Code</span><span class="sxs-lookup"><span data-stu-id="63099-199">Bank Charge Code</span></span>|<span data-ttu-id="63099-200">Lower limit</span><span class="sxs-lookup"><span data-stu-id="63099-200">Lower limit</span></span>|<span data-ttu-id="63099-201">Upper limit</span><span class="sxs-lookup"><span data-stu-id="63099-201">Upper limit</span></span>|<span data-ttu-id="63099-202">Formula</span><span class="sxs-lookup"><span data-stu-id="63099-202">Formula</span></span> |<span data-ttu-id="63099-203">Min.</span><span class="sxs-lookup"><span data-stu-id="63099-203">Min.</span></span> <span data-ttu-id="63099-204">Deemed Value</span><span class="sxs-lookup"><span data-stu-id="63099-204">Deemed Value</span></span>|<span data-ttu-id="63099-205">Max Deemed Value</span><span class="sxs-lookup"><span data-stu-id="63099-205">Max Deemed Value</span></span>|<span data-ttu-id="63099-206">Deemed %</span><span class="sxs-lookup"><span data-stu-id="63099-206">Deemed %</span></span>|<span data-ttu-id="63099-207">Fixed Amount</span><span class="sxs-lookup"><span data-stu-id="63099-207">Fixed Amount</span></span>|
|---------|---------|--|--|--|--|--|--|
|<span data-ttu-id="63099-208">BKCHG_01</span><span class="sxs-lookup"><span data-stu-id="63099-208">BKCHG_01</span></span>|<span data-ttu-id="63099-209">0</span><span class="sxs-lookup"><span data-stu-id="63099-209">0</span></span>|<span data-ttu-id="63099-210">10,00,000</span><span class="sxs-lookup"><span data-stu-id="63099-210">10,00,000</span></span>|<span data-ttu-id="63099-211">Deemed %</span><span class="sxs-lookup"><span data-stu-id="63099-211">Deemed %</span></span>|<span data-ttu-id="63099-212">0</span><span class="sxs-lookup"><span data-stu-id="63099-212">0</span></span>|<span data-ttu-id="63099-213">0</span><span class="sxs-lookup"><span data-stu-id="63099-213">0</span></span>|<span data-ttu-id="63099-214">1%</span><span class="sxs-lookup"><span data-stu-id="63099-214">1%</span></span>|<span data-ttu-id="63099-215">0</span><span class="sxs-lookup"><span data-stu-id="63099-215">0</span></span>|


- <span data-ttu-id="63099-216">Sample values for transactions</span><span class="sxs-lookup"><span data-stu-id="63099-216">Sample values for transactions</span></span>

    |<span data-ttu-id="63099-217">Component</span><span class="sxs-lookup"><span data-stu-id="63099-217">Component</span></span>|<span data-ttu-id="63099-218">Amount</span><span class="sxs-lookup"><span data-stu-id="63099-218">Amount</span></span>|
    |----------------------------------|---------------------------------------|  
    |<span data-ttu-id="63099-219">**CGST**</span><span class="sxs-lookup"><span data-stu-id="63099-219">**CGST**</span></span>|<span data-ttu-id="63099-220">9%</span><span class="sxs-lookup"><span data-stu-id="63099-220">9%</span></span>|  
    |<span data-ttu-id="63099-221">**SGST**</span><span class="sxs-lookup"><span data-stu-id="63099-221">**SGST**</span></span>|<span data-ttu-id="63099-222">9%</span><span class="sxs-lookup"><span data-stu-id="63099-222">9%</span></span>|
    |<span data-ttu-id="63099-223">**IGST**</span><span class="sxs-lookup"><span data-stu-id="63099-223">**IGST**</span></span>|<span data-ttu-id="63099-224">18%</span><span class="sxs-lookup"><span data-stu-id="63099-224">18%</span></span>|
    |<span data-ttu-id="63099-225">**Document Type**</span><span class="sxs-lookup"><span data-stu-id="63099-225">**Document Type**</span></span>|<span data-ttu-id="63099-226">Refund or Payment</span><span class="sxs-lookup"><span data-stu-id="63099-226">Refund or Payment</span></span>|
    |<span data-ttu-id="63099-227">**Account Type**</span><span class="sxs-lookup"><span data-stu-id="63099-227">**Account Type**</span></span>|<span data-ttu-id="63099-228">Vendor or Customer (Registered)</span><span class="sxs-lookup"><span data-stu-id="63099-228">Vendor or Customer (Registered)</span></span>|
    |<span data-ttu-id="63099-229">**Amount**</span><span class="sxs-lookup"><span data-stu-id="63099-229">**Amount**</span></span>|<span data-ttu-id="63099-230">INR -1000</span><span class="sxs-lookup"><span data-stu-id="63099-230">USD -1000</span></span>|
    |<span data-ttu-id="63099-231">**Currency**</span><span class="sxs-lookup"><span data-stu-id="63099-231">**Currency**</span></span>|<span data-ttu-id="63099-232">INR (Exchange Rate 65)</span><span class="sxs-lookup"><span data-stu-id="63099-232">USD (Exchange Rate 65)</span></span>|
    |<span data-ttu-id="63099-233">**Amount (LCY)**</span><span class="sxs-lookup"><span data-stu-id="63099-233">**Amount (LCY)**</span></span>|<span data-ttu-id="63099-234">INR -65000</span><span class="sxs-lookup"><span data-stu-id="63099-234">INR -65000</span></span>|
    |<span data-ttu-id="63099-235">**Bank Charge**</span><span class="sxs-lookup"><span data-stu-id="63099-235">**Bank Charge**</span></span>|<span data-ttu-id="63099-236">BKCHG_01</span><span class="sxs-lookup"><span data-stu-id="63099-236">BKCHG_01</span></span>|
    |<span data-ttu-id="63099-237">**GST Transactional Value**</span><span class="sxs-lookup"><span data-stu-id="63099-237">**GST Transactional Value**</span></span>|<span data-ttu-id="63099-238">INR 6500</span><span class="sxs-lookup"><span data-stu-id="63099-238">INR 6500</span></span>|
    |<span data-ttu-id="63099-239">**GST Amount**</span><span class="sxs-lookup"><span data-stu-id="63099-239">**GST Amount**</span></span>|<span data-ttu-id="63099-240">INR 1170</span><span class="sxs-lookup"><span data-stu-id="63099-240">INR 1170</span></span>|

- <span data-ttu-id="63099-241">Once posted the bank payment GL entries for Intrastate Bank Receipt Voucher with Document Type as Refund for Bank Charges and GST is posted with Credit Availment and GST Document Type Invoice, will be as following:</span><span class="sxs-lookup"><span data-stu-id="63099-241">Once posted the bank payment GL entries for Intrastate Bank Receipt Voucher with Document Type as Refund for Bank Charges and GST is posted with Credit Availment and GST Document Type Invoice, will be as following:</span></span>
    
    |<span data-ttu-id="63099-242">Document Type</span><span class="sxs-lookup"><span data-stu-id="63099-242">Document Type</span></span>|<span data-ttu-id="63099-243">Particulars</span><span class="sxs-lookup"><span data-stu-id="63099-243">Particulars</span></span>|<span data-ttu-id="63099-244">Amount</span><span class="sxs-lookup"><span data-stu-id="63099-244">Amount</span></span>|
    |------|----------------------------------|---------------------------------------|  
    |<span data-ttu-id="63099-245">**Refund**</span><span class="sxs-lookup"><span data-stu-id="63099-245">**Refund**</span></span>|<span data-ttu-id="63099-246">**Vendor**</span><span class="sxs-lookup"><span data-stu-id="63099-246">**Vendor**</span></span>|<span data-ttu-id="63099-247">-65000</span><span class="sxs-lookup"><span data-stu-id="63099-247">-65000</span></span>|  
    |<span data-ttu-id="63099-248">**Refund**</span><span class="sxs-lookup"><span data-stu-id="63099-248">**Refund**</span></span>|<span data-ttu-id="63099-249">**SGST/UTGST Receivable Account**</span><span class="sxs-lookup"><span data-stu-id="63099-249">**SGST/UTGST Receivable Account**</span></span>|<span data-ttu-id="63099-250">585</span><span class="sxs-lookup"><span data-stu-id="63099-250">585</span></span>|
    |<span data-ttu-id="63099-251">**Refund**</span><span class="sxs-lookup"><span data-stu-id="63099-251">**Refund**</span></span>|<span data-ttu-id="63099-252">**CGST Receivable Account**</span><span class="sxs-lookup"><span data-stu-id="63099-252">**CGST Receivable Account**</span></span>|<span data-ttu-id="63099-253">585</span><span class="sxs-lookup"><span data-stu-id="63099-253">585</span></span>|
    |<span data-ttu-id="63099-254">**Refund**</span><span class="sxs-lookup"><span data-stu-id="63099-254">**Refund**</span></span>|<span data-ttu-id="63099-255">**Bank Account**</span><span class="sxs-lookup"><span data-stu-id="63099-255">**Bank Account**</span></span>|<span data-ttu-id="63099-256">63830</span><span class="sxs-lookup"><span data-stu-id="63099-256">63830</span></span>|

- <span data-ttu-id="63099-257">The bank payment GL entries for Intrastate Bank Receipt Voucher with Document Type as Payment for Bank Charges and GST is posted with Credit Availment and GST Document Type as Invoice, will be as following:</span><span class="sxs-lookup"><span data-stu-id="63099-257">The bank payment GL entries for Intrastate Bank Receipt Voucher with Document Type as Payment for Bank Charges and GST is posted with Credit Availment and GST Document Type as Invoice, will be as following:</span></span>
    
    |<span data-ttu-id="63099-258">Document Type</span><span class="sxs-lookup"><span data-stu-id="63099-258">Document Type</span></span>|<span data-ttu-id="63099-259">Particulars</span><span class="sxs-lookup"><span data-stu-id="63099-259">Particulars</span></span>|<span data-ttu-id="63099-260">Amount</span><span class="sxs-lookup"><span data-stu-id="63099-260">Amount</span></span>|
    |------|----------------------------------|---------------------------------------|  
    |<span data-ttu-id="63099-261">**Payment**</span><span class="sxs-lookup"><span data-stu-id="63099-261">**Payment**</span></span>|<span data-ttu-id="63099-262">**Customer**</span><span class="sxs-lookup"><span data-stu-id="63099-262">**Customer**</span></span>|<span data-ttu-id="63099-263">-65000</span><span class="sxs-lookup"><span data-stu-id="63099-263">-65000</span></span>|  
    |<span data-ttu-id="63099-264">**Payment**</span><span class="sxs-lookup"><span data-stu-id="63099-264">**Payment**</span></span>|<span data-ttu-id="63099-265">**SGST/UTGST Receivable Account**</span><span class="sxs-lookup"><span data-stu-id="63099-265">**SGST/UTGST Receivable Account**</span></span>|<span data-ttu-id="63099-266">585</span><span class="sxs-lookup"><span data-stu-id="63099-266">585</span></span>|
    |<span data-ttu-id="63099-267">**Payment**</span><span class="sxs-lookup"><span data-stu-id="63099-267">**Payment**</span></span>|<span data-ttu-id="63099-268">**CGST Receivable Account**</span><span class="sxs-lookup"><span data-stu-id="63099-268">**CGST Receivable Account**</span></span>|<span data-ttu-id="63099-269">585</span><span class="sxs-lookup"><span data-stu-id="63099-269">585</span></span>|
    |<span data-ttu-id="63099-270">**Payment**</span><span class="sxs-lookup"><span data-stu-id="63099-270">**Payment**</span></span>|<span data-ttu-id="63099-271">**Bank Account**</span><span class="sxs-lookup"><span data-stu-id="63099-271">**Bank Account**</span></span>|<span data-ttu-id="63099-272">63830</span><span class="sxs-lookup"><span data-stu-id="63099-272">63830</span></span>|

- <span data-ttu-id="63099-273">The bank payment GL entries for Intrastate Bank Receipt Voucher with Document Type as Refund for Bank Charges and GST is posted with Credit Non-Availment and GST Document Type as Invoice, will be as following:</span><span class="sxs-lookup"><span data-stu-id="63099-273">The bank payment GL entries for Intrastate Bank Receipt Voucher with Document Type as Refund for Bank Charges and GST is posted with Credit Non-Availment and GST Document Type as Invoice, will be as following:</span></span>
    
    |<span data-ttu-id="63099-274">Document Type</span><span class="sxs-lookup"><span data-stu-id="63099-274">Document Type</span></span>|<span data-ttu-id="63099-275">Particulars</span><span class="sxs-lookup"><span data-stu-id="63099-275">Particulars</span></span>|<span data-ttu-id="63099-276">Amount</span><span class="sxs-lookup"><span data-stu-id="63099-276">Amount</span></span>|
    |------|----------------------------------|---------------------------------------|  
    |<span data-ttu-id="63099-277">**Refund**</span><span class="sxs-lookup"><span data-stu-id="63099-277">**Refund**</span></span>|<span data-ttu-id="63099-278">**Vendor**</span><span class="sxs-lookup"><span data-stu-id="63099-278">**Vendor**</span></span>|<span data-ttu-id="63099-279">-65000</span><span class="sxs-lookup"><span data-stu-id="63099-279">-65000</span></span>|  
    |<span data-ttu-id="63099-280">**Refund**</span><span class="sxs-lookup"><span data-stu-id="63099-280">**Refund**</span></span>|<span data-ttu-id="63099-281">**Other Charges**</span><span class="sxs-lookup"><span data-stu-id="63099-281">**Other Charges**</span></span>|<span data-ttu-id="63099-282">1170</span><span class="sxs-lookup"><span data-stu-id="63099-282">1170</span></span>|
    |<span data-ttu-id="63099-283">**Refund**</span><span class="sxs-lookup"><span data-stu-id="63099-283">**Refund**</span></span>|<span data-ttu-id="63099-284">**Bank Account**</span><span class="sxs-lookup"><span data-stu-id="63099-284">**Bank Account**</span></span>|<span data-ttu-id="63099-285">63830</span><span class="sxs-lookup"><span data-stu-id="63099-285">63830</span></span>|

- <span data-ttu-id="63099-286">The bank payment GL entries for Intrastate Bank Receipt Voucher with Document Type as Payment for Bank Charges and GST is posted with Credit Non-Availment and GST Document Type as Invoice, will be as following:</span><span class="sxs-lookup"><span data-stu-id="63099-286">The bank payment GL entries for Intrastate Bank Receipt Voucher with Document Type as Payment for Bank Charges and GST is posted with Credit Non-Availment and GST Document Type as Invoice, will be as following:</span></span>
    
    |<span data-ttu-id="63099-287">Document Type</span><span class="sxs-lookup"><span data-stu-id="63099-287">Document Type</span></span>|<span data-ttu-id="63099-288">Particulars</span><span class="sxs-lookup"><span data-stu-id="63099-288">Particulars</span></span>|<span data-ttu-id="63099-289">Amount</span><span class="sxs-lookup"><span data-stu-id="63099-289">Amount</span></span>|
    |------|----------------------------------|---------------------------------------|  
    |<span data-ttu-id="63099-290">**Payment**</span><span class="sxs-lookup"><span data-stu-id="63099-290">**Payment**</span></span>|<span data-ttu-id="63099-291">**Customer**</span><span class="sxs-lookup"><span data-stu-id="63099-291">**Customer**</span></span>|<span data-ttu-id="63099-292">-65000</span><span class="sxs-lookup"><span data-stu-id="63099-292">-65000</span></span>|  
    |<span data-ttu-id="63099-293">**Payment**</span><span class="sxs-lookup"><span data-stu-id="63099-293">**Payment**</span></span>|<span data-ttu-id="63099-294">**Other Charges**</span><span class="sxs-lookup"><span data-stu-id="63099-294">**Other Charges**</span></span>|<span data-ttu-id="63099-295">1170</span><span class="sxs-lookup"><span data-stu-id="63099-295">1170</span></span>|
    |<span data-ttu-id="63099-296">**Payment**</span><span class="sxs-lookup"><span data-stu-id="63099-296">**Payment**</span></span>|<span data-ttu-id="63099-297">**Bank Account**</span><span class="sxs-lookup"><span data-stu-id="63099-297">**Bank Account**</span></span>|<span data-ttu-id="63099-298">63830</span><span class="sxs-lookup"><span data-stu-id="63099-298">63830</span></span>|



































