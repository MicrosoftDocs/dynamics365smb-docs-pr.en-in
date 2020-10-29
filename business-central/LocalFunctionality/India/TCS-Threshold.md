---
title: TCS calculation considering threshold limits
description: TCS calculation considering threshold limits
author: v-debapd
ms.service: dynamics365-business-central
ms.topic: article
ms.devlang: na
ms.tgt_pltfrm: na
ms.workload: na
ms.search.keywords: India, local, IN, English
ms.date: 10/01/2020
ms.author: v-debapd
ms.openlocfilehash: 434abe1d38ccb5703928d8059227e8dcffa5eac2
ms.sourcegitcommit: ddbb5cede750df1baba4b3eab8fbed6744b5b9d6
ms.translationtype: HT
ms.contentlocale: en-IN
ms.lasthandoff: 10/01/2020
ms.locfileid: "3948614"
---
# <a name="tcs-with-threshold"></a>TCS with Threshold

[!INCLUDE[vnext_preview](../../includes/vnext_preview.md)]

This topic explains the requirement of threshold amount in TCS and  the process of calculating TCS for such transactions.

## <a name="tcs-calculation-considering-threshold-limits"></a>TCS calculation considering threshold limits

TCS threshold defines the threshold limit for each TCS Nature of Collection.  TCS can be deducted only if the total transaction with the assessee exceeds the threshold limit in the financial year.

If a payment under TCS Type A is below Threshold INR 20,000, no tax will be collected. Another factor to be considered is the aggregate of total payments to be made in a year. If for a customer it is expected that the threshold limit would be crossed eventually, it means Threshold is overlooked. Hence, payments received from customers can cross the TCS threshold of INR 20,000. However, if the payment expected is below the threshold limit defined, TCS will not be collected.

1. GL Entries for TCS where payment is less than the threshold limits, will be as following:
    
    |Particulars|Amount|
    |----------------------------------|---------------------------------------|  
    |**Customer Account**|19000|
    |**Sales Account**|-19000|

2. GL Entries for TCS where payment is more than (exceeding) Threshold limits, will be as following:

    |Particulars|Amount|
    |----------------------------------|---------------------------------------|  
    |**Bank Account**|10000| 
    |**TCS Payable Account**|287| 
    |**Customer Account**|-9713|





































