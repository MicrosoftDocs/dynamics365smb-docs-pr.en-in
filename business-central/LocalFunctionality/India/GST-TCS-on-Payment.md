---
title: GST TCS on Vendor Payment
description: GST TCS on Vendor Payment
author: v-debapd
ms.service: dynamics365-business-central
ms.topic: article
ms.devlang: na
ms.tgt_pltfrm: na
ms.workload: na
ms.search.keywords: India, local, IN, English
ms.date: 10/01/2020
ms.author: v-debapd
ms.openlocfilehash: 4e27b50b7d104323a60740b0f4e31799b591b31f
ms.sourcegitcommit: ddbb5cede750df1baba4b3eab8fbed6744b5b9d6
ms.translationtype: HT
ms.contentlocale: en-IN
ms.lasthandoff: 10/01/2020
ms.locfileid: "3948623"
---
# <a name="gst-tcs-on-vendor-payment"></a><span data-ttu-id="e63f8-103">GST TCS on Vendor Payment</span><span class="sxs-lookup"><span data-stu-id="e63f8-103">GST TCS on Vendor Payment</span></span>

[!INCLUDE[vnext_preview](../../includes/vnext_preview.md)]

<span data-ttu-id="e63f8-104">GST TCS can be applicable for Registered Vendor.</span><span class="sxs-lookup"><span data-stu-id="e63f8-104">GST TCS can be applicable for Registered Vendor.</span></span> <span data-ttu-id="e63f8-105">On posting of GST TCS transaction against Vendor, system updates 'Liable to Pay' field in GST TDS/TCS Entry table as 'TRUE'.</span><span class="sxs-lookup"><span data-stu-id="e63f8-105">On posting of GST TCS transaction against Vendor, system updates 'Liable to Pay' field in GST TDS/TCS Entry table as 'TRUE'.</span></span> <span data-ttu-id="e63f8-106">The GST TCS entries that have 'Liable to Pay' field 'TRUE' will be shown on settlement page.</span><span class="sxs-lookup"><span data-stu-id="e63f8-106">The GST TCS entries that have 'Liable to Pay' field 'TRUE' will be shown on settlement page.</span></span> <span data-ttu-id="e63f8-107">The GST TCS Liability can only be paid through Cash or Bank.</span><span class="sxs-lookup"><span data-stu-id="e63f8-107">The GST TCS Liability can only be paid through Cash or Bank.</span></span> <span data-ttu-id="e63f8-108">It cannot be set off against any available credit.</span><span class="sxs-lookup"><span data-stu-id="e63f8-108">It cannot be set off against any available credit.</span></span>

<span data-ttu-id="e63f8-109">For example, INR 1000 paid to the vendor and 1% GST TCS (0.50% CGST, 0.50% SGST for Intra-State or Intra-Union Territory and 1% IGST for Inter State) has to be calculated on payment amount.</span><span class="sxs-lookup"><span data-stu-id="e63f8-109">For example, INR 1000 paid to the vendor and 1% GST TCS (0.50% CGST, 0.50% SGST for Intra-State or Intra-Union Territory and 1% IGST for Inter State) has to be calculated on payment amount.</span></span>

1. <span data-ttu-id="e63f8-110">GST calculation will appear in the Fact Box on Bank or Cash Payment Voucher, as following:</span><span class="sxs-lookup"><span data-stu-id="e63f8-110">GST calculation will appear in the Fact Box on Bank or Cash Payment Voucher, as following:</span></span>
    
    |<span data-ttu-id="e63f8-111">Component</span><span class="sxs-lookup"><span data-stu-id="e63f8-111">Component</span></span>|<span data-ttu-id="e63f8-112">Amount</span><span class="sxs-lookup"><span data-stu-id="e63f8-112">Amount</span></span>|
    |----------------------------------|---------------------------------------|  
    |<span data-ttu-id="e63f8-113">**Payment Amount**</span><span class="sxs-lookup"><span data-stu-id="e63f8-113">**Payment Amount**</span></span>|<span data-ttu-id="e63f8-114">1000</span><span class="sxs-lookup"><span data-stu-id="e63f8-114">1000</span></span>|
    |<span data-ttu-id="e63f8-115">**GST Transactional Value**</span><span class="sxs-lookup"><span data-stu-id="e63f8-115">**GST Transactional Value**</span></span>|<span data-ttu-id="e63f8-116">1,000</span><span class="sxs-lookup"><span data-stu-id="e63f8-116">1,000</span></span>|
    |<span data-ttu-id="e63f8-117">**CGST Amount**</span><span class="sxs-lookup"><span data-stu-id="e63f8-117">**CGST Amount**</span></span>|<span data-ttu-id="e63f8-118">5</span><span class="sxs-lookup"><span data-stu-id="e63f8-118">5</span></span>|
    |<span data-ttu-id="e63f8-119">**SGST Amount**</span><span class="sxs-lookup"><span data-stu-id="e63f8-119">**SGST Amount**</span></span>|<span data-ttu-id="e63f8-120">5</span><span class="sxs-lookup"><span data-stu-id="e63f8-120">5</span></span>|
    |<span data-ttu-id="e63f8-121">**IGST Amount**</span><span class="sxs-lookup"><span data-stu-id="e63f8-121">**IGST Amount**</span></span>|<span data-ttu-id="e63f8-122">10</span><span class="sxs-lookup"><span data-stu-id="e63f8-122">10</span></span>|

## <a name="gst-tcs-on-vendor-payment-entry-process"></a><span data-ttu-id="e63f8-123">GST TCS on vendor payment entry process</span><span class="sxs-lookup"><span data-stu-id="e63f8-123">GST TCS on vendor payment entry process</span></span>
 
1. <span data-ttu-id="e63f8-124">Choose the ![Search for Page or Report](image/search_small.png "Search for Page or Report icon") icon, enter **Bank Payment Voucher** or **Cash Payment Voucher** , and then choose the related link.</span><span class="sxs-lookup"><span data-stu-id="e63f8-124">Choose the ![Search for Page or Report](image/search_small.png "Search for Page or Report icon") icon, enter **Bank Payment Voucher** or **Cash Payment Voucher** , and then choose the related link.</span></span>
2. <span data-ttu-id="e63f8-125">Fill in the fields as described on **Bank Payment Voucher** or **Cash Payment Voucher** .</span><span class="sxs-lookup"><span data-stu-id="e63f8-125">Fill in the fields as described on **Bank Payment Voucher** or **Cash Payment Voucher** .</span></span>
    
    |<span data-ttu-id="e63f8-126">Field</span><span class="sxs-lookup"><span data-stu-id="e63f8-126">Field</span></span>|<span data-ttu-id="e63f8-127">Description</span><span class="sxs-lookup"><span data-stu-id="e63f8-127">Description</span></span>| 
    |---------------------------------|  ---------------------------------------| 
    |<span data-ttu-id="e63f8-128">**Posting Date**</span><span class="sxs-lookup"><span data-stu-id="e63f8-128">**Posting Date**</span></span>|<span data-ttu-id="e63f8-129">Specify the posting date of the document.</span><span class="sxs-lookup"><span data-stu-id="e63f8-129">Specify the posting date of the document.</span></span>|
    |<span data-ttu-id="e63f8-130">**Document Type**</span><span class="sxs-lookup"><span data-stu-id="e63f8-130">**Document Type**</span></span>|<span data-ttu-id="e63f8-131">Specify as 'Payment'</span><span class="sxs-lookup"><span data-stu-id="e63f8-131">Specify as 'Payment'</span></span>|
    |<span data-ttu-id="e63f8-132">**Account Type**</span><span class="sxs-lookup"><span data-stu-id="e63f8-132">**Account Type**</span></span>|<span data-ttu-id="e63f8-133">Specify as 'Vendor'</span><span class="sxs-lookup"><span data-stu-id="e63f8-133">Specify as 'Vendor'</span></span>|
    |<span data-ttu-id="e63f8-134">**Account No.**</span><span class="sxs-lookup"><span data-stu-id="e63f8-134">**Account No.**</span></span>|<span data-ttu-id="e63f8-135">Select the relevant vendor code.</span><span class="sxs-lookup"><span data-stu-id="e63f8-135">Select the relevant vendor code.</span></span>|
    |<span data-ttu-id="e63f8-136">**Amount**</span><span class="sxs-lookup"><span data-stu-id="e63f8-136">**Amount**</span></span>|<span data-ttu-id="e63f8-137">Specify the amount.</span><span class="sxs-lookup"><span data-stu-id="e63f8-137">Specify the amount.</span></span>|
    |<span data-ttu-id="e63f8-138">**Bal. Account Type**</span><span class="sxs-lookup"><span data-stu-id="e63f8-138">**Bal. Account Type**</span></span>|<span data-ttu-id="e63f8-139">Specify G/L Account or Bank Account.</span><span class="sxs-lookup"><span data-stu-id="e63f8-139">Specify G/L Account or Bank Account.</span></span>|
    |<span data-ttu-id="e63f8-140">**Location Code**</span><span class="sxs-lookup"><span data-stu-id="e63f8-140">**Location Code**</span></span>|<span data-ttu-id="e63f8-141">Specify the relevant location code.</span><span class="sxs-lookup"><span data-stu-id="e63f8-141">Specify the relevant location code.</span></span>|
    |<span data-ttu-id="e63f8-142">**GST TCS State Code**</span><span class="sxs-lookup"><span data-stu-id="e63f8-142">**GST TCS State Code**</span></span>|<span data-ttu-id="e63f8-143">Specify the relevant state code.</span><span class="sxs-lookup"><span data-stu-id="e63f8-143">Specify the relevant state code.</span></span>|
    |<span data-ttu-id="e63f8-144">**GST TDS/TCS Base Amount**</span><span class="sxs-lookup"><span data-stu-id="e63f8-144">**GST TDS/TCS Base Amount**</span></span>|<span data-ttu-id="e63f8-145">Specify the GST TCS calculation base amount.</span><span class="sxs-lookup"><span data-stu-id="e63f8-145">Specify the GST TCS calculation base amount.</span></span>|
    |<span data-ttu-id="e63f8-146">**GST TCS**</span><span class="sxs-lookup"><span data-stu-id="e63f8-146">**GST TCS**</span></span>|<span data-ttu-id="e63f8-147">Mark this field as True.</span><span class="sxs-lookup"><span data-stu-id="e63f8-147">Mark this field as True.</span></span>|

    
3. <span data-ttu-id="e63f8-148">GL Entries for GST TCS - Intrastate Transaction, will be as following:</span><span class="sxs-lookup"><span data-stu-id="e63f8-148">GL Entries for GST TCS - Intrastate Transaction, will be as following:</span></span>

    |<span data-ttu-id="e63f8-149">Particulars</span><span class="sxs-lookup"><span data-stu-id="e63f8-149">Particulars</span></span>|<span data-ttu-id="e63f8-150">Amount</span><span class="sxs-lookup"><span data-stu-id="e63f8-150">Amount</span></span>|
    |----------------------------------|---------------------------------------|  
    |<span data-ttu-id="e63f8-151">**Vendor Account**</span><span class="sxs-lookup"><span data-stu-id="e63f8-151">**Vendor Account**</span></span>|<span data-ttu-id="e63f8-152">1000</span><span class="sxs-lookup"><span data-stu-id="e63f8-152">1000</span></span>|  
    |<span data-ttu-id="e63f8-153">**CGST TCS Payable Account**</span><span class="sxs-lookup"><span data-stu-id="e63f8-153">**CGST TCS Payable Account**</span></span>|<span data-ttu-id="e63f8-154">-5</span><span class="sxs-lookup"><span data-stu-id="e63f8-154">-5</span></span>|  
    |<span data-ttu-id="e63f8-155">**SGST/UTGST TCS Payable Account**</span><span class="sxs-lookup"><span data-stu-id="e63f8-155">**SGST/UTGST TCS Payable Account**</span></span>|<span data-ttu-id="e63f8-156">-5</span><span class="sxs-lookup"><span data-stu-id="e63f8-156">-5</span></span>| 
    |<span data-ttu-id="e63f8-157">**Bank Account**</span><span class="sxs-lookup"><span data-stu-id="e63f8-157">**Bank Account**</span></span>|<span data-ttu-id="e63f8-158">-990</span><span class="sxs-lookup"><span data-stu-id="e63f8-158">-990</span></span>| 
    
3. <span data-ttu-id="e63f8-159">GL Entries for GST TCS - Interstate Transaction, will be as following:</span><span class="sxs-lookup"><span data-stu-id="e63f8-159">GL Entries for GST TCS - Interstate Transaction, will be as following:</span></span>

    |<span data-ttu-id="e63f8-160">Particulars</span><span class="sxs-lookup"><span data-stu-id="e63f8-160">Particulars</span></span>|<span data-ttu-id="e63f8-161">Amount</span><span class="sxs-lookup"><span data-stu-id="e63f8-161">Amount</span></span>|
    |----------------------------------|---------------------------------------|  
    |<span data-ttu-id="e63f8-162">**Vendor Account**</span><span class="sxs-lookup"><span data-stu-id="e63f8-162">**Vendor Account**</span></span>|<span data-ttu-id="e63f8-163">1000</span><span class="sxs-lookup"><span data-stu-id="e63f8-163">1000</span></span>|  
    |<span data-ttu-id="e63f8-164">**IGST TCS Payable Account**</span><span class="sxs-lookup"><span data-stu-id="e63f8-164">**IGST TCS Payable Account**</span></span>|<span data-ttu-id="e63f8-165">-10</span><span class="sxs-lookup"><span data-stu-id="e63f8-165">-10</span></span>|  
    |<span data-ttu-id="e63f8-166">**Bank Account**</span><span class="sxs-lookup"><span data-stu-id="e63f8-166">**Bank Account**</span></span>|<span data-ttu-id="e63f8-167">-990</span><span class="sxs-lookup"><span data-stu-id="e63f8-167">-990</span></span>| 

