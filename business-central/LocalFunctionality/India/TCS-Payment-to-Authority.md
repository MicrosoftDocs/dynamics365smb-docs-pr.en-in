---
title: Payment of TCS to the Government Authorities
description: Payment of TCS to the Government Authorities
author: v-debapd
ms.service: dynamics365-business-central
ms.topic: article
ms.devlang: na
ms.tgt_pltfrm: na
ms.workload: na
ms.search.keywords: India, local, IN, English
ms.date: 10/01/2020
ms.author: v-debapd
ms.openlocfilehash: f3fc82db6d57ffee86b33da1f15b2a9ccf238dd2
ms.sourcegitcommit: ddbb5cede750df1baba4b3eab8fbed6744b5b9d6
ms.translationtype: HT
ms.contentlocale: en-IN
ms.lasthandoff: 10/01/2020
ms.locfileid: "3948615"
---
# <a name="payment-of-tcs-to-government-authorities"></a>Payment of TCS to Government Authorities

[!INCLUDE[vnext_preview](../../includes/vnext_preview.md)]

The TCS that have been collected from various transactions, need to be deposited to the government. Payment of TCS will be handled through Payment Journal/Bank Payment Voucher. Provision to select the TCS Entries which assessee needs to pay to the government authorities depends on the basis of filters, for example, T.C.A.N, Assesses, Date etc.

1. Choose the ![Search for Page or Report](image/search_small.png "Search for Page or Report icon") icon, enter **Payment Journal** or **Bank Payment Voucher** , and then choose the related link.
2. Select the relevant TCS payable account in **Account No.** field -> select the relevant TCAN in **T.C.A.N No.** field -> Navigate -> Tax Payments -> TCS -> then click on TCS. 
3. Select entries and system will generate TCS payment entry on the journal line. 
1. On posting of the payment journal TCS Entries will be marked as 'Paid'.

1. GL Entries will be as following:
    
    |Particulars|Amount|
    |----------------------------------|---------------------------------------|  
    |**TCS Payable Account**|10000|
    |**Bank Account**|-10000|




























