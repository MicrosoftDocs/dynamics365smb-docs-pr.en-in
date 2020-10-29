---
title: Sales to Registered or Unregistered Customer
description: Sales to Registered or Unregistered Customer
author: v-debapd
ms.service: dynamics365-business-central
ms.topic: article
ms.devlang: na
ms.tgt_pltfrm: na
ms.workload: na
ms.search.keywords: India, local, IN, English
ms.date: 10/01/2020
ms.author: v-debapd
ms.openlocfilehash: 9cb00a88d7e6261eec7fd6706d58f15daed866ed
ms.sourcegitcommit: ddbb5cede750df1baba4b3eab8fbed6744b5b9d6
ms.translationtype: HT
ms.contentlocale: en-IN
ms.lasthandoff: 10/01/2020
ms.locfileid: "3948630"
---
# <a name="sales-to-registered-or-unregistered-customer"></a><span data-ttu-id="5b39b-103">Sales to Registered or Unregistered Customer</span><span class="sxs-lookup"><span data-stu-id="5b39b-103">Sales to Registered or Unregistered Customer</span></span>

[!INCLUDE[vnext_preview](../../includes/vnext_preview.md)]

<span data-ttu-id="5b39b-104">Sales to a registered customer are known as B2B sales, sales to an unregistered customer are known as B2C sales.</span><span class="sxs-lookup"><span data-stu-id="5b39b-104">Sales to a registered customer are known as B2B sales, sales to an unregistered customer are known as B2C sales.</span></span> <span data-ttu-id="5b39b-105">There is no difference in computation of tax for a B2B and B2C sales.</span><span class="sxs-lookup"><span data-stu-id="5b39b-105">There is no difference in computation of tax for a B2B and B2C sales.</span></span> <span data-ttu-id="5b39b-106">However, they are required to be reported separately in GSTR-1.</span><span class="sxs-lookup"><span data-stu-id="5b39b-106">However, they are required to be reported separately in GSTR-1.</span></span>

<span data-ttu-id="5b39b-107">Process of sales to registered or unregistered customer has been explained in this document.</span><span class="sxs-lookup"><span data-stu-id="5b39b-107">Process of sales to registered or unregistered customer has been explained in this document.</span></span>

## <a name="create-a-sales-invoice"></a><span data-ttu-id="5b39b-108">Create a sales invoice</span><span class="sxs-lookup"><span data-stu-id="5b39b-108">Create a sales invoice</span></span>

1. <span data-ttu-id="5b39b-109">Choose the ![Search for Page or Report](image/search_small.png "Search for Page or Report icon") icon, enter **Sales Invoice** , and then choose the related link.</span><span class="sxs-lookup"><span data-stu-id="5b39b-109">Choose the ![Search for Page or Report](image/search_small.png "Search for Page or Report icon") icon, enter **Sales Invoice** , and then choose the related link.</span></span>

2. <span data-ttu-id="5b39b-110">Select **Customer** on **Sales Invoice** header, GST customer type should be **Registered** or **Unregistered** .</span><span class="sxs-lookup"><span data-stu-id="5b39b-110">Select **Customer** on **Sales Invoice** header, GST customer type should be **Registered** or **Unregistered** .</span></span>

3. <span data-ttu-id="5b39b-111">Select **Item Code** for goods or **G/L Account** for service sales on **Sales Invoice** line.</span><span class="sxs-lookup"><span data-stu-id="5b39b-111">Select **Item Code** for goods or **G/L Account** for service sales on **Sales Invoice** line.</span></span> <span data-ttu-id="5b39b-112">GST Group Code, HSN/SAC Code should not be blank on the item or G/L account.</span><span class="sxs-lookup"><span data-stu-id="5b39b-112">GST Group Code, HSN/SAC Code should not be blank on the item or G/L account.</span></span> 

<span data-ttu-id="5b39b-113">For example, there is a sales invoice for INR 10,000 and 18% GST (i.e. 9% CGST and 9% SGST/UTGST in case of Intra-State or Intra-Union Territory transaction or 18% IGST in case of Inter-State transaction) has to be charged on the invoice amount.</span><span class="sxs-lookup"><span data-stu-id="5b39b-113">For example, there is a sales invoice for INR 10,000 and 18% GST (i.e. 9% CGST and 9% SGST/UTGST in case of Intra-State or Intra-Union Territory transaction or 18% IGST in case of Inter-State transaction) has to be charged on the invoice amount.</span></span>

- <span data-ttu-id="5b39b-114">GST calculation will appear in the Fact Box, as following:</span><span class="sxs-lookup"><span data-stu-id="5b39b-114">GST calculation will appear in the Fact Box, as following:</span></span>
    
    |<span data-ttu-id="5b39b-115">Component</span><span class="sxs-lookup"><span data-stu-id="5b39b-115">Component</span></span>|<span data-ttu-id="5b39b-116">Amount</span><span class="sxs-lookup"><span data-stu-id="5b39b-116">Amount</span></span>|
    |----------------------------------|---------------------------------------|  
    |<span data-ttu-id="5b39b-117">**GST Base Amount**</span><span class="sxs-lookup"><span data-stu-id="5b39b-117">**GST Base Amount**</span></span>|<span data-ttu-id="5b39b-118">10,000</span><span class="sxs-lookup"><span data-stu-id="5b39b-118">10,000</span></span>|  
    |<span data-ttu-id="5b39b-119">**CGST**</span><span class="sxs-lookup"><span data-stu-id="5b39b-119">**CGST**</span></span>|<span data-ttu-id="5b39b-120">900</span><span class="sxs-lookup"><span data-stu-id="5b39b-120">900</span></span>|  
    |<span data-ttu-id="5b39b-121">**SGST**</span><span class="sxs-lookup"><span data-stu-id="5b39b-121">**SGST**</span></span>|<span data-ttu-id="5b39b-122">900</span><span class="sxs-lookup"><span data-stu-id="5b39b-122">900</span></span>|
    |<span data-ttu-id="5b39b-123">**IGST**</span><span class="sxs-lookup"><span data-stu-id="5b39b-123">**IGST**</span></span>|<span data-ttu-id="5b39b-124">1800</span><span class="sxs-lookup"><span data-stu-id="5b39b-124">1800</span></span>|

- <span data-ttu-id="5b39b-125">GL Entries for Intra-State or Intra-Union Territory sale of goods to registered or unregistered customer, will be as following:</span><span class="sxs-lookup"><span data-stu-id="5b39b-125">GL Entries for Intra-State or Intra-Union Territory sale of goods to registered or unregistered customer, will be as following:</span></span>

    |<span data-ttu-id="5b39b-126">Particulars</span><span class="sxs-lookup"><span data-stu-id="5b39b-126">Particulars</span></span>|<span data-ttu-id="5b39b-127">Amount</span><span class="sxs-lookup"><span data-stu-id="5b39b-127">Amount</span></span>|
    |----------------------------------|---------------------------------------|  
    |<span data-ttu-id="5b39b-128">**Customer Account**</span><span class="sxs-lookup"><span data-stu-id="5b39b-128">**Customer Account**</span></span>|<span data-ttu-id="5b39b-129">11,800</span><span class="sxs-lookup"><span data-stu-id="5b39b-129">11,800</span></span>|  
    |<span data-ttu-id="5b39b-130">**SGST/UTGST Payable Account**</span><span class="sxs-lookup"><span data-stu-id="5b39b-130">**SGST/UTGST Payable Account**</span></span>|<span data-ttu-id="5b39b-131">- 900</span><span class="sxs-lookup"><span data-stu-id="5b39b-131">- 900</span></span>|  
    |<span data-ttu-id="5b39b-132">**CGST Payable Account**</span><span class="sxs-lookup"><span data-stu-id="5b39b-132">**CGST Payable Account**</span></span>|<span data-ttu-id="5b39b-133">- 900</span><span class="sxs-lookup"><span data-stu-id="5b39b-133">- 900</span></span>|
    |<span data-ttu-id="5b39b-134">**Sales Account**</span><span class="sxs-lookup"><span data-stu-id="5b39b-134">**Sales Account**</span></span>|<span data-ttu-id="5b39b-135">- 10000</span><span class="sxs-lookup"><span data-stu-id="5b39b-135">- 10000</span></span>|

- <span data-ttu-id="5b39b-136">GL Entries for Inter-State sale of goods to registered or unregistered customer, will be as following:</span><span class="sxs-lookup"><span data-stu-id="5b39b-136">GL Entries for Inter-State sale of goods to registered or unregistered customer, will be as following:</span></span>

    |<span data-ttu-id="5b39b-137">Particulars</span><span class="sxs-lookup"><span data-stu-id="5b39b-137">Particulars</span></span>|<span data-ttu-id="5b39b-138">Amount</span><span class="sxs-lookup"><span data-stu-id="5b39b-138">Amount</span></span>|
    |----------------------------------|---------------------------------------|  
    |<span data-ttu-id="5b39b-139">**Customer Account**</span><span class="sxs-lookup"><span data-stu-id="5b39b-139">**Customer Account**</span></span>|<span data-ttu-id="5b39b-140">11,800</span><span class="sxs-lookup"><span data-stu-id="5b39b-140">11,800</span></span>|  
    |<span data-ttu-id="5b39b-141">**IGST Payable Account**</span><span class="sxs-lookup"><span data-stu-id="5b39b-141">**IGST Payable Account**</span></span>|<span data-ttu-id="5b39b-142">- 1800</span><span class="sxs-lookup"><span data-stu-id="5b39b-142">- 1800</span></span>| 
    |<span data-ttu-id="5b39b-143">**Sales Account**</span><span class="sxs-lookup"><span data-stu-id="5b39b-143">**Sales Account**</span></span>|<span data-ttu-id="5b39b-144">- 10000</span><span class="sxs-lookup"><span data-stu-id="5b39b-144">- 10000</span></span>|

- <span data-ttu-id="5b39b-145">GL Entries for Intra-State or Intra-Union Territory sale of services to registered or unregistered customer, will be as following:</span><span class="sxs-lookup"><span data-stu-id="5b39b-145">GL Entries for Intra-State or Intra-Union Territory sale of services to registered or unregistered customer, will be as following:</span></span>

    |<span data-ttu-id="5b39b-146">Particular</span><span class="sxs-lookup"><span data-stu-id="5b39b-146">Particular</span></span>|<span data-ttu-id="5b39b-147">Amount</span><span class="sxs-lookup"><span data-stu-id="5b39b-147">Amount</span></span>|
    |----------------------------------|---------------------------------------|  
    |<span data-ttu-id="5b39b-148">**Customer Account**</span><span class="sxs-lookup"><span data-stu-id="5b39b-148">**Customer Account**</span></span>|<span data-ttu-id="5b39b-149">11,800</span><span class="sxs-lookup"><span data-stu-id="5b39b-149">11,800</span></span>|  
    |<span data-ttu-id="5b39b-150">**SGST/UTGST Payable Account**</span><span class="sxs-lookup"><span data-stu-id="5b39b-150">**SGST/UTGST Payable Account**</span></span>|<span data-ttu-id="5b39b-151">- 900</span><span class="sxs-lookup"><span data-stu-id="5b39b-151">- 900</span></span>|  
    |<span data-ttu-id="5b39b-152">**CGST Payable Account**</span><span class="sxs-lookup"><span data-stu-id="5b39b-152">**CGST Payable Account**</span></span>|<span data-ttu-id="5b39b-153">- 900</span><span class="sxs-lookup"><span data-stu-id="5b39b-153">- 900</span></span>|
    |<span data-ttu-id="5b39b-154">**Sales Account**</span><span class="sxs-lookup"><span data-stu-id="5b39b-154">**Sales Account**</span></span>|<span data-ttu-id="5b39b-155">- 10000</span><span class="sxs-lookup"><span data-stu-id="5b39b-155">- 10000</span></span>|

- <span data-ttu-id="5b39b-156">GL Entries for Inter-State sale of services to registered or unregistered customer, will be as following :</span><span class="sxs-lookup"><span data-stu-id="5b39b-156">GL Entries for Inter-State sale of services to registered or unregistered customer, will be as following :</span></span>

    |<span data-ttu-id="5b39b-157">Particular</span><span class="sxs-lookup"><span data-stu-id="5b39b-157">Particular</span></span>|<span data-ttu-id="5b39b-158">Amount</span><span class="sxs-lookup"><span data-stu-id="5b39b-158">Amount</span></span>|
    |----------------------------------|---------------------------------------|  
    |<span data-ttu-id="5b39b-159">**Customer Account**</span><span class="sxs-lookup"><span data-stu-id="5b39b-159">**Customer Account**</span></span>|<span data-ttu-id="5b39b-160">11,800</span><span class="sxs-lookup"><span data-stu-id="5b39b-160">11,800</span></span>|  
    |<span data-ttu-id="5b39b-161">**IGST Payable Account**</span><span class="sxs-lookup"><span data-stu-id="5b39b-161">**IGST Payable Account**</span></span>|<span data-ttu-id="5b39b-162">- 1800</span><span class="sxs-lookup"><span data-stu-id="5b39b-162">- 1800</span></span>|
    |<span data-ttu-id="5b39b-163">**Services Account**</span><span class="sxs-lookup"><span data-stu-id="5b39b-163">**Services Account**</span></span>|<span data-ttu-id="5b39b-164">- 10000</span><span class="sxs-lookup"><span data-stu-id="5b39b-164">- 10000</span></span>|

> [!TIP]
> <span data-ttu-id="5b39b-165">System will automatically update 'Nature of Supply' for Registered customer as B2B and for Unregistered customer as B2C.</span><span class="sxs-lookup"><span data-stu-id="5b39b-165">System will automatically update 'Nature of Supply' for Registered customer as B2B and for Unregistered customer as B2C.</span></span>






































