---
title: Calculation of TCS as per the Income Tax Act, 1961 and GST on Sales Transactions
description: Calculation of TCS as per the Income Tax Act, 1961 and GST on Sales Transactions
author: v-debapd
ms.service: dynamics365-business-central
ms.topic: article
ms.devlang: na
ms.tgt_pltfrm: na
ms.workload: na
ms.search.keywords: India, local, IN, English
ms.date: 10/01/2020
ms.author: v-debapd
ms.openlocfilehash: 46b68c39d8a7bf10d02d7075f9357a89cd668dcb
ms.sourcegitcommit: ddbb5cede750df1baba4b3eab8fbed6744b5b9d6
ms.translationtype: HT
ms.contentlocale: en-IN
ms.lasthandoff: 10/01/2020
ms.locfileid: "3948624"
---
# <a name="calculation-of-tcs-as-per-the-income-tax-act-1961-and-gst-on-sales-transactions"></a>Calculation of TCS as per the Income Tax Act, 1961 and GST on Sales Transactions

[!INCLUDE[vnext_preview](../../includes/vnext_preview.md)]

The Government has placed the responsibility on the e-commerce operators to collect the ‘tax’ at a specified rate from the supplier. This shall be done by the Operator by paying the supplier the price of the product or services, less the tax, calculated at the specified rate.

The process of calculation of TCS and GST has been explained in this document.

## <a name="create-a-sales-invoice"></a>Create a sales invoice

1. Choose the ![Search for Page or Report](image/search_small.png "Search for Page or Report icon") icon, enter **Sales Invoice** , and then choose the related link.

2. Select **Customer** on **Sales Invoice** header.

3. Select **Item** on **Sales Invoice** line. GST Group Code, HSN/SAC Code should not be blank on the Item. 

For example, there is a sales invoice for INR 10,000 and 18% GST (i.e. 9% CGST and 9% SGST/UTGST in case of Intra-State or Intra-Union Territory transaction or 18% IGST in case of Inter-State transaction) and 1% TCS as per Income Tax Act, 1961 has to be charged on the invoice amount.

-  GST calculation will appear in the Fact Box, as following:
    
    |Component|Amount|
    |----------------------------------|---------------------------------------|  
    |**GST Base Amount**|10,000|  
    |**CGST**|900|  
    |**SGST**|900|
    |**TCS**|100|

-  On posting of sales invoice, GL Entries will be as following:

    |Particulars|Amount|
    |----------------------------------|---------------------------------------|  
    |**Customer Account**|11900|  
    |**SGST/UTGST Payable Account**|-900|  
    |**CGST Payable Account**|-900|
    |**TCS Payable Account**|-100|
    |**Sales Account**|-10000|

> [!TIP]
> In case of Inter-State Sales, IGST will be calculated with TCS as per the Income Tax Act, 1961.







































