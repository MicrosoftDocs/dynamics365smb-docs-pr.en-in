---
title: Purchase of Services for Overseas Place of Supply from Registered Vendor
description: Purchase of Services for Overseas Place of Supply from Registered Vendor
author: v-debapd
ms.service: dynamics365-business-central
ms.topic: article
ms.devlang: na
ms.tgt_pltfrm: na
ms.workload: na
ms.search.keywords: India, local, IN, English
ms.date: 10/01/2020
ms.author: v-debapd
ms.openlocfilehash: 815ac18d60488a082b0abcacd52ba249bb779358
ms.sourcegitcommit: ddbb5cede750df1baba4b3eab8fbed6744b5b9d6
ms.translationtype: HT
ms.contentlocale: en-IN
ms.lasthandoff: 10/01/2020
ms.locfileid: "3948629"
---
# <a name="purchase-of-services-for-overseas-place-of-supply-from-registered-vendor"></a>Purchase of Services for Overseas Place of Supply from Registered Vendor

[!INCLUDE[vnext_preview](../../includes/vnext_preview.md)]

The supply of goods or services or both when the supplier is located in India and the place of supply is outside India shall be treated to be a supply of goods or services or both in the course of inter-state trade or commerce.

The process of computing tax on purchase from vendor with overseas place of supply has been explained in this document.

## <a name="create-a-purchase-invoice"></a>Create a purchase invoice

1. Choose the ![Search for Page or Report](image/search_small.png "Search for Page or Report icon") icon, enter **Purchase Invoice** , and then choose the related link.
2. Select **Vendor** on **Purchase Invoice** header, GST vendor type should be **Registered** .
3. Select **G/L Account** on **Purchase Invoice** line. GST Group Code, HSN/SAC Code and GST Credit value should be selected as **Availment** if the tax input credit is available or else **Non-Availment** on the G/L Account. 
4. GST Credit option can be changed on **Purchase Invoice** line.

For example, the service recipient has a GSTIN in West Bengal and the Vendor also has a GSTIN for West Bengal, but service provider and place of supply is outside India. In this case, IGST will be charged as place of supply is outside India. So, invoice will be issued for INR 10,000 on which 18% IGST, has to be charged.

- GST calculation will appear in the Fact Box, as following:
    
    |Component|Amount|
    |----------------------------------|---------------------------------------|  
    |**GST Base Amount**|10,000|  
    |**IGST**|1800|

- GL Entries for purchase of services for overseas place of supply from registered vendor where input tax credit is available, will be as following:
    
    |Particulars|Amount|
    |----------------------------------|---------------------------------------|  
    |**Services Account**|10000|
    |**IGST Receivable Account**|1800|  
    |**Vendor Account**|-11800|

- GL Entries for purchase of services for overseas place of supply from registered vendor where input tax credit is not available, will be as following:
    
    |Particulars|Amount|
    |----------------------------------|---------------------------------------|  
    |**Services Account**|11800|
    |**Vendor Account**|-11800|






































