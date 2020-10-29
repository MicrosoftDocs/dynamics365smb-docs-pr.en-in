---
title: Export of Goods and/or Services to Foreign Customer
description: Export of Goods and Services to Foreign Customer
author: v-debapd
ms.service: dynamics365-business-central
ms.topic: article
ms.devlang: na
ms.tgt_pltfrm: na
ms.workload: na
ms.search.keywords: India, local, IN, English
ms.date: 10/01/2020
ms.author: v-debapd
ms.openlocfilehash: 9282b0819b5b8702f889683e71db2f6a7945e95d
ms.sourcegitcommit: ddbb5cede750df1baba4b3eab8fbed6744b5b9d6
ms.translationtype: HT
ms.contentlocale: en-IN
ms.lasthandoff: 10/01/2020
ms.locfileid: "3948635"
---
# <a name="export-of-goods-and-services-to-foreign-customer"></a>Export of Goods and Services to Foreign Customer

[!INCLUDE[vnext_preview](../../includes/vnext_preview.md)]

Export of goods is defined as taking goods out of India to a place outside India. Export of services means the supply of services where the supplier of service is located in India, recipient of service is located outside India and the place of supply is outside India. Exports can be without Payment of duty or with payment of duty.
 
Process of sale to foreign customer has been explained in this document.

## <a name="create-a-sales-invoice"></a>Create a sales invoice

1. Choose the ![Search for Page or Report](image/search_small.png "Search for Page or Report icon") icon, enter **Sales Invoice** , and then choose the related link.
2. Select **Customer** on **Sales Invoice** header, GST customer type should be **Export** or **Deemed Export** or **SEZ Development** or **SEZ Unit** .
3. Select **G/L Account** or **Item Code** on **Sales Invoice** line. GST Group Code, HSN/SAC Code should not be blank on the G/L Account or Item Card. 

For example, there is a sales invoice for INR 10,000 and 18% IGST has to be charged on the invoice amount.
- GST calculation will appear in the Fact Box, as following:
    
    |Component|Amount|
    |----------------------------------|---------------------------------------|  
    |**GST Base Amount**|10,000|  
    |**IGST**|1800|  
    
- GL Entries for export of goods and/or services with payment of duty to Foreign Customer, SEZ Unit, SEZ Development Customer will be as following:

    |Particulars|Amount|
    |----------------------------------|---------------------------------------|  
    |**Customer Account**|10,000|  
    |**IGST Refund Account**|1800|
    |**IGST Payable Account**|-1800|
    |**Sales Account**|-10000|

- GL Entries for export of goods and/or services without payment of duty to Foreign Customer, SEZ Unit, SEZ Development Customer will be as following:

    |Particulars|Amount|
    |----------------------------------|---------------------------------------|  
    |**Customer Account**|10,000|  
    |**Sales Account**|-10000|


> [!NOTE]
> Export or Deemed export will have same treatment, as it is treated as interstate transaction and only IGST is applicable irrespective of location of receiver. There is no scenario of deemed export without payment of Duty, as company has to pay IGST and claim refund. Refund can be claimed either by seller or recipient.







































