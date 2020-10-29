---
title: Purchase Return to Registered Vendor
description: Purchase Return to Registered Vendor
author: v-debapd
ms.service: dynamics365-business-central
ms.topic: article
ms.devlang: na
ms.tgt_pltfrm: na
ms.workload: na
ms.search.keywords: India, local, IN, English
ms.date: 10/01/2020
ms.author: v-debapd
ms.openlocfilehash: 64c7531a8cb9d7fd8750a8f8bdd139ae58c03b2e
ms.sourcegitcommit: ddbb5cede750df1baba4b3eab8fbed6744b5b9d6
ms.translationtype: HT
ms.contentlocale: en-IN
ms.lasthandoff: 10/01/2020
ms.locfileid: "3948646"
---
# <a name="purchase-return-to-registered-vendor"></a><span data-ttu-id="b6a38-103">Purchase Return to Registered Vendor</span><span class="sxs-lookup"><span data-stu-id="b6a38-103">Purchase Return to Registered Vendor</span></span>

[!INCLUDE[vnext_preview](../../includes/vnext_preview.md)]

<span data-ttu-id="b6a38-104">A registered vendor is a person who is registered with GST authorities.</span><span class="sxs-lookup"><span data-stu-id="b6a38-104">A registered vendor is a person who is registered with GST authorities.</span></span> <span data-ttu-id="b6a38-105">For purchases from registered vendors for services attracting reverse charge, purchasers themselves has to pay tax to the government.</span><span class="sxs-lookup"><span data-stu-id="b6a38-105">For purchases from registered vendors for services attracting reverse charge, purchasers themselves has to pay tax to the government.</span></span>
<span data-ttu-id="b6a38-106">If exempted goods and services are purchased from registered Vendor, then no GST is to be paid to supplier or to the Government.</span><span class="sxs-lookup"><span data-stu-id="b6a38-106">If exempted goods and services are purchased from registered Vendor, then no GST is to be paid to supplier or to the Government.</span></span>

<span data-ttu-id="b6a38-107">A buyer may have to return the goods or issue credit note due to various reasons like damaged goods, quality issues etc.</span><span class="sxs-lookup"><span data-stu-id="b6a38-107">A buyer may have to return the goods or issue credit note due to various reasons like damaged goods, quality issues etc.</span></span>

<span data-ttu-id="b6a38-108">Process for purchase returns to registered vendor has been explained in this document.</span><span class="sxs-lookup"><span data-stu-id="b6a38-108">Process for purchase returns to registered vendor has been explained in this document.</span></span>


## <a name="create-a-purchase-return-order-or-credit-memo"></a><span data-ttu-id="b6a38-109">Create a purchase return order or credit memo</span><span class="sxs-lookup"><span data-stu-id="b6a38-109">Create a purchase return order or credit memo</span></span>

1.  <span data-ttu-id="b6a38-110">Choose the ![Search for Page or Report](image/search_small.png "Search for Page or Report icon") icon, enter **Purchase Return Order** or **Purchase Credit Memo** , and then choose the related link.</span><span class="sxs-lookup"><span data-stu-id="b6a38-110">Choose the ![Search for Page or Report](image/search_small.png "Search for Page or Report icon") icon, enter **Purchase Return Order** or **Purchase Credit Memo** , and then choose the related link.</span></span> 
2. <span data-ttu-id="b6a38-111">Select **Vendor** on **Purchase Credit Memo** header, GST vendor type should be **Registered** .</span><span class="sxs-lookup"><span data-stu-id="b6a38-111">Select **Vendor** on **Purchase Credit Memo** header, GST vendor type should be **Registered** .</span></span>
3. <span data-ttu-id="b6a38-112">Select **Item Code** for goods, **G/L Account** for Service purchase, **Fixed Asset** for Fixed Asset purchase and **Charge (Item)** for Item Charge on **Purchase Credit Memo** line.</span><span class="sxs-lookup"><span data-stu-id="b6a38-112">Select **Item Code** for goods, **G/L Account** for Service purchase, **Fixed Asset** for Fixed Asset purchase and **Charge (Item)** for Item Charge on **Purchase Credit Memo** line.</span></span> <span data-ttu-id="b6a38-113">GST Group Code, HSN/SAC Code and GST Credit value should be selected as **Availment** if the tax input credit is available or else **Non-Availment** on the Item, G/L Account, Fixed Asset, Charge (Item).</span><span class="sxs-lookup"><span data-stu-id="b6a38-113">GST Group Code, HSN/SAC Code and GST Credit value should be selected as **Availment** if the tax input credit is available or else **Non-Availment** on the Item, G/L Account, Fixed Asset, Charge (Item).</span></span> 

<span data-ttu-id="b6a38-114">For example, purchase credit memo or return order is issued for INR 10000 on which 18% GST (9% CGST and 9% SGST/UTGST in case of Intra-State or Intra-Union Territory transaction or 18% IGST in case of Inter-State transaction), has to be charged.</span><span class="sxs-lookup"><span data-stu-id="b6a38-114">For example, purchase credit memo or return order is issued for INR 10000 on which 18% GST (9% CGST and 9% SGST/UTGST in case of Intra-State or Intra-Union Territory transaction or 18% IGST in case of Inter-State transaction), has to be charged.</span></span>

- <span data-ttu-id="b6a38-115">GST calculation will appear in the Fact Box, as following:</span><span class="sxs-lookup"><span data-stu-id="b6a38-115">GST calculation will appear in the Fact Box, as following:</span></span>
    
    |<span data-ttu-id="b6a38-116">Component</span><span class="sxs-lookup"><span data-stu-id="b6a38-116">Component</span></span>|<span data-ttu-id="b6a38-117">Amount</span><span class="sxs-lookup"><span data-stu-id="b6a38-117">Amount</span></span>|
    |----------------------------------|---------------------------------------|  
    |<span data-ttu-id="b6a38-118">**GST Base Amount**</span><span class="sxs-lookup"><span data-stu-id="b6a38-118">**GST Base Amount**</span></span>|<span data-ttu-id="b6a38-119">10,000</span><span class="sxs-lookup"><span data-stu-id="b6a38-119">10,000</span></span>|  
    |<span data-ttu-id="b6a38-120">**CGST**</span><span class="sxs-lookup"><span data-stu-id="b6a38-120">**CGST**</span></span>|<span data-ttu-id="b6a38-121">900</span><span class="sxs-lookup"><span data-stu-id="b6a38-121">900</span></span>|  
    |<span data-ttu-id="b6a38-122">**SGST**</span><span class="sxs-lookup"><span data-stu-id="b6a38-122">**SGST**</span></span>|<span data-ttu-id="b6a38-123">900</span><span class="sxs-lookup"><span data-stu-id="b6a38-123">900</span></span>|
    |<span data-ttu-id="b6a38-124">**IGST**</span><span class="sxs-lookup"><span data-stu-id="b6a38-124">**IGST**</span></span>|<span data-ttu-id="b6a38-125">1800</span><span class="sxs-lookup"><span data-stu-id="b6a38-125">1800</span></span>| 

- <span data-ttu-id="b6a38-126">GL Entries for Intra-State or Intra-Union Territory purchase return of goods, service, fixed asset and item charge to registered vendor where input tax credit is available, will be as following:</span><span class="sxs-lookup"><span data-stu-id="b6a38-126">GL Entries for Intra-State or Intra-Union Territory purchase return of goods, service, fixed asset and item charge to registered vendor where input tax credit is available, will be as following:</span></span>

    |<span data-ttu-id="b6a38-127">Particulars</span><span class="sxs-lookup"><span data-stu-id="b6a38-127">Particulars</span></span>|<span data-ttu-id="b6a38-128">Amount</span><span class="sxs-lookup"><span data-stu-id="b6a38-128">Amount</span></span>|
    |----------------------------------|---------------------------------------|
    |<span data-ttu-id="b6a38-129">**Vendor Account**</span><span class="sxs-lookup"><span data-stu-id="b6a38-129">**Vendor Account**</span></span>|<span data-ttu-id="b6a38-130">11800</span><span class="sxs-lookup"><span data-stu-id="b6a38-130">11800</span></span>|
    |<span data-ttu-id="b6a38-131">**SGST/UTGST Receivable Account**</span><span class="sxs-lookup"><span data-stu-id="b6a38-131">**SGST/UTGST Receivable Account**</span></span>|<span data-ttu-id="b6a38-132">-900</span><span class="sxs-lookup"><span data-stu-id="b6a38-132">-900</span></span>|
    |<span data-ttu-id="b6a38-133">**CGST Receivable Account**</span><span class="sxs-lookup"><span data-stu-id="b6a38-133">**CGST Receivable Account**</span></span>|<span data-ttu-id="b6a38-134">-900</span><span class="sxs-lookup"><span data-stu-id="b6a38-134">-900</span></span>|
    |<span data-ttu-id="b6a38-135">**Purchase or Service Account or Fixed Asset increase during the year**</span><span class="sxs-lookup"><span data-stu-id="b6a38-135">**Purchase or Service Account or Fixed Asset increase during the year**</span></span>|<span data-ttu-id="b6a38-136">-10000</span><span class="sxs-lookup"><span data-stu-id="b6a38-136">-10000</span></span>|

- <span data-ttu-id="b6a38-137">GL Entries for Intra-State or Intra-Union Territory purchase return of goods, service, fixed asset and item charge to registered vendor where input tax credit is not available, will be as following:</span><span class="sxs-lookup"><span data-stu-id="b6a38-137">GL Entries for Intra-State or Intra-Union Territory purchase return of goods, service, fixed asset and item charge to registered vendor where input tax credit is not available, will be as following:</span></span>

    |<span data-ttu-id="b6a38-138">Particulars</span><span class="sxs-lookup"><span data-stu-id="b6a38-138">Particulars</span></span>|<span data-ttu-id="b6a38-139">Amount</span><span class="sxs-lookup"><span data-stu-id="b6a38-139">Amount</span></span>|
    |----------------------------------|---------------------------------------|
    |<span data-ttu-id="b6a38-140">**Vendor Account**</span><span class="sxs-lookup"><span data-stu-id="b6a38-140">**Vendor Account**</span></span>|<span data-ttu-id="b6a38-141">11800</span><span class="sxs-lookup"><span data-stu-id="b6a38-141">11800</span></span>|
    |<span data-ttu-id="b6a38-142">**Purchase or Service Account or Fixed Asset increase during the year**</span><span class="sxs-lookup"><span data-stu-id="b6a38-142">**Purchase or Service Account or Fixed Asset increase during the year**</span></span>|<span data-ttu-id="b6a38-143">-11800</span><span class="sxs-lookup"><span data-stu-id="b6a38-143">-11800</span></span>|


- <span data-ttu-id="b6a38-144">GL Entries for Inter-State purchase return of goods, services, fixed asset, charge item to registered vendor where input tax credit is available, will be as following:</span><span class="sxs-lookup"><span data-stu-id="b6a38-144">GL Entries for Inter-State purchase return of goods, services, fixed asset, charge item to registered vendor where input tax credit is available, will be as following:</span></span>

    |<span data-ttu-id="b6a38-145">Particulars</span><span class="sxs-lookup"><span data-stu-id="b6a38-145">Particulars</span></span>|<span data-ttu-id="b6a38-146">Amount</span><span class="sxs-lookup"><span data-stu-id="b6a38-146">Amount</span></span>|
    |----------------------------------|---------------------------------------|    
    |<span data-ttu-id="b6a38-147">**Vendor Account**</span><span class="sxs-lookup"><span data-stu-id="b6a38-147">**Vendor Account**</span></span>|<span data-ttu-id="b6a38-148">11800</span><span class="sxs-lookup"><span data-stu-id="b6a38-148">11800</span></span>| 
    |<span data-ttu-id="b6a38-149">**IGST Receivable Account**</span><span class="sxs-lookup"><span data-stu-id="b6a38-149">**IGST Receivable Account**</span></span>|<span data-ttu-id="b6a38-150">-1800</span><span class="sxs-lookup"><span data-stu-id="b6a38-150">-1800</span></span>| 
    |<span data-ttu-id="b6a38-151">**Purchase or Services Account or Fixed Asset increase during the year**</span><span class="sxs-lookup"><span data-stu-id="b6a38-151">**Purchase or Services Account or Fixed Asset increase during the year**</span></span>|<span data-ttu-id="b6a38-152">-10000</span><span class="sxs-lookup"><span data-stu-id="b6a38-152">-10000</span></span>|

- <span data-ttu-id="b6a38-153">GL Entries for Inter-State purchase return of goods, services, fixed asset, charge item to registered vendor where input tax credit is not available, will be as following:</span><span class="sxs-lookup"><span data-stu-id="b6a38-153">GL Entries for Inter-State purchase return of goods, services, fixed asset, charge item to registered vendor where input tax credit is not available, will be as following:</span></span>

    |<span data-ttu-id="b6a38-154">Particulars</span><span class="sxs-lookup"><span data-stu-id="b6a38-154">Particulars</span></span>|<span data-ttu-id="b6a38-155">Amount</span><span class="sxs-lookup"><span data-stu-id="b6a38-155">Amount</span></span>|
    |----------------------------------|---------------------------------------|
    |<span data-ttu-id="b6a38-156">**Vendor Account**</span><span class="sxs-lookup"><span data-stu-id="b6a38-156">**Vendor Account**</span></span>|<span data-ttu-id="b6a38-157">11800</span><span class="sxs-lookup"><span data-stu-id="b6a38-157">11800</span></span>| 
    |<span data-ttu-id="b6a38-158">**Purchase or Services Account or Fixed Asset increase during the year**</span><span class="sxs-lookup"><span data-stu-id="b6a38-158">**Purchase or Services Account or Fixed Asset increase during the year**</span></span>|<span data-ttu-id="b6a38-159">-11800</span><span class="sxs-lookup"><span data-stu-id="b6a38-159">-11800</span></span>|





































