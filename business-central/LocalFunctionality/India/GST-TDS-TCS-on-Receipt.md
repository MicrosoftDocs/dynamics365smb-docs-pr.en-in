---
title: GST TDS and GST TCS on Customer Payments
description: GST TDS and GST TCS on Customer Payments
author: v-debapd
ms.service: dynamics365-business-central
ms.topic: article
ms.devlang: na
ms.tgt_pltfrm: na
ms.workload: na
ms.search.keywords: India, local, IN, English
ms.date: 10/01/2020
ms.author: v-debapd
ms.openlocfilehash: 7cec9b413b1a9649fdfddc63f7dc8b04f5304a68
ms.sourcegitcommit: ddbb5cede750df1baba4b3eab8fbed6744b5b9d6
ms.translationtype: HT
ms.contentlocale: en-IN
ms.lasthandoff: 10/01/2020
ms.locfileid: "3948621"
---
# <a name="gst-tcs-on-customer-payments"></a><span data-ttu-id="4a8bc-103">GST TCS on Customer Payments</span><span class="sxs-lookup"><span data-stu-id="4a8bc-103">GST TCS on Customer Payments</span></span>

[!INCLUDE[vnext_preview](../../includes/vnext_preview.md)]

<span data-ttu-id="4a8bc-104">GST TCS can be liable on cash or bank payment from customer.</span><span class="sxs-lookup"><span data-stu-id="4a8bc-104">GST TCS can be liable on cash or bank payment from customer.</span></span> <span data-ttu-id="4a8bc-105">The GST TCS entries which are not reversed will be part of settlement.</span><span class="sxs-lookup"><span data-stu-id="4a8bc-105">The GST TCS entries which are not reversed will be part of settlement.</span></span> <span data-ttu-id="4a8bc-106">Business user can reverse the GST TCS entries before settlement is posted.</span><span class="sxs-lookup"><span data-stu-id="4a8bc-106">Business user can reverse the GST TCS entries before settlement is posted.</span></span> <span data-ttu-id="4a8bc-107">The GST TCS entries which have Credit Availed field 'TRUE' will be shown on settlement page.</span><span class="sxs-lookup"><span data-stu-id="4a8bc-107">The GST TCS entries which have Credit Availed field 'TRUE' will be shown on settlement page.</span></span> <span data-ttu-id="4a8bc-108">Users can manually enter amount in GST TCS Credit Utilised field for utilising against the liability.</span><span class="sxs-lookup"><span data-stu-id="4a8bc-108">User can manually enter amount in GST TCS Credit Utilized field for utilizing against the liability.</span></span>
 
1. <span data-ttu-id="4a8bc-109">Choose the ![Search for Page or Report](image/search_small.png "Search for Page or Report icon") icon, enter **Bank Receipt Voucher** or **Cash Receipt Voucher** , and then choose the related link.</span><span class="sxs-lookup"><span data-stu-id="4a8bc-109">Choose the ![Search for Page or Report](image/search_small.png "Search for Page or Report icon") icon, enter **Bank Receipt Voucher** or **Cash Receipt Voucher** , and then choose the related link.</span></span>
2. <span data-ttu-id="4a8bc-110">Fill in the fields as described on **Bank Receipt Voucher** or **Cash Receipt Voucher** .</span><span class="sxs-lookup"><span data-stu-id="4a8bc-110">Fill in the fields as described on **Bank Receipt Voucher** or **Cash Receipt Voucher** .</span></span>
    
    |<span data-ttu-id="4a8bc-111">Field</span><span class="sxs-lookup"><span data-stu-id="4a8bc-111">Field</span></span>|<span data-ttu-id="4a8bc-112">Description</span><span class="sxs-lookup"><span data-stu-id="4a8bc-112">Description</span></span>| 
    |---------------------------------|  ---------------------------------------| 
    |<span data-ttu-id="4a8bc-113">**Posting Date**</span><span class="sxs-lookup"><span data-stu-id="4a8bc-113">**Posting Date**</span></span>|<span data-ttu-id="4a8bc-114">Specify the posting date of the document.</span><span class="sxs-lookup"><span data-stu-id="4a8bc-114">Specify the posting date of the document.</span></span>|
    |<span data-ttu-id="4a8bc-115">**Document Type**</span><span class="sxs-lookup"><span data-stu-id="4a8bc-115">**Document Type**</span></span>|<span data-ttu-id="4a8bc-116">Specify as 'Payment'</span><span class="sxs-lookup"><span data-stu-id="4a8bc-116">Specify as 'Payment'</span></span>|
    |<span data-ttu-id="4a8bc-117">**Account Type**</span><span class="sxs-lookup"><span data-stu-id="4a8bc-117">**Account Type**</span></span>|<span data-ttu-id="4a8bc-118">Specify as 'Customer'</span><span class="sxs-lookup"><span data-stu-id="4a8bc-118">Specify as 'Customer'</span></span>|
    |<span data-ttu-id="4a8bc-119">**Account No.**</span><span class="sxs-lookup"><span data-stu-id="4a8bc-119">**Account No.**</span></span>|<span data-ttu-id="4a8bc-120">Select the relevant customer code.</span><span class="sxs-lookup"><span data-stu-id="4a8bc-120">Select the relevant customer code.</span></span>|
    |<span data-ttu-id="4a8bc-121">**Amount**</span><span class="sxs-lookup"><span data-stu-id="4a8bc-121">**Amount**</span></span>|<span data-ttu-id="4a8bc-122">Specify the amount.</span><span class="sxs-lookup"><span data-stu-id="4a8bc-122">Specify the amount.</span></span>|
    |<span data-ttu-id="4a8bc-123">**Bal. Account Type**</span><span class="sxs-lookup"><span data-stu-id="4a8bc-123">**Bal. Account Type**</span></span>|<span data-ttu-id="4a8bc-124">Specify G/L Account or Bank Account.</span><span class="sxs-lookup"><span data-stu-id="4a8bc-124">Specify G/L Account or Bank Account.</span></span>|
    |<span data-ttu-id="4a8bc-125">**Location Code**</span><span class="sxs-lookup"><span data-stu-id="4a8bc-125">**Location Code**</span></span>|<span data-ttu-id="4a8bc-126">Specify the relevant location code.</span><span class="sxs-lookup"><span data-stu-id="4a8bc-126">Specify the relevant location code.</span></span>|
    |<span data-ttu-id="4a8bc-127">**GST TCS State Code**</span><span class="sxs-lookup"><span data-stu-id="4a8bc-127">**GST TCS State Code**</span></span>|<span data-ttu-id="4a8bc-128">Specify the relevant state code.</span><span class="sxs-lookup"><span data-stu-id="4a8bc-128">Specify the relevant state code.</span></span>|
    |<span data-ttu-id="4a8bc-129">**GST TDS/TCS Base Amount**</span><span class="sxs-lookup"><span data-stu-id="4a8bc-129">**GST TDS/TCS Base Amount**</span></span>|<span data-ttu-id="4a8bc-130">Specify the GST TCS calculation base amount.</span><span class="sxs-lookup"><span data-stu-id="4a8bc-130">Specify the GST TCS calculation base amount.</span></span>|
    |<span data-ttu-id="4a8bc-131">**GST TCS**</span><span class="sxs-lookup"><span data-stu-id="4a8bc-131">**GST TCS**</span></span>|<span data-ttu-id="4a8bc-132">Mark this field as True.</span><span class="sxs-lookup"><span data-stu-id="4a8bc-132">Mark this field as True.</span></span>|

<span data-ttu-id="4a8bc-133">For example, INR 1000 paid by the customer and 1% GST TCS (0.50% CGST, 0.50% SGST for Intra-State or Intra-Union Territory and 1% IGST for Inter State) has to be charged on the payment amount.</span><span class="sxs-lookup"><span data-stu-id="4a8bc-133">For example, INR 1000 paid by the customer and 1% GST TCS (0.50% CGST, 0.50% SGST for Intra-State or Intra-Union Territory and 1% IGST for Inter State) has to be charged on the payment amount.</span></span>

- <span data-ttu-id="4a8bc-134">GST Calculation will appear in the Fact Box on Bank or Cash Receipt Voucher, as following:</span><span class="sxs-lookup"><span data-stu-id="4a8bc-134">GST Calculation will appear in the Fact Box on Bank or Cash Receipt Voucher, as following:</span></span>
    
    |<span data-ttu-id="4a8bc-135">Component</span><span class="sxs-lookup"><span data-stu-id="4a8bc-135">Component</span></span>|<span data-ttu-id="4a8bc-136">Amount</span><span class="sxs-lookup"><span data-stu-id="4a8bc-136">Amount</span></span>|
    |----------------------------------|---------------------------------------|  
    |<span data-ttu-id="4a8bc-137">**Payment Amount**</span><span class="sxs-lookup"><span data-stu-id="4a8bc-137">**Payment Amount**</span></span>|<span data-ttu-id="4a8bc-138">1000</span><span class="sxs-lookup"><span data-stu-id="4a8bc-138">1000</span></span>|
    |<span data-ttu-id="4a8bc-139">**GST Transactional Value**</span><span class="sxs-lookup"><span data-stu-id="4a8bc-139">**GST Transactional Value**</span></span>|<span data-ttu-id="4a8bc-140">1,000</span><span class="sxs-lookup"><span data-stu-id="4a8bc-140">1,000</span></span>|
    |<span data-ttu-id="4a8bc-141">**CGST Amount**</span><span class="sxs-lookup"><span data-stu-id="4a8bc-141">**CGST Amount**</span></span>|<span data-ttu-id="4a8bc-142">5</span><span class="sxs-lookup"><span data-stu-id="4a8bc-142">5</span></span>|
    |<span data-ttu-id="4a8bc-143">**SGST Amount**</span><span class="sxs-lookup"><span data-stu-id="4a8bc-143">**SGST Amount**</span></span>|<span data-ttu-id="4a8bc-144">5</span><span class="sxs-lookup"><span data-stu-id="4a8bc-144">5</span></span>|
    |<span data-ttu-id="4a8bc-145">**IGST Amount**</span><span class="sxs-lookup"><span data-stu-id="4a8bc-145">**IGST Amount**</span></span>|<span data-ttu-id="4a8bc-146">10</span><span class="sxs-lookup"><span data-stu-id="4a8bc-146">10</span></span>|
    
- <span data-ttu-id="4a8bc-147">On posting of voucher for GST TCS - Intrastate Transaction, GL Entries will be as following:</span><span class="sxs-lookup"><span data-stu-id="4a8bc-147">On posting of voucher for GST TCS - Intrastate Transaction, GL Entries will be as following:</span></span>

    |<span data-ttu-id="4a8bc-148">Particulars</span><span class="sxs-lookup"><span data-stu-id="4a8bc-148">Particulars</span></span>|<span data-ttu-id="4a8bc-149">Amount</span><span class="sxs-lookup"><span data-stu-id="4a8bc-149">Amount</span></span>|
    |----------------------------------|---------------------------------------|  
    |<span data-ttu-id="4a8bc-150">**Customer Account**</span><span class="sxs-lookup"><span data-stu-id="4a8bc-150">**Customer Account**</span></span>|<span data-ttu-id="4a8bc-151">-1000</span><span class="sxs-lookup"><span data-stu-id="4a8bc-151">-1000</span></span>|  
    |<span data-ttu-id="4a8bc-152">**CGST TCS Receivable Account**</span><span class="sxs-lookup"><span data-stu-id="4a8bc-152">**CGST TCS Receivable Account**</span></span>|<span data-ttu-id="4a8bc-153">5</span><span class="sxs-lookup"><span data-stu-id="4a8bc-153">5</span></span>|  
    |<span data-ttu-id="4a8bc-154">**SGST/UTGST TCS Receivable Account**</span><span class="sxs-lookup"><span data-stu-id="4a8bc-154">**SGST/UTGST TCS Receivable Account**</span></span>|<span data-ttu-id="4a8bc-155">5</span><span class="sxs-lookup"><span data-stu-id="4a8bc-155">5</span></span>| 
    |<span data-ttu-id="4a8bc-156">**Bank Account**</span><span class="sxs-lookup"><span data-stu-id="4a8bc-156">**Bank Account**</span></span>|<span data-ttu-id="4a8bc-157">990</span><span class="sxs-lookup"><span data-stu-id="4a8bc-157">990</span></span>| 
    
- <span data-ttu-id="4a8bc-158">On posting of voucher for GST TCS - Interstate Transaction, GL Entries will be as following:</span><span class="sxs-lookup"><span data-stu-id="4a8bc-158">On posting of voucher for GST TCS - Interstate Transaction, GL Entries will be as following:</span></span>

    |<span data-ttu-id="4a8bc-159">Particulars</span><span class="sxs-lookup"><span data-stu-id="4a8bc-159">Particulars</span></span>|<span data-ttu-id="4a8bc-160">Amount</span><span class="sxs-lookup"><span data-stu-id="4a8bc-160">Amount</span></span>|
    |----------------------------------|---------------------------------------|  
    |<span data-ttu-id="4a8bc-161">**Customer Account**</span><span class="sxs-lookup"><span data-stu-id="4a8bc-161">**Customer Account**</span></span>|<span data-ttu-id="4a8bc-162">-1000</span><span class="sxs-lookup"><span data-stu-id="4a8bc-162">-1000</span></span>|  
    |<span data-ttu-id="4a8bc-163">**IGST TCS Receivable Account**</span><span class="sxs-lookup"><span data-stu-id="4a8bc-163">**IGST TCS Receivable Account**</span></span>|<span data-ttu-id="4a8bc-164">10</span><span class="sxs-lookup"><span data-stu-id="4a8bc-164">10</span></span>|  
    |<span data-ttu-id="4a8bc-165">**Bank Account**</span><span class="sxs-lookup"><span data-stu-id="4a8bc-165">**Bank Account**</span></span>|<span data-ttu-id="4a8bc-166">990</span><span class="sxs-lookup"><span data-stu-id="4a8bc-166">990</span></span>| 

## <a name="gst-tds-on-customer-payment"></a><span data-ttu-id="4a8bc-167">GST TDS on customer payment</span><span class="sxs-lookup"><span data-stu-id="4a8bc-167">GST TDS on customer payment</span></span>

<span data-ttu-id="4a8bc-168">GST TDS is applicable for Registered Customers.</span><span class="sxs-lookup"><span data-stu-id="4a8bc-168">GST TDS is applicable for Registered Customers.</span></span> <span data-ttu-id="4a8bc-169">User can calculate GST TDS on cash or bank payment from customer, user needs to enter GST TDS/TCS Base Amount manually for calculating GST TDS.</span><span class="sxs-lookup"><span data-stu-id="4a8bc-169">User can calculate GST TDS on cash or bank payment from customer, user needs to enter GST TDS/TCS Base Amount manually for calculating GST TDS.</span></span> 

<span data-ttu-id="4a8bc-170">A provision for updating GST TDS certificate details is available under Financial Management > Periodic Activities > GST > Task: Update GST TDS Certificate Dtl.</span><span class="sxs-lookup"><span data-stu-id="4a8bc-170">A provision for updating GST TDS certificate details is available under Financial Management > Periodic Activities > GST > Task: Update GST TDS Certificate Dtl.</span></span> <span data-ttu-id="4a8bc-171">The GST TDS entries against which the certificate is received will be a part of GST settlement.</span><span class="sxs-lookup"><span data-stu-id="4a8bc-171">The GST TDS entries against which the certificate is received will be a part of GST settlement.</span></span>

<span data-ttu-id="4a8bc-172">User can reverse the GST TDS entries before certificate is received.</span><span class="sxs-lookup"><span data-stu-id="4a8bc-172">User can reverse the GST TDS entries before certificate is received.</span></span> <span data-ttu-id="4a8bc-173">An additional option has been provided to user to modify GST TDS Certificate Details.</span><span class="sxs-lookup"><span data-stu-id="4a8bc-173">An additional option has been provided to user to modify GST TDS Certificate Details.</span></span> <span data-ttu-id="4a8bc-174">The GST TDS Credit received will be shown on settlement page.</span><span class="sxs-lookup"><span data-stu-id="4a8bc-174">The GST TDS Credit received will be shown on settlement page.</span></span> 

<span data-ttu-id="4a8bc-175">User can manually enter amount in GST TDS Credit Utilised field for utilising against the liability.</span><span class="sxs-lookup"><span data-stu-id="4a8bc-175">User can manually enter amount in GST TDS Credit Utilized field for utilizing against the liability.</span></span>
 
1. <span data-ttu-id="4a8bc-176">Choose the ![Search for Page or Report](image/search_small.png "Search for Page or Report icon") icon, enter **Bank Receipt Voucher** or **Cash Receipt Voucher** , and then choose the related link.</span><span class="sxs-lookup"><span data-stu-id="4a8bc-176">Choose the ![Search for Page or Report](image/search_small.png "Search for Page or Report icon") icon, enter **Bank Receipt Voucher** or **Cash Receipt Voucher** , and then choose the related link.</span></span>
2. <span data-ttu-id="4a8bc-177">Fill in the fields as described on **Bank Receipt Voucher** or **Cash Receipt Voucher** .</span><span class="sxs-lookup"><span data-stu-id="4a8bc-177">Fill in the fields as described on **Bank Receipt Voucher** or **Cash Receipt Voucher** .</span></span>
    
    |<span data-ttu-id="4a8bc-178">Field</span><span class="sxs-lookup"><span data-stu-id="4a8bc-178">Field</span></span>|<span data-ttu-id="4a8bc-179">Description</span><span class="sxs-lookup"><span data-stu-id="4a8bc-179">Description</span></span>| 
    |---------------------------------|  ---------------------------------------| 
    |<span data-ttu-id="4a8bc-180">**Posting Date**</span><span class="sxs-lookup"><span data-stu-id="4a8bc-180">**Posting Date**</span></span>|<span data-ttu-id="4a8bc-181">Specify the posting date of the document.</span><span class="sxs-lookup"><span data-stu-id="4a8bc-181">Specify the posting date of the document.</span></span>|
    |<span data-ttu-id="4a8bc-182">**Document Type**</span><span class="sxs-lookup"><span data-stu-id="4a8bc-182">**Document Type**</span></span>|<span data-ttu-id="4a8bc-183">Specify as 'Payment'</span><span class="sxs-lookup"><span data-stu-id="4a8bc-183">Specify as 'Payment'</span></span>|
    |<span data-ttu-id="4a8bc-184">**Account Type**</span><span class="sxs-lookup"><span data-stu-id="4a8bc-184">**Account Type**</span></span>|<span data-ttu-id="4a8bc-185">Specify as 'Customer'</span><span class="sxs-lookup"><span data-stu-id="4a8bc-185">Specify as 'Customer'</span></span>|
    |<span data-ttu-id="4a8bc-186">**Account No.**</span><span class="sxs-lookup"><span data-stu-id="4a8bc-186">**Account No.**</span></span>|<span data-ttu-id="4a8bc-187">Select the relevant customer code.</span><span class="sxs-lookup"><span data-stu-id="4a8bc-187">Select the relevant customer code.</span></span>|
    |<span data-ttu-id="4a8bc-188">**Amount**</span><span class="sxs-lookup"><span data-stu-id="4a8bc-188">**Amount**</span></span>|<span data-ttu-id="4a8bc-189">Specify the amount.</span><span class="sxs-lookup"><span data-stu-id="4a8bc-189">Specify the amount.</span></span>|
    |<span data-ttu-id="4a8bc-190">**Bal. Account Type**</span><span class="sxs-lookup"><span data-stu-id="4a8bc-190">**Bal. Account Type**</span></span>|<span data-ttu-id="4a8bc-191">Specify G/L Account or Bank Account.</span><span class="sxs-lookup"><span data-stu-id="4a8bc-191">Specify G/L Account or Bank Account.</span></span>|
    |<span data-ttu-id="4a8bc-192">**Location Code**</span><span class="sxs-lookup"><span data-stu-id="4a8bc-192">**Location Code**</span></span>|<span data-ttu-id="4a8bc-193">Specify the relevant location code.</span><span class="sxs-lookup"><span data-stu-id="4a8bc-193">Specify the relevant location code.</span></span>|
    |<span data-ttu-id="4a8bc-194">**GST TDS/TCS State Code**</span><span class="sxs-lookup"><span data-stu-id="4a8bc-194">**GST TDS/TCS State Code**</span></span>|<span data-ttu-id="4a8bc-195">Specify the relevant state code.</span><span class="sxs-lookup"><span data-stu-id="4a8bc-195">Specify the relevant state code.</span></span>|
    |<span data-ttu-id="4a8bc-196">**GST TDS/TCS Base Amount**</span><span class="sxs-lookup"><span data-stu-id="4a8bc-196">**GST TDS/TCS Base Amount**</span></span>|<span data-ttu-id="4a8bc-197">Specify the GST TCS calculation base amount.</span><span class="sxs-lookup"><span data-stu-id="4a8bc-197">Specify the GST TCS calculation base amount.</span></span>|
    |<span data-ttu-id="4a8bc-198">**GST TDS**</span><span class="sxs-lookup"><span data-stu-id="4a8bc-198">**GST TDS**</span></span>|<span data-ttu-id="4a8bc-199">Mark this field as True.</span><span class="sxs-lookup"><span data-stu-id="4a8bc-199">Mark this field as True.</span></span>|

<span data-ttu-id="4a8bc-200">For example, INR 1000 received from customer and 2% GST TDS (1% CGST, 1% SGST for Intra-State or Intra-Union Territory and 2% IGST for Inter State) has to be charged.</span><span class="sxs-lookup"><span data-stu-id="4a8bc-200">For example, INR 1000 received from customer and 2% GST TDS (1% CGST, 1% SGST for Intra-State or Intra-Union Territory and 2% IGST for Inter State) has to be charged.</span></span>

- <span data-ttu-id="4a8bc-201">GST calculation will appear in the Fact Box on Cash or Bank Receipt Voucher, as following:</span><span class="sxs-lookup"><span data-stu-id="4a8bc-201">GST calculation will appear in the Fact Box on Cash or Bank Receipt Voucher, as following:</span></span>
    
    |<span data-ttu-id="4a8bc-202">Component</span><span class="sxs-lookup"><span data-stu-id="4a8bc-202">Component</span></span>|<span data-ttu-id="4a8bc-203">Amount</span><span class="sxs-lookup"><span data-stu-id="4a8bc-203">Amount</span></span>|
    |----------------------------------|---------------------------------------|  
    |<span data-ttu-id="4a8bc-204">**Payment Amount**</span><span class="sxs-lookup"><span data-stu-id="4a8bc-204">**Payment Amount**</span></span>|<span data-ttu-id="4a8bc-205">1000</span><span class="sxs-lookup"><span data-stu-id="4a8bc-205">1000</span></span>|
    |<span data-ttu-id="4a8bc-206">**GST Transactional Value**</span><span class="sxs-lookup"><span data-stu-id="4a8bc-206">**GST Transactional Value**</span></span>|<span data-ttu-id="4a8bc-207">1,000</span><span class="sxs-lookup"><span data-stu-id="4a8bc-207">1,000</span></span>|
    |<span data-ttu-id="4a8bc-208">**CGST Amount**</span><span class="sxs-lookup"><span data-stu-id="4a8bc-208">**CGST Amount**</span></span>|<span data-ttu-id="4a8bc-209">10</span><span class="sxs-lookup"><span data-stu-id="4a8bc-209">10</span></span>|
    |<span data-ttu-id="4a8bc-210">**SGST Amount**</span><span class="sxs-lookup"><span data-stu-id="4a8bc-210">**SGST Amount**</span></span>|<span data-ttu-id="4a8bc-211">10</span><span class="sxs-lookup"><span data-stu-id="4a8bc-211">10</span></span>|
    |<span data-ttu-id="4a8bc-212">**IGST Amount**</span><span class="sxs-lookup"><span data-stu-id="4a8bc-212">**IGST Amount**</span></span>|<span data-ttu-id="4a8bc-213">20</span><span class="sxs-lookup"><span data-stu-id="4a8bc-213">20</span></span>|
    
- <span data-ttu-id="4a8bc-214">On posting of voucher for GST TDS - Intrastate Transaction, GL Entries will be as following:</span><span class="sxs-lookup"><span data-stu-id="4a8bc-214">On posting of voucher for GST TDS - Intrastate Transaction, GL Entries will be as following:</span></span>

    |<span data-ttu-id="4a8bc-215">Particulars</span><span class="sxs-lookup"><span data-stu-id="4a8bc-215">Particulars</span></span>|<span data-ttu-id="4a8bc-216">Amount</span><span class="sxs-lookup"><span data-stu-id="4a8bc-216">Amount</span></span>|
    |----------------------------------|---------------------------------------|  
    |<span data-ttu-id="4a8bc-217">**Customer Account**</span><span class="sxs-lookup"><span data-stu-id="4a8bc-217">**Customer Account**</span></span>|<span data-ttu-id="4a8bc-218">-1000</span><span class="sxs-lookup"><span data-stu-id="4a8bc-218">-1000</span></span>|  
    |<span data-ttu-id="4a8bc-219">**CGST TDS Receivable Account**</span><span class="sxs-lookup"><span data-stu-id="4a8bc-219">**CGST TDS Receivable Account**</span></span>|<span data-ttu-id="4a8bc-220">10</span><span class="sxs-lookup"><span data-stu-id="4a8bc-220">10</span></span>|  
    |<span data-ttu-id="4a8bc-221">**SGST/UTGST TDS Receivable Account**</span><span class="sxs-lookup"><span data-stu-id="4a8bc-221">**SGST/UTGST TDS Receivable Account**</span></span>|<span data-ttu-id="4a8bc-222">10</span><span class="sxs-lookup"><span data-stu-id="4a8bc-222">10</span></span>| 
    |<span data-ttu-id="4a8bc-223">**Bank Account**</span><span class="sxs-lookup"><span data-stu-id="4a8bc-223">**Bank Account**</span></span>|<span data-ttu-id="4a8bc-224">980</span><span class="sxs-lookup"><span data-stu-id="4a8bc-224">980</span></span>| 
    
- <span data-ttu-id="4a8bc-225">On posting of voucher for GST TDS - Interstate Transaction, GL Entries will be as following:</span><span class="sxs-lookup"><span data-stu-id="4a8bc-225">On posting of voucher for GST TDS - Interstate Transaction, GL Entries will be as following:</span></span>

    |<span data-ttu-id="4a8bc-226">Particulars</span><span class="sxs-lookup"><span data-stu-id="4a8bc-226">Particulars</span></span>|<span data-ttu-id="4a8bc-227">Amount</span><span class="sxs-lookup"><span data-stu-id="4a8bc-227">Amount</span></span>|
    |----------------------------------|---------------------------------------|  
    |<span data-ttu-id="4a8bc-228">**Customer Account**</span><span class="sxs-lookup"><span data-stu-id="4a8bc-228">**Customer Account**</span></span>|<span data-ttu-id="4a8bc-229">-1000</span><span class="sxs-lookup"><span data-stu-id="4a8bc-229">-1000</span></span>|  
    |<span data-ttu-id="4a8bc-230">**IGST TDS Receivable Account**</span><span class="sxs-lookup"><span data-stu-id="4a8bc-230">**IGST TDS Receivable Account**</span></span>|<span data-ttu-id="4a8bc-231">20</span><span class="sxs-lookup"><span data-stu-id="4a8bc-231">20</span></span>|  
    |<span data-ttu-id="4a8bc-232">**Bank Account**</span><span class="sxs-lookup"><span data-stu-id="4a8bc-232">**Bank Account**</span></span>|<span data-ttu-id="4a8bc-233">980</span><span class="sxs-lookup"><span data-stu-id="4a8bc-233">980</span></span>| 
