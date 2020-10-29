---
title: GST on Advance Payment application with Purchase Invoice
description: GST on Advance Payment application with Purchase Invoice
author: v-debapd
ms.service: dynamics365-business-central
ms.topic: article
ms.devlang: na
ms.tgt_pltfrm: na
ms.workload: na
ms.search.keywords: India, local, IN, English
ms.date: 10/01/2020
ms.author: v-debapd
ms.openlocfilehash: 5e7a69730cfe83fb24c3a2a328b6b7b957f50e30
ms.sourcegitcommit: ddbb5cede750df1baba4b3eab8fbed6744b5b9d6
ms.translationtype: HT
ms.contentlocale: en-IN
ms.lasthandoff: 10/01/2020
ms.locfileid: "3948656"
---
# <a name="gst-on-advance-payment-or-normal-payment-application-with-purchase-invoice"></a><span data-ttu-id="9ab8e-103">GST on Advance Payment or Normal Payment Application with Purchase Invoice</span><span class="sxs-lookup"><span data-stu-id="9ab8e-103">GST on Advance Payment or Normal Payment Application with Purchase Invoice</span></span>

[!INCLUDE[vnext_preview](../../includes/vnext_preview.md)]

<span data-ttu-id="9ab8e-104">An advance payment made to vendor for a transaction that is subject to reverse charge is to be reported in GSTR-2.</span><span class="sxs-lookup"><span data-stu-id="9ab8e-104">An advance payment made to vendor for a transaction that is subject to reverse charge is to be reported in GSTR-2.</span></span> 

<span data-ttu-id="9ab8e-105">If the advance payment is applied to the invoice in the same month, then such applications need not be disclosed in GSTR-2.</span><span class="sxs-lookup"><span data-stu-id="9ab8e-105">If the advance payment is applied to the invoice in the same month, then such applications need not be disclosed in GSTR-2.</span></span> <span data-ttu-id="9ab8e-106">However, if advance payment is paid in a month and is applied to invoice in the subsequent month, then this application is to be reported in GSTR-2.</span><span class="sxs-lookup"><span data-stu-id="9ab8e-106">However, if advance payment is paid in a month and is applied to invoice in the subsequent month, then this application is to be reported in GSTR-2.</span></span> 

<span data-ttu-id="9ab8e-107">Process for application and un-application of payment and invoice has been explained in this document</span><span class="sxs-lookup"><span data-stu-id="9ab8e-107">Process for application and un-application of payment and invoice has been explained in this document</span></span>


## <a name="gst-on-advance-payment-and-application-with-purchase-invoice"></a><span data-ttu-id="9ab8e-108">GST on advance payment and application with purchase invoice</span><span class="sxs-lookup"><span data-stu-id="9ab8e-108">GST on advance payment and application with purchase invoice</span></span>

 <span data-ttu-id="9ab8e-109">GST is liable at the time of advance payment to vendor, for example, service amount is INR 20000 and advance payment made to vendor for INR 10000 and 18% GST (i.e. 9% CGST and 9% SGST/UTGST) has to be charged.</span><span class="sxs-lookup"><span data-stu-id="9ab8e-109">GST is liable at the time of advance payment to vendor, for example, service amount is INR 20000 and advance payment made to vendor for INR 10000 and 18% GST (i.e. 9% CGST and 9% SGST/UTGST) has to be charged.</span></span> <span data-ttu-id="9ab8e-110">Taxpayer paying advance is not eligible to claim ITC on advance paid.</span><span class="sxs-lookup"><span data-stu-id="9ab8e-110">Taxpayer paying advance is not eligible to claim ITC on advance paid.</span></span> <span data-ttu-id="9ab8e-111">The taxpayer can claim ITC on advance paid only on receipt of services.</span><span class="sxs-lookup"><span data-stu-id="9ab8e-111">The taxpayer can claim ITC on advance paid only on receipt of services.</span></span>

- <span data-ttu-id="9ab8e-112">GST calculation for Intra-State or Intra-Union Territory transactions will appear in the Fact Box, as following:</span><span class="sxs-lookup"><span data-stu-id="9ab8e-112">GST calculation for Intra-State or Intra-Union Territory transactions will appear in the Fact Box, as following:</span></span>
    
    |<span data-ttu-id="9ab8e-113">Component</span><span class="sxs-lookup"><span data-stu-id="9ab8e-113">Component</span></span>|<span data-ttu-id="9ab8e-114">Amount</span><span class="sxs-lookup"><span data-stu-id="9ab8e-114">Amount</span></span>|
    |----------------------------------|---------------------------------------|  
    |<span data-ttu-id="9ab8e-115">**GST Base Amount**</span><span class="sxs-lookup"><span data-stu-id="9ab8e-115">**GST Base Amount**</span></span>|<span data-ttu-id="9ab8e-116">10,000</span><span class="sxs-lookup"><span data-stu-id="9ab8e-116">10,000</span></span>|  
    |<span data-ttu-id="9ab8e-117">**CGST**</span><span class="sxs-lookup"><span data-stu-id="9ab8e-117">**CGST**</span></span>|<span data-ttu-id="9ab8e-118">900</span><span class="sxs-lookup"><span data-stu-id="9ab8e-118">900</span></span>|  
    |<span data-ttu-id="9ab8e-119">**SGST**</span><span class="sxs-lookup"><span data-stu-id="9ab8e-119">**SGST**</span></span>|<span data-ttu-id="9ab8e-120">900</span><span class="sxs-lookup"><span data-stu-id="9ab8e-120">900</span></span>| 

- <span data-ttu-id="9ab8e-121">GL Entries for advance payment made to vendor, will be as following:</span><span class="sxs-lookup"><span data-stu-id="9ab8e-121">GL Entries for advance payment made to vendor, will be as following:</span></span>

    |<span data-ttu-id="9ab8e-122">Particulars</span><span class="sxs-lookup"><span data-stu-id="9ab8e-122">Particulars</span></span>|<span data-ttu-id="9ab8e-123">Amount</span><span class="sxs-lookup"><span data-stu-id="9ab8e-123">Amount</span></span>|
    |----------------------------------|---------------------------------------|  
    |<span data-ttu-id="9ab8e-124">**Vendor Account**</span><span class="sxs-lookup"><span data-stu-id="9ab8e-124">**Vendor Account**</span></span>|<span data-ttu-id="9ab8e-125">10,000</span><span class="sxs-lookup"><span data-stu-id="9ab8e-125">10,000</span></span>|  
    |<span data-ttu-id="9ab8e-126">**SGST/UTGST Receivable (Interim) Account**</span><span class="sxs-lookup"><span data-stu-id="9ab8e-126">**SGST/UTGST Receivable (Interim) Account**</span></span>|<span data-ttu-id="9ab8e-127">900</span><span class="sxs-lookup"><span data-stu-id="9ab8e-127">900</span></span>|  
    |<span data-ttu-id="9ab8e-128">**CGST Receivable (Interim) Account**</span><span class="sxs-lookup"><span data-stu-id="9ab8e-128">**CGST Receivable (Interim) Account**</span></span>|<span data-ttu-id="9ab8e-129">900</span><span class="sxs-lookup"><span data-stu-id="9ab8e-129">900</span></span>| 
    |<span data-ttu-id="9ab8e-130">**SGST/UTGST Payable Account**</span><span class="sxs-lookup"><span data-stu-id="9ab8e-130">**SGST/UTGST Payable Account**</span></span>|<span data-ttu-id="9ab8e-131">-900</span><span class="sxs-lookup"><span data-stu-id="9ab8e-131">-900</span></span>| 
    |<span data-ttu-id="9ab8e-132">**CGST Payable Account**</span><span class="sxs-lookup"><span data-stu-id="9ab8e-132">**CGST Payable Account**</span></span>|<span data-ttu-id="9ab8e-133">-900</span><span class="sxs-lookup"><span data-stu-id="9ab8e-133">-900</span></span>| 
    |<span data-ttu-id="9ab8e-134">**Bank Account**</span><span class="sxs-lookup"><span data-stu-id="9ab8e-134">**Bank Account**</span></span>|<span data-ttu-id="9ab8e-135">-10000</span><span class="sxs-lookup"><span data-stu-id="9ab8e-135">-10000</span></span>| 


<span data-ttu-id="9ab8e-136">Later invoice for service purchase issued by vendor for INR 20,000 and 18% GST (i.e. 9% CGST and 9% SGST/UTGST), will be charged.</span><span class="sxs-lookup"><span data-stu-id="9ab8e-136">Later invoice for service purchase issued by vendor for INR 20,000 and 18% GST (i.e. 9% CGST and 9% SGST/UTGST), will be charged.</span></span>

- <span data-ttu-id="9ab8e-137">GST Calculation will appear in the Fact Box, as following:</span><span class="sxs-lookup"><span data-stu-id="9ab8e-137">GST Calculation will appear in the Fact Box, as following:</span></span>

    |<span data-ttu-id="9ab8e-138">Component</span><span class="sxs-lookup"><span data-stu-id="9ab8e-138">Component</span></span>|<span data-ttu-id="9ab8e-139">Amount</span><span class="sxs-lookup"><span data-stu-id="9ab8e-139">Amount</span></span>|
    |----------------------------------|---------------------------------------|  
    |<span data-ttu-id="9ab8e-140">**GST Base Amount**</span><span class="sxs-lookup"><span data-stu-id="9ab8e-140">**GST Base Amount**</span></span>|<span data-ttu-id="9ab8e-141">20000</span><span class="sxs-lookup"><span data-stu-id="9ab8e-141">20000</span></span>|  
    |<span data-ttu-id="9ab8e-142">**CGST**</span><span class="sxs-lookup"><span data-stu-id="9ab8e-142">**CGST**</span></span>|<span data-ttu-id="9ab8e-143">1800</span><span class="sxs-lookup"><span data-stu-id="9ab8e-143">1800</span></span>|  
    |<span data-ttu-id="9ab8e-144">**SGST**</span><span class="sxs-lookup"><span data-stu-id="9ab8e-144">**SGST**</span></span>|<span data-ttu-id="9ab8e-145">1800</span><span class="sxs-lookup"><span data-stu-id="9ab8e-145">1800</span></span>| 


- <span data-ttu-id="9ab8e-146">GL Entries for application of an advance payment with an invoice for services, where input tax credit is available:</span><span class="sxs-lookup"><span data-stu-id="9ab8e-146">GL Entries for application of an advance payment with an invoice for services, where input tax credit is available:</span></span>

    |<span data-ttu-id="9ab8e-147">Particulars</span><span class="sxs-lookup"><span data-stu-id="9ab8e-147">Particulars</span></span>|<span data-ttu-id="9ab8e-148">Amount</span><span class="sxs-lookup"><span data-stu-id="9ab8e-148">Amount</span></span>|
    |----------------------------------|---------------------------------------|  
    |<span data-ttu-id="9ab8e-149">**Service Account**</span><span class="sxs-lookup"><span data-stu-id="9ab8e-149">**Service Account**</span></span>|<span data-ttu-id="9ab8e-150">20000</span><span class="sxs-lookup"><span data-stu-id="9ab8e-150">20000</span></span>|  
    |<span data-ttu-id="9ab8e-151">**CGST Receivable (Interim) Account**</span><span class="sxs-lookup"><span data-stu-id="9ab8e-151">**CGST Receivable (Interim) Account**</span></span>|<span data-ttu-id="9ab8e-152">1800</span><span class="sxs-lookup"><span data-stu-id="9ab8e-152">1800</span></span>| 
    |<span data-ttu-id="9ab8e-153">**SGST/UTGST Receivable (Interim) Account**</span><span class="sxs-lookup"><span data-stu-id="9ab8e-153">**SGST/UTGST Receivable (Interim) Account**</span></span>|<span data-ttu-id="9ab8e-154">1800</span><span class="sxs-lookup"><span data-stu-id="9ab8e-154">1800</span></span>|
    |<span data-ttu-id="9ab8e-155">**CGST Payable (Interim) Account**</span><span class="sxs-lookup"><span data-stu-id="9ab8e-155">**CGST Payable (Interim) Account**</span></span>|<span data-ttu-id="9ab8e-156">-1800</span><span class="sxs-lookup"><span data-stu-id="9ab8e-156">-1800</span></span>|
    |<span data-ttu-id="9ab8e-157">**SGST/UTGST Payable (Interim) Account**</span><span class="sxs-lookup"><span data-stu-id="9ab8e-157">**SGST/UTGST Payable (Interim) Account**</span></span>|<span data-ttu-id="9ab8e-158">-1800</span><span class="sxs-lookup"><span data-stu-id="9ab8e-158">-1800</span></span>| 
    |<span data-ttu-id="9ab8e-159">**Vendor Account**</span><span class="sxs-lookup"><span data-stu-id="9ab8e-159">**Vendor Account**</span></span>|<span data-ttu-id="9ab8e-160">-20000</span><span class="sxs-lookup"><span data-stu-id="9ab8e-160">-20000</span></span>| 
    |<span data-ttu-id="9ab8e-161">**CGST Payable (Interim) Account**</span><span class="sxs-lookup"><span data-stu-id="9ab8e-161">**CGST Payable (Interim) Account**</span></span>|<span data-ttu-id="9ab8e-162">900</span><span class="sxs-lookup"><span data-stu-id="9ab8e-162">900</span></span>|   
    |<span data-ttu-id="9ab8e-163">**SGST/UTGST Payable (Interim) Account**</span><span class="sxs-lookup"><span data-stu-id="9ab8e-163">**SGST/UTGST Payable (Interim) Account**</span></span>|<span data-ttu-id="9ab8e-164">900</span><span class="sxs-lookup"><span data-stu-id="9ab8e-164">900</span></span>|
    |<span data-ttu-id="9ab8e-165">**CGST Receivable Account**</span><span class="sxs-lookup"><span data-stu-id="9ab8e-165">**CGST Receivable Account**</span></span>|<span data-ttu-id="9ab8e-166">900</span><span class="sxs-lookup"><span data-stu-id="9ab8e-166">900</span></span>|
    |<span data-ttu-id="9ab8e-167">**SGST/UTGST Receivable  Account**</span><span class="sxs-lookup"><span data-stu-id="9ab8e-167">**SGST/UTGST Receivable  Account**</span></span>|<span data-ttu-id="9ab8e-168">900</span><span class="sxs-lookup"><span data-stu-id="9ab8e-168">900</span></span>|
    |<span data-ttu-id="9ab8e-169">**CGST Receivable (Interim) Account**</span><span class="sxs-lookup"><span data-stu-id="9ab8e-169">**CGST Receivable (Interim) Account**</span></span>|<span data-ttu-id="9ab8e-170">-1800</span><span class="sxs-lookup"><span data-stu-id="9ab8e-170">-1800</span></span>|
    |<span data-ttu-id="9ab8e-171">**SGST/UTGST Receivable (Interim) Account**</span><span class="sxs-lookup"><span data-stu-id="9ab8e-171">**SGST/UTGST Receivable (Interim) Account**</span></span>|<span data-ttu-id="9ab8e-172">-1800</span><span class="sxs-lookup"><span data-stu-id="9ab8e-172">-1800</span></span>|


- <span data-ttu-id="9ab8e-173">GL Entries for application of an advance payment with an invoice for services, where input tax credit is not available:</span><span class="sxs-lookup"><span data-stu-id="9ab8e-173">GL Entries for application of an advance payment with an invoice for services, where input tax credit is not available:</span></span>

    |<span data-ttu-id="9ab8e-174">Particulars</span><span class="sxs-lookup"><span data-stu-id="9ab8e-174">Particulars</span></span>|<span data-ttu-id="9ab8e-175">Amount</span><span class="sxs-lookup"><span data-stu-id="9ab8e-175">Amount</span></span>|
    |----------------------------------|---------------------------------------|  
    |<span data-ttu-id="9ab8e-176">**Service Account**</span><span class="sxs-lookup"><span data-stu-id="9ab8e-176">**Service Account**</span></span>|<span data-ttu-id="9ab8e-177">23600</span><span class="sxs-lookup"><span data-stu-id="9ab8e-177">23600</span></span>|  
    |<span data-ttu-id="9ab8e-178">**CGST Payable (Interim) Account**</span><span class="sxs-lookup"><span data-stu-id="9ab8e-178">**CGST Payable (Interim) Account**</span></span>|<span data-ttu-id="9ab8e-179">-1800</span><span class="sxs-lookup"><span data-stu-id="9ab8e-179">-1800</span></span>| 
    |<span data-ttu-id="9ab8e-180">**SGST/UTGST Payable (Interim) Account**</span><span class="sxs-lookup"><span data-stu-id="9ab8e-180">**SGST/UTGST Payable (Interim) Account**</span></span>|<span data-ttu-id="9ab8e-181">-1800</span><span class="sxs-lookup"><span data-stu-id="9ab8e-181">-1800</span></span>|
    |<span data-ttu-id="9ab8e-182">**Vendor Account**</span><span class="sxs-lookup"><span data-stu-id="9ab8e-182">**Vendor Account**</span></span>|<span data-ttu-id="9ab8e-183">-20000</span><span class="sxs-lookup"><span data-stu-id="9ab8e-183">-20000</span></span>|
    |<span data-ttu-id="9ab8e-184">**CGST Payable (Interim) Account**</span><span class="sxs-lookup"><span data-stu-id="9ab8e-184">**CGST Payable (Interim) Account**</span></span>|<span data-ttu-id="9ab8e-185">900</span><span class="sxs-lookup"><span data-stu-id="9ab8e-185">900</span></span>|
    |<span data-ttu-id="9ab8e-186">**SGST/UTGST Payable (Interim) Account**</span><span class="sxs-lookup"><span data-stu-id="9ab8e-186">**SGST/UTGST Payable (Interim) Account**</span></span>|<span data-ttu-id="9ab8e-187">900</span><span class="sxs-lookup"><span data-stu-id="9ab8e-187">900</span></span>|
    <span data-ttu-id="9ab8e-188">**CGST Receivable (Interim) Account**</span><span class="sxs-lookup"><span data-stu-id="9ab8e-188">**CGST Receivable (Interim) Account**</span></span>|<span data-ttu-id="9ab8e-189">-900</span><span class="sxs-lookup"><span data-stu-id="9ab8e-189">-900</span></span>|
    |<span data-ttu-id="9ab8e-190">**SGST/UTGST Receivable (Interim) Account**</span><span class="sxs-lookup"><span data-stu-id="9ab8e-190">**SGST/UTGST Receivable (Interim) Account**</span></span>|<span data-ttu-id="9ab8e-191">-900</span><span class="sxs-lookup"><span data-stu-id="9ab8e-191">-900</span></span>|

<span data-ttu-id="9ab8e-192">If this is found that the payment and invoice was wrongly applied and the application needs to be reversed, in such a case un-apply functionality can be used.</span><span class="sxs-lookup"><span data-stu-id="9ab8e-192">If this is found that the payment and invoice was wrongly applied and the application needs to be reversed, in such a case un-apply functionality can be used.</span></span> <span data-ttu-id="9ab8e-193">Un-application entries are same for both online application and offline application.</span><span class="sxs-lookup"><span data-stu-id="9ab8e-193">Un-application entries are same for both online application and offline application.</span></span>

- <span data-ttu-id="9ab8e-194">GL Entries for un-application of an advance payment with an invoice for services, where input tax credit is available:</span><span class="sxs-lookup"><span data-stu-id="9ab8e-194">GL Entries for un-application of an advance payment with an invoice for services, where input tax credit is available:</span></span>
    
    |<span data-ttu-id="9ab8e-195">Particulars</span><span class="sxs-lookup"><span data-stu-id="9ab8e-195">Particulars</span></span>|<span data-ttu-id="9ab8e-196">Amount</span><span class="sxs-lookup"><span data-stu-id="9ab8e-196">Amount</span></span>|
    |----------------------------------|---------------------------------------|  
    |<span data-ttu-id="9ab8e-197">**CGST Receivable (Interim) Account**</span><span class="sxs-lookup"><span data-stu-id="9ab8e-197">**CGST Receivable (Interim) Account**</span></span>|<span data-ttu-id="9ab8e-198">1800</span><span class="sxs-lookup"><span data-stu-id="9ab8e-198">1800</span></span>| 
    |<span data-ttu-id="9ab8e-199">**SGST/UTGST Receivable (Interim) Account**</span><span class="sxs-lookup"><span data-stu-id="9ab8e-199">**SGST/UTGST Receivable (Interim) Account**</span></span>|<span data-ttu-id="9ab8e-200">1800</span><span class="sxs-lookup"><span data-stu-id="9ab8e-200">1800</span></span>| 
    |<span data-ttu-id="9ab8e-201">**CGST Receivable Account**</span><span class="sxs-lookup"><span data-stu-id="9ab8e-201">**CGST Receivable Account**</span></span>|<span data-ttu-id="9ab8e-202">-900</span><span class="sxs-lookup"><span data-stu-id="9ab8e-202">-900</span></span>|
    |<span data-ttu-id="9ab8e-203">**SGST/UTGST Receivable Account**</span><span class="sxs-lookup"><span data-stu-id="9ab8e-203">**SGST/UTGST Receivable Account**</span></span>|<span data-ttu-id="9ab8e-204">-900</span><span class="sxs-lookup"><span data-stu-id="9ab8e-204">-900</span></span>|
    |<span data-ttu-id="9ab8e-205">**CGST Payable (Interim) Account**</span><span class="sxs-lookup"><span data-stu-id="9ab8e-205">**CGST Payable (Interim) Account**</span></span>|<span data-ttu-id="9ab8e-206">-900</span><span class="sxs-lookup"><span data-stu-id="9ab8e-206">-900</span></span>| 
    |<span data-ttu-id="9ab8e-207">**SGST/UTGST Payable (Interim) Account**</span><span class="sxs-lookup"><span data-stu-id="9ab8e-207">**SGST/UTGST Payable (Interim) Account**</span></span>|<span data-ttu-id="9ab8e-208">-900</span><span class="sxs-lookup"><span data-stu-id="9ab8e-208">-900</span></span>|
            
- <span data-ttu-id="9ab8e-209">GL Entries for un-application of an advance payment with an invoice of services, where input tax credit is not available:</span><span class="sxs-lookup"><span data-stu-id="9ab8e-209">GL Entries for un-application of an advance payment with an invoice of services, where input tax credit is not available:</span></span>
    
    |<span data-ttu-id="9ab8e-210">Particulars</span><span class="sxs-lookup"><span data-stu-id="9ab8e-210">Particulars</span></span>|<span data-ttu-id="9ab8e-211">Amount</span><span class="sxs-lookup"><span data-stu-id="9ab8e-211">Amount</span></span>|
    |----------------------------------|---------------------------------------|  
    |<span data-ttu-id="9ab8e-212">**CGST Receivable (Interim) Account**</span><span class="sxs-lookup"><span data-stu-id="9ab8e-212">**CGST Receivable (Interim) Account**</span></span>|<span data-ttu-id="9ab8e-213">900</span><span class="sxs-lookup"><span data-stu-id="9ab8e-213">900</span></span>| 
    |<span data-ttu-id="9ab8e-214">**SGST/UTGST Receivable (Interim) Account**</span><span class="sxs-lookup"><span data-stu-id="9ab8e-214">**SGST/UTGST Receivable (Interim) Account**</span></span>|<span data-ttu-id="9ab8e-215">900</span><span class="sxs-lookup"><span data-stu-id="9ab8e-215">900</span></span>| 
    |<span data-ttu-id="9ab8e-216">**CGST Payable (Interim) Account**</span><span class="sxs-lookup"><span data-stu-id="9ab8e-216">**CGST Payable (Interim) Account**</span></span>|<span data-ttu-id="9ab8e-217">-900</span><span class="sxs-lookup"><span data-stu-id="9ab8e-217">-900</span></span>| 
    |<span data-ttu-id="9ab8e-218">**SGST/UTGST Payable (Interim) Account**</span><span class="sxs-lookup"><span data-stu-id="9ab8e-218">**SGST/UTGST Payable (Interim) Account**</span></span>|<span data-ttu-id="9ab8e-219">-900</span><span class="sxs-lookup"><span data-stu-id="9ab8e-219">-900</span></span>|

## <a name="normal-payment-to-vendor-and-application-with-purchase-invoice"></a><span data-ttu-id="9ab8e-220">Normal Payment to vendor and application with purchase invoice</span><span class="sxs-lookup"><span data-stu-id="9ab8e-220">Normal Payment to vendor and application with purchase invoice</span></span>

<span data-ttu-id="9ab8e-221">For unregistered, import vendor and reverse charge purchase of service from registered vendor, user has to post a separate invoice for goods and services in the system.</span><span class="sxs-lookup"><span data-stu-id="9ab8e-221">For unregistered, import vendor and reverse charge purchase of service from registered vendor, user has to post a separate invoice for goods and services in the system.</span></span> <span data-ttu-id="9ab8e-222">No GST calculation is done at the time of application.</span><span class="sxs-lookup"><span data-stu-id="9ab8e-222">No GST calculation is done at the time of application.</span></span>
<span data-ttu-id="9ab8e-223">In ordinary course, when a normal payment is applied to the invoice, system proportionately posts the liability from Payable Interim Account to Payable Account and credit (if applicable) from Receivable Interim Account to Receivable Account.</span><span class="sxs-lookup"><span data-stu-id="9ab8e-223">In ordinary course, when a normal payment is applied to the invoice, system proportionately posts the liability from Payable Interim Account to Payable Account and credit (if applicable) from Receivable Interim Account to Receivable Account.</span></span> 

<span data-ttu-id="9ab8e-224">For example, Purchase Invoice for service purchase issued to vendor for INR 60,000 and 18% GST (i.e. 9% CGST and 9% SGST/UTGST), has to be charged.</span><span class="sxs-lookup"><span data-stu-id="9ab8e-224">For example, Purchase Invoice for service purchase issued to vendor for INR 60,000 and 18% GST (i.e. 9% CGST and 9% SGST/UTGST), has to be charged.</span></span> <span data-ttu-id="9ab8e-225">Later a payment of INR 10,000 has been made to vendor against to the purchase invoice, which doesn't have any GST impact.</span><span class="sxs-lookup"><span data-stu-id="9ab8e-225">Later a payment of INR 10,000 has been made to vendor against to the purchase invoice, which doesn't have any GST impact.</span></span>

- <span data-ttu-id="9ab8e-226">GST Calculation will appear in the Fact Box, as following:</span><span class="sxs-lookup"><span data-stu-id="9ab8e-226">GST Calculation will appear in the Fact Box, as following:</span></span>
    
    |<span data-ttu-id="9ab8e-227">Component</span><span class="sxs-lookup"><span data-stu-id="9ab8e-227">Component</span></span>|<span data-ttu-id="9ab8e-228">Amount</span><span class="sxs-lookup"><span data-stu-id="9ab8e-228">Amount</span></span>|
    |----------------------------------|---------------------------------------|  
    |<span data-ttu-id="9ab8e-229">**Total GST Transactional Value**</span><span class="sxs-lookup"><span data-stu-id="9ab8e-229">**Total GST Transactional Value**</span></span>|<span data-ttu-id="9ab8e-230">60000</span><span class="sxs-lookup"><span data-stu-id="9ab8e-230">60000</span></span>| 
    |<span data-ttu-id="9ab8e-231">**Invoice Total CGST Amount**</span><span class="sxs-lookup"><span data-stu-id="9ab8e-231">**Invoice Total CGST Amount**</span></span>|<span data-ttu-id="9ab8e-232">5,400 (60000\*9%)</span><span class="sxs-lookup"><span data-stu-id="9ab8e-232">5,400 (60000\*9%)</span></span>| 
    |<span data-ttu-id="9ab8e-233">**Invoice Total SGST/UTGST Amount**</span><span class="sxs-lookup"><span data-stu-id="9ab8e-233">**Invoice Total SGST/UTGST Amount**</span></span>|<span data-ttu-id="9ab8e-234">5,400 (60,000\*9%)</span><span class="sxs-lookup"><span data-stu-id="9ab8e-234">5,400 (60,000\*9%)</span></span>|  
    |<span data-ttu-id="9ab8e-235">**Normal Payment Applied**</span><span class="sxs-lookup"><span data-stu-id="9ab8e-235">**Normal Payment Applied**</span></span>|<span data-ttu-id="9ab8e-236">10000</span><span class="sxs-lookup"><span data-stu-id="9ab8e-236">10000</span></span>| 
    |<span data-ttu-id="9ab8e-237">**SGST/UTGST Amount = Invoice Total SGST/UTGST amount x (Normal Payment Applied/Total Transactional Value)**</span><span class="sxs-lookup"><span data-stu-id="9ab8e-237">**SGST/UTGST Amount = Invoice Total SGST/UTGST amount x (Normal Payment Applied/Total Transactional Value)**</span></span>|<span data-ttu-id="9ab8e-238">900 (5,400\*(10,000/60,000)</span><span class="sxs-lookup"><span data-stu-id="9ab8e-238">900 (5,400\*(10,000/60,000)</span></span>|
    |<span data-ttu-id="9ab8e-239">**CGST Amount = Invoice Total CGST amount x (Normal Payment Applied/Total Transactional Value)**</span><span class="sxs-lookup"><span data-stu-id="9ab8e-239">**CGST Amount = Invoice Total CGST amount x (Normal Payment Applied/Total Transactional Value)**</span></span>|<span data-ttu-id="9ab8e-240">900 (5,400\*(10,000/60,000)</span><span class="sxs-lookup"><span data-stu-id="9ab8e-240">900 (5,400\*(10,000/60,000)</span></span>|

- <span data-ttu-id="9ab8e-241">GL Entries for Application of invoice with normal payment:</span><span class="sxs-lookup"><span data-stu-id="9ab8e-241">GL Entries for Application of invoice with normal payment:</span></span>

    |<span data-ttu-id="9ab8e-242">Particulars</span><span class="sxs-lookup"><span data-stu-id="9ab8e-242">Particulars</span></span>|<span data-ttu-id="9ab8e-243">Amount</span><span class="sxs-lookup"><span data-stu-id="9ab8e-243">Amount</span></span>|
    |----------------------------------|---------------------------------------|  
    |<span data-ttu-id="9ab8e-244">**Vendor Account**</span><span class="sxs-lookup"><span data-stu-id="9ab8e-244">**Vendor Account**</span></span>|<span data-ttu-id="9ab8e-245">10000</span><span class="sxs-lookup"><span data-stu-id="9ab8e-245">10000</span></span>|  
    |<span data-ttu-id="9ab8e-246">**CGST Payable (Interim) Account**</span><span class="sxs-lookup"><span data-stu-id="9ab8e-246">**CGST Payable (Interim) Account**</span></span>|<span data-ttu-id="9ab8e-247">900</span><span class="sxs-lookup"><span data-stu-id="9ab8e-247">900</span></span>|  
    |<span data-ttu-id="9ab8e-248">**SGST/UTGST Payable (Interim) Account**</span><span class="sxs-lookup"><span data-stu-id="9ab8e-248">**SGST/UTGST Payable (Interim) Account**</span></span>|<span data-ttu-id="9ab8e-249">900</span><span class="sxs-lookup"><span data-stu-id="9ab8e-249">900</span></span>|
    |<span data-ttu-id="9ab8e-250">**CGST Receivable Account**</span><span class="sxs-lookup"><span data-stu-id="9ab8e-250">**CGST Receivable Account**</span></span>|<span data-ttu-id="9ab8e-251">900</span><span class="sxs-lookup"><span data-stu-id="9ab8e-251">900</span></span>|
    |<span data-ttu-id="9ab8e-252">**SGST/UTGST Receivable Account**</span><span class="sxs-lookup"><span data-stu-id="9ab8e-252">**SGST/UTGST Receivable Account**</span></span>|<span data-ttu-id="9ab8e-253">900</span><span class="sxs-lookup"><span data-stu-id="9ab8e-253">900</span></span>|
    |<span data-ttu-id="9ab8e-254">**CGST Payable Account**</span><span class="sxs-lookup"><span data-stu-id="9ab8e-254">**CGST Payable Account**</span></span>|<span data-ttu-id="9ab8e-255">-900</span><span class="sxs-lookup"><span data-stu-id="9ab8e-255">-900</span></span>|
    |<span data-ttu-id="9ab8e-256">**SGST/UTGST Payable Account**</span><span class="sxs-lookup"><span data-stu-id="9ab8e-256">**SGST/UTGST Payable Account**</span></span>|<span data-ttu-id="9ab8e-257">-900</span><span class="sxs-lookup"><span data-stu-id="9ab8e-257">-900</span></span>|
    |<span data-ttu-id="9ab8e-258">**CGST Receivable (Interim) Account**</span><span class="sxs-lookup"><span data-stu-id="9ab8e-258">**CGST Receivable (Interim) Account**</span></span>|<span data-ttu-id="9ab8e-259">-900</span><span class="sxs-lookup"><span data-stu-id="9ab8e-259">-900</span></span>|
    |<span data-ttu-id="9ab8e-260">**SGST/UTGST Receivable (Interim) Account**</span><span class="sxs-lookup"><span data-stu-id="9ab8e-260">**SGST/UTGST Receivable (Interim) Account**</span></span>|<span data-ttu-id="9ab8e-261">-900</span><span class="sxs-lookup"><span data-stu-id="9ab8e-261">-900</span></span>|  
    |<span data-ttu-id="9ab8e-262">**Bank Account**</span><span class="sxs-lookup"><span data-stu-id="9ab8e-262">**Bank Account**</span></span>|<span data-ttu-id="9ab8e-263">10000</span><span class="sxs-lookup"><span data-stu-id="9ab8e-263">10000</span></span>|

<span data-ttu-id="9ab8e-264">If this is found that the payment and invoice was wrongly applied and the application needs to be reversed, in such a case un apply functionality can be used.</span><span class="sxs-lookup"><span data-stu-id="9ab8e-264">If this is found that the payment and invoice was wrongly applied and the application needs to be reversed, in such a case un apply functionality can be used.</span></span> <span data-ttu-id="9ab8e-265">Un-application entries are same for both online application and offline application.</span><span class="sxs-lookup"><span data-stu-id="9ab8e-265">Un-application entries are same for both online application and offline application.</span></span>

- <span data-ttu-id="9ab8e-266">GL Entries for un-application of invoice with normal payment:</span><span class="sxs-lookup"><span data-stu-id="9ab8e-266">GL Entries for un-application of invoice with normal payment:</span></span>

    |<span data-ttu-id="9ab8e-267">Particulars</span><span class="sxs-lookup"><span data-stu-id="9ab8e-267">Particulars</span></span>|<span data-ttu-id="9ab8e-268">Amount</span><span class="sxs-lookup"><span data-stu-id="9ab8e-268">Amount</span></span>|
    |----------------------------------|---------------------------------------|  
    |<span data-ttu-id="9ab8e-269">**CGST Payable Account**</span><span class="sxs-lookup"><span data-stu-id="9ab8e-269">**CGST Payable Account**</span></span>|<span data-ttu-id="9ab8e-270">900</span><span class="sxs-lookup"><span data-stu-id="9ab8e-270">900</span></span>|  
    |<span data-ttu-id="9ab8e-271">**SGST/UTGST Payable Account**</span><span class="sxs-lookup"><span data-stu-id="9ab8e-271">**SGST/UTGST Payable Account**</span></span>|<span data-ttu-id="9ab8e-272">900</span><span class="sxs-lookup"><span data-stu-id="9ab8e-272">900</span></span>|  
    |<span data-ttu-id="9ab8e-273">**CGST Receivable (Interim) Account**</span><span class="sxs-lookup"><span data-stu-id="9ab8e-273">**CGST Receivable (Interim) Account**</span></span>|<span data-ttu-id="9ab8e-274">900</span><span class="sxs-lookup"><span data-stu-id="9ab8e-274">900</span></span>|
    |<span data-ttu-id="9ab8e-275">**SGST/UTGST Receivable (Interim) Account**</span><span class="sxs-lookup"><span data-stu-id="9ab8e-275">**SGST/UTGST Receivable (Interim) Account**</span></span>|<span data-ttu-id="9ab8e-276">900</span><span class="sxs-lookup"><span data-stu-id="9ab8e-276">900</span></span>|
    |<span data-ttu-id="9ab8e-277">**CGST Payable (Interim) Account**</span><span class="sxs-lookup"><span data-stu-id="9ab8e-277">**CGST Payable (Interim) Account**</span></span>|<span data-ttu-id="9ab8e-278">-900</span><span class="sxs-lookup"><span data-stu-id="9ab8e-278">-900</span></span>| 
    |<span data-ttu-id="9ab8e-279">**SGST/UTGST Payable (Interim) Account**</span><span class="sxs-lookup"><span data-stu-id="9ab8e-279">**SGST/UTGST Payable (Interim) Account**</span></span>|<span data-ttu-id="9ab8e-280">-900</span><span class="sxs-lookup"><span data-stu-id="9ab8e-280">-900</span></span>|
    |<span data-ttu-id="9ab8e-281">**SGST/UTGST Receivable Account**</span><span class="sxs-lookup"><span data-stu-id="9ab8e-281">**SGST/UTGST Receivable Account**</span></span>|<span data-ttu-id="9ab8e-282">-900</span><span class="sxs-lookup"><span data-stu-id="9ab8e-282">-900</span></span>|
    |<span data-ttu-id="9ab8e-283">**CGST Receivable Account**</span><span class="sxs-lookup"><span data-stu-id="9ab8e-283">**CGST Receivable Account**</span></span>|<span data-ttu-id="9ab8e-284">-900</span><span class="sxs-lookup"><span data-stu-id="9ab8e-284">-900</span></span>| 

>[!Tip]
>
> <span data-ttu-id="9ab8e-285">Note: In case of Inter-State Purchase, IGST will be calculated.</span><span class="sxs-lookup"><span data-stu-id="9ab8e-285">Note: In case of Inter-State Purchase, IGST will be calculated.</span></span>






































