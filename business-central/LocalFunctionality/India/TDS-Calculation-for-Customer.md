---
title: TDS calculation for Customer
description: Specifies a calculation and tracking process of TDS on customer
author: v-debapd
ms.service: dynamics365-business-central
ms.topic: article
ms.devlang: na
ms.tgt_pltfrm: na
ms.workload: na
ms.search.keywords: India, local, IN, English
ms.date: 10/01/2020
ms.author: v-debapd
ms.openlocfilehash: 54bcc90a99504d63a06f7561c125988cffff61e7
ms.sourcegitcommit: ddbb5cede750df1baba4b3eab8fbed6744b5b9d6
ms.translationtype: HT
ms.contentlocale: en-IN
ms.lasthandoff: 10/01/2020
ms.locfileid: "3948611"
---
# <a name="tds-for-customer"></a><span data-ttu-id="b791b-103">TDS for Customer</span><span class="sxs-lookup"><span data-stu-id="b791b-103">TDS for Customer</span></span> 

[!INCLUDE[vnext_preview](../../includes/vnext_preview.md)]

<span data-ttu-id="b791b-104">This topic explains the process of calculating TDS on customer payments.</span><span class="sxs-lookup"><span data-stu-id="b791b-104">This topic explains the process of calculating TDS on customer payments.</span></span>

## <a name="tds-calculation-and-tracking-of-tds-certificate-receivable"></a><span data-ttu-id="b791b-105">TDS calculation and tracking of TDS certificate receivable</span><span class="sxs-lookup"><span data-stu-id="b791b-105">TDS calculation and tracking of TDS certificate receivable</span></span>

<span data-ttu-id="b791b-106">TDS can be deducted on receiving payment from customer.</span><span class="sxs-lookup"><span data-stu-id="b791b-106">TDS can be deducted on receiving payment from customer.</span></span> <span data-ttu-id="b791b-107">TDS can be calculated on the following documents:</span><span class="sxs-lookup"><span data-stu-id="b791b-107">TDS can be calculated on the following documents:</span></span>

- <span data-ttu-id="b791b-108">General Journal</span><span class="sxs-lookup"><span data-stu-id="b791b-108">General Journal</span></span>
- <span data-ttu-id="b791b-109">Cash Receipt Voucher</span><span class="sxs-lookup"><span data-stu-id="b791b-109">Cash Receipt Voucher</span></span>
- <span data-ttu-id="b791b-110">Bank Receipt Voucher</span><span class="sxs-lookup"><span data-stu-id="b791b-110">Bank Receipt Voucher</span></span>
- <span data-ttu-id="b791b-111">Cash Receipt Journal</span><span class="sxs-lookup"><span data-stu-id="b791b-111">Cash Receipt Journal</span></span>

<span data-ttu-id="b791b-112">TDS certificate will be receivable from customer on receiving the advance payment or issuing sales invoice to customer.</span><span class="sxs-lookup"><span data-stu-id="b791b-112">TDS certificate will be receivable from customer on receiving the advance payment or issuing sales invoice to customer.</span></span> <span data-ttu-id="b791b-113">TDS Certificate Receivable can be tracked through following documents:</span><span class="sxs-lookup"><span data-stu-id="b791b-113">TDS Certificate Receivable can be tracked through following documents:</span></span>

- <span data-ttu-id="b791b-114">General Journal</span><span class="sxs-lookup"><span data-stu-id="b791b-114">General Journal</span></span>
- <span data-ttu-id="b791b-115">Cash Receipt Voucher</span><span class="sxs-lookup"><span data-stu-id="b791b-115">Cash Receipt Voucher</span></span>
- <span data-ttu-id="b791b-116">Bank Receipt Voucher</span><span class="sxs-lookup"><span data-stu-id="b791b-116">Bank Receipt Voucher</span></span>
- <span data-ttu-id="b791b-117">Cash Receipt Journal</span><span class="sxs-lookup"><span data-stu-id="b791b-117">Cash Receipt Journal</span></span>
- <span data-ttu-id="b791b-118">Sales Invoice</span><span class="sxs-lookup"><span data-stu-id="b791b-118">Sales Invoice</span></span>

#### <a name="mandatory-fields-for-tds-calculation-on-general-journal-cash-receipt-journal-bank-receipt-voucher-and-cash-receipt-voucher-at-the-time-of-tds-calculation"></a><span data-ttu-id="b791b-119">Mandatory fields for TDS calculation on general journal, cash receipt journal, bank receipt voucher and cash receipt voucher at the time of TDS calculation</span><span class="sxs-lookup"><span data-stu-id="b791b-119">Mandatory fields for TDS calculation on general journal, cash receipt journal, bank receipt voucher and cash receipt voucher at the time of TDS calculation</span></span>

1. <span data-ttu-id="b791b-120">Choose the ![Search for Page or Report](image/search_small.png "Search for Page or Report icon") icon, enter **General Journal** , **Cash Receipt Journal** , **Bank Receipt Voucher** or **Cash Receipt Voucher** , and then choose the related link.</span><span class="sxs-lookup"><span data-stu-id="b791b-120">Choose the ![Search for Page or Report](image/search_small.png "Search for Page or Report icon") icon, enter **General Journal** , **Cash Receipt Journal** , **Bank Receipt Voucher** or **Cash Receipt Voucher** , and then choose the related link.</span></span> 
2. <span data-ttu-id="b791b-121">Select **Customer** in Account Type and select relevant customer code in **Account No.** field.</span><span class="sxs-lookup"><span data-stu-id="b791b-121">Select **Customer** in Account Type and select relevant customer code in **Account No.** field.</span></span> <span data-ttu-id="b791b-122">Select **G/L Account** or **Bank Account** in Bal. Account Type and select relevant cash or bank account in **Bal. Account No.** field.</span><span class="sxs-lookup"><span data-stu-id="b791b-122">Select **G/L Account** or **Bank Account** in Bal. Account Type and select relevant cash or bank account in **Bal. Account No.** field.</span></span>
3. <span data-ttu-id="b791b-123">**TDS Certificate Receivable** field should be marked true and then select relevant **TDS Section** on journal line, **Location Code** field should not be blank.</span><span class="sxs-lookup"><span data-stu-id="b791b-123">**TDS Certificate Receivable** field should be marked true and then select relevant **TDS Section** on journal line, **Location Code** field should not be blank.</span></span>

#### <a name="mandatory-fields-for-tds-certificate-receivable-tracking-on-general-journal-cash-receipt-journal-bank-receipt-voucher-cash-receipt-voucher-and-sales-invoice"></a><span data-ttu-id="b791b-124">Mandatory fields for TDS certificate receivable tracking on general journal, cash receipt journal, bank receipt voucher, cash receipt voucher and sales invoice</span><span class="sxs-lookup"><span data-stu-id="b791b-124">Mandatory fields for TDS certificate receivable tracking on general journal, cash receipt journal, bank receipt voucher, cash receipt voucher and sales invoice</span></span>

1. <span data-ttu-id="b791b-125">Choose the ![Search for Page or Report](image/search_small.png "Search for Page or Report icon") icon, enter **General Journal** , **Cash Receipt Journal** , **Bank Receipt Voucher** , **Cash Receipt Voucher** or **Sales Invoice** , and then choose the related link.</span><span class="sxs-lookup"><span data-stu-id="b791b-125">Choose the ![Search for Page or Report](image/search_small.png "Search for Page or Report icon") icon, enter **General Journal** , **Cash Receipt Journal** , **Bank Receipt Voucher** , **Cash Receipt Voucher** or **Sales Invoice** , and then choose the related link.</span></span>
2. <span data-ttu-id="b791b-126">**TDS Certificate Receivable** should be marked true on **Journal** line or **Sales Invoice** header.</span><span class="sxs-lookup"><span data-stu-id="b791b-126">**TDS Certificate Receivable** should be marked true on **Journal** line or **Sales Invoice** header.</span></span>
3. <span data-ttu-id="b791b-127">**TDS Certificate Receivable** identification will flow into Customer Ledger Entry on posting of the document.</span><span class="sxs-lookup"><span data-stu-id="b791b-127">**TDS Certificate Receivable** identification will flow into Customer Ledger Entry on posting of the document.</span></span>

#### <a name="tds-to-be-calculated-on-customer-receipts-through-general-journal-cash-receipt-journal-bank-receipt-voucher-cash-receipt-voucher"></a><span data-ttu-id="b791b-128">TDS to be calculated on customer receipts (through general journal, cash receipt journal, bank receipt voucher, cash receipt voucher)</span><span class="sxs-lookup"><span data-stu-id="b791b-128">TDS to be calculated on customer receipts (through general journal, cash receipt journal, bank receipt voucher, cash receipt voucher)</span></span>

- <span data-ttu-id="b791b-129">In the given scenario, advance payment received from customer for INR 50,000 on which 2% TDS is applicable under TDS Section 194C.</span><span class="sxs-lookup"><span data-stu-id="b791b-129">In the given scenario, advance payment received from customer for INR 50,000 on which 2% TDS is applicable under TDS Section 194C.</span></span>

  <span data-ttu-id="b791b-130">In this case TDS calculation will be as following:</span><span class="sxs-lookup"><span data-stu-id="b791b-130">In this case TDS calculation will be as following:</span></span>

    |<span data-ttu-id="b791b-131">Component</span><span class="sxs-lookup"><span data-stu-id="b791b-131">Component</span></span>|<span data-ttu-id="b791b-132">Value</span><span class="sxs-lookup"><span data-stu-id="b791b-132">Value</span></span>|
    |----------------------------------|---------------------------------------|  
    |<span data-ttu-id="b791b-133">**TDS Base Amount**</span><span class="sxs-lookup"><span data-stu-id="b791b-133">**TDS Base Amount**</span></span>|<span data-ttu-id="b791b-134">50000</span><span class="sxs-lookup"><span data-stu-id="b791b-134">50000</span></span>|  
    |<span data-ttu-id="b791b-135">**TDS Amount**</span><span class="sxs-lookup"><span data-stu-id="b791b-135">**TDS Amount**</span></span>|<span data-ttu-id="b791b-136">1000 (50000\*2%)</span><span class="sxs-lookup"><span data-stu-id="b791b-136">1000 (50000\*2%)</span></span>|

  <span data-ttu-id="b791b-137">GL Entries will be as following:</span><span class="sxs-lookup"><span data-stu-id="b791b-137">GL Entries will be as following:</span></span>
     
    |<span data-ttu-id="b791b-138">Particulars</span><span class="sxs-lookup"><span data-stu-id="b791b-138">Particulars</span></span>|<span data-ttu-id="b791b-139">Amount</span><span class="sxs-lookup"><span data-stu-id="b791b-139">Amount</span></span>|
    |----------------------------------|---------------------------------------|  
    |<span data-ttu-id="b791b-140">**Customer Account**</span><span class="sxs-lookup"><span data-stu-id="b791b-140">**Customer Account**</span></span>|<span data-ttu-id="b791b-141">-50000</span><span class="sxs-lookup"><span data-stu-id="b791b-141">-50000</span></span>|
    |<span data-ttu-id="b791b-142">**TDS Receivable Account**</span><span class="sxs-lookup"><span data-stu-id="b791b-142">**TDS Receivable Account**</span></span>|<span data-ttu-id="b791b-143">1000</span><span class="sxs-lookup"><span data-stu-id="b791b-143">1000</span></span>|
    |<span data-ttu-id="b791b-144">**Bank Account**</span><span class="sxs-lookup"><span data-stu-id="b791b-144">**Bank Account**</span></span>|<span data-ttu-id="b791b-145">49000</span><span class="sxs-lookup"><span data-stu-id="b791b-145">49000</span></span>|


#### <a name="tds-certificate-is-receivable-against-payment-received-from-customer-or-against-customer-sales-invoice"></a><span data-ttu-id="b791b-146">TDS Certificate is receivable against payment received from customer or against customer sales invoice</span><span class="sxs-lookup"><span data-stu-id="b791b-146">TDS Certificate is receivable against payment received from customer or against customer sales invoice</span></span>

<span data-ttu-id="b791b-147">It is required to identify the payment or invoice transaction against which TDS certificate is receivable while receiving the payment from customer who has deducted TDS or issuing the sales invoice on which TDS has been deducted, it is required to identify the payment or invoice transaction against which TDS certificate is receivable.</span><span class="sxs-lookup"><span data-stu-id="b791b-147">It is required to identify the payment or invoice transaction against which TDS certificate is receivable while receiving the payment from customer who has deducted TDS or issuing the sales invoice on which TDS has been deducted, it is required to identify the payment or invoice transaction against which TDS certificate is receivable.</span></span>

1. <span data-ttu-id="b791b-148">Choose the ![Search for Page or Report](image/search_small.png "Search for Page or Report icon") icon, enter **General Journal** , **Cash Receipt Journal** , **Bank Receipt Voucher** , **Cash Receipt Voucher** or **Sales Invoice** , and then choose the related link.</span><span class="sxs-lookup"><span data-stu-id="b791b-148">Choose the ![Search for Page or Report](image/search_small.png "Search for Page or Report icon") icon, enter **General Journal** , **Cash Receipt Journal** , **Bank Receipt Voucher** , **Cash Receipt Voucher** or **Sales Invoice** , and then choose the related link.</span></span>
2. <span data-ttu-id="b791b-149">**TDS Certificate Receivable** should be marked true on **Journal** line or **Sales Invoice** header.</span><span class="sxs-lookup"><span data-stu-id="b791b-149">**TDS Certificate Receivable** should be marked true on **Journal** line or **Sales Invoice** header.</span></span>
3. <span data-ttu-id="b791b-150">**TDS Certificate Receivable** identification will flow into Customer Ledger Entry on posting of the document.</span><span class="sxs-lookup"><span data-stu-id="b791b-150">**TDS Certificate Receivable** identification will flow into Customer Ledger Entry on posting of the document.</span></span>