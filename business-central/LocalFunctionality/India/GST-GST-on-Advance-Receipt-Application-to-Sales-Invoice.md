---
title: GST on Advance Payment Application with Sales Invoice
description: GST on Advance Payment Application with Sales Invoice
author: v-debapd
ms.service: dynamics365-business-central
ms.topic: article
ms.devlang: na
ms.tgt_pltfrm: na
ms.workload: na
ms.search.keywords: India, local, IN, English
ms.date: 10/01/2020
ms.author: v-debapd
ms.openlocfilehash: 4a6f7b9e850de61c71e31f8294e952afeb5188fb
ms.sourcegitcommit: ddbb5cede750df1baba4b3eab8fbed6744b5b9d6
ms.translationtype: HT
ms.contentlocale: en-IN
ms.lasthandoff: 10/01/2020
ms.locfileid: "3948647"
---
# <a name="gst-on-advance-payment-and-application-with-sales-invoice"></a>GST on Advance Payment and Application with Sales Invoice

[!INCLUDE[vnext_preview](../../includes/vnext_preview.md)]

GST can also be liable at the time of receiving advance payment from customer. If advance payment is applied to an invoice in the same month, then such applications need not be disclosed in GSTR-1. However, if advance payment is paid in a month and is applied to invoice in the subsequent month, then this application needs to be reported in GSTR-1.

Process of application of advance payment from customer and sale invoice has been explained in this document.

For example, service amount is INR 20000 and customer made an advance payment of INR 10,000 and 18% GST (i.e. 9% CGST and 9% SGST/UTGST) has to be charged on the advance payment.

- GST Calculation will appear in the Fact Box, as following:
    
    |Component|Amount|
    |----------------------------------|---------------------------------------|  
    |**GST Base Amount**|10,000|
    |**GST Transactional Value**|8,474 (10000*100/118)|
    |**CGST**|763 (8,475*9%)|  
    |**SGST**|763 (8,475*9%)|

Later sales invoice for services is issued to the customer for INR 20,000. 18% GST (i.e. 9% CGST and 9% SGST/UTGST in case of Intra-State or Intra-Union Territory transaction or 18% IGST in case of Inter-State transaction) has to be charged on the invoice amount.

- GST calculation will appear in the Fact Box, as following:

    |Component|Amount|
    |----------------------------------|---------------------------------------|  
    |**GST Base Amount**|20000|  
    |**CGST**|1800|  
    |**SGST**|1800|

- GL Entries for application of advance payment with sales invoice, will be as following:

    |Particulars|Amount|
    |----------------------------------|---------------------------------------|  
    |**Customer Account**|23600|  
    |**CGST Payable Account**|-1800|  
    |**SGST/UTGST Payable Account**|-1800| 
    |**Sales Account**|-20000| 
    |**CGST Payable Account**|763| 
    |**SGST/UTGST Payable Account**|763| 
    |**CGST Payable (Interim) Account**|-763|   
    |**SGST/UTGST Payable (Interim) Account**|-763|  

## <a name="gst-un-application-of-customer-advance-with-sales-invoice"></a>GST un-application of customer advance with sales invoice

If this is found that the payment and invoice was wrongly applied  and the application needs to be reversed, in such a case un apply functionality can be used. Un-application entries are same for both online application and offline application.

> [!TIP]
> An advance receipt and invoice application cannot be unapplied, if the tax liability on both is discharged through GST Settlement Screen.

- GL Entries for un-application of an advance payment and sales invoice:

    |Particulars|Amount|
    |----------------------------------|---------------------------------------|  
    |**CGST Payable (Interim) Account**|763|  
    |**SGST/UTGST Payable (Interim) Account**|763|  
    |**CGST Payable Account**|-763| 
    |**SGST/UTGST Payable Account**|-763| 


> [!TIP]
> In case of Inter-State Sale, IGST will be calculated.

