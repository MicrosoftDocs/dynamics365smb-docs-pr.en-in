---
title: Service Transfer
description: Service Transfer
author: v-debapd
ms.service: dynamics365-business-central
ms.topic: article
ms.devlang: na
ms.tgt_pltfrm: na
ms.workload: na
ms.search.keywords: India, local, IN, English
ms.date: 10/01/2020
ms.author: v-debapd
ms.openlocfilehash: 96595eeacc9578dd56327905526efaa14d382059
ms.sourcegitcommit: ddbb5cede750df1baba4b3eab8fbed6744b5b9d6
ms.translationtype: HT
ms.contentlocale: en-IN
ms.lasthandoff: 10/01/2020
ms.locfileid: "3948628"
---
# <a name="service-transfer"></a><span data-ttu-id="67148-103">Service Transfer</span><span class="sxs-lookup"><span data-stu-id="67148-103">Service Transfer</span></span>

[!INCLUDE[vnext_preview](../../includes/vnext_preview.md)]

<span data-ttu-id="67148-104">Service transfers between locations, branches or divisions having different registration numbers are taxable under GST.</span><span class="sxs-lookup"><span data-stu-id="67148-104">Service transfers between locations, branches or divisions having different registration numbers are taxable under GST.</span></span> <span data-ttu-id="67148-105">In such a case, if services transferred within the state from one location to another, then CGST and SGST/UTGST will be levied, other-wise, where the registration number is same, there shall be no levy.</span><span class="sxs-lookup"><span data-stu-id="67148-105">In such a case, if services transferred within the state from one location to another, then CGST and SGST/UTGST will be levied, other-wise, where the registration number is same, there shall be no levy.</span></span> <span data-ttu-id="67148-106">Service transferred from one state to another state, then IGST will be levied.</span><span class="sxs-lookup"><span data-stu-id="67148-106">Service transferred from one state to another state, then IGST will be levied.</span></span>

## <a name="create-a-service-transfer-order"></a><span data-ttu-id="67148-107">Create a service transfer order</span><span class="sxs-lookup"><span data-stu-id="67148-107">Create a service transfer order</span></span>

1. <span data-ttu-id="67148-108">Choose the ![Search for Page or Report](image/search_small.png "Search for Page or Report icon") icon, enter **Service Transfer Order** , and then choose the related link.</span><span class="sxs-lookup"><span data-stu-id="67148-108">Choose the ![Search for Page or Report](image/search_small.png "Search for Page or Report icon") icon, enter **Service Transfer Order** , and then choose the related link.</span></span> 
2. <span data-ttu-id="67148-109">Select **Transfer-from Code** and **Transfer-to Code** on **Service Transfer Order** header.</span><span class="sxs-lookup"><span data-stu-id="67148-109">Select **Transfer-from Code** and **Transfer-to Code** on **Service Transfer Order** header.</span></span> <span data-ttu-id="67148-110">State Code and GST registration number should not be blank on **Location** card.</span><span class="sxs-lookup"><span data-stu-id="67148-110">State Code and GST registration number should not be blank on **Location** card.</span></span>
3. <span data-ttu-id="67148-111">Select **Ship Control Account** and **Receive Control Account** on **Service Transfer Order** header.</span><span class="sxs-lookup"><span data-stu-id="67148-111">Select **Ship Control Account** and **Receive Control Account** on **Service Transfer Order** header.</span></span>

4. <span data-ttu-id="67148-112">Select G/L Account for **Transfer From G/L Account No.** on **Shipment Line** and **Transfer To G/L Account No.** on **Receipt Line** .</span><span class="sxs-lookup"><span data-stu-id="67148-112">Select G/L Account for **Transfer From G/L Account No.** on **Shipment Line** and **Transfer To G/L Account No.** on **Receipt Line** .</span></span> <span data-ttu-id="67148-113">GST Group Code, HSN/SAC Code should not be blank on **G/L Account** card.</span><span class="sxs-lookup"><span data-stu-id="67148-113">GST Group Code, HSN/SAC Code should not be blank on **G/L Account** card.</span></span>

<span data-ttu-id="67148-114">For example, service for INR 10000 is being transferred on which 18% GST (9% CGST and 9% SGST/UTGST in case of Intra-State or Intra-Union Territory transaction or 18% IGST in case of Inter-State transaction), has to be charged.</span><span class="sxs-lookup"><span data-stu-id="67148-114">For example, service for INR 10000 is being transferred on which 18% GST (9% CGST and 9% SGST/UTGST in case of Intra-State or Intra-Union Territory transaction or 18% IGST in case of Inter-State transaction), has to be charged.</span></span>

- <span data-ttu-id="67148-115">GST Calculation on Service Transfer Order will appear in the Fact Box, as following:</span><span class="sxs-lookup"><span data-stu-id="67148-115">GST Calculation on Service Transfer Order will appear in the Fact Box, as following:</span></span>
    
    |<span data-ttu-id="67148-116">Component</span><span class="sxs-lookup"><span data-stu-id="67148-116">Component</span></span>|<span data-ttu-id="67148-117">Amount</span><span class="sxs-lookup"><span data-stu-id="67148-117">Amount</span></span>|
    |----------------------------------|---------------------------------------|  
    |<span data-ttu-id="67148-118">**GST Base Amount**</span><span class="sxs-lookup"><span data-stu-id="67148-118">**GST Base Amount**</span></span>|<span data-ttu-id="67148-119">10000</span><span class="sxs-lookup"><span data-stu-id="67148-119">10000</span></span>|  
    |<span data-ttu-id="67148-120">**IGST**</span><span class="sxs-lookup"><span data-stu-id="67148-120">**IGST**</span></span>|<span data-ttu-id="67148-121">1800</span><span class="sxs-lookup"><span data-stu-id="67148-121">1800</span></span>|
    |<span data-ttu-id="67148-122">**CGST**</span><span class="sxs-lookup"><span data-stu-id="67148-122">**CGST**</span></span>|<span data-ttu-id="67148-123">900</span><span class="sxs-lookup"><span data-stu-id="67148-123">900</span></span>| 
    |<span data-ttu-id="67148-124">**SGST**</span><span class="sxs-lookup"><span data-stu-id="67148-124">**SGST**</span></span>|<span data-ttu-id="67148-125">900</span><span class="sxs-lookup"><span data-stu-id="67148-125">900</span></span>|

- <span data-ttu-id="67148-126">On posting of shipment in case of Intra-State or Intra-Union Territory service transfer, GL Entries will be as following:</span><span class="sxs-lookup"><span data-stu-id="67148-126">On posting of shipment in case of Intra-State or Intra-Union Territory service transfer, GL Entries will be as following:</span></span>

    |<span data-ttu-id="67148-127">Particulars</span><span class="sxs-lookup"><span data-stu-id="67148-127">Particulars</span></span>|<span data-ttu-id="67148-128">Amount</span><span class="sxs-lookup"><span data-stu-id="67148-128">Amount</span></span>|
    |----------------------------------|---------------------------------------|  
    |<span data-ttu-id="67148-129">**Inter-location Control Account**</span><span class="sxs-lookup"><span data-stu-id="67148-129">**Inter-location Control Account**</span></span>|<span data-ttu-id="67148-130">11800</span><span class="sxs-lookup"><span data-stu-id="67148-130">11800</span></span>|
    |<span data-ttu-id="67148-131">**CGST Payable Account**</span><span class="sxs-lookup"><span data-stu-id="67148-131">**CGST Payable Account**</span></span>|<span data-ttu-id="67148-132">-900</span><span class="sxs-lookup"><span data-stu-id="67148-132">-900</span></span>|
    |<span data-ttu-id="67148-133">**SGST/UTGST Payable Account**</span><span class="sxs-lookup"><span data-stu-id="67148-133">**SGST/UTGST Payable Account**</span></span>|<span data-ttu-id="67148-134">-900</span><span class="sxs-lookup"><span data-stu-id="67148-134">-900</span></span>|
    |<span data-ttu-id="67148-135">**Services Account**</span><span class="sxs-lookup"><span data-stu-id="67148-135">**Services Account**</span></span>|<span data-ttu-id="67148-136">-10000</span><span class="sxs-lookup"><span data-stu-id="67148-136">-10000</span></span>|

- <span data-ttu-id="67148-137">On posting of receipt in case of Intra-State or Intra-Union Territory service transfer, GL Entries will be as following:</span><span class="sxs-lookup"><span data-stu-id="67148-137">On posting of receipt in case of Intra-State or Intra-Union Territory service transfer, GL Entries will be as following:</span></span>
    
    |<span data-ttu-id="67148-138">Particular</span><span class="sxs-lookup"><span data-stu-id="67148-138">Particular</span></span>|<span data-ttu-id="67148-139">Amount</span><span class="sxs-lookup"><span data-stu-id="67148-139">Amount</span></span>|
    |----------------------------------|---------------------------------------|  
    |<span data-ttu-id="67148-140">**Services Account**</span><span class="sxs-lookup"><span data-stu-id="67148-140">**Services Account**</span></span>|<span data-ttu-id="67148-141">10000</span><span class="sxs-lookup"><span data-stu-id="67148-141">10000</span></span>|  
    |<span data-ttu-id="67148-142">**SGST/UTGST Receivable Account**</span><span class="sxs-lookup"><span data-stu-id="67148-142">**SGST/UTGST Receivable Account**</span></span>|<span data-ttu-id="67148-143">900</span><span class="sxs-lookup"><span data-stu-id="67148-143">900</span></span>|  
    |<span data-ttu-id="67148-144">**CGST Receivable Account**</span><span class="sxs-lookup"><span data-stu-id="67148-144">**CGST Receivable Account**</span></span>|<span data-ttu-id="67148-145">900</span><span class="sxs-lookup"><span data-stu-id="67148-145">900</span></span>|
    |<span data-ttu-id="67148-146">**Inter-location Control Account**</span><span class="sxs-lookup"><span data-stu-id="67148-146">**Inter-location Control Account**</span></span>|<span data-ttu-id="67148-147">-11800</span><span class="sxs-lookup"><span data-stu-id="67148-147">-11800</span></span>|

- <span data-ttu-id="67148-148">On posting of shipment in case of Interstate service transfer, GL Entries will be as following:</span><span class="sxs-lookup"><span data-stu-id="67148-148">On posting of shipment in case of Interstate service transfer, GL Entries will be as following:</span></span>
    
    |<span data-ttu-id="67148-149">Particular</span><span class="sxs-lookup"><span data-stu-id="67148-149">Particular</span></span>|<span data-ttu-id="67148-150">Amount</span><span class="sxs-lookup"><span data-stu-id="67148-150">Amount</span></span>|
    |----------------------------------|---------------------------------------|  
    |<span data-ttu-id="67148-151">**Inter-location Control Account**</span><span class="sxs-lookup"><span data-stu-id="67148-151">**Inter-location Control Account**</span></span>|<span data-ttu-id="67148-152">11800</span><span class="sxs-lookup"><span data-stu-id="67148-152">11800</span></span>|
    |<span data-ttu-id="67148-153">**IGST Payable Account**</span><span class="sxs-lookup"><span data-stu-id="67148-153">**IGST Payable Account**</span></span>|<span data-ttu-id="67148-154">-1800</span><span class="sxs-lookup"><span data-stu-id="67148-154">-1800</span></span>|
    |<span data-ttu-id="67148-155">**Services Account**</span><span class="sxs-lookup"><span data-stu-id="67148-155">**Services Account**</span></span>|<span data-ttu-id="67148-156">-10000</span><span class="sxs-lookup"><span data-stu-id="67148-156">-10000</span></span>|

- <span data-ttu-id="67148-157">On posting of receipt in case of Interstate service transfer, GL Entries will be as following:</span><span class="sxs-lookup"><span data-stu-id="67148-157">On posting of receipt in case of Interstate service transfer, GL Entries will be as following:</span></span>
    
    |<span data-ttu-id="67148-158">Particular</span><span class="sxs-lookup"><span data-stu-id="67148-158">Particular</span></span>|<span data-ttu-id="67148-159">Amount</span><span class="sxs-lookup"><span data-stu-id="67148-159">Amount</span></span>|
    |----------------------------------|---------------------------------------|  
    |<span data-ttu-id="67148-160">**Services Account**</span><span class="sxs-lookup"><span data-stu-id="67148-160">**Services Account**</span></span>|<span data-ttu-id="67148-161">10000</span><span class="sxs-lookup"><span data-stu-id="67148-161">10000</span></span>|
    |<span data-ttu-id="67148-162">**IGST Receivable Account**</span><span class="sxs-lookup"><span data-stu-id="67148-162">**IGST Receivable Account**</span></span>|<span data-ttu-id="67148-163">1800</span><span class="sxs-lookup"><span data-stu-id="67148-163">1800</span></span>|
    |<span data-ttu-id="67148-164">**Inter-location Control Account**</span><span class="sxs-lookup"><span data-stu-id="67148-164">**Inter-location Control Account**</span></span>|<span data-ttu-id="67148-165">-11800</span><span class="sxs-lookup"><span data-stu-id="67148-165">-11800</span></span>|






































