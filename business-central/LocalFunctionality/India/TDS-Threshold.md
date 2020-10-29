---
title: TDS calculation considering Threshold limits
description: TDS calculation considering Threshold limits
author: v-debapd
ms.service: dynamics365-business-central
ms.topic: article
ms.devlang: na
ms.tgt_pltfrm: na
ms.workload: na
ms.search.keywords: India, local, IN, English
ms.date: 10/01/2020
ms.author: v-debapd
ms.openlocfilehash: c3e428934ea8657d1f25b9f56b9224db551cdaf1
ms.sourcegitcommit: ddbb5cede750df1baba4b3eab8fbed6744b5b9d6
ms.translationtype: HT
ms.contentlocale: en-IN
ms.lasthandoff: 10/01/2020
ms.locfileid: "3948603"
---
# <a name="tds-with-threshold"></a>TDS with Threshold

[!INCLUDE[vnext_preview](../../includes/vnext_preview.md)]

This topic explains the requirement of threshold amount in TDS and  the process of calculating TDS for such transactions.

## <a name="tds-calculation-considering-threshold-limits"></a>TDS calculation considering threshold limits

TDS Threshold defines the threshold limit for each TDS Section.  TDS can be deducted only if the total transaction with the assessee exceeds the threshold limit in the financial year.

In a scenario where, credit or payment to a contractor under TDS Section 194C is below TDS threshold limit of INR 1,00,000 in aggregate in a financial year and single transaction threshold limit INR 30,000, TDS will not be deducted. 

In the example given below, four transactions of INR 29,000 took place in a financial year, on the fourth transaction TDS will be deducted as the aggregate (previous transactions) credit or payment amount exceeds the TDS threshold limit of INR 1,00,000. TDS Calculation as following:

   |Particulars|Amount Credited or Paid|TDS Rates|TDS Amount|Threshold Limit|
   |--------------------|-----------------------|-----------------|----------|-------|  
   |First Invoice|29000|2%|Zero|Less than Single Transaction Threshold Limit 30,000|
   |Second Invoice|29000|2%|Zero|Less than Single Transaction Threshold Limit 30,000|
   |Third Invoice|29000|2%|Zero|Less than Single Transaction Threshold Limit 30,000|
   |Forth Invoice|20000|2%|2,140 (2% of 1,07,000 i.e. total of all invoices)|Exceeds TDS Threshold Limit 1,00,000|

1. GL Entries for TDS where payment is less than threshold limits (first transaction where vendor has given the invoice for INR 29,000), will be as following:
    
    |Particulars|Amount|
    |----------------------------------|---------------------------------------|  
    |**Purchases Account**|29000| 
    |**Vendor Account**|-29000|

2. GL Entries for TDS where payment is less than threshold limits (second transaction where vendor has given the invoice for INR 29,000), will be as following:

    |Particulars|Amount|
    |----------------------------------|---------------------------------------|  
    |**Purchases Account**|29000|  
    |**Vendor Account**|-29000|

3. GL Entries for TDS where payment is less than threshold limits (third transaction where vendor has given the invoice for INR 29,000), will be as following:
 
    |Particulars|Amount|
    |----------------------------------|---------------------------------------|  
    |**Purchases Account**|29000|  
    |**Vendor Account**|-29000|

4. GL Entries for TDS where payment is more than (exceeding) Threshold limits (forth transaction where vendor has given the invoice for INR 20,000), will be as following:
    
    |Particulars|Amount|
    |----------------------------------|---------------------------------------|  
    |**Purchases Account**|29000| 
    |**TDS Payable Account**|2140| 
    |**Vendor Account**|-29000|






































