---
title: TDS on Provisional Entries
description: TDS on Provisional Entries
author: v-debapd
ms.service: dynamics365-business-central
ms.topic: article
ms.devlang: na
ms.tgt_pltfrm: na
ms.workload: na
ms.search.keywords: India, local, IN, English
ms.date: 10/01/2020
ms.author: v-debapd
ms.openlocfilehash: 7a73ddfc692ea12e61df211889aa1712dd84c1f7
ms.sourcegitcommit: ddbb5cede750df1baba4b3eab8fbed6744b5b9d6
ms.translationtype: HT
ms.contentlocale: en-IN
ms.lasthandoff: 10/01/2020
ms.locfileid: "3948606"
---
# <a name="tds-on-provisional-entries"></a>TDS on Provisional Entries

[!INCLUDE[vnext_preview](../../includes/vnext_preview.md)]

As per TDS rules, tax (TDS) has to be deducted at source, when amount is paid or credited to the account of the payee whichever is earlier. When the amount is credited to suspense account or any provisional account, then it is treated as amount is credited to the account of the payee and tax has to be deducted at source. Hence, Tax has to be deducted at source even on provisions made in the books of accounts to which TDS provisions are applicable.

A provisional entry should be posted before posting an actual entry, on posting of actual entry, provisional entry will be reversed. As per requirement, TDS to be calculated on provisional entry and on posting of actual entry, system should not calculate TDS as it is deducted in provisional entry. 

For example, provisional expense journal has to be created and posted for INR 10000 against professional expense and 10% TDS to be calculated on the expense amount.

1.  Choose the ![Search for Page or Report](image/search_small.png "Search for Page or Report icon") icon, enter **Purchase Journal** , and then choose the related link.
2.  Fill in the fields as described in the following table.

    |Field|Description|
    |----------------------------------|---------------------------------------|  
    |**Posting Date**|Specify the date of entry.|  
    |**Document Type**|Select Invoice as document type.|
    |**Document No.**|Specify the document number.|
    |**Party Type**|Select Vendor as party type.|
    |**Party Code**|Select relevant vendor code.|
    |**Account Type**|Select G/L Account.| 
    |**Account No**|Select relevant account number for provision entry.|
    |**Amount**|Amount should be negative.|
    |**TDS Section**|Select relevant TDS Section.|
    |**Bal. Account Type**|Select G/L Account as balance account type.|
    |**Bal. Account No.**|Select the relevant expanse account.|
    |**Provisional Entry**|Mark true.|

    In this case TDS calculation will be as following:

    |Component|Value|
    |----------------------------------|---------------------------------------|  
    |**TDS Base Amount**|10000|  
    |**TDS Amount**|1000 (10000*1%)|

    GL Entries for Provisional Entry, will be as following:

    |Particulars|Amount|
    |----------------------------------|---------------------------------------|  
    |**Expense Account**|10000| 
    |**Provisional Account**|-10000|
    |**TDS Payable Account**|-1000|
    |**Vendor Account**|1000|

•   Later invoice created against the provisional entry.

1.  Choose the ![Search for Page or Report](image/search_small.png "Search for Page or Report icon") icon, enter **Purchase Journal** , and then choose the related link.
2.  Fill in the fields as described in the following table.

    |Field|Description|
    |----------------------------------|---------------------------------------|  
    |**Posting Date**|Specify the date of entry.|  
    |**Document Type**|Select Invoice as document type.|
    |**Document No.**|Specify the document number.|
    |**Party Type**|Select Vendor as party type.|
    |**Party Code**|Select relevant vendor code.|
    |**Account Type**|Select Vendor.| 
    |**Account No**|Select relevant vendor code.|
    |**Amount**|Amount should be negative.|
    |**Bal. Account Type**|Select G/L Account as balance account type.|
    |**Bal. Account No.**|Select the relevant expanse account.|
    

3. Select Apply Provisional Entry and select the relevant provision entry posted for the vendor.

   GL Entries for purchase invoice against provisional entry, will be as following:

    |Particulars|Amount|
    |----------------------------------|---------------------------------------|  
    |**Vendor Account**|-10000|
    |**Provisional Account**|10000|

4.  On posting of provisional entry Provisional Entries will be created, and once the invoice is applied with the entry Applied Invoice No. field will be updated with the invoice number.

•   If this is found that the provisional entry needs to be reversed, then option of **Reverse Transaction** and **Reverse Without TDS** are available in Provisional Entries.
1.  Reverse Transaction will reverse all the posted entries of the selected transaction.
2.  Reverse Without TDS will reverse all the posted entries of the selected transaction other than the TDS entry.
3.  System will mark the reverse transaction as **Reversed After TDS Paid** if TDS is paid to the government for the selected transaction.



























