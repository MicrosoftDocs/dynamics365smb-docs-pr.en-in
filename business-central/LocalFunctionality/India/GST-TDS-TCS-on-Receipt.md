---
title: GST TDS and GST TCS on Customer Payments
description: GST TDS and GST TCS on Customer Payments
author: v-debapd
ms.service: dynamics365-business-central
ms.topic: article
ms.devlang: na
ms.tgt_pltfrm: na
ms.workload: na
ms.search.keywords: India, local, IN, English
ms.date: 10/01/2020
ms.author: v-debapd
ms.openlocfilehash: 7cec9b413b1a9649fdfddc63f7dc8b04f5304a68
ms.sourcegitcommit: ddbb5cede750df1baba4b3eab8fbed6744b5b9d6
ms.translationtype: HT
ms.contentlocale: en-IN
ms.lasthandoff: 10/01/2020
ms.locfileid: "3948621"
---
# <a name="gst-tcs-on-customer-payments"></a>GST TCS on Customer Payments

[!INCLUDE[vnext_preview](../../includes/vnext_preview.md)]

GST TCS can be liable on cash or bank payment from customer. The GST TCS entries which are not reversed will be part of settlement. Business user can reverse the GST TCS entries before settlement is posted. The GST TCS entries which have Credit Availed field 'TRUE' will be shown on settlement page. Users can manually enter amount in GST TCS Credit Utilised field for utilising against the liability.
 
1. Choose the ![Search for Page or Report](image/search_small.png "Search for Page or Report icon") icon, enter **Bank Receipt Voucher** or **Cash Receipt Voucher** , and then choose the related link.
2. Fill in the fields as described on **Bank Receipt Voucher** or **Cash Receipt Voucher** .
    
    |Field|Description| 
    |---------------------------------|  ---------------------------------------| 
    |**Posting Date**|Specify the posting date of the document.|
    |**Document Type**|Specify as 'Payment'|
    |**Account Type**|Specify as 'Customer'|
    |**Account No.**|Select the relevant customer code.|
    |**Amount**|Specify the amount.|
    |**Bal. Account Type**|Specify G/L Account or Bank Account.|
    |**Location Code**|Specify the relevant location code.|
    |**GST TCS State Code**|Specify the relevant state code.|
    |**GST TDS/TCS Base Amount**|Specify the GST TCS calculation base amount.|
    |**GST TCS**|Mark this field as True.|

For example, INR 1000 paid by the customer and 1% GST TCS (0.50% CGST, 0.50% SGST for Intra-State or Intra-Union Territory and 1% IGST for Inter State) has to be charged on the payment amount.

- GST Calculation will appear in the Fact Box on Bank or Cash Receipt Voucher, as following:
    
    |Component|Amount|
    |----------------------------------|---------------------------------------|  
    |**Payment Amount**|1000|
    |**GST Transactional Value**|1,000|
    |**CGST Amount**|5|
    |**SGST Amount**|5|
    |**IGST Amount**|10|
    
- On posting of voucher for GST TCS - Intrastate Transaction, GL Entries will be as following:

    |Particulars|Amount|
    |----------------------------------|---------------------------------------|  
    |**Customer Account**|-1000|  
    |**CGST TCS Receivable Account**|5|  
    |**SGST/UTGST TCS Receivable Account**|5| 
    |**Bank Account**|990| 
    
- On posting of voucher for GST TCS - Interstate Transaction, GL Entries will be as following:

    |Particulars|Amount|
    |----------------------------------|---------------------------------------|  
    |**Customer Account**|-1000|  
    |**IGST TCS Receivable Account**|10|  
    |**Bank Account**|990| 

## <a name="gst-tds-on-customer-payment"></a>GST TDS on customer payment

GST TDS is applicable for Registered Customers. User can calculate GST TDS on cash or bank payment from customer, user needs to enter GST TDS/TCS Base Amount manually for calculating GST TDS. 

A provision for updating GST TDS certificate details is available under Financial Management > Periodic Activities > GST > Task: Update GST TDS Certificate Dtl. The GST TDS entries against which the certificate is received will be a part of GST settlement.

User can reverse the GST TDS entries before certificate is received. An additional option has been provided to user to modify GST TDS Certificate Details. The GST TDS Credit received will be shown on settlement page. 

User can manually enter amount in GST TDS Credit Utilised field for utilising against the liability.
 
1. Choose the ![Search for Page or Report](image/search_small.png "Search for Page or Report icon") icon, enter **Bank Receipt Voucher** or **Cash Receipt Voucher** , and then choose the related link.
2. Fill in the fields as described on **Bank Receipt Voucher** or **Cash Receipt Voucher** .
    
    |Field|Description| 
    |---------------------------------|  ---------------------------------------| 
    |**Posting Date**|Specify the posting date of the document.|
    |**Document Type**|Specify as 'Payment'|
    |**Account Type**|Specify as 'Customer'|
    |**Account No.**|Select the relevant customer code.|
    |**Amount**|Specify the amount.|
    |**Bal. Account Type**|Specify G/L Account or Bank Account.|
    |**Location Code**|Specify the relevant location code.|
    |**GST TDS/TCS State Code**|Specify the relevant state code.|
    |**GST TDS/TCS Base Amount**|Specify the GST TCS calculation base amount.|
    |**GST TDS**|Mark this field as True.|

For example, INR 1000 received from customer and 2% GST TDS (1% CGST, 1% SGST for Intra-State or Intra-Union Territory and 2% IGST for Inter State) has to be charged.

- GST calculation will appear in the Fact Box on Cash or Bank Receipt Voucher, as following:
    
    |Component|Amount|
    |----------------------------------|---------------------------------------|  
    |**Payment Amount**|1000|
    |**GST Transactional Value**|1,000|
    |**CGST Amount**|10|
    |**SGST Amount**|10|
    |**IGST Amount**|20|
    
- On posting of voucher for GST TDS - Intrastate Transaction, GL Entries will be as following:

    |Particulars|Amount|
    |----------------------------------|---------------------------------------|  
    |**Customer Account**|-1000|  
    |**CGST TDS Receivable Account**|10|  
    |**SGST/UTGST TDS Receivable Account**|10| 
    |**Bank Account**|980| 
    
- On posting of voucher for GST TDS - Interstate Transaction, GL Entries will be as following:

    |Particulars|Amount|
    |----------------------------------|---------------------------------------|  
    |**Customer Account**|-1000|  
    |**IGST TDS Receivable Account**|20|  
    |**Bank Account**|980| 
