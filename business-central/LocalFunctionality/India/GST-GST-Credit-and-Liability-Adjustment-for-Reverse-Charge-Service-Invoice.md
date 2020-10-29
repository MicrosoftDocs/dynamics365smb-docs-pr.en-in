---
title: GST Credit and GST Liability adjustment for open Reverse Charge Goods and Services Invoices
description: GST Credit and GST Liability adjustment for open Reverse Charge Services Invoices
author: v-debapd
ms.service: dynamics365-business-central
ms.topic: article
ms.devlang: na
ms.tgt_pltfrm: na
ms.workload: na
ms.search.keywords: India, local, IN, English
ms.date: 10/01/2020
ms.author: v-debapd
ms.openlocfilehash: e17e749e96040e648d6ff3d15b8bd9b8ae215295
ms.sourcegitcommit: ddbb5cede750df1baba4b3eab8fbed6744b5b9d6
ms.translationtype: HT
ms.contentlocale: en-IN
ms.lasthandoff: 10/01/2020
ms.locfileid: "3948650"
---
# <a name="gst-credit-and-gst-liability-adjustment-for-open-reverse-charge-goods-and-services-invoices"></a><span data-ttu-id="347bb-103">GST Credit and GST Liability Adjustment for Open Reverse Charge Goods and Services Invoices</span><span class="sxs-lookup"><span data-stu-id="347bb-103">GST Credit and GST Liability Adjustment for Open Reverse Charge Goods and Services Invoices</span></span>

[!INCLUDE[vnext_preview](../../includes/vnext_preview.md)]

<span data-ttu-id="347bb-104">This topic explains the process of adjusting GST Credit and GST Liability for open reverse charge goods and services invoices.</span><span class="sxs-lookup"><span data-stu-id="347bb-104">This topic explains the process of adjusting GST Credit and GST Liability for open reverse charge goods and services invoices.</span></span>

- <span data-ttu-id="347bb-105">For reverse charge invoices of goods, GST Liability and Credit shall be generated immediately, or in next 30 days from date of issue of supplier invoice, if payment to supplier is not made against it.</span><span class="sxs-lookup"><span data-stu-id="347bb-105">For reverse charge invoices of goods, GST Liability and Credit shall be generated immediately, or in next 30 days from date of issue of supplier invoice, if payment to supplier is not made against it.</span></span>

- <span data-ttu-id="347bb-106">For reverse charge for service invoices, GST Liability and Credit shall be generated immediately, or 60 days from date of issue of supplier invoice, if payment to supplier is not made against it.</span><span class="sxs-lookup"><span data-stu-id="347bb-106">For reverse charge for service invoices, GST Liability and Credit shall be generated immediately, or 60 days from date of issue of supplier invoice, if payment to supplier is not made against it.</span></span>

- <span data-ttu-id="347bb-107">User can generate GST liability and credit for open reverse charge service invoice through GST Liability Adjustment.</span><span class="sxs-lookup"><span data-stu-id="347bb-107">User can generate GST liability and credit for open reverse charge service invoice through GST Liability Adjustment.</span></span>

  1. <span data-ttu-id="347bb-108">Choose the ![Search for Page or Report](image/search_small.png "Search for Page or Report icon") icon, enter **GST Liability Adjustment** , and then choose the related link.</span><span class="sxs-lookup"><span data-stu-id="347bb-108">Choose the ![Search for Page or Report](image/search_small.png "Search for Page or Report icon") icon, enter **GST Liability Adjustment** , and then choose the related link.</span></span>
  2. <span data-ttu-id="347bb-109">Select the following in the request page</span><span class="sxs-lookup"><span data-stu-id="347bb-109">Select the following in the request page</span></span>

      |<span data-ttu-id="347bb-110">Field Name</span><span class="sxs-lookup"><span data-stu-id="347bb-110">Field Name</span></span>|<span data-ttu-id="347bb-111">Description</span><span class="sxs-lookup"><span data-stu-id="347bb-111">Description</span></span>|
      |----------------------------------|---------------------------------------|  
      |<span data-ttu-id="347bb-112">**Adjustment Document No.**</span><span class="sxs-lookup"><span data-stu-id="347bb-112">**Adjustment Document No.**</span></span>|<span data-ttu-id="347bb-113">System will generate number from number series assigned in Purchases & Payable Setup</span><span class="sxs-lookup"><span data-stu-id="347bb-113">System will generate number from number series assigned in Purchases & Payable Setup</span></span>|
      |<span data-ttu-id="347bb-114">**GST Registration No.**</span><span class="sxs-lookup"><span data-stu-id="347bb-114">**GST Registration No.**</span></span>|<span data-ttu-id="347bb-115">System will list only transactions posted with selected GST Registration No.</span><span class="sxs-lookup"><span data-stu-id="347bb-115">System will list only transactions posted with selected GST Registration No.</span></span>|  
      |<span data-ttu-id="347bb-116">**Posting Date**</span><span class="sxs-lookup"><span data-stu-id="347bb-116">**Posting Date**</span></span>|<span data-ttu-id="347bb-117">Adjustment posting date</span><span class="sxs-lookup"><span data-stu-id="347bb-117">Adjustment posting date</span></span>|  
      |<span data-ttu-id="347bb-118">**Liability Date Formula**</span><span class="sxs-lookup"><span data-stu-id="347bb-118">**Liability Date Formula**</span></span>|<span data-ttu-id="347bb-119">Enter 0D, 30D or 60D.</span><span class="sxs-lookup"><span data-stu-id="347bb-119">Enter 0D, 30D or 60D.</span></span> <span data-ttu-id="347bb-120">For example, if 60D is mentioned, the system will reverse count 60 days from posting date for arriving Liability Filter Date</span><span class="sxs-lookup"><span data-stu-id="347bb-120">For example, if 60D is mentioned, the system will reverse count 60 days from posting date for arriving Liability Filter Date</span></span>|
      |<span data-ttu-id="347bb-121">**Liability Filter Date**</span><span class="sxs-lookup"><span data-stu-id="347bb-121">**Liability Filter Date**</span></span>|<span data-ttu-id="347bb-122">System will update automatically (Posting date – Liability Date Formula, Ex: 01-Jan-18- 60D= 02-Nov-17), System will consider all open Reverse Charge service invoices posted before date updated in this field.</span><span class="sxs-lookup"><span data-stu-id="347bb-122">System will update automatically (Posting date – Liability Date Formula, Ex: 01-Jan-18- 60D= 02-Nov-17), System will consider all open Reverse Charge service invoices posted before date updated in this field.</span></span> <span data-ttu-id="347bb-123">(Ex: 02-Nov-17)</span><span class="sxs-lookup"><span data-stu-id="347bb-123">(Ex: 02-Nov-17)</span></span>|
      |<span data-ttu-id="347bb-124">**Vendor No.**</span><span class="sxs-lookup"><span data-stu-id="347bb-124">**Vendor No.**</span></span>|<span data-ttu-id="347bb-125">System will list invoice from this vendor only</span><span class="sxs-lookup"><span data-stu-id="347bb-125">System will list invoice from this vendor only</span></span>|
     <span data-ttu-id="347bb-126">**Document No.**</span><span class="sxs-lookup"><span data-stu-id="347bb-126">**Document No.**</span></span>|<span data-ttu-id="347bb-127">System will verify only for this document</span><span class="sxs-lookup"><span data-stu-id="347bb-127">System will verify only for this document</span></span>|
      |<span data-ttu-id="347bb-128">**External Document No.**</span><span class="sxs-lookup"><span data-stu-id="347bb-128">**External Document No.**</span></span>|<span data-ttu-id="347bb-129">System will verify only for this document</span><span class="sxs-lookup"><span data-stu-id="347bb-129">System will verify only for this document</span></span>|
      |<span data-ttu-id="347bb-130">**Nature of Adjustment**</span><span class="sxs-lookup"><span data-stu-id="347bb-130">**Nature of Adjustment**</span></span>|<span data-ttu-id="347bb-131">User need to select the option, available options: Generate, Reverse</span><span class="sxs-lookup"><span data-stu-id="347bb-131">User need to select the option, available options: Generate, Reverse</span></span>|
    
<span data-ttu-id="347bb-132">For example, vendor issued invoice for INR 10000, in an Intra-State or Intra-Union Territory transaction, and GST 18% (9% CGST and 9% SGST), has to be charged.</span><span class="sxs-lookup"><span data-stu-id="347bb-132">For example, vendor issued invoice for INR 10000, in an Intra-State or Intra-Union Territory transaction, and GST 18% (9% CGST and 9% SGST), has to be charged.</span></span>

- <span data-ttu-id="347bb-133">GL Entries at the time of posting invoice where Input Tax Credit is available, will be as following:</span><span class="sxs-lookup"><span data-stu-id="347bb-133">GL Entries at the time of posting invoice where Input Tax Credit is available, will be as following:</span></span>

    |<span data-ttu-id="347bb-134">Particulars</span><span class="sxs-lookup"><span data-stu-id="347bb-134">Particulars</span></span>|<span data-ttu-id="347bb-135">Amount</span><span class="sxs-lookup"><span data-stu-id="347bb-135">Amount</span></span>|
    |----------------------------------|---------------------------------------|  
    |<span data-ttu-id="347bb-136">**Purchase Account**</span><span class="sxs-lookup"><span data-stu-id="347bb-136">**Purchase Account**</span></span>|<span data-ttu-id="347bb-137">10000</span><span class="sxs-lookup"><span data-stu-id="347bb-137">10000</span></span>|
    |<span data-ttu-id="347bb-138">**CGST Receivable (Interim) Account**</span><span class="sxs-lookup"><span data-stu-id="347bb-138">**CGST Receivable (Interim) Account**</span></span>|<span data-ttu-id="347bb-139">900</span><span class="sxs-lookup"><span data-stu-id="347bb-139">900</span></span>|
    |<span data-ttu-id="347bb-140">**SGST/UTGST Receivable (Interim) Account**</span><span class="sxs-lookup"><span data-stu-id="347bb-140">**SGST/UTGST Receivable (Interim) Account**</span></span>|<span data-ttu-id="347bb-141">900</span><span class="sxs-lookup"><span data-stu-id="347bb-141">900</span></span>|
    |<span data-ttu-id="347bb-142">**CGST Payable (Interim) Account**</span><span class="sxs-lookup"><span data-stu-id="347bb-142">**CGST Payable (Interim) Account**</span></span>|<span data-ttu-id="347bb-143">-900</span><span class="sxs-lookup"><span data-stu-id="347bb-143">-900</span></span>|
    |<span data-ttu-id="347bb-144">**SGST/UTGST Payable (Interim) Account**</span><span class="sxs-lookup"><span data-stu-id="347bb-144">**SGST/UTGST Payable (Interim) Account**</span></span>|<span data-ttu-id="347bb-145">-900</span><span class="sxs-lookup"><span data-stu-id="347bb-145">-900</span></span>|
    |<span data-ttu-id="347bb-146">**Vendor Account**</span><span class="sxs-lookup"><span data-stu-id="347bb-146">**Vendor Account**</span></span>|<span data-ttu-id="347bb-147">10000</span><span class="sxs-lookup"><span data-stu-id="347bb-147">10000</span></span>|

- <span data-ttu-id="347bb-148">GL Entries at the time of posting invoice where Input Tax Credit is not available, will be as following:</span><span class="sxs-lookup"><span data-stu-id="347bb-148">GL Entries at the time of posting invoice where Input Tax Credit is not available, will be as following:</span></span>

    |<span data-ttu-id="347bb-149">Particulars</span><span class="sxs-lookup"><span data-stu-id="347bb-149">Particulars</span></span>|<span data-ttu-id="347bb-150">Amount</span><span class="sxs-lookup"><span data-stu-id="347bb-150">Amount</span></span>|
    |----------------------------------|---------------------------------------|  
    |<span data-ttu-id="347bb-151">**Purchase Account**</span><span class="sxs-lookup"><span data-stu-id="347bb-151">**Purchase Account**</span></span>|<span data-ttu-id="347bb-152">11800</span><span class="sxs-lookup"><span data-stu-id="347bb-152">11800</span></span>|
    |<span data-ttu-id="347bb-153">**SGST Payable Acc(Interim)**</span><span class="sxs-lookup"><span data-stu-id="347bb-153">**SGST Payable Acc(Interim)**</span></span>|<span data-ttu-id="347bb-154">-900</span><span class="sxs-lookup"><span data-stu-id="347bb-154">-900</span></span>|
    |<span data-ttu-id="347bb-155">**CGST Payable Acc(Interim)**</span><span class="sxs-lookup"><span data-stu-id="347bb-155">**CGST Payable Acc(Interim)**</span></span>|<span data-ttu-id="347bb-156">-900</span><span class="sxs-lookup"><span data-stu-id="347bb-156">-900</span></span>|
    |<span data-ttu-id="347bb-157">**Vendor Account**</span><span class="sxs-lookup"><span data-stu-id="347bb-157">**Vendor Account**</span></span>|<span data-ttu-id="347bb-158">10000</span><span class="sxs-lookup"><span data-stu-id="347bb-158">10000</span></span>|


- <span data-ttu-id="347bb-159">GL Entries for Generating GST Liability and GST Credit where Input Tax Credit is available, will be as following:</span><span class="sxs-lookup"><span data-stu-id="347bb-159">GL Entries for Generating GST Liability and GST Credit where Input Tax Credit is available, will be as following:</span></span>
    
    |<span data-ttu-id="347bb-160">Particulars</span><span class="sxs-lookup"><span data-stu-id="347bb-160">Particulars</span></span>|<span data-ttu-id="347bb-161">Amount</span><span class="sxs-lookup"><span data-stu-id="347bb-161">Amount</span></span>|
    |----------------------------------|---------------------------------------|  
    |<span data-ttu-id="347bb-162">**CGST Receivable Account**</span><span class="sxs-lookup"><span data-stu-id="347bb-162">**CGST Receivable Account**</span></span>|<span data-ttu-id="347bb-163">900</span><span class="sxs-lookup"><span data-stu-id="347bb-163">900</span></span>|
    |<span data-ttu-id="347bb-164">**SGST/UTGST Receivable Account**</span><span class="sxs-lookup"><span data-stu-id="347bb-164">**SGST/UTGST Receivable Account**</span></span>|<span data-ttu-id="347bb-165">900</span><span class="sxs-lookup"><span data-stu-id="347bb-165">900</span></span>|
    |<span data-ttu-id="347bb-166">**CGST Receivable (Interim) Account**</span><span class="sxs-lookup"><span data-stu-id="347bb-166">**CGST Receivable (Interim) Account**</span></span>|<span data-ttu-id="347bb-167">-900</span><span class="sxs-lookup"><span data-stu-id="347bb-167">-900</span></span>|
    |<span data-ttu-id="347bb-168">**SGST/UTGST Receivable (Interim) Account**</span><span class="sxs-lookup"><span data-stu-id="347bb-168">**SGST/UTGST Receivable (Interim) Account**</span></span>|<span data-ttu-id="347bb-169">-900</span><span class="sxs-lookup"><span data-stu-id="347bb-169">-900</span></span>|
    |<span data-ttu-id="347bb-170">**CGST Payable (Interim) Account**</span><span class="sxs-lookup"><span data-stu-id="347bb-170">**CGST Payable (Interim) Account**</span></span>|<span data-ttu-id="347bb-171">900</span><span class="sxs-lookup"><span data-stu-id="347bb-171">900</span></span>|
    |<span data-ttu-id="347bb-172">**SGST/UTGST Payable (Interim) Account**</span><span class="sxs-lookup"><span data-stu-id="347bb-172">**SGST/UTGST Payable (Interim) Account**</span></span>|<span data-ttu-id="347bb-173">900</span><span class="sxs-lookup"><span data-stu-id="347bb-173">900</span></span>|
    |<span data-ttu-id="347bb-174">**CGST Payable Account**</span><span class="sxs-lookup"><span data-stu-id="347bb-174">**CGST Payable Account**</span></span>|<span data-ttu-id="347bb-175">-900</span><span class="sxs-lookup"><span data-stu-id="347bb-175">-900</span></span>|
    |<span data-ttu-id="347bb-176">**SGST/UTGST Payable Account**</span><span class="sxs-lookup"><span data-stu-id="347bb-176">**SGST/UTGST Payable Account**</span></span>|<span data-ttu-id="347bb-177">-900</span><span class="sxs-lookup"><span data-stu-id="347bb-177">-900</span></span>|

- <span data-ttu-id="347bb-178">GL Entries for Generating GST Liability and GST Credit where Input Tax Credit is not available, will be as following:</span><span class="sxs-lookup"><span data-stu-id="347bb-178">GL Entries for Generating GST Liability and GST Credit where Input Tax Credit is not available, will be as following:</span></span>
    
    |<span data-ttu-id="347bb-179">Particulars</span><span class="sxs-lookup"><span data-stu-id="347bb-179">Particulars</span></span>|<span data-ttu-id="347bb-180">Amount</span><span class="sxs-lookup"><span data-stu-id="347bb-180">Amount</span></span>|
    |----------------------------------|---------------------------------------|  
    |<span data-ttu-id="347bb-181">**CGST Payable (Interim) Account**</span><span class="sxs-lookup"><span data-stu-id="347bb-181">**CGST Payable (Interim) Account**</span></span>|<span data-ttu-id="347bb-182">900</span><span class="sxs-lookup"><span data-stu-id="347bb-182">900</span></span>|
    |<span data-ttu-id="347bb-183">**SGST/UTGST Payable (Interim) Account**</span><span class="sxs-lookup"><span data-stu-id="347bb-183">**SGST/UTGST Payable (Interim) Account**</span></span>|<span data-ttu-id="347bb-184">900</span><span class="sxs-lookup"><span data-stu-id="347bb-184">900</span></span>|
    |<span data-ttu-id="347bb-185">**CGST Payable Account**</span><span class="sxs-lookup"><span data-stu-id="347bb-185">**CGST Payable Account**</span></span>|<span data-ttu-id="347bb-186">-900</span><span class="sxs-lookup"><span data-stu-id="347bb-186">-900</span></span>|
    |<span data-ttu-id="347bb-187">**SGST/UTGST Payable Account**</span><span class="sxs-lookup"><span data-stu-id="347bb-187">**SGST/UTGST Payable Account**</span></span>|<span data-ttu-id="347bb-188">-900</span><span class="sxs-lookup"><span data-stu-id="347bb-188">-900</span></span>|

- <span data-ttu-id="347bb-189">GL Entries for Reversing GST Liability and GST Credit where Input Tax Credit is available, will be as following:</span><span class="sxs-lookup"><span data-stu-id="347bb-189">GL Entries for Reversing GST Liability and GST Credit where Input Tax Credit is available, will be as following:</span></span>
    
    |<span data-ttu-id="347bb-190">Particulars</span><span class="sxs-lookup"><span data-stu-id="347bb-190">Particulars</span></span>|<span data-ttu-id="347bb-191">Amount</span><span class="sxs-lookup"><span data-stu-id="347bb-191">Amount</span></span>|
    |----------------------------------|---------------------------------------|  
    |<span data-ttu-id="347bb-192">**CGST Receivable Account**</span><span class="sxs-lookup"><span data-stu-id="347bb-192">**CGST Receivable Account**</span></span>|<span data-ttu-id="347bb-193">-900</span><span class="sxs-lookup"><span data-stu-id="347bb-193">-900</span></span>|
    |<span data-ttu-id="347bb-194">**SGST/UTGST Receivable Account**</span><span class="sxs-lookup"><span data-stu-id="347bb-194">**SGST/UTGST Receivable Account**</span></span>|<span data-ttu-id="347bb-195">-900</span><span class="sxs-lookup"><span data-stu-id="347bb-195">-900</span></span>|
    |<span data-ttu-id="347bb-196">**CGST Receivable (Interim) Account**</span><span class="sxs-lookup"><span data-stu-id="347bb-196">**CGST Receivable (Interim) Account**</span></span>|<span data-ttu-id="347bb-197">900</span><span class="sxs-lookup"><span data-stu-id="347bb-197">900</span></span>|
    |<span data-ttu-id="347bb-198">**SGST/UTGST Receivable (Interim) Account**</span><span class="sxs-lookup"><span data-stu-id="347bb-198">**SGST/UTGST Receivable (Interim) Account**</span></span>|<span data-ttu-id="347bb-199">900</span><span class="sxs-lookup"><span data-stu-id="347bb-199">900</span></span>|
    |<span data-ttu-id="347bb-200">**CGST Payable (Interim) Account**</span><span class="sxs-lookup"><span data-stu-id="347bb-200">**CGST Payable (Interim) Account**</span></span>|<span data-ttu-id="347bb-201">-900</span><span class="sxs-lookup"><span data-stu-id="347bb-201">-900</span></span>|
    |<span data-ttu-id="347bb-202">**SGST/UTGST Payable (Interim) Account**</span><span class="sxs-lookup"><span data-stu-id="347bb-202">**SGST/UTGST Payable (Interim) Account**</span></span>|<span data-ttu-id="347bb-203">-900</span><span class="sxs-lookup"><span data-stu-id="347bb-203">-900</span></span>|
    |<span data-ttu-id="347bb-204">**CGST Payable Account**</span><span class="sxs-lookup"><span data-stu-id="347bb-204">**CGST Payable Account**</span></span>|<span data-ttu-id="347bb-205">900</span><span class="sxs-lookup"><span data-stu-id="347bb-205">900</span></span>|
    |<span data-ttu-id="347bb-206">**SGST/UTGST Payable Account**</span><span class="sxs-lookup"><span data-stu-id="347bb-206">**SGST/UTGST Payable Account**</span></span>|<span data-ttu-id="347bb-207">900</span><span class="sxs-lookup"><span data-stu-id="347bb-207">900</span></span>|

- <span data-ttu-id="347bb-208">GL Entries for Reversing GST Liability and GST Credit where Input Tax Credit is not available, will be as following:</span><span class="sxs-lookup"><span data-stu-id="347bb-208">GL Entries for Reversing GST Liability and GST Credit where Input Tax Credit is not available, will be as following:</span></span>
    
    |<span data-ttu-id="347bb-209">Particulars</span><span class="sxs-lookup"><span data-stu-id="347bb-209">Particulars</span></span>|<span data-ttu-id="347bb-210">Amount</span><span class="sxs-lookup"><span data-stu-id="347bb-210">Amount</span></span>|
    |----------------------------------|---------------------------------------|  
    |<span data-ttu-id="347bb-211">**CGST Payable (Interim) Account**</span><span class="sxs-lookup"><span data-stu-id="347bb-211">**CGST Payable (Interim) Account**</span></span>|<span data-ttu-id="347bb-212">-900</span><span class="sxs-lookup"><span data-stu-id="347bb-212">-900</span></span>|
    |<span data-ttu-id="347bb-213">**SGST/UTGST Payable (Interim) Account**</span><span class="sxs-lookup"><span data-stu-id="347bb-213">**SGST/UTGST Payable (Interim) Account**</span></span>|<span data-ttu-id="347bb-214">-900</span><span class="sxs-lookup"><span data-stu-id="347bb-214">-900</span></span>|
    |<span data-ttu-id="347bb-215">**CGST Payable Account**</span><span class="sxs-lookup"><span data-stu-id="347bb-215">**CGST Payable Account**</span></span>|<span data-ttu-id="347bb-216">900</span><span class="sxs-lookup"><span data-stu-id="347bb-216">900</span></span>|
    |<span data-ttu-id="347bb-217">**SGST/UTGST Payable Account**</span><span class="sxs-lookup"><span data-stu-id="347bb-217">**SGST/UTGST Payable Account**</span></span>|<span data-ttu-id="347bb-218">900</span><span class="sxs-lookup"><span data-stu-id="347bb-218">900</span></span>|

> [!TIP]
> <span data-ttu-id="347bb-219">In case of Inter-state Reverse Charge Service purchase, IGST Liability and IGST Credit will get generated.</span><span class="sxs-lookup"><span data-stu-id="347bb-219">In case of Inter-state Reverse Charge Service purchase, IGST Liability and IGST Credit will get generated.</span></span>





































