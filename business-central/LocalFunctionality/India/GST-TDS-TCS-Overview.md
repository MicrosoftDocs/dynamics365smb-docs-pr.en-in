---
title: Setting up for GST TDS and GST TCS
description: Setting up for GST TDS and GST TCS
author: v-debapd
ms.service: dynamics365-business-central
ms.topic: article
ms.devlang: na
ms.tgt_pltfrm: na
ms.workload: na
ms.search.keywords: India, local, IN, English
ms.date: 10/01/2020
ms.author: v-debapd
ms.openlocfilehash: 5efa1367aba8d2d2f367cb81db20ca28523a9cc2
ms.sourcegitcommit: ddbb5cede750df1baba4b3eab8fbed6744b5b9d6
ms.translationtype: HT
ms.contentlocale: en-IN
ms.lasthandoff: 10/01/2020
ms.locfileid: "3948622"
---
# <a name="setup-for-gst-tds-and-gst-tcs"></a><span data-ttu-id="bf4d4-103">Setup for GST TDS and GST TCS</span><span class="sxs-lookup"><span data-stu-id="bf4d4-103">Setup for GST TDS and GST TCS</span></span> 

[!INCLUDE[vnext_preview](../../includes/vnext_preview.md)]

<span data-ttu-id="bf4d4-104">This topic explains the requirement and the process of setting up GST TDS and GST TCS.</span><span class="sxs-lookup"><span data-stu-id="bf4d4-104">This topic explains the requirement and the process of setting up GST TDS and GST TCS.</span></span>

## <a name="gst-tds"></a><span data-ttu-id="bf4d4-105">GST TDS</span><span class="sxs-lookup"><span data-stu-id="bf4d4-105">GST TDS</span></span> 

<span data-ttu-id="bf4d4-106">As per Section 51 of CGST Act, recipient of goods and services shall deduct TDS of 2% on payment amount where contract amount exceeds INR 250000.</span><span class="sxs-lookup"><span data-stu-id="bf4d4-106">As per Section 51 of CGST Act, recipient of goods and services shall deduct TDS of 2% on payment amount where contract amount exceeds INR 250000.</span></span> <span data-ttu-id="bf4d4-107">The recipient will issue a certificate for the tax amount deducted against the payment made for contract to supplier.</span><span class="sxs-lookup"><span data-stu-id="bf4d4-107">The recipient will issue a certificate for the tax amount deducted against the payment made for contract to supplier.</span></span> <span data-ttu-id="bf4d4-108">Recipient will pay the deducted amount to government and the same is reflected in supplier’s electronic ledger entry, which he can further adjust it against liability.</span><span class="sxs-lookup"><span data-stu-id="bf4d4-108">Recipient will pay the deducted amount to government and the same is reflected in supplier’s electronic ledger entry, which he can further adjust it against liability.</span></span>

## <a name="gst-tcs"></a><span data-ttu-id="bf4d4-109">GST TCS</span><span class="sxs-lookup"><span data-stu-id="bf4d4-109">GST TCS</span></span>

<span data-ttu-id="bf4d4-110">As per Section 52 of CGST Act, 2017, every e-commerce operator is required to collect tax at the rate of 1% (0.5% of CGST and 0.5% of SGST for intra state supply or 1% of IGST on interstate supply) on the net value of taxable supplies provided the supplier is supplying goods or services through e-commerce operator (online market place) and consideration with respect to the supply is to be collected by the said e-commerce operator The taxable supplies includes total sales and returns.</span><span class="sxs-lookup"><span data-stu-id="bf4d4-110">As per Section 52 of CGST Act, 2017, every e-commerce operator is required to collect tax at the rate of 1% (0.5% of CGST and 0.5% of SGST for intra state supply or 1% of IGST on interstate supply) on the net value of taxable supplies provided the supplier is supplying goods or services through e-commerce operator (online market place) and consideration with respect to the supply is to be collected by the said e-commerce operator The taxable supplies includes total sales and returns.</span></span> <span data-ttu-id="bf4d4-111">The GST TCS amount collected by e-commerce operator shall be paid to GSTIN and the same will be reflected as available credit for supplier in their electronic cash ledger that can be utilised to offset liability.</span><span class="sxs-lookup"><span data-stu-id="bf4d4-111">The GST TCS amount collected by e-commerce operator shall be paid to GSTIN and the same will be reflected as available credit for supplier in their electronic cash ledger that can be utilized to setoff liability.</span></span>
<span data-ttu-id="bf4d4-112">Corrections are allowed before GST TCS amount is paid to GSTIN by e-commerce operator.</span><span class="sxs-lookup"><span data-stu-id="bf4d4-112">Corrections are allowed before GST TCS amount is paid to GSTIN by e-commerce operator.</span></span>
<span data-ttu-id="bf4d4-113">Hence, there will not be any refund or negative credit.</span><span class="sxs-lookup"><span data-stu-id="bf4d4-113">Hence, there will not be any refund or negative credit.</span></span> <span data-ttu-id="bf4d4-114">If refund of payment is to be paid by supplier to e-commerce operator then, full amount (without GST TCS) shall be considered.</span><span class="sxs-lookup"><span data-stu-id="bf4d4-114">If refund of payment is to be paid by supplier to e-commerce operator then, full amount (without GST TCS) shall be considered.</span></span>
<span data-ttu-id="bf4d4-115">GST TCS to be calculated on Invoice amount excluding GST.</span><span class="sxs-lookup"><span data-stu-id="bf4d4-115">GST TCS to be calculated on Invoice amount excluding GST.</span></span> <span data-ttu-id="bf4d4-116">The Credit Memo amount excluding GST should be deducted from Invoice amount for the period before calculating GST TCS.</span><span class="sxs-lookup"><span data-stu-id="bf4d4-116">The Credit Memo amount excluding GST should be deducted from Invoice amount for the period before calculating GST TCS.</span></span>
<span data-ttu-id="bf4d4-117">GST TCS can be calculated for a given period, which can be week, fortnight or a month.</span><span class="sxs-lookup"><span data-stu-id="bf4d4-117">GST TCS can be calculated for a given period, which can be week, fortnight or a month.</span></span>
<span data-ttu-id="bf4d4-118">GST TDS is applicable only for Registered Suppliers The calculation of GST TCS is provided on Bank or Cash Payment and Receipt Vouchers.</span><span class="sxs-lookup"><span data-stu-id="bf4d4-118">GST TDS is applicable only for Registered Suppliers The calculation of GST TCS is provided on Bank or Cash Payment and Receipt Vouchers.</span></span>


## <a name="to-set-up-gst-tdstcs"></a><span data-ttu-id="bf4d4-119">To set up GST TDS/TCS</span><span class="sxs-lookup"><span data-stu-id="bf4d4-119">To set up GST TDS/TCS</span></span>

<span data-ttu-id="bf4d4-120">This setup is required for calculation of GST TDS and GST TCS on payment to vendor or receipt from customer.</span><span class="sxs-lookup"><span data-stu-id="bf4d4-120">This setup is required for calculation of GST TDS and GST TCS on payment to vendor or receipt from customer.</span></span>

1. <span data-ttu-id="bf4d4-121">Choose the ![Search for Page or Report](image/search_small.png "Search for Page or Report icon") icon, enter **GST TDS/TCS Setup** , and then choose the related link.</span><span class="sxs-lookup"><span data-stu-id="bf4d4-121">Choose the ![Search for Page or Report](image/search_small.png "Search for Page or Report icon") icon, enter **GST TDS/TCS Setup** , and then choose the related link.</span></span>
2. <span data-ttu-id="bf4d4-122">Fill in the fields as described in the following table.</span><span class="sxs-lookup"><span data-stu-id="bf4d4-122">Fill in the fields as described in the following table.</span></span>
    
    |<span data-ttu-id="bf4d4-123">Field</span><span class="sxs-lookup"><span data-stu-id="bf4d4-123">Field</span></span>|<span data-ttu-id="bf4d4-124">Description</span><span class="sxs-lookup"><span data-stu-id="bf4d4-124">Description</span></span>| 
    |---------------------------------|  ---------------------------------------| 
    |<span data-ttu-id="bf4d4-125">**Type**</span><span class="sxs-lookup"><span data-stu-id="bf4d4-125">**Type**</span></span>|<span data-ttu-id="bf4d4-126">Specify the relevant type, for example: TDS, TCS.</span><span class="sxs-lookup"><span data-stu-id="bf4d4-126">Specify the relevant type, for example: TDS, TCS.</span></span>|
    |<span data-ttu-id="bf4d4-127">**GST Component**</span><span class="sxs-lookup"><span data-stu-id="bf4d4-127">**GST Component**</span></span>|<span data-ttu-id="bf4d4-128">Specify the relevant GST component, for example: CGST, SGST, IGST etc.</span><span class="sxs-lookup"><span data-stu-id="bf4d4-128">Specify the relevant GST component, for example: CGST, SGST, IGST etc.</span></span>|
    |<span data-ttu-id="bf4d4-129">**GST Effective Date**</span><span class="sxs-lookup"><span data-stu-id="bf4d4-129">**GST Effective Date**</span></span>|<span data-ttu-id="bf4d4-130">Specify the effective date.</span><span class="sxs-lookup"><span data-stu-id="bf4d4-130">Specify the effective date.</span></span>|
    |<span data-ttu-id="bf4d4-131">**GST TDS/TCS %**</span><span class="sxs-lookup"><span data-stu-id="bf4d4-131">**GST TDS/TCS %**</span></span>|<span data-ttu-id="bf4d4-132">Specify the relevant TDS or TCS percentage.</span><span class="sxs-lookup"><span data-stu-id="bf4d4-132">Specify the relevant TDS or TCS percentage.</span></span>|
    |<span data-ttu-id="bf4d4-133">**GST Jurisdiction**</span><span class="sxs-lookup"><span data-stu-id="bf4d4-133">**GST Jurisdiction**</span></span>|<span data-ttu-id="bf4d4-134">Specify the relevant jurisdiction type.</span><span class="sxs-lookup"><span data-stu-id="bf4d4-134">Specify the relevant jurisdiction type.</span></span>|





















