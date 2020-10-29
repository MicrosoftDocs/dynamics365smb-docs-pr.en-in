---
title: Purchase from Composite Vendor or Purchase of exempted goods and services with no GST Impact
description: Purchase from Composite Vendor or Purchase of exempted goods and services with no GST Impact
author: v-debapd
ms.service: dynamics365-business-central
ms.topic: article
ms.devlang: na
ms.tgt_pltfrm: na
ms.workload: na
ms.search.keywords: India, local, IN, English
ms.date: 10/01/2020
ms.author: v-debapd
ms.openlocfilehash: 21aa71454a53d0bbce28974a50006761f9803be5
ms.sourcegitcommit: ddbb5cede750df1baba4b3eab8fbed6744b5b9d6
ms.translationtype: HT
ms.contentlocale: en-IN
ms.lasthandoff: 10/01/2020
ms.locfileid: "3948640"
---
# <a name="purchase-from-composite-vendor-or-purchase-of-exempted-goods-and-services-with-no-gst-impact"></a><span data-ttu-id="f3c72-103">Purchase from Composite Vendor or Purchase of Exempted Goods and Services with No GST Impact</span><span class="sxs-lookup"><span data-stu-id="f3c72-103">Purchase from Composite Vendor or Purchase of Exempted Goods and Services with No GST Impact</span></span>

[!INCLUDE[vnext_preview](../../includes/vnext_preview.md)]

<span data-ttu-id="f3c72-104">A composite vendor is a vendor whose aggregate turnover in a financial year does not exceed fifty lakh rupees and has opted for composition scheme.</span><span class="sxs-lookup"><span data-stu-id="f3c72-104">A composite vendor is a vendor whose aggregate turnover in a financial year does not exceed fifty lakh rupees and has opted for composition scheme.</span></span> <span data-ttu-id="f3c72-105">A composite vendor neither collects tax from the recipient of supplies nor passes on any credit of input tax.</span><span class="sxs-lookup"><span data-stu-id="f3c72-105">A composite vendor neither collects tax from the recipient of supplies nor passes on any credit of input tax.</span></span> <span data-ttu-id="f3c72-106">Hence, no GST is computed if the purchases are made from a composite vendor.</span><span class="sxs-lookup"><span data-stu-id="f3c72-106">Hence, no GST is computed if the purchases are made from a composite vendor.</span></span> 

<span data-ttu-id="f3c72-107">A composite vendor has to register himself with the GST authorities and hence registration no. is mandatorily mentioned in the vendor card, if the vendor type is selected as composite.</span><span class="sxs-lookup"><span data-stu-id="f3c72-107">A composite vendor has to register himself with the GST authorities and hence registration no. is mandatorily mentioned in the vendor card, if the vendor type is selected as composite.</span></span> <span data-ttu-id="f3c72-108">State code is also mandatory.</span><span class="sxs-lookup"><span data-stu-id="f3c72-108">State code is also mandatory.</span></span> <span data-ttu-id="f3c72-109">No GST entries are generated for a composite vendor, as a composite vendor is not entitled to collect any tax from the customers.</span><span class="sxs-lookup"><span data-stu-id="f3c72-109">No GST entries are generated for a composite vendor, as a composite vendor is not entitled to collect any tax from the customers.</span></span> 

<span data-ttu-id="f3c72-110">Process for purchases from a composite vendor has been explained in this document.</span><span class="sxs-lookup"><span data-stu-id="f3c72-110">Process for purchases from a composite vendor has been explained in this document.</span></span>

## <a name="create-a-purchase-invoice"></a><span data-ttu-id="f3c72-111">Create a purchase invoice</span><span class="sxs-lookup"><span data-stu-id="f3c72-111">Create a purchase invoice</span></span>

1. <span data-ttu-id="f3c72-112">Choose the ![Search for Page or Report](image/search_small.png "Search for Page or Report icon") icon, enter **Purchase Invoice** , and then choose the related link.</span><span class="sxs-lookup"><span data-stu-id="f3c72-112">Choose the ![Search for Page or Report](image/search_small.png "Search for Page or Report icon") icon, enter **Purchase Invoice** , and then choose the related link.</span></span>
2. <span data-ttu-id="f3c72-113">Select **Vendor** on **Purchase Invoice** header, GST vendor type should be **Composite** or **Exempted** .</span><span class="sxs-lookup"><span data-stu-id="f3c72-113">Select **Vendor** on **Purchase Invoice** header, GST vendor type should be **Composite** or **Exempted** .</span></span>
3. <span data-ttu-id="f3c72-114">Select **G/L Account** , **Item Code** , **Fixed Asset** or **Charge (Item)** on **Purchase Invoice** line.</span><span class="sxs-lookup"><span data-stu-id="f3c72-114">Select **G/L Account** , **Item Code** , **Fixed Asset** or **Charge (Item)** on **Purchase Invoice** line.</span></span>

<span data-ttu-id="f3c72-115">For example, invoice will be issued for INR 10000 on which there is no GST is charged.</span><span class="sxs-lookup"><span data-stu-id="f3c72-115">For example, invoice will be issued for INR 10000 on which there is no GST is charged.</span></span>

- <span data-ttu-id="f3c72-116">GL Entries will be as following:</span><span class="sxs-lookup"><span data-stu-id="f3c72-116">GL Entries will be as following:</span></span>
    
    |<span data-ttu-id="f3c72-117">Particulars</span><span class="sxs-lookup"><span data-stu-id="f3c72-117">Particulars</span></span>|<span data-ttu-id="f3c72-118">Amount</span><span class="sxs-lookup"><span data-stu-id="f3c72-118">Amount</span></span>|
    |----------------------------------|---------------------------------------|  
    |<span data-ttu-id="f3c72-119">**Purchas or Services Account**</span><span class="sxs-lookup"><span data-stu-id="f3c72-119">**Purchas or Services Account**</span></span>|<span data-ttu-id="f3c72-120">10000</span><span class="sxs-lookup"><span data-stu-id="f3c72-120">10000</span></span>|  
    |<span data-ttu-id="f3c72-121">**Vendor Account**</span><span class="sxs-lookup"><span data-stu-id="f3c72-121">**Vendor Account**</span></span>|<span data-ttu-id="f3c72-122">-10000</span><span class="sxs-lookup"><span data-stu-id="f3c72-122">-10000</span></span>|






































