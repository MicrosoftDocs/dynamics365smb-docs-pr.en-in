---
title: Purchase Return of Goods and Services to Composite Vendor or Purchase Return of exempted goods and services with no GST Impact
description: Purchase Return of Goods and Services to Composite Vendor or Purchase Return of exempted goods and services with no GST Impact
author: v-debapd
ms.service: dynamics365-business-central
ms.topic: article
ms.devlang: na
ms.tgt_pltfrm: na
ms.workload: na
ms.search.keywords: India, local, IN, English
ms.date: 10/01/2020
ms.author: v-debapd
ms.openlocfilehash: 7ec5f9a77156973e7f193fb506aeddae0f6b4a54
ms.sourcegitcommit: ddbb5cede750df1baba4b3eab8fbed6744b5b9d6
ms.translationtype: HT
ms.contentlocale: en-IN
ms.lasthandoff: 10/01/2020
ms.locfileid: "3948644"
---
# <a name="purchase-return-of-goods-and-services-to-composite-vendor-or-purchase-return-of-exempted-goods-and-services-with-no-gst-impact"></a><span data-ttu-id="e03a1-103">Purchase Return of Goods and Services to Composite Vendor or Purchase Return of Exempted Goods and Services with no GST Impact</span><span class="sxs-lookup"><span data-stu-id="e03a1-103">Purchase Return of Goods and Services to Composite Vendor or Purchase Return of Exempted Goods and Services with no GST Impact</span></span>

[!INCLUDE[vnext_preview](../../includes/vnext_preview.md)]

<span data-ttu-id="e03a1-104">A composite vendor is a vendor whose aggregate turnover in a financial year does not exceed fifty lakh rupees and has opted for composition scheme.</span><span class="sxs-lookup"><span data-stu-id="e03a1-104">A composite vendor is a vendor whose aggregate turnover in a financial year does not exceed fifty lakh rupees and has opted for composition scheme.</span></span> <span data-ttu-id="e03a1-105">A composite vendor neither collects tax from the recipient of supplies nor passes on any credit of Input Tax.</span><span class="sxs-lookup"><span data-stu-id="e03a1-105">A composite vendor neither collects tax from the recipient of supplies nor passes on any credit of Input Tax.</span></span> <span data-ttu-id="e03a1-106">Hence, no GST is computed if the purchases are made from a composite vendor.</span><span class="sxs-lookup"><span data-stu-id="e03a1-106">Hence, no GST is computed if the purchases are made from a composite vendor.</span></span> 

<span data-ttu-id="e03a1-107">A composite vendor has to register himself with the GST authorities and hence registration no. is mandatory on the vendor card, if the vendor Type is selected as Composite.</span><span class="sxs-lookup"><span data-stu-id="e03a1-107">A composite vendor has to register himself with the GST authorities and hence registration no. is mandatory on the vendor card, if the vendor Type is selected as Composite.</span></span> <span data-ttu-id="e03a1-108">State Code is also mandatory.</span><span class="sxs-lookup"><span data-stu-id="e03a1-108">State Code is also mandatory.</span></span> <span data-ttu-id="e03a1-109">No GST entries are generated for a composite vendor, as a composite vendor is not entitled to collect any tax from the customers.</span><span class="sxs-lookup"><span data-stu-id="e03a1-109">No GST entries are generated for a composite vendor, as a composite vendor is not entitled to collect any tax from the customers.</span></span> 

<span data-ttu-id="e03a1-110">A buyer may have to return the goods or issue credit note due to various reasons like damaged goods, quality issues etc.</span><span class="sxs-lookup"><span data-stu-id="e03a1-110">A buyer may have to return the goods or issue credit note due to various reasons like damaged goods, quality issues etc.</span></span>

<span data-ttu-id="e03a1-111">Process for purchase returns to a composite vendor has been explained in this document.</span><span class="sxs-lookup"><span data-stu-id="e03a1-111">Process for purchase returns to a composite vendor has been explained in this document.</span></span>


## <a name="create-a-purchase-return-order-or-credit-memo"></a><span data-ttu-id="e03a1-112">Create a purchase return order or credit memo</span><span class="sxs-lookup"><span data-stu-id="e03a1-112">Create a purchase return order or credit memo</span></span>

1. <span data-ttu-id="e03a1-113">Choose the ![Search for Page or Report](image/search_small.png "Search for Page or Report icon") icon, enter **Purchase Return Order or Credit Memo** , and then choose the related link.</span><span class="sxs-lookup"><span data-stu-id="e03a1-113">Choose the ![Search for Page or Report](image/search_small.png "Search for Page or Report icon") icon, enter **Purchase Return Order or Credit Memo** , and then choose the related link.</span></span>
2. <span data-ttu-id="e03a1-114">Select **Vendor** on **Purchase Credit Memo** header, GST vendor type should be **Composite** or **Exempted** .</span><span class="sxs-lookup"><span data-stu-id="e03a1-114">Select **Vendor** on **Purchase Credit Memo** header, GST vendor type should be **Composite** or **Exempted** .</span></span>
3. <span data-ttu-id="e03a1-115">Select **Item Code** for goods, **G/L Account** for Service purchase, **Fixed Asset** for Fixed Asset purchase and **Charge (Item)** for Item Charge on **Purchase Credit Memo** line.</span><span class="sxs-lookup"><span data-stu-id="e03a1-115">Select **Item Code** for goods, **G/L Account** for Service purchase, **Fixed Asset** for Fixed Asset purchase and **Charge (Item)** for Item Charge on **Purchase Credit Memo** line.</span></span> 

<span data-ttu-id="e03a1-116">For example, Purchase Return Order or Credit Memo has been issued for INR 10000 on which no GST is charged.</span><span class="sxs-lookup"><span data-stu-id="e03a1-116">For example, Purchase Return Order or Credit Memo has been issued for INR 10000 on which no GST is charged.</span></span>

- <span data-ttu-id="e03a1-117">GL Entries will be as following:</span><span class="sxs-lookup"><span data-stu-id="e03a1-117">GL Entries will be as following:</span></span>

    |<span data-ttu-id="e03a1-118">Particulars</span><span class="sxs-lookup"><span data-stu-id="e03a1-118">Particulars</span></span>|<span data-ttu-id="e03a1-119">Amount</span><span class="sxs-lookup"><span data-stu-id="e03a1-119">Amount</span></span>|
    |----------------------------------|---------------------------------------|
    |<span data-ttu-id="e03a1-120">**Vendor Account**</span><span class="sxs-lookup"><span data-stu-id="e03a1-120">**Vendor Account**</span></span>|<span data-ttu-id="e03a1-121">10000</span><span class="sxs-lookup"><span data-stu-id="e03a1-121">10000</span></span>|
    |<span data-ttu-id="e03a1-122">**Purchase or Services or Fixed Asset increase during the year Account**</span><span class="sxs-lookup"><span data-stu-id="e03a1-122">**Purchase or Services or Fixed Asset increase during the year Account**</span></span>|<span data-ttu-id="e03a1-123">-10000</span><span class="sxs-lookup"><span data-stu-id="e03a1-123">-10000</span></span>|







































