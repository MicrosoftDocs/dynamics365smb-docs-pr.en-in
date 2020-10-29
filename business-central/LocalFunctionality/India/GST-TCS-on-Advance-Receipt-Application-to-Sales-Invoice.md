---
title: GST and TCS on Advance Customer Payments
description: GST and TCS on Advance Customer Payments
author: v-debapd
ms.service: dynamics365-business-central
ms.topic: article
ms.devlang: na
ms.tgt_pltfrm: na
ms.workload: na
ms.search.keywords: India, local, IN, English
ms.date: 10/01/2020
ms.author: v-debapd
ms.openlocfilehash: 853cc9f3b448e22a46a4ec766cf92da01f1413ce
ms.sourcegitcommit: ddbb5cede750df1baba4b3eab8fbed6744b5b9d6
ms.translationtype: HT
ms.contentlocale: en-IN
ms.lasthandoff: 10/01/2020
ms.locfileid: "3948626"
---
# <a name="gst-and-tcs-on-advance-customer-payments"></a><span data-ttu-id="023dc-103">GST and TCS on Advance Customer Payments</span><span class="sxs-lookup"><span data-stu-id="023dc-103">GST and TCS on Advance Customer Payments</span></span> 

[!INCLUDE[vnext_preview](../../includes/vnext_preview.md)]

<span data-ttu-id="023dc-104">Assessee is liable for paying GST and TCS at the time of receiving advance payment from customer.</span><span class="sxs-lookup"><span data-stu-id="023dc-104">Assessee is liable for paying GST and TCS at the time of receiving advance payment from customer.</span></span>

### <a name="mandatory-fields-in-cash-or-bank-receipt-voucher"></a><span data-ttu-id="023dc-105">Mandatory fields in cash or bank receipt voucher</span><span class="sxs-lookup"><span data-stu-id="023dc-105">Mandatory fields in cash or bank receipt voucher</span></span>

1. <span data-ttu-id="023dc-106">Choose the ![Search for Page or Report](image/search_small.png "Search for Page or Report icon") icon, enter **Bank Receipt Voucher** or **Cash Receipt Voucher** , and then choose the related link.</span><span class="sxs-lookup"><span data-stu-id="023dc-106">Choose the ![Search for Page or Report](image/search_small.png "Search for Page or Report icon") icon, enter **Bank Receipt Voucher** or **Cash Receipt Voucher** , and then choose the related link.</span></span>
2. <span data-ttu-id="023dc-107">Select **Customer** in **Account Type** field and select relevant customer code in **Account No.** field.</span><span class="sxs-lookup"><span data-stu-id="023dc-107">Select **Customer** in **Account Type** field and select relevant customer code in **Account No.** field.</span></span>
3. <span data-ttu-id="023dc-108">Select **G/L Account** for cash or **Bank Account** for bank in **Bal. Account Type** field, and select relevant cash or bank account in **Bal. Account No.** field.</span><span class="sxs-lookup"><span data-stu-id="023dc-108">Select **G/L Account** for cash or **Bank Account** for bank in **Bal. Account Type** field, and select relevant cash or bank account in **Bal. Account No.** field.</span></span>
4. <span data-ttu-id="023dc-109">Select relevant TCS Nature of Collection, GST Group Code, HSN/SAC Code, Location Code on journal line.</span><span class="sxs-lookup"><span data-stu-id="023dc-109">Select relevant TCS Nature of Collection, GST Group Code, HSN/SAC Code, Location Code on journal line.</span></span>
5. <span data-ttu-id="023dc-110">**GST on Advance Payment** should be marked true.</span><span class="sxs-lookup"><span data-stu-id="023dc-110">**GST on Advance Payment** should be marked true.</span></span>  

 <span data-ttu-id="023dc-111">For example, service amount is INR 20000 and customer made an advance payment of INR 10,000, 18% IGST and 1% TCS has to be charged on the advance payment.</span><span class="sxs-lookup"><span data-stu-id="023dc-111">For example, service amount is INR 20000 and customer made an advance payment of INR 10,000, 18% IGST and 1% TCS has to be charged on the advance payment.</span></span>

- <span data-ttu-id="023dc-112">GST Calculation will appear in the Fact Box, as following:</span><span class="sxs-lookup"><span data-stu-id="023dc-112">GST Calculation will appear in the Fact Box, as following:</span></span>
    
    |<span data-ttu-id="023dc-113">Component</span><span class="sxs-lookup"><span data-stu-id="023dc-113">Component</span></span>|<span data-ttu-id="023dc-114">Amount</span><span class="sxs-lookup"><span data-stu-id="023dc-114">Amount</span></span>|
    |----------------------------------|---------------------------------------|  
    |<span data-ttu-id="023dc-115">**GST Base Amount**</span><span class="sxs-lookup"><span data-stu-id="023dc-115">**GST Base Amount**</span></span>|<span data-ttu-id="023dc-116">10,000</span><span class="sxs-lookup"><span data-stu-id="023dc-116">10,000</span></span>|
    |<span data-ttu-id="023dc-117">**GST Transactional Value**</span><span class="sxs-lookup"><span data-stu-id="023dc-117">**GST Transactional Value**</span></span>|<span data-ttu-id="023dc-118">8,474 (10000\*100/118)</span><span class="sxs-lookup"><span data-stu-id="023dc-118">8,474 (10000\*100/118)</span></span>|
    |<span data-ttu-id="023dc-119">**IGST Amount**</span><span class="sxs-lookup"><span data-stu-id="023dc-119">**IGST Amount**</span></span>|<span data-ttu-id="023dc-120">1525 (8,474\*18%)</span><span class="sxs-lookup"><span data-stu-id="023dc-120">1525 (8,474\*18%)</span></span>|
    |<span data-ttu-id="023dc-121">**TCS Amount**</span><span class="sxs-lookup"><span data-stu-id="023dc-121">**TCS Amount**</span></span>|<span data-ttu-id="023dc-122">100 (10,000\*1%)</span><span class="sxs-lookup"><span data-stu-id="023dc-122">100 (10,000\*1%)</span></span>|
    
- <span data-ttu-id="023dc-123">On posting of advance receipt from customer, GL Entries will be as following:</span><span class="sxs-lookup"><span data-stu-id="023dc-123">On posting of advance receipt from customer, GL Entries will be as following:</span></span>

    |<span data-ttu-id="023dc-124">Particulars</span><span class="sxs-lookup"><span data-stu-id="023dc-124">Particulars</span></span>|<span data-ttu-id="023dc-125">Amount</span><span class="sxs-lookup"><span data-stu-id="023dc-125">Amount</span></span>|
    |----------------------------------|---------------------------------------|  
    |<span data-ttu-id="023dc-126">**Bank Account**</span><span class="sxs-lookup"><span data-stu-id="023dc-126">**Bank Account**</span></span>|<span data-ttu-id="023dc-127">10000</span><span class="sxs-lookup"><span data-stu-id="023dc-127">10000</span></span>|  
    |<span data-ttu-id="023dc-128">**IGST Payable (Interim) Account**</span><span class="sxs-lookup"><span data-stu-id="023dc-128">**IGST Payable (Interim) Account**</span></span>|<span data-ttu-id="023dc-129">1525</span><span class="sxs-lookup"><span data-stu-id="023dc-129">1525</span></span>|  
    |<span data-ttu-id="023dc-130">**IGST Payable Account**</span><span class="sxs-lookup"><span data-stu-id="023dc-130">**IGST Payable Account**</span></span>|<span data-ttu-id="023dc-131">-1525</span><span class="sxs-lookup"><span data-stu-id="023dc-131">-1525</span></span>| 
    |<span data-ttu-id="023dc-132">**TCS Amount**</span><span class="sxs-lookup"><span data-stu-id="023dc-132">**TCS Amount**</span></span>|<span data-ttu-id="023dc-133">-100</span><span class="sxs-lookup"><span data-stu-id="023dc-133">-100</span></span>|
    |<span data-ttu-id="023dc-134">**Customer Account**</span><span class="sxs-lookup"><span data-stu-id="023dc-134">**Customer Account**</span></span>|<span data-ttu-id="023dc-135">-9900</span><span class="sxs-lookup"><span data-stu-id="023dc-135">-9900</span></span>| 


<span data-ttu-id="023dc-136">Later sales invoice for services is issued to the customer for INR 20,000, 18% IGST and 1% TCS has to be charged on the invoice amount, and the advance receipt from customer will be applied with the invoice.</span><span class="sxs-lookup"><span data-stu-id="023dc-136">Later sales invoice for services is issued to the customer for INR 20,000, 18% IGST and 1% TCS has to be charged on the invoice amount, and the advance receipt from customer will be applied with the invoice.</span></span>

### <a name="mandatory-fields-on-sales-invoice"></a><span data-ttu-id="023dc-137">Mandatory fields on sales invoice</span><span class="sxs-lookup"><span data-stu-id="023dc-137">Mandatory fields on sales invoice</span></span>

1. <span data-ttu-id="023dc-138">Choose the ![Search for Page or Report](image/search_small.png "Search for Page or Report icon") icon, enter **Sales Invoice** , and then choose the related link.</span><span class="sxs-lookup"><span data-stu-id="023dc-138">Choose the ![Search for Page or Report](image/search_small.png "Search for Page or Report icon") icon, enter **Sales Invoice** , and then choose the related link.</span></span>
2. <span data-ttu-id="023dc-139">Select **Customer** on **Sales Invoice** header.</span><span class="sxs-lookup"><span data-stu-id="023dc-139">Select **Customer** on **Sales Invoice** header.</span></span>
3. <span data-ttu-id="023dc-140">Select **G/L Account** for service or **Item** for goods on **Sales Invoice** line.</span><span class="sxs-lookup"><span data-stu-id="023dc-140">Select **G/L Account** for service or **Item** for goods on **Sales Invoice** line.</span></span>
4. <span data-ttu-id="023dc-141">Select relevant TCS Nature of Collection on **Sales Invoice** line.</span><span class="sxs-lookup"><span data-stu-id="023dc-141">Select relevant TCS Nature of Collection on **Sales Invoice** line.</span></span>
5. <span data-ttu-id="023dc-142">GST Group Code, HSN/SAC Code, GST Credit should have a value in **G/L Account** or **Item** card.</span><span class="sxs-lookup"><span data-stu-id="023dc-142">GST Group Code, HSN/SAC Code, GST Credit should have a value in **G/L Account** or **Item** card.</span></span>
6. <span data-ttu-id="023dc-143">**Location Code** field should not be blank on both **Sales Invoice** header and line.</span><span class="sxs-lookup"><span data-stu-id="023dc-143">**Location Code** field should not be blank on both **Sales Invoice** header and line.</span></span>
7. <span data-ttu-id="023dc-144">Select the advance payment in **Applies to Doc. No.**</span><span class="sxs-lookup"><span data-stu-id="023dc-144">Select the advance payment in **Applies to Doc. No.**</span></span> <span data-ttu-id="023dc-145">field on **Sales Invoice** header.</span><span class="sxs-lookup"><span data-stu-id="023dc-145">field on **Sales Invoice** header.</span></span>

- <span data-ttu-id="023dc-146">GST calculation will appear in the Fact Box, as following:</span><span class="sxs-lookup"><span data-stu-id="023dc-146">GST calculation will appear in the Fact Box, as following:</span></span>

    |<span data-ttu-id="023dc-147">Component</span><span class="sxs-lookup"><span data-stu-id="023dc-147">Component</span></span>|<span data-ttu-id="023dc-148">Amount</span><span class="sxs-lookup"><span data-stu-id="023dc-148">Amount</span></span>|
    |----------------------------------|---------------------------------------|  
    |<span data-ttu-id="023dc-149">**GST Base Amount**</span><span class="sxs-lookup"><span data-stu-id="023dc-149">**GST Base Amount**</span></span>|<span data-ttu-id="023dc-150">20000</span><span class="sxs-lookup"><span data-stu-id="023dc-150">20000</span></span>|  
    |<span data-ttu-id="023dc-151">**IGST**</span><span class="sxs-lookup"><span data-stu-id="023dc-151">**IGST**</span></span>|<span data-ttu-id="023dc-152">2075 = [3,600 (20,000 \* 18%)]-[1525 (8,474 \* 18%)]</span><span class="sxs-lookup"><span data-stu-id="023dc-152">2075 = [3,600 (20,000 \* 18%)]-[1525 (8,474 \* 18%)]</span></span>|  
    |<span data-ttu-id="023dc-153">**TCS Amount**</span><span class="sxs-lookup"><span data-stu-id="023dc-153">**TCS Amount**</span></span>|<span data-ttu-id="023dc-154">136 = [236 (23,600 \* 1%)] - [100 (10,000 \* 1%)]</span><span class="sxs-lookup"><span data-stu-id="023dc-154">136 = [236 (23,600 \* 1%)] - [100 (10,000 \* 1%)]</span></span> |

<span data-ttu-id="023dc-155">GST and TCS will be calculated on the remaining amount, i.e. Invoice Amount - Advance Payment Amount.</span><span class="sxs-lookup"><span data-stu-id="023dc-155">GST and TCS will be calculated on the remaining amount, i.e. Invoice Amount - Advance Payment Amount.</span></span> <span data-ttu-id="023dc-156">If advance payment is not applied with the sales invoice then GST and TCS will be calculated on the whole invoice amount.</span><span class="sxs-lookup"><span data-stu-id="023dc-156">If advance payment is not applied with the sales invoice then GST and TCS will be calculated on the whole invoice amount.</span></span>

- <span data-ttu-id="023dc-157">On posting of sales invoice, GL Entries will be following:</span><span class="sxs-lookup"><span data-stu-id="023dc-157">On posting of sales invoice, GL Entries will be following:</span></span>

    |<span data-ttu-id="023dc-158">Particulars</span><span class="sxs-lookup"><span data-stu-id="023dc-158">Particulars</span></span>|<span data-ttu-id="023dc-159">Amount</span><span class="sxs-lookup"><span data-stu-id="023dc-159">Amount</span></span>|
    |----------------------------------|---------------------------------------|  
    |<span data-ttu-id="023dc-160">**Customer Account**</span><span class="sxs-lookup"><span data-stu-id="023dc-160">**Customer Account**</span></span>|<span data-ttu-id="023dc-161">23736</span><span class="sxs-lookup"><span data-stu-id="023dc-161">23736</span></span>|  
    |<span data-ttu-id="023dc-162">**IGST Payable Account**</span><span class="sxs-lookup"><span data-stu-id="023dc-162">**IGST Payable Account**</span></span>|<span data-ttu-id="023dc-163">-3600</span><span class="sxs-lookup"><span data-stu-id="023dc-163">-3600</span></span>|
    |<span data-ttu-id="023dc-164">**Sales Account**</span><span class="sxs-lookup"><span data-stu-id="023dc-164">**Sales Account**</span></span>|<span data-ttu-id="023dc-165">-20000</span><span class="sxs-lookup"><span data-stu-id="023dc-165">-20000</span></span>|
    |<span data-ttu-id="023dc-166">**TCS Payable Account**</span><span class="sxs-lookup"><span data-stu-id="023dc-166">**TCS Payable Account**</span></span>|<span data-ttu-id="023dc-167">-136</span><span class="sxs-lookup"><span data-stu-id="023dc-167">-136</span></span>|
    |<span data-ttu-id="023dc-168">**IGST Payable Account**</span><span class="sxs-lookup"><span data-stu-id="023dc-168">**IGST Payable Account**</span></span>|<span data-ttu-id="023dc-169">1525</span><span class="sxs-lookup"><span data-stu-id="023dc-169">1525</span></span>|
    |<span data-ttu-id="023dc-170">**IGST Payable (Interim) Account**</span><span class="sxs-lookup"><span data-stu-id="023dc-170">**IGST Payable (Interim) Account**</span></span>|<span data-ttu-id="023dc-171">-1525</span><span class="sxs-lookup"><span data-stu-id="023dc-171">-1525</span></span>|
    

> [!TIP]
> <span data-ttu-id="023dc-172">In case of Intra-State Sale, CGST and SGST/UTGST will be calculated.</span><span class="sxs-lookup"><span data-stu-id="023dc-172">In case of Intra-State Sale, CGST and SGST/UTGST will be calculated.</span></span>

