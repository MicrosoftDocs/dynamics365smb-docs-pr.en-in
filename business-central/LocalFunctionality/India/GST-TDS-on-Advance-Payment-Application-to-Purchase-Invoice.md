---
title: GST and TDS on Vendor Advance Payments
description: GST and TDS on Vendor Advance Payments
author: v-debapd
ms.service: dynamics365-business-central
ms.topic: article
ms.devlang: na
ms.tgt_pltfrm: na
ms.workload: na
ms.search.keywords: India, local, IN, English
ms.date: 10/01/2020
ms.author: v-debapd
ms.openlocfilehash: cf170b3d3807f5052294d18303f6d4a646eafcbd
ms.sourcegitcommit: ddbb5cede750df1baba4b3eab8fbed6744b5b9d6
ms.translationtype: HT
ms.contentlocale: en-IN
ms.lasthandoff: 10/01/2020
ms.locfileid: "3948619"
---
# <a name="gst-and-tds-on-vendor-advance-payments"></a><span data-ttu-id="23fbe-103">GST and TDS on Vendor Advance Payments</span><span class="sxs-lookup"><span data-stu-id="23fbe-103">GST and TDS on Vendor Advance Payments</span></span>

[!INCLUDE[vnext_preview](../../includes/vnext_preview.md)]

<span data-ttu-id="23fbe-104">Liability of paying GST and TDS arises at the time of advance payment to vendor.</span><span class="sxs-lookup"><span data-stu-id="23fbe-104">Liability of paying GST and TDS arises at the time of advance payment to vendor.</span></span>

### <a name="mandatory-fields-in-cash-or-bank-payment-voucher"></a><span data-ttu-id="23fbe-105">Mandatory fields in cash or bank payment voucher</span><span class="sxs-lookup"><span data-stu-id="23fbe-105">Mandatory fields in cash or bank payment voucher</span></span>

1. <span data-ttu-id="23fbe-106">Choose the ![Search for Page or Report](image/search_small.png "Search for Page or Report icon") icon, enter **Bank Payment Voucher** or **Cash Payment Voucher** , and then choose the related link.</span><span class="sxs-lookup"><span data-stu-id="23fbe-106">Choose the ![Search for Page or Report](image/search_small.png "Search for Page or Report icon") icon, enter **Bank Payment Voucher** or **Cash Payment Voucher** , and then choose the related link.</span></span>
2. <span data-ttu-id="23fbe-107">Select **Vendor** in **Account Type** field and select relevant vendor code in **Account No.** field.</span><span class="sxs-lookup"><span data-stu-id="23fbe-107">Select **Vendor** in **Account Type** field and select relevant vendor code in **Account No.** field.</span></span>
3. <span data-ttu-id="23fbe-108">Select **G/L Account** for cash or **Bank Account** for bank in **Bal. Account Type** field, and select relevant cash or bank account in **Bal. Account No.** field.</span><span class="sxs-lookup"><span data-stu-id="23fbe-108">Select **G/L Account** for cash or **Bank Account** for bank in **Bal. Account Type** field, and select relevant cash or bank account in **Bal. Account No.** field.</span></span>
4. <span data-ttu-id="23fbe-109">Select relevant TDS Section, GST Group Code, HSN/SAC Code, Location Code on journal line.</span><span class="sxs-lookup"><span data-stu-id="23fbe-109">Select relevant TDS Section, GST Group Code, HSN/SAC Code, Location Code on journal line.</span></span>
5. <span data-ttu-id="23fbe-110">**GST on Advance Payment** should be marked true.</span><span class="sxs-lookup"><span data-stu-id="23fbe-110">**GST on Advance Payment** should be marked true.</span></span> 

<span data-ttu-id="23fbe-111">For example, service amount is INR 20000 and advance payment made to vendor for INR 10000, 18% GST (i.e. 9% CGST and 9% SGST/UTGST) and 10% TDS has to be charged.</span><span class="sxs-lookup"><span data-stu-id="23fbe-111">For example, service amount is INR 20000 and advance payment made to vendor for INR 10000, 18% GST (i.e. 9% CGST and 9% SGST/UTGST) and 10% TDS has to be charged.</span></span>

- <span data-ttu-id="23fbe-112">GST calculation for Intra-State or Intra-Union Territory transactions will appear in the Fact Box, as following:</span><span class="sxs-lookup"><span data-stu-id="23fbe-112">GST calculation for Intra-State or Intra-Union Territory transactions will appear in the Fact Box, as following:</span></span>
    
    |<span data-ttu-id="23fbe-113">Component</span><span class="sxs-lookup"><span data-stu-id="23fbe-113">Component</span></span>|<span data-ttu-id="23fbe-114">Amount</span><span class="sxs-lookup"><span data-stu-id="23fbe-114">Amount</span></span>|
    |----------------------------------|---------------------------------------|  
    |<span data-ttu-id="23fbe-115">**GST Base Amount**</span><span class="sxs-lookup"><span data-stu-id="23fbe-115">**GST Base Amount**</span></span>|<span data-ttu-id="23fbe-116">10,000</span><span class="sxs-lookup"><span data-stu-id="23fbe-116">10,000</span></span>|  
    |<span data-ttu-id="23fbe-117">**CGST**</span><span class="sxs-lookup"><span data-stu-id="23fbe-117">**CGST**</span></span>|<span data-ttu-id="23fbe-118">900 (10000\*9%)</span><span class="sxs-lookup"><span data-stu-id="23fbe-118">900 (10000\*9%)</span></span>|  
    |<span data-ttu-id="23fbe-119">**SGST**</span><span class="sxs-lookup"><span data-stu-id="23fbe-119">**SGST**</span></span>|<span data-ttu-id="23fbe-120">900 (10000\*9%)</span><span class="sxs-lookup"><span data-stu-id="23fbe-120">900 (10000\*9%)</span></span>| 
    |<span data-ttu-id="23fbe-121">**TDS Amount**</span><span class="sxs-lookup"><span data-stu-id="23fbe-121">**TDS Amount**</span></span>|<span data-ttu-id="23fbe-122">1000 (10000\*10%)</span><span class="sxs-lookup"><span data-stu-id="23fbe-122">1000 (10000\*10%)</span></span>|

- <span data-ttu-id="23fbe-123">On posting of advance payment made to vendor, GL Entries will be as following:</span><span class="sxs-lookup"><span data-stu-id="23fbe-123">On posting of advance payment made to vendor, GL Entries will be as following:</span></span>

    |<span data-ttu-id="23fbe-124">Particulars</span><span class="sxs-lookup"><span data-stu-id="23fbe-124">Particulars</span></span>|<span data-ttu-id="23fbe-125">Amount</span><span class="sxs-lookup"><span data-stu-id="23fbe-125">Amount</span></span>|
    |----------------------------------|---------------------------------------|  
    |<span data-ttu-id="23fbe-126">**Vendor Account**</span><span class="sxs-lookup"><span data-stu-id="23fbe-126">**Vendor Account**</span></span>|<span data-ttu-id="23fbe-127">10,000</span><span class="sxs-lookup"><span data-stu-id="23fbe-127">10,000</span></span>|  
    |<span data-ttu-id="23fbe-128">**SGST/UTGST Receivable (Interim) Account**</span><span class="sxs-lookup"><span data-stu-id="23fbe-128">**SGST/UTGST Receivable (Interim) Account**</span></span>|<span data-ttu-id="23fbe-129">900</span><span class="sxs-lookup"><span data-stu-id="23fbe-129">900</span></span>|  
    |<span data-ttu-id="23fbe-130">**CGST Receivable (Interim) Account**</span><span class="sxs-lookup"><span data-stu-id="23fbe-130">**CGST Receivable (Interim) Account**</span></span>|<span data-ttu-id="23fbe-131">900</span><span class="sxs-lookup"><span data-stu-id="23fbe-131">900</span></span>| 
    |<span data-ttu-id="23fbe-132">**TDS Payable Account**</span><span class="sxs-lookup"><span data-stu-id="23fbe-132">**TDS Payable Account**</span></span>|<span data-ttu-id="23fbe-133">-1000</span><span class="sxs-lookup"><span data-stu-id="23fbe-133">-1000</span></span>|
    |<span data-ttu-id="23fbe-134">**SGST/UTGST Payable Account**</span><span class="sxs-lookup"><span data-stu-id="23fbe-134">**SGST/UTGST Payable Account**</span></span>|<span data-ttu-id="23fbe-135">-900</span><span class="sxs-lookup"><span data-stu-id="23fbe-135">-900</span></span>| 
    |<span data-ttu-id="23fbe-136">**CGST Payable Account**</span><span class="sxs-lookup"><span data-stu-id="23fbe-136">**CGST Payable Account**</span></span>|<span data-ttu-id="23fbe-137">-900</span><span class="sxs-lookup"><span data-stu-id="23fbe-137">-900</span></span>| 
    |<span data-ttu-id="23fbe-138">**Bank Account**</span><span class="sxs-lookup"><span data-stu-id="23fbe-138">**Bank Account**</span></span>|<span data-ttu-id="23fbe-139">-9000</span><span class="sxs-lookup"><span data-stu-id="23fbe-139">-9000</span></span>| 

> [!IMPORTANT]
> <span data-ttu-id="23fbe-140">In some cases GST needs to be calculated on the amount excluding GST, provision has been made to handle such scenario.</span><span class="sxs-lookup"><span data-stu-id="23fbe-140">In some cases GST needs to be calculated on the amount excluding GST, provision has been made to handle such scenario.</span></span> <span data-ttu-id="23fbe-141">Business user need to fill the TDS Base Value in **Amount Excl. GST** filed on **Bank Payment Voucher** , and system will calculate TDS on the mentioned value.</span><span class="sxs-lookup"><span data-stu-id="23fbe-141">Business user need to fill the TDS Base Value in **Amount Excl. GST** filed on **Bank Payment Voucher** , and system will calculate TDS on the mentioned value.</span></span>

<span data-ttu-id="23fbe-142">Later invoice for service purchase issued by vendor for INR 20,000, 18% GST (i.e. 9% CGST and 9% SGST/UTGST) and 10% TDS, will be charged, and the advance payment will be applied with the invoice.</span><span class="sxs-lookup"><span data-stu-id="23fbe-142">Later invoice for service purchase issued by vendor for INR 20,000, 18% GST (i.e. 9% CGST and 9% SGST/UTGST) and 10% TDS, will be charged, and the advance payment will be applied with the invoice.</span></span>

### <a name="mandatory-fields-on-purchase-invoice"></a><span data-ttu-id="23fbe-143">Mandatory fields on purchase invoice</span><span class="sxs-lookup"><span data-stu-id="23fbe-143">Mandatory fields on purchase invoice</span></span>

1. <span data-ttu-id="23fbe-144">Choose the ![Search for Page or Report](image/search_small.png "Search for Page or Report icon") icon, enter **Purchase Invoice** , and then choose the related link.</span><span class="sxs-lookup"><span data-stu-id="23fbe-144">Choose the ![Search for Page or Report](image/search_small.png "Search for Page or Report icon") icon, enter **Purchase Invoice** , and then choose the related link.</span></span>
2. <span data-ttu-id="23fbe-145">Select **Vendor** on **Purchase Invoice** header.</span><span class="sxs-lookup"><span data-stu-id="23fbe-145">Select **Vendor** on **Purchase Invoice** header.</span></span>
3. <span data-ttu-id="23fbe-146">Select **G/L Account** for service on **Purchase Invoice** line.</span><span class="sxs-lookup"><span data-stu-id="23fbe-146">Select **G/L Account** for service on **Purchase Invoice** line.</span></span>
4. <span data-ttu-id="23fbe-147">Select TDS Section on **Purchase Invoice** line.</span><span class="sxs-lookup"><span data-stu-id="23fbe-147">Select TDS Section on **Purchase Invoice** line.</span></span>
5. <span data-ttu-id="23fbe-148">GST Group Code, HSN/SAC Code, GST Credit should have a value in **G/L Account** card.</span><span class="sxs-lookup"><span data-stu-id="23fbe-148">GST Group Code, HSN/SAC Code, GST Credit should have a value in **G/L Account** card.</span></span>
6. <span data-ttu-id="23fbe-149">**Location Code** field should not be blank on both **Purchase Invoice** header and line.</span><span class="sxs-lookup"><span data-stu-id="23fbe-149">**Location Code** field should not be blank on both **Purchase Invoice** header and line.</span></span>
7. <span data-ttu-id="23fbe-150">Apply the advance payment in **Applies to Doc. No.**</span><span class="sxs-lookup"><span data-stu-id="23fbe-150">Apply the advance payment in **Applies to Doc. No.**</span></span> <span data-ttu-id="23fbe-151">field on **Purchase Invoice** header.</span><span class="sxs-lookup"><span data-stu-id="23fbe-151">field on **Purchase Invoice** header.</span></span>
  
- <span data-ttu-id="23fbe-152">GST calculation will appear in the Fact Box, as following:</span><span class="sxs-lookup"><span data-stu-id="23fbe-152">GST calculation will appear in the Fact Box, as following:</span></span>

  |<span data-ttu-id="23fbe-153">Component</span><span class="sxs-lookup"><span data-stu-id="23fbe-153">Component</span></span>|<span data-ttu-id="23fbe-154">Amount</span><span class="sxs-lookup"><span data-stu-id="23fbe-154">Amount</span></span>|
  |----------------------------------|---------------------------------------|  
  |<span data-ttu-id="23fbe-155">**GST Base Amount**</span><span class="sxs-lookup"><span data-stu-id="23fbe-155">**GST Base Amount**</span></span>|<span data-ttu-id="23fbe-156">20000</span><span class="sxs-lookup"><span data-stu-id="23fbe-156">20000</span></span>|  
  |<span data-ttu-id="23fbe-157">**CGST**</span><span class="sxs-lookup"><span data-stu-id="23fbe-157">**CGST**</span></span>|<span data-ttu-id="23fbe-158">900 = [1800 (20000 \* 9%)] - [900 (10000 \* 9%)]</span><span class="sxs-lookup"><span data-stu-id="23fbe-158">900 = [1800 (20000 \* 9%)] - [900 (10000 \* 9%)]</span></span>|  
  |<span data-ttu-id="23fbe-159">**SGST**</span><span class="sxs-lookup"><span data-stu-id="23fbe-159">**SGST**</span></span>|<span data-ttu-id="23fbe-160">900 = [1800 (20000 \* 9%)] - [900 (10000 \* 9%)]</span><span class="sxs-lookup"><span data-stu-id="23fbe-160">900 = [1800 (20000 \* 9%)] - [900 (10000 \* 9%)]</span></span>| 
  |<span data-ttu-id="23fbe-161">**TDS Amount**</span><span class="sxs-lookup"><span data-stu-id="23fbe-161">**TDS Amount**</span></span>|<span data-ttu-id="23fbe-162">1000 = [2000 (20000 \* 10%)] - [1000 (10000 \*10%)]</span><span class="sxs-lookup"><span data-stu-id="23fbe-162">1000 = [2000 (20000 \* 10%)] - [1000 (10000 \*10%)]</span></span>|

<span data-ttu-id="23fbe-163">GST and TDS will be calculated on the remaining amount, i.e. Invoice Amount - Advance Payment Amount.</span><span class="sxs-lookup"><span data-stu-id="23fbe-163">GST and TDS will be calculated on the remaining amount, i.e. Invoice Amount - Advance Payment Amount.</span></span> <span data-ttu-id="23fbe-164">If advance payment is not applied with the purchase invoice then GST and TDS will be calculated on the whole invoice amount.</span><span class="sxs-lookup"><span data-stu-id="23fbe-164">If advance payment is not applied with the purchase invoice then GST and TDS will be calculated on the whole invoice amount.</span></span>

- <span data-ttu-id="23fbe-165">On posting the purchase invoice, GL Entries will be as following:</span><span class="sxs-lookup"><span data-stu-id="23fbe-165">On posting the purchase invoice, GL Entries will be as following:</span></span>

    |<span data-ttu-id="23fbe-166">Particulars</span><span class="sxs-lookup"><span data-stu-id="23fbe-166">Particulars</span></span>|<span data-ttu-id="23fbe-167">Amount</span><span class="sxs-lookup"><span data-stu-id="23fbe-167">Amount</span></span>|
    |----------------------------------|---------------------------------------|  
    |<span data-ttu-id="23fbe-168">**Vendor Account**</span><span class="sxs-lookup"><span data-stu-id="23fbe-168">**Vendor Account**</span></span>|<span data-ttu-id="23fbe-169">-19000</span><span class="sxs-lookup"><span data-stu-id="23fbe-169">-19000</span></span>|  
    |<span data-ttu-id="23fbe-170">**SGST/UTGST Payable (Interim) Account**</span><span class="sxs-lookup"><span data-stu-id="23fbe-170">**SGST/UTGST Payable (Interim) Account**</span></span>|<span data-ttu-id="23fbe-171">-1800</span><span class="sxs-lookup"><span data-stu-id="23fbe-171">-1800</span></span>|
    |<span data-ttu-id="23fbe-172">**CGST Payable (Interim) Account**</span><span class="sxs-lookup"><span data-stu-id="23fbe-172">**CGST Payable (Interim) Account**</span></span>|<span data-ttu-id="23fbe-173">-1800</span><span class="sxs-lookup"><span data-stu-id="23fbe-173">-1800</span></span>|
    |<span data-ttu-id="23fbe-174">**SGST/UTGST Receivable (Interim) Account**</span><span class="sxs-lookup"><span data-stu-id="23fbe-174">**SGST/UTGST Receivable (Interim) Account**</span></span>|<span data-ttu-id="23fbe-175">-1800</span><span class="sxs-lookup"><span data-stu-id="23fbe-175">-1800</span></span>|
    |<span data-ttu-id="23fbe-176">**CGST Receivable (Interim) Account**</span><span class="sxs-lookup"><span data-stu-id="23fbe-176">**CGST Receivable (Interim) Account**</span></span>|<span data-ttu-id="23fbe-177">-1800</span><span class="sxs-lookup"><span data-stu-id="23fbe-177">-1800</span></span>|
    |<span data-ttu-id="23fbe-178">**TDS Payable Account**</span><span class="sxs-lookup"><span data-stu-id="23fbe-178">**TDS Payable Account**</span></span>|<span data-ttu-id="23fbe-179">-1000</span><span class="sxs-lookup"><span data-stu-id="23fbe-179">-1000</span></span>|
    |<span data-ttu-id="23fbe-180">**CGST Payable (Interim) Account**</span><span class="sxs-lookup"><span data-stu-id="23fbe-180">**CGST Payable (Interim) Account**</span></span>|<span data-ttu-id="23fbe-181">900</span><span class="sxs-lookup"><span data-stu-id="23fbe-181">900</span></span>|
    |<span data-ttu-id="23fbe-182">**CGST Receivable Account**</span><span class="sxs-lookup"><span data-stu-id="23fbe-182">**CGST Receivable Account**</span></span>|<span data-ttu-id="23fbe-183">900</span><span class="sxs-lookup"><span data-stu-id="23fbe-183">900</span></span>|
    |<span data-ttu-id="23fbe-184">**SGST/UTGST Payable (Interim) Account**</span><span class="sxs-lookup"><span data-stu-id="23fbe-184">**SGST/UTGST Payable (Interim) Account**</span></span>|<span data-ttu-id="23fbe-185">900</span><span class="sxs-lookup"><span data-stu-id="23fbe-185">900</span></span>|
    |<span data-ttu-id="23fbe-186">**SGST/UTGST Receivable  Account**</span><span class="sxs-lookup"><span data-stu-id="23fbe-186">**SGST/UTGST Receivable  Account**</span></span>|<span data-ttu-id="23fbe-187">900</span><span class="sxs-lookup"><span data-stu-id="23fbe-187">900</span></span>|
    |<span data-ttu-id="23fbe-188">**SGST/UTGST Receivable (Interim) Account**</span><span class="sxs-lookup"><span data-stu-id="23fbe-188">**SGST/UTGST Receivable (Interim) Account**</span></span>|<span data-ttu-id="23fbe-189">1800</span><span class="sxs-lookup"><span data-stu-id="23fbe-189">1800</span></span>|
    |<span data-ttu-id="23fbe-190">**CGST Receivable (Interim) Account**</span><span class="sxs-lookup"><span data-stu-id="23fbe-190">**CGST Receivable (Interim) Account**</span></span>|<span data-ttu-id="23fbe-191">1800</span><span class="sxs-lookup"><span data-stu-id="23fbe-191">1800</span></span>|
    |<span data-ttu-id="23fbe-192">**Service Account**</span><span class="sxs-lookup"><span data-stu-id="23fbe-192">**Service Account**</span></span>|<span data-ttu-id="23fbe-193">20000</span><span class="sxs-lookup"><span data-stu-id="23fbe-193">20000</span></span>|

>[!Tip]
>
> <span data-ttu-id="23fbe-194">Note: In case of Inter-State Purchase, IGST will be calculated.</span><span class="sxs-lookup"><span data-stu-id="23fbe-194">Note: In case of Inter-State Purchase, IGST will be calculated.</span></span>






































