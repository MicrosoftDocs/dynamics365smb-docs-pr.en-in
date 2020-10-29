---
title: Purchase Return of Goods and Services to Composite Vendor or Purchase Return of exempted goods and services with no GST Impact
description: Purchase Return of Goods and Services to Composite Vendor or Purchase Return of exempted goods and services with no GST Impact
author: v-debapd
ms.service: dynamics365-business-central
ms.topic: article
ms.devlang: na
ms.tgt_pltfrm: na
ms.workload: na
ms.search.keywords: India, local, IN, English
ms.date: 10/01/2020
ms.author: v-debapd
ms.openlocfilehash: 7ec5f9a77156973e7f193fb506aeddae0f6b4a54
ms.sourcegitcommit: ddbb5cede750df1baba4b3eab8fbed6744b5b9d6
ms.translationtype: HT
ms.contentlocale: en-IN
ms.lasthandoff: 10/01/2020
ms.locfileid: "3948644"
---
# <a name="purchase-return-of-goods-and-services-to-composite-vendor-or-purchase-return-of-exempted-goods-and-services-with-no-gst-impact"></a>Purchase Return of Goods and Services to Composite Vendor or Purchase Return of Exempted Goods and Services with no GST Impact

[!INCLUDE[vnext_preview](../../includes/vnext_preview.md)]

A composite vendor is a vendor whose aggregate turnover in a financial year does not exceed fifty lakh rupees and has opted for composition scheme. A composite vendor neither collects tax from the recipient of supplies nor passes on any credit of Input Tax. Hence, no GST is computed if the purchases are made from a composite vendor. 

A composite vendor has to register himself with the GST authorities and hence registration no. is mandatory on the vendor card, if the vendor Type is selected as Composite. State Code is also mandatory. No GST entries are generated for a composite vendor, as a composite vendor is not entitled to collect any tax from the customers. 

A buyer may have to return the goods or issue credit note due to various reasons like damaged goods, quality issues etc.

Process for purchase returns to a composite vendor has been explained in this document.


## <a name="create-a-purchase-return-order-or-credit-memo"></a>Create a purchase return order or credit memo

1. Choose the ![Search for Page or Report](image/search_small.png "Search for Page or Report icon") icon, enter **Purchase Return Order or Credit Memo** , and then choose the related link.
2. Select **Vendor** on **Purchase Credit Memo** header, GST vendor type should be **Composite** or **Exempted** .
3. Select **Item Code** for goods, **G/L Account** for Service purchase, **Fixed Asset** for Fixed Asset purchase and **Charge (Item)** for Item Charge on **Purchase Credit Memo** line. 

For example, Purchase Return Order or Credit Memo has been issued for INR 10000 on which no GST is charged.

- GL Entries will be as following:

    |Particulars|Amount|
    |----------------------------------|---------------------------------------|
    |**Vendor Account**|10000|
    |**Purchase or Services or Fixed Asset increase during the year Account**|-10000|







































