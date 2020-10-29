---
title: Sales to Registered or Unregistered Customer
description: Sales to Registered or Unregistered Customer
author: v-debapd
ms.service: dynamics365-business-central
ms.topic: article
ms.devlang: na
ms.tgt_pltfrm: na
ms.workload: na
ms.search.keywords: India, local, IN, English
ms.date: 10/01/2020
ms.author: v-debapd
ms.openlocfilehash: 9cb00a88d7e6261eec7fd6706d58f15daed866ed
ms.sourcegitcommit: ddbb5cede750df1baba4b3eab8fbed6744b5b9d6
ms.translationtype: HT
ms.contentlocale: en-IN
ms.lasthandoff: 10/01/2020
ms.locfileid: "3948630"
---
# <a name="sales-to-registered-or-unregistered-customer"></a>Sales to Registered or Unregistered Customer

[!INCLUDE[vnext_preview](../../includes/vnext_preview.md)]

Sales to a registered customer are known as B2B sales, sales to an unregistered customer are known as B2C sales. There is no difference in computation of tax for a B2B and B2C sales. However, they are required to be reported separately in GSTR-1.

Process of sales to registered or unregistered customer has been explained in this document.

## <a name="create-a-sales-invoice"></a>Create a sales invoice

1. Choose the ![Search for Page or Report](image/search_small.png "Search for Page or Report icon") icon, enter **Sales Invoice** , and then choose the related link.

2. Select **Customer** on **Sales Invoice** header, GST customer type should be **Registered** or **Unregistered** .

3. Select **Item Code** for goods or **G/L Account** for service sales on **Sales Invoice** line. GST Group Code, HSN/SAC Code should not be blank on the item or G/L account. 

For example, there is a sales invoice for INR 10,000 and 18% GST (i.e. 9% CGST and 9% SGST/UTGST in case of Intra-State or Intra-Union Territory transaction or 18% IGST in case of Inter-State transaction) has to be charged on the invoice amount.

- GST calculation will appear in the Fact Box, as following:
    
    |Component|Amount|
    |----------------------------------|---------------------------------------|  
    |**GST Base Amount**|10,000|  
    |**CGST**|900|  
    |**SGST**|900|
    |**IGST**|1800|

- GL Entries for Intra-State or Intra-Union Territory sale of goods to registered or unregistered customer, will be as following:

    |Particulars|Amount|
    |----------------------------------|---------------------------------------|  
    |**Customer Account**|11,800|  
    |**SGST/UTGST Payable Account**|- 900|  
    |**CGST Payable Account**|- 900|
    |**Sales Account**|- 10000|

- GL Entries for Inter-State sale of goods to registered or unregistered customer, will be as following:

    |Particulars|Amount|
    |----------------------------------|---------------------------------------|  
    |**Customer Account**|11,800|  
    |**IGST Payable Account**|- 1800| 
    |**Sales Account**|- 10000|

- GL Entries for Intra-State or Intra-Union Territory sale of services to registered or unregistered customer, will be as following:

    |Particular|Amount|
    |----------------------------------|---------------------------------------|  
    |**Customer Account**|11,800|  
    |**SGST/UTGST Payable Account**|- 900|  
    |**CGST Payable Account**|- 900|
    |**Sales Account**|- 10000|

- GL Entries for Inter-State sale of services to registered or unregistered customer, will be as following :

    |Particular|Amount|
    |----------------------------------|---------------------------------------|  
    |**Customer Account**|11,800|  
    |**IGST Payable Account**|- 1800|
    |**Services Account**|- 10000|

> [!TIP]
> System will automatically update 'Nature of Supply' for Registered customer as B2B and for Unregistered customer as B2C.






































