---
title: Payment of TDS to Government Authorities
description: Payment of TDS to Government Authorities
author: v-debapd
ms.service: dynamics365-business-central
ms.topic: article
ms.devlang: na
ms.tgt_pltfrm: na
ms.workload: na
ms.search.keywords: India, local, IN, English
ms.date: 10/01/2020
ms.author: v-debapd
ms.openlocfilehash: 20fa941c960535328f868e8bb06ea629248767d6
ms.sourcegitcommit: ddbb5cede750df1baba4b3eab8fbed6744b5b9d6
ms.translationtype: HT
ms.contentlocale: en-IN
ms.lasthandoff: 10/01/2020
ms.locfileid: "3948604"
---
# <a name="payment-of-tds-to-government-authorities"></a>Payment of TDS to Government Authorities

[!INCLUDE[vnext_preview](../../includes/vnext_preview.md)]

The TDS that have been deducted on various transactions, needs to be deposited to the government. Payment of TDS will be handled through Payment Journal or General Journal. Provision available to select the TDS Entries which assessee needs to pay to government authorities depends on the basis of filters, for example – TAN, Assesses, Date etc.

1. Choose the ![Search for Page or Report](image/search_small.png "Search for Page or Report icon") icon, enter **Payment Journal** or **Bank Payment Voucher** , and then choose the related link.
2. Select the relevant TDS payable account number in **Account No.** field -> Select relevant TAN in **T.A.N No.** field -> Navigate -> Pay TDS -> then click on TDS, select entries and system will generate TDS payment entry in the journal line. 
3. On posting of the payment journal TDS Entries will be marked as 'Paid'.

1. GL Entries will be as following:
    
    |Particulars|Amount|
    |----------------------------------|---------------------------------------|  
    |**TDS Payable Account**|10000|
    |**Bank Account**|-10000|




























