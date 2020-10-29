---
title: GST Exempted Sales
description: GST Exempted Sales
author: v-debapd
ms.service: dynamics365-business-central
ms.topic: article
ms.devlang: na
ms.tgt_pltfrm: na
ms.workload: na
ms.search.keywords: India, local, IN, English
ms.date: 10/01/2020
ms.author: v-debapd
ms.openlocfilehash: e9ccaf989f4789dfc46841f04a8bdc62c81198b8
ms.sourcegitcommit: ddbb5cede750df1baba4b3eab8fbed6744b5b9d6
ms.translationtype: HT
ms.contentlocale: en-IN
ms.lasthandoff: 10/01/2020
ms.locfileid: "3948652"
---
# <a name="gst-exempted-sales"></a><span data-ttu-id="67f9d-103">GST Exempted Sales</span><span class="sxs-lookup"><span data-stu-id="67f9d-103">GST Exempted Sales</span></span>

[!INCLUDE[vnext_preview](../../includes/vnext_preview.md)]

<span data-ttu-id="67f9d-104">Sales made to an exempted customer are known as exempt sales.</span><span class="sxs-lookup"><span data-stu-id="67f9d-104">Sales made to an exempted customer are known as exempt sales.</span></span> <span data-ttu-id="67f9d-105">GST customer type shall be selected as Exempted.</span><span class="sxs-lookup"><span data-stu-id="67f9d-105">GST customer type shall be selected as Exempted.</span></span> <span data-ttu-id="67f9d-106">No GST is computed on such transactions.</span><span class="sxs-lookup"><span data-stu-id="67f9d-106">No GST is computed on such transactions.</span></span> 

<span data-ttu-id="67f9d-107">Process of sale to unregistered customer has been explained in this document.</span><span class="sxs-lookup"><span data-stu-id="67f9d-107">Process of sale to unregistered customer has been explained in this document.</span></span>

## <a name="create-a-sales-invoice-or-credit-memo"></a><span data-ttu-id="67f9d-108">Create a sales invoice or credit memo</span><span class="sxs-lookup"><span data-stu-id="67f9d-108">Create a sales invoice or credit memo</span></span>

1. <span data-ttu-id="67f9d-109">Choose the ![Search for Page or Report](image/search_small.png "Search for Page or Report icon") icon, enter **Sales Invoice** or **Sales Credit Memo** , and then choose the related link.</span><span class="sxs-lookup"><span data-stu-id="67f9d-109">Choose the ![Search for Page or Report](image/search_small.png "Search for Page or Report icon") icon, enter **Sales Invoice** or **Sales Credit Memo** , and then choose the related link.</span></span>
2. <span data-ttu-id="67f9d-110">Select **Customer** on **Sales Invoice** or **Sales Credit Memo** header, GST customer type should be **Exempted** .</span><span class="sxs-lookup"><span data-stu-id="67f9d-110">Select **Customer** on **Sales Invoice** or **Sales Credit Memo** header, GST customer type should be **Exempted** .</span></span>
3. <span data-ttu-id="67f9d-111">Select **G/L Account** or **Item Code** on **Sales Invoice** or **Sales Credit Memo** line.</span><span class="sxs-lookup"><span data-stu-id="67f9d-111">Select **G/L Account** or **Item Code** on **Sales Invoice** or **Sales Credit Memo** line.</span></span> 

<span data-ttu-id="67f9d-112">For example, there is a sales invoice and a sales credit memo for INR 10,000.</span><span class="sxs-lookup"><span data-stu-id="67f9d-112">For example, there is a sales invoice and a sales credit memo for INR 10,000.</span></span>

- <span data-ttu-id="67f9d-113">GL Entries for Exempted Sales, will be as following:</span><span class="sxs-lookup"><span data-stu-id="67f9d-113">GL Entries for Exempted Sales, will be as following:</span></span>

    |<span data-ttu-id="67f9d-114">Particulars</span><span class="sxs-lookup"><span data-stu-id="67f9d-114">Particulars</span></span>|<span data-ttu-id="67f9d-115">Amount</span><span class="sxs-lookup"><span data-stu-id="67f9d-115">Amount</span></span>|
    |----------------------------------|---------------------------------------|  
    |<span data-ttu-id="67f9d-116">**Customer Account**</span><span class="sxs-lookup"><span data-stu-id="67f9d-116">**Customer Account**</span></span>|<span data-ttu-id="67f9d-117">10,000</span><span class="sxs-lookup"><span data-stu-id="67f9d-117">10,000</span></span>|  
    |<span data-ttu-id="67f9d-118">**Sales or Services Account**</span><span class="sxs-lookup"><span data-stu-id="67f9d-118">**Sales or Services Account**</span></span>|<span data-ttu-id="67f9d-119">-10,000</span><span class="sxs-lookup"><span data-stu-id="67f9d-119">-10,000</span></span>| 

- <span data-ttu-id="67f9d-120">GL Entries for Sales Credit Memo for Exempted Sales, will be as following:</span><span class="sxs-lookup"><span data-stu-id="67f9d-120">GL Entries for Sales Credit Memo for Exempted Sales, will be as following:</span></span>

    |<span data-ttu-id="67f9d-121">Particulars</span><span class="sxs-lookup"><span data-stu-id="67f9d-121">Particulars</span></span>|<span data-ttu-id="67f9d-122">Amount</span><span class="sxs-lookup"><span data-stu-id="67f9d-122">Amount</span></span>|
    |----------------------------------|---------------------------------------|  
    |<span data-ttu-id="67f9d-123">**Customer Account**</span><span class="sxs-lookup"><span data-stu-id="67f9d-123">**Customer Account**</span></span>|<span data-ttu-id="67f9d-124">-10,000</span><span class="sxs-lookup"><span data-stu-id="67f9d-124">-10,000</span></span>|  
    |<span data-ttu-id="67f9d-125">**Sales or Services Account**</span><span class="sxs-lookup"><span data-stu-id="67f9d-125">**Sales or Services Account**</span></span>|<span data-ttu-id="67f9d-126">10,000</span><span class="sxs-lookup"><span data-stu-id="67f9d-126">10,000</span></span>| 







































