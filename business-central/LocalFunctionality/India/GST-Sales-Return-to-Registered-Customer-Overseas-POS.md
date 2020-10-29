---
title: Return or Credit Note of Services for Overseas Place of Supply to Registered Customer
description: Return or Credit Note of Services for Overseas Place of Supply to Registered Customer
author: v-debapd
ms.service: dynamics365-business-central
ms.topic: article
ms.devlang: na
ms.tgt_pltfrm: na
ms.workload: na
ms.search.keywords: India, local, IN, English
ms.date: 10/01/2020
ms.author: v-debapd
ms.openlocfilehash: e20194f0de3ab41b9b2b65ff37cb1e14f30968d9
ms.sourcegitcommit: ddbb5cede750df1baba4b3eab8fbed6744b5b9d6
ms.translationtype: HT
ms.contentlocale: en-IN
ms.lasthandoff: 10/01/2020
ms.locfileid: "3948631"
---
# <a name="return-or-credit-note-of-services-for-overseas-place-of-supply-to-registered-customer"></a>Return or Credit Note of Services for Overseas Place of Supply to Registered Customer

[!INCLUDE[vnext_preview](../../includes/vnext_preview.md)]

GST is destination based tax i.e consumption tax, which means tax will be levied where goods and services are consumed and will accrue to that state.  The supply of goods or services or both when the supplier is located in India and the place of supply is outside India shall be treated to be a supply of goods or services or both in the course of inter-state trade or commerce. 

A customer may require to return the goods or issue credit note due to various reasons like damaged goods, quality issues etc.

Process of sale return from a registered customer with overseas place of supply  has been explained in this document.

## <a name="create-a-sales-return-order-or-credit-memo"></a>Create a sales return order or credit memo

1. Choose the ![Search for Page or Report](image/search_small.png "Search for Page or Report icon") icon, enter **Sales Return Order** or **Sales Credit Memo** , and then choose the related link. 
2. Select **Customer** on **Sales Return Order** or **Sales Credit Memo** header, GST customer type should be **Registered** .
3. Select **G/L Account** on **Sales Return Order** or **Sales Credit Memo** line. GST Group Code, HSN/SAC Code should not be blank on the G/L Account.
4. **POS Out of India** field on **Sales Return Order** or **Sales Credit Memo** header should be marked as True. 

For example, there is a sales credit memo for INR 10,000 and 18% IGST has to be charged on the credit memo amount.

- GST calculation will appear in the Fact Box, as following:

    |Component|Amount|
    |----------------------------------|---------------------------------------|  
    |**GST Base Amount**|10,000|  
    |**IGST**|1800|  
  
- GL Entries for Intra-State Return or Credit Note of services for overseas place of supply to registered customer, will be as following:

    |Particulars|Amount|
    |----------------------------------|---------------------------------------|  
    |**Service Account**|10000|  
    |**IGST Payable Account**|1800|
    |**Customer Account**|-11800|







































