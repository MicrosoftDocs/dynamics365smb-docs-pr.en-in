---
title: GST and Kerala Flood Cess on Sales Transaction
description: GST and Kerala Flood Cess on Sales Transaction
author: v-debapd
ms.service: dynamics365-business-central
ms.topic: article
ms.devlang: na
ms.tgt_pltfrm: na
ms.workload: na
ms.search.keywords: India, local, IN, English
ms.date: 10/01/2020
ms.author: v-debapd
ms.openlocfilehash: 08349a18e578064b33f152130735f524d5f55dfb
ms.sourcegitcommit: ddbb5cede750df1baba4b3eab8fbed6744b5b9d6
ms.translationtype: HT
ms.contentlocale: en-IN
ms.lasthandoff: 10/01/2020
ms.locfileid: "3948618"
---
# <a name="gst-and-kerala-flood-cess-on-sales-transaction"></a>GST and Kerala Flood Cess on Sales Transaction

[!INCLUDE[vnext_preview](../../includes/vnext_preview.md)]

Kerala Flood CESS (KFC) is applicable on all intra-state supplies of goods and/or services, made by taxable person to an unregistered person i.e. B2C supplies. Kerala Flood CESS is required to be shown separately on the invoice.

## <a name="create-a-sales-invoice"></a>Create a sales invoice

1. Choose the ![Search for Page or Report](image/search_small.png "Search for Page or Report icon") icon, enter **Sales Invoice** , and then choose the related link.

2. Select **Customer** on **Sales Invoice** header, GST customer type should be **Unregistered** .

3. Select **Item Code** for goods or **G/L Account** for service sales on **Sales Invoice** line. GST Group Code, HSN/SAC Code should not be blank on **Item** or **G/L Account** . 

For example, there is a sales invoice for INR 10,000 and 18% GST (i.e. 9% CGST and 9% SGST/UTGST in case of Intra-State or Intra-Union Territory transaction) and 1% Kerala Flood Cess has to be charged on the invoice amount.

-  GST calculation will appear in the Fact Box, as following:
    
    |Component|Amount|
    |----------------------------------|---------------------------------------|  
    |**GST Base Amount**|10,000|  
    |**CGST**|900|  
    |**SGST**|900|
    |**KFC**|100|

- On posting the sales invoice for Intra-State or Intra-Union Territory sale of goods to unregistered customer, GL Entries will be as following:

    |Particulars|Amount|
    |----------------------------------|---------------------------------------|  
    |**Customer Account**|13700|  
    |**SGST/UTGST Payable Account**|-1800|  
    |**CGST Payable Account**|-1800|
    |**Kerala Flood Cess**|-100|
    |**Sales Account**|-10000|


> [!TIP]
> System will automatically update 'Nature of Supply' B2C for Unregistered Customer.





































