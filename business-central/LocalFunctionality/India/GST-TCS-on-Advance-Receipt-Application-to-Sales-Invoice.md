---
title: GST and TCS on Advance Customer Payments
description: GST and TCS on Advance Customer Payments
author: v-debapd
ms.service: dynamics365-business-central
ms.topic: article
ms.devlang: na
ms.tgt_pltfrm: na
ms.workload: na
ms.search.keywords: India, local, IN, English
ms.date: 10/01/2020
ms.author: v-debapd
ms.openlocfilehash: 853cc9f3b448e22a46a4ec766cf92da01f1413ce
ms.sourcegitcommit: ddbb5cede750df1baba4b3eab8fbed6744b5b9d6
ms.translationtype: HT
ms.contentlocale: en-IN
ms.lasthandoff: 10/01/2020
ms.locfileid: "3948626"
---
# <a name="gst-and-tcs-on-advance-customer-payments"></a>GST and TCS on Advance Customer Payments 

[!INCLUDE[vnext_preview](../../includes/vnext_preview.md)]

Assessee is liable for paying GST and TCS at the time of receiving advance payment from customer.

### <a name="mandatory-fields-in-cash-or-bank-receipt-voucher"></a>Mandatory fields in cash or bank receipt voucher

1. Choose the ![Search for Page or Report](image/search_small.png "Search for Page or Report icon") icon, enter **Bank Receipt Voucher** or **Cash Receipt Voucher** , and then choose the related link.
2. Select **Customer** in **Account Type** field and select relevant customer code in **Account No.** field.
3. Select **G/L Account** for cash or **Bank Account** for bank in **Bal. Account Type** field, and select relevant cash or bank account in **Bal. Account No.** field.
4. Select relevant TCS Nature of Collection, GST Group Code, HSN/SAC Code, Location Code on journal line.
5. **GST on Advance Payment** should be marked true.  

 For example, service amount is INR 20000 and customer made an advance payment of INR 10,000, 18% IGST and 1% TCS has to be charged on the advance payment.

- GST Calculation will appear in the Fact Box, as following:
    
    |Component|Amount|
    |----------------------------------|---------------------------------------|  
    |**GST Base Amount**|10,000|
    |**GST Transactional Value**|8,474 (10000*100/118)|
    |**IGST Amount**|1525 (8,474*18%)|
    |**TCS Amount**|100 (10,000*1%)|
    
- On posting of advance receipt from customer, GL Entries will be as following:

    |Particulars|Amount|
    |----------------------------------|---------------------------------------|  
    |**Bank Account**|10000|  
    |**IGST Payable (Interim) Account**|1525|  
    |**IGST Payable Account**|-1525| 
    |**TCS Amount**|-100|
    |**Customer Account**|-9900| 


Later sales invoice for services is issued to the customer for INR 20,000, 18% IGST and 1% TCS has to be charged on the invoice amount, and the advance receipt from customer will be applied with the invoice.

### <a name="mandatory-fields-on-sales-invoice"></a>Mandatory fields on sales invoice

1. Choose the ![Search for Page or Report](image/search_small.png "Search for Page or Report icon") icon, enter **Sales Invoice** , and then choose the related link.
2. Select **Customer** on **Sales Invoice** header.
3. Select **G/L Account** for service or **Item** for goods on **Sales Invoice** line.
4. Select relevant TCS Nature of Collection on **Sales Invoice** line.
5. GST Group Code, HSN/SAC Code, GST Credit should have a value in **G/L Account** or **Item** card.
6. **Location Code** field should not be blank on both **Sales Invoice** header and line.
7. Select the advance payment in **Applies to Doc. No.** field on **Sales Invoice** header.

- GST calculation will appear in the Fact Box, as following:

    |Component|Amount|
    |----------------------------------|---------------------------------------|  
    |**GST Base Amount**|20000|  
    |**IGST**|2075 = [3,600 (20,000 * 18%)]-[1525 (8,474 * 18%)]|  
    |**TCS Amount**|136 = [236 (23,600 * 1%)] - [100 (10,000 * 1%)] |

GST and TCS will be calculated on the remaining amount, i.e. Invoice Amount - Advance Payment Amount. If advance payment is not applied with the sales invoice then GST and TCS will be calculated on the whole invoice amount.

- On posting of sales invoice, GL Entries will be following:

    |Particulars|Amount|
    |----------------------------------|---------------------------------------|  
    |**Customer Account**|23736|  
    |**IGST Payable Account**|-3600|
    |**Sales Account**|-20000|
    |**TCS Payable Account**|-136|
    |**IGST Payable Account**|1525|
    |**IGST Payable (Interim) Account**|-1525|
    

> [!TIP]
> In case of Intra-State Sale, CGST and SGST/UTGST will be calculated.

