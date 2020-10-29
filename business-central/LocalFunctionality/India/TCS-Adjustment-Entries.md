---
title: TCS Adjustment Entries
description: TCS Adjustment Entries
author: v-debapd
ms.service: dynamics365-business-central
ms.topic: article
ms.devlang: na
ms.tgt_pltfrm: na
ms.workload: na
ms.search.keywords: India, local, IN, English
ms.date: 10/01/2020
ms.author: v-debapd
ms.openlocfilehash: 2813ddebc9e69513c66635c2810da5736663e8d1
ms.sourcegitcommit: ddbb5cede750df1baba4b3eab8fbed6744b5b9d6
ms.translationtype: HT
ms.contentlocale: en-IN
ms.lasthandoff: 10/01/2020
ms.locfileid: "3948617"
---
# <a name="tcs-adjustment-entries"></a><span data-ttu-id="b63a8-103">TCS Adjustment Entries</span><span class="sxs-lookup"><span data-stu-id="b63a8-103">TCS Adjustment Entries</span></span>

[!INCLUDE[vnext_preview](../../includes/vnext_preview.md)]

<span data-ttu-id="b63a8-104">TCS adjustment is applicable for any correction of the TCS amount, TCS rate and TCS base amount already calculated but not paid to the government authorities.</span><span class="sxs-lookup"><span data-stu-id="b63a8-104">TCS adjustment is applicable for any correction of the TCS amount, TCS rate and TCS base amount already calculated but not paid to the government authorities.</span></span> <span data-ttu-id="b63a8-105">Provision is available to enter the new TCS rates, new TCS amount and new TCS base amount for the TCS entry which was created against invoice or payment and not paid to the government authorities.</span><span class="sxs-lookup"><span data-stu-id="b63a8-105">Provision is available to enter the new TCS rates, new TCS amount and new TCS base amount for the TCS entry which was created against invoice or payment and not paid to the government authorities.</span></span> <span data-ttu-id="b63a8-106">System should recalculate TCS amount and adjustments would be made accordingly.</span><span class="sxs-lookup"><span data-stu-id="b63a8-106">System should recalculate TCS amount and adjustments would be made accordingly.</span></span> <span data-ttu-id="b63a8-107">The revised TCS amount should be updated in the relevant GL Accounts for TCS Payable and Customer Account.</span><span class="sxs-lookup"><span data-stu-id="b63a8-107">The revised TCS amount should be updated in the relevant GL Accounts for TCS Payable and Customer Account.</span></span> <span data-ttu-id="b63a8-108">Existing TCS entry should be updated with revised TCS percentages, TCS amount and TCS base amount.</span><span class="sxs-lookup"><span data-stu-id="b63a8-108">Existing TCS entry should be updated with revised TCS percentages, TCS amount and TCS base amount.</span></span>

## <a name="tcs-adjustment-process"></a><span data-ttu-id="b63a8-109">TCS adjustment process</span><span class="sxs-lookup"><span data-stu-id="b63a8-109">TCS adjustment process</span></span>

1. <span data-ttu-id="b63a8-110">Choose the ![Search for Page or Report](image/search_small.png "Search for Page or Report icon") icon, enter **TCS Adjustment Journal** , and then choose the related link.</span><span class="sxs-lookup"><span data-stu-id="b63a8-110">Choose the ![Search for Page or Report](image/search_small.png "Search for Page or Report icon") icon, enter **TCS Adjustment Journal** , and then choose the related link.</span></span>
2. <span data-ttu-id="b63a8-111">Select the relevant transaction number in **Transaction No.**</span><span class="sxs-lookup"><span data-stu-id="b63a8-111">Select the relevant transaction number in **Transaction No.**</span></span> <span data-ttu-id="b63a8-112">field from the drop down, and the selected line, will get populated with the posted record.</span><span class="sxs-lookup"><span data-stu-id="b63a8-112">field from the drop down, and the selected line, will get populated with the posted record.</span></span> <span data-ttu-id="b63a8-113">Following information can be changed, in the adjustment journal as per the requirements:</span><span class="sxs-lookup"><span data-stu-id="b63a8-113">Following information can be changed, in the adjustment journal as per the requirements:</span></span>
  
    |<span data-ttu-id="b63a8-114">Field Name</span><span class="sxs-lookup"><span data-stu-id="b63a8-114">Field Name</span></span>|<span data-ttu-id="b63a8-115">Use</span><span class="sxs-lookup"><span data-stu-id="b63a8-115">Use</span></span>|
    |----------------------------------|---------------------------------------|  
    |<span data-ttu-id="b63a8-116">**TCS % Applied**</span><span class="sxs-lookup"><span data-stu-id="b63a8-116">**TCS % Applied**</span></span>|<span data-ttu-id="b63a8-117">Fill the revised TCS %.</span><span class="sxs-lookup"><span data-stu-id="b63a8-117">Fill the revised TCS %.</span></span>|  
    |<span data-ttu-id="b63a8-118">**Surcharge % Applied**</span><span class="sxs-lookup"><span data-stu-id="b63a8-118">**Surcharge % Applied**</span></span>|<span data-ttu-id="b63a8-119">Fill the revised Surcharge %.</span><span class="sxs-lookup"><span data-stu-id="b63a8-119">Fill the revised Surcharge %.</span></span>|
    |<span data-ttu-id="b63a8-120">**eCESS % Applied**</span><span class="sxs-lookup"><span data-stu-id="b63a8-120">**eCESS % Applied**</span></span>| <span data-ttu-id="b63a8-121">Fill the revised eCess %.</span><span class="sxs-lookup"><span data-stu-id="b63a8-121">Fill the revised eCess %.</span></span>|
    |<span data-ttu-id="b63a8-122">**SHE Cess % Applied**</span><span class="sxs-lookup"><span data-stu-id="b63a8-122">**SHE Cess % Applied**</span></span>|<span data-ttu-id="b63a8-123">Fill the revised SHE Cess %.</span><span class="sxs-lookup"><span data-stu-id="b63a8-123">Fill the revised SHE Cess %.</span></span>|
    |<span data-ttu-id="b63a8-124">**TCS Base Applied**</span><span class="sxs-lookup"><span data-stu-id="b63a8-124">**TCS Base Applied**</span></span>|<span data-ttu-id="b63a8-125">Fill the revised TCS base amount.</span><span class="sxs-lookup"><span data-stu-id="b63a8-125">Fill the revised TCS base amount.</span></span>|

3. <span data-ttu-id="b63a8-126">On posting of the adjustment journal G/L Entry, TCS Entry, Customer Ledger Entry and Detailed Customer Ledger Entry will be updated with the adjusted amount and revised information.</span><span class="sxs-lookup"><span data-stu-id="b63a8-126">On posting of the adjustment journal G/L Entry, TCS Entry, Customer Ledger Entry and Detailed Customer Ledger Entry will be updated with the adjusted amount and revised information.</span></span>
























