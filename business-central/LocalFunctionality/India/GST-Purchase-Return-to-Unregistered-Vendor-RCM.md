---
title: Purchase Return to Unregistered Vendor (Reverse Charge)
description: Purchase Return to Unregistered Vendor (Reverse Charge)
author: v-debapd
ms.service: dynamics365-business-central
ms.topic: article
ms.devlang: na
ms.tgt_pltfrm: na
ms.workload: na
ms.search.keywords: India, local, IN, English
ms.date: 10/01/2020
ms.author: v-debapd
ms.openlocfilehash: 7a1ee436a866da1beab0f58146ce400d6f44029f
ms.sourcegitcommit: ddbb5cede750df1baba4b3eab8fbed6744b5b9d6
ms.translationtype: HT
ms.contentlocale: en-IN
ms.lasthandoff: 10/01/2020
ms.locfileid: "3948642"
---
# <a name="purchase-return-to-unregistered-vendor-reverse-charge"></a><span data-ttu-id="c4bd4-103">Purchase Return to Unregistered Vendor (Reverse Charge)</span><span class="sxs-lookup"><span data-stu-id="c4bd4-103">Purchase Return to Unregistered Vendor (Reverse Charge)</span></span>

[!INCLUDE[vnext_preview](../../includes/vnext_preview.md)]

<span data-ttu-id="c4bd4-104">Persons whose aggregate turnover in a financial year does not exceed forty lakh rupees are not required to be registered with the GST authorities.</span><span class="sxs-lookup"><span data-stu-id="c4bd4-104">Persons whose aggregate turnover in a financial year does not exceed forty lakh rupees are not required to be registered with the GST authorities.</span></span> <span data-ttu-id="c4bd4-105">Such persons are called unregistered vendors.</span><span class="sxs-lookup"><span data-stu-id="c4bd4-105">Such persons are called unregistered vendors.</span></span> <span data-ttu-id="c4bd4-106">Any purchases from unregistered vendors do not attract GST.</span><span class="sxs-lookup"><span data-stu-id="c4bd4-106">Any purchases from unregistered vendors do not attract GST.</span></span> <span data-ttu-id="c4bd4-107">However, there are some notified services under GST, on supply of such services GST is applicable under reverse charge i.e. the purchasers are required to  pay GST to the Government.</span><span class="sxs-lookup"><span data-stu-id="c4bd4-107">However, there are some notified services under GST, on supply of such services GST is applicable under reverse charge i.e. the purchasers are required to  pay GST to the Government.</span></span>

<span data-ttu-id="c4bd4-108">A buyer may have to return the goods or issue credit note due to various reasons like damaged goods, quality issues etc.</span><span class="sxs-lookup"><span data-stu-id="c4bd4-108">A buyer may have to return the goods or issue credit note due to various reasons like damaged goods, quality issues etc.</span></span>

<span data-ttu-id="c4bd4-109">Process for purchase returns to unregistered vendor has been explained in this document.</span><span class="sxs-lookup"><span data-stu-id="c4bd4-109">Process for purchase returns to unregistered vendor has been explained in this document.</span></span>


## <a name="create-a-purchase-return-order-or-credit-memo"></a><span data-ttu-id="c4bd4-110">Create a purchase return order or credit memo</span><span class="sxs-lookup"><span data-stu-id="c4bd4-110">Create a purchase return order or credit memo</span></span>

1. <span data-ttu-id="c4bd4-111">Choose the ![Search for Page or Report](image/search_small.png "Search for Page or Report icon") icon, enter **Purchase Return Order** or **Purchase Credit Memo** , and then choose the related link.</span><span class="sxs-lookup"><span data-stu-id="c4bd4-111">Choose the ![Search for Page or Report](image/search_small.png "Search for Page or Report icon") icon, enter **Purchase Return Order** or **Purchase Credit Memo** , and then choose the related link.</span></span> 
2. <span data-ttu-id="c4bd4-112">Select **Vendor** on **Purchase Credit Memo** header, GST vendor type should be **Unregistered** .</span><span class="sxs-lookup"><span data-stu-id="c4bd4-112">Select **Vendor** on **Purchase Credit Memo** header, GST vendor type should be **Unregistered** .</span></span>
3. <span data-ttu-id="c4bd4-113">Select **Item Code** for goods, **G/L Account** for Service purchase, **Fixed Asset** for Fixed Asset purchase and **Charge (Item)** for Item Charge on **Purchase Credit Memo** line.</span><span class="sxs-lookup"><span data-stu-id="c4bd4-113">Select **Item Code** for goods, **G/L Account** for Service purchase, **Fixed Asset** for Fixed Asset purchase and **Charge (Item)** for Item Charge on **Purchase Credit Memo** line.</span></span> <span data-ttu-id="c4bd4-114">GST Group Code, HSN/SAC Code and GST Credit value should be selected as **Availment** if the tax input credit is available or else **Non-Availment** on the Item, G/L Account, Fixed Asset, Item (Charge).</span><span class="sxs-lookup"><span data-stu-id="c4bd4-114">GST Group Code, HSN/SAC Code and GST Credit value should be selected as **Availment** if the tax input credit is available or else **Non-Availment** on the Item, G/L Account, Fixed Asset, Item (Charge).</span></span> 

<span data-ttu-id="c4bd4-115">For example, purchase credit memo or return order is issued for INR 10,000 on which 18% GST (9% CGST and 9% SGST/UTGST in case of Intra-State or Intra-Union Territory transaction or 18% IGST in case of Inter-State transaction), has to be charged.</span><span class="sxs-lookup"><span data-stu-id="c4bd4-115">For example, purchase credit memo or return order is issued for INR 10,000 on which 18% GST (9% CGST and 9% SGST/UTGST in case of Intra-State or Intra-Union Territory transaction or 18% IGST in case of Inter-State transaction), has to be charged.</span></span>

- <span data-ttu-id="c4bd4-116">GST calculation will appear in the Fact Box, as following:</span><span class="sxs-lookup"><span data-stu-id="c4bd4-116">GST calculation will appear in the Fact Box, as following:</span></span>
    
    |<span data-ttu-id="c4bd4-117">Component</span><span class="sxs-lookup"><span data-stu-id="c4bd4-117">Component</span></span>|<span data-ttu-id="c4bd4-118">Amount</span><span class="sxs-lookup"><span data-stu-id="c4bd4-118">Amount</span></span>|
    |----------------------------------|---------------------------------------|  
    |<span data-ttu-id="c4bd4-119">**GST Base Amount**</span><span class="sxs-lookup"><span data-stu-id="c4bd4-119">**GST Base Amount**</span></span>|<span data-ttu-id="c4bd4-120">10,000</span><span class="sxs-lookup"><span data-stu-id="c4bd4-120">10,000</span></span>|  
    |<span data-ttu-id="c4bd4-121">**CGST**</span><span class="sxs-lookup"><span data-stu-id="c4bd4-121">**CGST**</span></span>|<span data-ttu-id="c4bd4-122">900</span><span class="sxs-lookup"><span data-stu-id="c4bd4-122">900</span></span>|  
    |<span data-ttu-id="c4bd4-123">**SGST**</span><span class="sxs-lookup"><span data-stu-id="c4bd4-123">**SGST**</span></span>|<span data-ttu-id="c4bd4-124">900</span><span class="sxs-lookup"><span data-stu-id="c4bd4-124">900</span></span>|
    |<span data-ttu-id="c4bd4-125">**IGST**</span><span class="sxs-lookup"><span data-stu-id="c4bd4-125">**IGST**</span></span>|<span data-ttu-id="c4bd4-126">1800</span><span class="sxs-lookup"><span data-stu-id="c4bd4-126">1800</span></span>|

- <span data-ttu-id="c4bd4-127">GL Entries for Intra-State or Intra-Union Territory purchase return of goods, services, fixed asset, charge item to unregistered vendor where input tax credit is available (reverse charge), will be as following:</span><span class="sxs-lookup"><span data-stu-id="c4bd4-127">GL Entries for Intra-State or Intra-Union Territory purchase return of goods, services, fixed asset, charge item to unregistered vendor where input tax credit is available (reverse charge), will be as following:</span></span>

    |<span data-ttu-id="c4bd4-128">Particulars</span><span class="sxs-lookup"><span data-stu-id="c4bd4-128">Particulars</span></span>|<span data-ttu-id="c4bd4-129">Amount</span><span class="sxs-lookup"><span data-stu-id="c4bd4-129">Amount</span></span>|
    |----------------------------------|---------------------------------------|
    |<span data-ttu-id="c4bd4-130">**Vendor Account**</span><span class="sxs-lookup"><span data-stu-id="c4bd4-130">**Vendor Account**</span></span>|<span data-ttu-id="c4bd4-131">10000</span><span class="sxs-lookup"><span data-stu-id="c4bd4-131">10000</span></span>| 
    |<span data-ttu-id="c4bd4-132">**CGST Payable Account**</span><span class="sxs-lookup"><span data-stu-id="c4bd4-132">**CGST Payable Account**</span></span>|<span data-ttu-id="c4bd4-133">900</span><span class="sxs-lookup"><span data-stu-id="c4bd4-133">900</span></span>|
    |<span data-ttu-id="c4bd4-134">**SGST/UTGST Payable Account**</span><span class="sxs-lookup"><span data-stu-id="c4bd4-134">**SGST/UTGST Payable Account**</span></span>|<span data-ttu-id="c4bd4-135">900</span><span class="sxs-lookup"><span data-stu-id="c4bd4-135">900</span></span>|
    |<span data-ttu-id="c4bd4-136">**CGST Receivable Account**</span><span class="sxs-lookup"><span data-stu-id="c4bd4-136">**CGST Receivable Account**</span></span>|<span data-ttu-id="c4bd4-137">-900</span><span class="sxs-lookup"><span data-stu-id="c4bd4-137">-900</span></span>|
    |<span data-ttu-id="c4bd4-138">**SGST/UTGST Receivable Account**</span><span class="sxs-lookup"><span data-stu-id="c4bd4-138">**SGST/UTGST Receivable Account**</span></span>|<span data-ttu-id="c4bd4-139">-900</span><span class="sxs-lookup"><span data-stu-id="c4bd4-139">-900</span></span>|
    |<span data-ttu-id="c4bd4-140">**Purchase or Services Account or Fixed Asset increase during the year**</span><span class="sxs-lookup"><span data-stu-id="c4bd4-140">**Purchase or Services Account or Fixed Asset increase during the year**</span></span>|<span data-ttu-id="c4bd4-141">-10000</span><span class="sxs-lookup"><span data-stu-id="c4bd4-141">-10000</span></span>|

- <span data-ttu-id="c4bd4-142">GL Entries for Intra-State or Intra-Union Territory purchase return of goods, services, fixed asset, charge item to unregistered vendor where input tax credit is not available (reverse charge), will be as following:</span><span class="sxs-lookup"><span data-stu-id="c4bd4-142">GL Entries for Intra-State or Intra-Union Territory purchase return of goods, services, fixed asset, charge item to unregistered vendor where input tax credit is not available (reverse charge), will be as following:</span></span>

    |<span data-ttu-id="c4bd4-143">Particulars</span><span class="sxs-lookup"><span data-stu-id="c4bd4-143">Particulars</span></span>|<span data-ttu-id="c4bd4-144">Amount</span><span class="sxs-lookup"><span data-stu-id="c4bd4-144">Amount</span></span>|
    |----------------------------------|---------------------------------------|
    |<span data-ttu-id="c4bd4-145">**Vendor Account**</span><span class="sxs-lookup"><span data-stu-id="c4bd4-145">**Vendor Account**</span></span>|<span data-ttu-id="c4bd4-146">10000</span><span class="sxs-lookup"><span data-stu-id="c4bd4-146">10000</span></span>|
    |<span data-ttu-id="c4bd4-147">**CGST Payable Account**</span><span class="sxs-lookup"><span data-stu-id="c4bd4-147">**CGST Payable Account**</span></span>|<span data-ttu-id="c4bd4-148">900</span><span class="sxs-lookup"><span data-stu-id="c4bd4-148">900</span></span>|
    |<span data-ttu-id="c4bd4-149">**SGST/UTGST Payable Account**</span><span class="sxs-lookup"><span data-stu-id="c4bd4-149">**SGST/UTGST Payable Account**</span></span>|<span data-ttu-id="c4bd4-150">900</span><span class="sxs-lookup"><span data-stu-id="c4bd4-150">900</span></span>|
    |<span data-ttu-id="c4bd4-151">**Purchase or Service Account or Fixed Asset increase during the year**</span><span class="sxs-lookup"><span data-stu-id="c4bd4-151">**Purchase or Service Account or Fixed Asset increase during the year**</span></span>|<span data-ttu-id="c4bd4-152">-11800</span><span class="sxs-lookup"><span data-stu-id="c4bd4-152">-11800</span></span>|







































