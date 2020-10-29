---
title: TDS calculation considering Threshold limits
description: TDS calculation considering Threshold limits
author: v-debapd
ms.service: dynamics365-business-central
ms.topic: article
ms.devlang: na
ms.tgt_pltfrm: na
ms.workload: na
ms.search.keywords: India, local, IN, English
ms.date: 10/01/2020
ms.author: v-debapd
ms.openlocfilehash: c3e428934ea8657d1f25b9f56b9224db551cdaf1
ms.sourcegitcommit: ddbb5cede750df1baba4b3eab8fbed6744b5b9d6
ms.translationtype: HT
ms.contentlocale: en-IN
ms.lasthandoff: 10/01/2020
ms.locfileid: "3948603"
---
# <a name="tds-with-threshold"></a><span data-ttu-id="77f6e-103">TDS with Threshold</span><span class="sxs-lookup"><span data-stu-id="77f6e-103">TDS with Threshold</span></span>

[!INCLUDE[vnext_preview](../../includes/vnext_preview.md)]

<span data-ttu-id="77f6e-104">This topic explains the requirement of threshold amount in TDS and  the process of calculating TDS for such transactions.</span><span class="sxs-lookup"><span data-stu-id="77f6e-104">This topic explains the requirement of threshold amount in TDS and  the process of calculating TDS for such transactions.</span></span>

## <a name="tds-calculation-considering-threshold-limits"></a><span data-ttu-id="77f6e-105">TDS calculation considering threshold limits</span><span class="sxs-lookup"><span data-stu-id="77f6e-105">TDS calculation considering threshold limits</span></span>

<span data-ttu-id="77f6e-106">TDS Threshold defines the threshold limit for each TDS Section.</span><span class="sxs-lookup"><span data-stu-id="77f6e-106">TDS Threshold defines the threshold limit for each TDS Section.</span></span>  <span data-ttu-id="77f6e-107">TDS can be deducted only if the total transaction with the assessee exceeds the threshold limit in the financial year.</span><span class="sxs-lookup"><span data-stu-id="77f6e-107">TDS can be deducted only if the total transaction with the assessee exceeds the threshold limit in the financial year.</span></span>

<span data-ttu-id="77f6e-108">In a scenario where, credit or payment to a contractor under TDS Section 194C is below TDS threshold limit of INR 1,00,000 in aggregate in a financial year and single transaction threshold limit INR 30,000, TDS will not be deducted.</span><span class="sxs-lookup"><span data-stu-id="77f6e-108">In a scenario where, credit or payment to a contractor under TDS Section 194C is below TDS threshold limit of INR 1,00,000 in aggregate in a financial year and single transaction threshold limit INR 30,000, TDS will not be deducted.</span></span> 

<span data-ttu-id="77f6e-109">In the example given below, four transactions of INR 29,000 took place in a financial year, on the fourth transaction TDS will be deducted as the aggregate (previous transactions) credit or payment amount exceeds the TDS threshold limit of INR 1,00,000.</span><span class="sxs-lookup"><span data-stu-id="77f6e-109">In the example given below, four transactions of INR 29,000 took place in a financial year, on the fourth transaction TDS will be deducted as the aggregate (previous transactions) credit or payment amount exceeds the TDS threshold limit of INR 1,00,000.</span></span> <span data-ttu-id="77f6e-110">TDS Calculation as following:</span><span class="sxs-lookup"><span data-stu-id="77f6e-110">TDS Calculation as following:</span></span>

   |<span data-ttu-id="77f6e-111">Particulars</span><span class="sxs-lookup"><span data-stu-id="77f6e-111">Particulars</span></span>|<span data-ttu-id="77f6e-112">Amount Credited or Paid</span><span class="sxs-lookup"><span data-stu-id="77f6e-112">Amount Credited or Paid</span></span>|<span data-ttu-id="77f6e-113">TDS Rates</span><span class="sxs-lookup"><span data-stu-id="77f6e-113">TDS Rates</span></span>|<span data-ttu-id="77f6e-114">TDS Amount</span><span class="sxs-lookup"><span data-stu-id="77f6e-114">TDS Amount</span></span>|<span data-ttu-id="77f6e-115">Threshold Limit</span><span class="sxs-lookup"><span data-stu-id="77f6e-115">Threshold Limit</span></span>|
   |--------------------|-----------------------|-----------------|----------|-------|  
   |<span data-ttu-id="77f6e-116">First Invoice</span><span class="sxs-lookup"><span data-stu-id="77f6e-116">First Invoice</span></span>|<span data-ttu-id="77f6e-117">29000</span><span class="sxs-lookup"><span data-stu-id="77f6e-117">29000</span></span>|<span data-ttu-id="77f6e-118">2%</span><span class="sxs-lookup"><span data-stu-id="77f6e-118">2%</span></span>|<span data-ttu-id="77f6e-119">Zero</span><span class="sxs-lookup"><span data-stu-id="77f6e-119">Zero</span></span>|<span data-ttu-id="77f6e-120">Less than Single Transaction Threshold Limit 30,000</span><span class="sxs-lookup"><span data-stu-id="77f6e-120">Less than Single Transaction Threshold Limit 30,000</span></span>|
   |<span data-ttu-id="77f6e-121">Second Invoice</span><span class="sxs-lookup"><span data-stu-id="77f6e-121">Second Invoice</span></span>|<span data-ttu-id="77f6e-122">29000</span><span class="sxs-lookup"><span data-stu-id="77f6e-122">29000</span></span>|<span data-ttu-id="77f6e-123">2%</span><span class="sxs-lookup"><span data-stu-id="77f6e-123">2%</span></span>|<span data-ttu-id="77f6e-124">Zero</span><span class="sxs-lookup"><span data-stu-id="77f6e-124">Zero</span></span>|<span data-ttu-id="77f6e-125">Less than Single Transaction Threshold Limit 30,000</span><span class="sxs-lookup"><span data-stu-id="77f6e-125">Less than Single Transaction Threshold Limit 30,000</span></span>|
   |<span data-ttu-id="77f6e-126">Third Invoice</span><span class="sxs-lookup"><span data-stu-id="77f6e-126">Third Invoice</span></span>|<span data-ttu-id="77f6e-127">29000</span><span class="sxs-lookup"><span data-stu-id="77f6e-127">29000</span></span>|<span data-ttu-id="77f6e-128">2%</span><span class="sxs-lookup"><span data-stu-id="77f6e-128">2%</span></span>|<span data-ttu-id="77f6e-129">Zero</span><span class="sxs-lookup"><span data-stu-id="77f6e-129">Zero</span></span>|<span data-ttu-id="77f6e-130">Less than Single Transaction Threshold Limit 30,000</span><span class="sxs-lookup"><span data-stu-id="77f6e-130">Less than Single Transaction Threshold Limit 30,000</span></span>|
   |<span data-ttu-id="77f6e-131">Forth Invoice</span><span class="sxs-lookup"><span data-stu-id="77f6e-131">Forth Invoice</span></span>|<span data-ttu-id="77f6e-132">20000</span><span class="sxs-lookup"><span data-stu-id="77f6e-132">20000</span></span>|<span data-ttu-id="77f6e-133">2%</span><span class="sxs-lookup"><span data-stu-id="77f6e-133">2%</span></span>|<span data-ttu-id="77f6e-134">2,140 (2% of 1,07,000 i.e. total of all invoices)</span><span class="sxs-lookup"><span data-stu-id="77f6e-134">2,140 (2% of 1,07,000 i.e. total of all invoices)</span></span>|<span data-ttu-id="77f6e-135">Exceeds TDS Threshold Limit 1,00,000</span><span class="sxs-lookup"><span data-stu-id="77f6e-135">Exceeds TDS Threshold Limit 1,00,000</span></span>|

1. <span data-ttu-id="77f6e-136">GL Entries for TDS where payment is less than threshold limits (first transaction where vendor has given the invoice for INR 29,000), will be as following:</span><span class="sxs-lookup"><span data-stu-id="77f6e-136">GL Entries for TDS where payment is less than threshold limits (first transaction where vendor has given the invoice for INR 29,000), will be as following:</span></span>
    
    |<span data-ttu-id="77f6e-137">Particulars</span><span class="sxs-lookup"><span data-stu-id="77f6e-137">Particulars</span></span>|<span data-ttu-id="77f6e-138">Amount</span><span class="sxs-lookup"><span data-stu-id="77f6e-138">Amount</span></span>|
    |----------------------------------|---------------------------------------|  
    |<span data-ttu-id="77f6e-139">**Purchases Account**</span><span class="sxs-lookup"><span data-stu-id="77f6e-139">**Purchases Account**</span></span>|<span data-ttu-id="77f6e-140">29000</span><span class="sxs-lookup"><span data-stu-id="77f6e-140">29000</span></span>| 
    |<span data-ttu-id="77f6e-141">**Vendor Account**</span><span class="sxs-lookup"><span data-stu-id="77f6e-141">**Vendor Account**</span></span>|<span data-ttu-id="77f6e-142">-29000</span><span class="sxs-lookup"><span data-stu-id="77f6e-142">-29000</span></span>|

2. <span data-ttu-id="77f6e-143">GL Entries for TDS where payment is less than threshold limits (second transaction where vendor has given the invoice for INR 29,000), will be as following:</span><span class="sxs-lookup"><span data-stu-id="77f6e-143">GL Entries for TDS where payment is less than threshold limits (second transaction where vendor has given the invoice for INR 29,000), will be as following:</span></span>

    |<span data-ttu-id="77f6e-144">Particulars</span><span class="sxs-lookup"><span data-stu-id="77f6e-144">Particulars</span></span>|<span data-ttu-id="77f6e-145">Amount</span><span class="sxs-lookup"><span data-stu-id="77f6e-145">Amount</span></span>|
    |----------------------------------|---------------------------------------|  
    |<span data-ttu-id="77f6e-146">**Purchases Account**</span><span class="sxs-lookup"><span data-stu-id="77f6e-146">**Purchases Account**</span></span>|<span data-ttu-id="77f6e-147">29000</span><span class="sxs-lookup"><span data-stu-id="77f6e-147">29000</span></span>|  
    |<span data-ttu-id="77f6e-148">**Vendor Account**</span><span class="sxs-lookup"><span data-stu-id="77f6e-148">**Vendor Account**</span></span>|<span data-ttu-id="77f6e-149">-29000</span><span class="sxs-lookup"><span data-stu-id="77f6e-149">-29000</span></span>|

3. <span data-ttu-id="77f6e-150">GL Entries for TDS where payment is less than threshold limits (third transaction where vendor has given the invoice for INR 29,000), will be as following:</span><span class="sxs-lookup"><span data-stu-id="77f6e-150">GL Entries for TDS where payment is less than threshold limits (third transaction where vendor has given the invoice for INR 29,000), will be as following:</span></span>
 
    |<span data-ttu-id="77f6e-151">Particulars</span><span class="sxs-lookup"><span data-stu-id="77f6e-151">Particulars</span></span>|<span data-ttu-id="77f6e-152">Amount</span><span class="sxs-lookup"><span data-stu-id="77f6e-152">Amount</span></span>|
    |----------------------------------|---------------------------------------|  
    |<span data-ttu-id="77f6e-153">**Purchases Account**</span><span class="sxs-lookup"><span data-stu-id="77f6e-153">**Purchases Account**</span></span>|<span data-ttu-id="77f6e-154">29000</span><span class="sxs-lookup"><span data-stu-id="77f6e-154">29000</span></span>|  
    |<span data-ttu-id="77f6e-155">**Vendor Account**</span><span class="sxs-lookup"><span data-stu-id="77f6e-155">**Vendor Account**</span></span>|<span data-ttu-id="77f6e-156">-29000</span><span class="sxs-lookup"><span data-stu-id="77f6e-156">-29000</span></span>|

4. <span data-ttu-id="77f6e-157">GL Entries for TDS where payment is more than (exceeding) Threshold limits (forth transaction where vendor has given the invoice for INR 20,000), will be as following:</span><span class="sxs-lookup"><span data-stu-id="77f6e-157">GL Entries for TDS where payment is more than (exceeding) Threshold limits (forth transaction where vendor has given the invoice for INR 20,000), will be as following:</span></span>
    
    |<span data-ttu-id="77f6e-158">Particulars</span><span class="sxs-lookup"><span data-stu-id="77f6e-158">Particulars</span></span>|<span data-ttu-id="77f6e-159">Amount</span><span class="sxs-lookup"><span data-stu-id="77f6e-159">Amount</span></span>|
    |----------------------------------|---------------------------------------|  
    |<span data-ttu-id="77f6e-160">**Purchases Account**</span><span class="sxs-lookup"><span data-stu-id="77f6e-160">**Purchases Account**</span></span>|<span data-ttu-id="77f6e-161">29000</span><span class="sxs-lookup"><span data-stu-id="77f6e-161">29000</span></span>| 
    |<span data-ttu-id="77f6e-162">**TDS Payable Account**</span><span class="sxs-lookup"><span data-stu-id="77f6e-162">**TDS Payable Account**</span></span>|<span data-ttu-id="77f6e-163">2140</span><span class="sxs-lookup"><span data-stu-id="77f6e-163">2140</span></span>| 
    |<span data-ttu-id="77f6e-164">**Vendor Account**</span><span class="sxs-lookup"><span data-stu-id="77f6e-164">**Vendor Account**</span></span>|<span data-ttu-id="77f6e-165">-29000</span><span class="sxs-lookup"><span data-stu-id="77f6e-165">-29000</span></span>|






































