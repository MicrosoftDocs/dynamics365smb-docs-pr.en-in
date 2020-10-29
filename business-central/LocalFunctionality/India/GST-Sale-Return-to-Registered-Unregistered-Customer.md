---
title: Sales Return of Goods from Registered or Unregistered Customer
description: Sales Return of Goods from Registered or Unregistered Customer
author: v-debapd
ms.service: dynamics365-business-central
ms.topic: article
ms.devlang: na
ms.tgt_pltfrm: na
ms.workload: na
ms.search.keywords: India, local, IN, English
ms.date: 10/01/2020
ms.author: v-debapd
ms.openlocfilehash: cf9c52e6b23b649ace742e72c1375530a08afe8c
ms.sourcegitcommit: ddbb5cede750df1baba4b3eab8fbed6744b5b9d6
ms.translationtype: HT
ms.contentlocale: en-IN
ms.lasthandoff: 10/01/2020
ms.locfileid: "3948633"
---
# <a name="sales-return-of-goods-from-registered-or-unregistered-customer"></a><span data-ttu-id="02fee-103">Sales Return of Goods from Registered or Unregistered Customer</span><span class="sxs-lookup"><span data-stu-id="02fee-103">Sales Return of Goods from Registered or Unregistered Customer</span></span>

[!INCLUDE[vnext_preview](../../includes/vnext_preview.md)]

<span data-ttu-id="02fee-104">Sales to a registered customer are known as B2B sales, sales to an unregistered customer are known as B2C sales.</span><span class="sxs-lookup"><span data-stu-id="02fee-104">Sales to a registered customer are known as B2B sales, sales to an unregistered customer are known as B2C sales.</span></span> <span data-ttu-id="02fee-105">There is no difference in computation of tax for a B2B and B2C sales.</span><span class="sxs-lookup"><span data-stu-id="02fee-105">There is no difference in computation of tax for a B2B and B2C sales.</span></span> <span data-ttu-id="02fee-106">However, they are required to be reported in separately in GSTR-1.</span><span class="sxs-lookup"><span data-stu-id="02fee-106">However, they are required to be reported in separately in GSTR-1.</span></span>

<span data-ttu-id="02fee-107">A customer may require to return the goods or issue credit note due to various reasons like damaged goods, quality issues etc.</span><span class="sxs-lookup"><span data-stu-id="02fee-107">A customer may require to return the goods or issue credit note due to various reasons like damaged goods, quality issues etc.</span></span>

<span data-ttu-id="02fee-108">Process of sale return from registered or unregistered customer has been explained in this document.</span><span class="sxs-lookup"><span data-stu-id="02fee-108">Process of sale return from registered or unregistered customer has been explained in this document.</span></span>

## <a name="create-a-sales-return-order-or-credit-memo"></a><span data-ttu-id="02fee-109">Create a sales return order or credit memo</span><span class="sxs-lookup"><span data-stu-id="02fee-109">Create a sales return order or credit memo</span></span>

1. <span data-ttu-id="02fee-110">Choose the ![Search for Page or Report](image/search_small.png "Search for Page or Report icon") icon, enter **Sales Return Order** or **Sales Credit Memo** , and then choose the related link.</span><span class="sxs-lookup"><span data-stu-id="02fee-110">Choose the ![Search for Page or Report](image/search_small.png "Search for Page or Report icon") icon, enter **Sales Return Order** or **Sales Credit Memo** , and then choose the related link.</span></span> 
2. <span data-ttu-id="02fee-111">Select **Customer** on **Sales Return Order** or **Sales Credit Memo** header, GST customer type should be **Registered** or **Unregistered** .</span><span class="sxs-lookup"><span data-stu-id="02fee-111">Select **Customer** on **Sales Return Order** or **Sales Credit Memo** header, GST customer type should be **Registered** or **Unregistered** .</span></span>
3. <span data-ttu-id="02fee-112">Select **Item Code** for goods or **G/L Account** for Service Sale on **Sales Return Order** or **Sales Credit Memo** line.</span><span class="sxs-lookup"><span data-stu-id="02fee-112">Select **Item Code** for goods or **G/L Account** for Service Sale on **Sales Return Order** or **Sales Credit Memo** line.</span></span> <span data-ttu-id="02fee-113">GST Group Code, HSN/SAC Code should not be blank on Item or G/L Account.</span><span class="sxs-lookup"><span data-stu-id="02fee-113">GST Group Code, HSN/SAC Code should not be blank on Item or G/L Account.</span></span> 

<span data-ttu-id="02fee-114">For example, there is a sales credit memo for INR 10,000 and 18% GST (i.e. 9% CGST and 9% SGST/UTGST in case of Intra-State or Intra-Union Territory transaction or 18% IGST in case of Inter-State transaction) has to be charged on the credit memo amount.</span><span class="sxs-lookup"><span data-stu-id="02fee-114">For example, there is a sales credit memo for INR 10,000 and 18% GST (i.e. 9% CGST and 9% SGST/UTGST in case of Intra-State or Intra-Union Territory transaction or 18% IGST in case of Inter-State transaction) has to be charged on the credit memo amount.</span></span>

- <span data-ttu-id="02fee-115">GST calculation will appear in the Fact Box, as following:</span><span class="sxs-lookup"><span data-stu-id="02fee-115">GST calculation will appear in the Fact Box, as following:</span></span>
    
    |<span data-ttu-id="02fee-116">Component</span><span class="sxs-lookup"><span data-stu-id="02fee-116">Component</span></span>|<span data-ttu-id="02fee-117">Amount</span><span class="sxs-lookup"><span data-stu-id="02fee-117">Amount</span></span>|
    |----------------------------------|---------------------------------------|  
    |<span data-ttu-id="02fee-118">**GST Base Amount**</span><span class="sxs-lookup"><span data-stu-id="02fee-118">**GST Base Amount**</span></span>|<span data-ttu-id="02fee-119">10,000</span><span class="sxs-lookup"><span data-stu-id="02fee-119">10,000</span></span>|  
    |<span data-ttu-id="02fee-120">**CGST**</span><span class="sxs-lookup"><span data-stu-id="02fee-120">**CGST**</span></span>|<span data-ttu-id="02fee-121">900</span><span class="sxs-lookup"><span data-stu-id="02fee-121">900</span></span>|  
    |<span data-ttu-id="02fee-122">**SGST**</span><span class="sxs-lookup"><span data-stu-id="02fee-122">**SGST**</span></span>|<span data-ttu-id="02fee-123">900</span><span class="sxs-lookup"><span data-stu-id="02fee-123">900</span></span>| 

- <span data-ttu-id="02fee-124">GL Entries for Intra-State Sales Return of Goods from Registered or Unregistered Customer, will be as following:</span><span class="sxs-lookup"><span data-stu-id="02fee-124">GL Entries for Intra-State Sales Return of Goods from Registered or Unregistered Customer, will be as following:</span></span>

    |<span data-ttu-id="02fee-125">Particulars</span><span class="sxs-lookup"><span data-stu-id="02fee-125">Particulars</span></span>|<span data-ttu-id="02fee-126">Amount</span><span class="sxs-lookup"><span data-stu-id="02fee-126">Amount</span></span>|
    |----------------------------------|---------------------------------------|  
    |<span data-ttu-id="02fee-127">**Sales Account**</span><span class="sxs-lookup"><span data-stu-id="02fee-127">**Sales Account**</span></span>|<span data-ttu-id="02fee-128">10,000</span><span class="sxs-lookup"><span data-stu-id="02fee-128">10,000</span></span>|  
    |<span data-ttu-id="02fee-129">**SGST/UTGST Payable Account**</span><span class="sxs-lookup"><span data-stu-id="02fee-129">**SGST/UTGST Payable Account**</span></span>|<span data-ttu-id="02fee-130">900</span><span class="sxs-lookup"><span data-stu-id="02fee-130">900</span></span>|  
    |<span data-ttu-id="02fee-131">**CGST Payable Account**</span><span class="sxs-lookup"><span data-stu-id="02fee-131">**CGST Payable Account**</span></span>|<span data-ttu-id="02fee-132">900</span><span class="sxs-lookup"><span data-stu-id="02fee-132">900</span></span>|
    |<span data-ttu-id="02fee-133">**Customer Account**</span><span class="sxs-lookup"><span data-stu-id="02fee-133">**Customer Account**</span></span>|<span data-ttu-id="02fee-134">-11800</span><span class="sxs-lookup"><span data-stu-id="02fee-134">-11800</span></span>|

- <span data-ttu-id="02fee-135">GL Entries for Inter-State Sales Return of Goods from Registered or Unregistered Customer, will be as following:</span><span class="sxs-lookup"><span data-stu-id="02fee-135">GL Entries for Inter-State Sales Return of Goods from Registered or Unregistered Customer, will be as following:</span></span>

    |<span data-ttu-id="02fee-136">Particulars</span><span class="sxs-lookup"><span data-stu-id="02fee-136">Particulars</span></span>|<span data-ttu-id="02fee-137">Amount</span><span class="sxs-lookup"><span data-stu-id="02fee-137">Amount</span></span>|
    |----------------------------------|---------------------------------------|  
    |<span data-ttu-id="02fee-138">**Sales Account**</span><span class="sxs-lookup"><span data-stu-id="02fee-138">**Sales Account**</span></span>|<span data-ttu-id="02fee-139">10,000</span><span class="sxs-lookup"><span data-stu-id="02fee-139">10,000</span></span>|  
    |<span data-ttu-id="02fee-140">**IGST Payable Account**</span><span class="sxs-lookup"><span data-stu-id="02fee-140">**IGST Payable Account**</span></span>|<span data-ttu-id="02fee-141">1800</span><span class="sxs-lookup"><span data-stu-id="02fee-141">1800</span></span>| 
    |<span data-ttu-id="02fee-142">**Customer Account**</span><span class="sxs-lookup"><span data-stu-id="02fee-142">**Customer Account**</span></span>|<span data-ttu-id="02fee-143">- 11800</span><span class="sxs-lookup"><span data-stu-id="02fee-143">- 11800</span></span>|

- <span data-ttu-id="02fee-144">GL Entries for Intra-State Sales Return of Services from Registered or Unregistered Customer, will be as following:</span><span class="sxs-lookup"><span data-stu-id="02fee-144">GL Entries for Intra-State Sales Return of Services from Registered or Unregistered Customer, will be as following:</span></span>

    |<span data-ttu-id="02fee-145">Particulars</span><span class="sxs-lookup"><span data-stu-id="02fee-145">Particulars</span></span>|<span data-ttu-id="02fee-146">Amount</span><span class="sxs-lookup"><span data-stu-id="02fee-146">Amount</span></span>|
    |----------------------------------|---------------------------------------|  
    |<span data-ttu-id="02fee-147">**Service Account**</span><span class="sxs-lookup"><span data-stu-id="02fee-147">**Service Account**</span></span>|<span data-ttu-id="02fee-148">10,000</span><span class="sxs-lookup"><span data-stu-id="02fee-148">10,000</span></span>|  
    |<span data-ttu-id="02fee-149">**SGST/UTGST Payable Account**</span><span class="sxs-lookup"><span data-stu-id="02fee-149">**SGST/UTGST Payable Account**</span></span>|<span data-ttu-id="02fee-150">900</span><span class="sxs-lookup"><span data-stu-id="02fee-150">900</span></span>|  
    |<span data-ttu-id="02fee-151">**CGST Payable Account**</span><span class="sxs-lookup"><span data-stu-id="02fee-151">**CGST Payable Account**</span></span>|<span data-ttu-id="02fee-152">900</span><span class="sxs-lookup"><span data-stu-id="02fee-152">900</span></span>|
    |<span data-ttu-id="02fee-153">**Customer Account**</span><span class="sxs-lookup"><span data-stu-id="02fee-153">**Customer Account**</span></span>|<span data-ttu-id="02fee-154">-11800</span><span class="sxs-lookup"><span data-stu-id="02fee-154">-11800</span></span>|

- <span data-ttu-id="02fee-155">GL Entries for Inter-State Sales Return of Services from Registered or Unregistered Customer, will be as following:</span><span class="sxs-lookup"><span data-stu-id="02fee-155">GL Entries for Inter-State Sales Return of Services from Registered or Unregistered Customer, will be as following:</span></span>

    |<span data-ttu-id="02fee-156">Particulars</span><span class="sxs-lookup"><span data-stu-id="02fee-156">Particulars</span></span>|<span data-ttu-id="02fee-157">Amount</span><span class="sxs-lookup"><span data-stu-id="02fee-157">Amount</span></span>|
    |----------------------------------|---------------------------------------|  
    |<span data-ttu-id="02fee-158">**Services Account**</span><span class="sxs-lookup"><span data-stu-id="02fee-158">**Services Account**</span></span>|<span data-ttu-id="02fee-159">10,000</span><span class="sxs-lookup"><span data-stu-id="02fee-159">10,000</span></span>|  
    |<span data-ttu-id="02fee-160">**IGST Payable Account**</span><span class="sxs-lookup"><span data-stu-id="02fee-160">**IGST Payable Account**</span></span>|<span data-ttu-id="02fee-161">1800</span><span class="sxs-lookup"><span data-stu-id="02fee-161">1800</span></span>|
    |<span data-ttu-id="02fee-162">**Customer Account**</span><span class="sxs-lookup"><span data-stu-id="02fee-162">**Customer Account**</span></span>|<span data-ttu-id="02fee-163">- 11800</span><span class="sxs-lookup"><span data-stu-id="02fee-163">- 11800</span></span>|







































