---
title: Setting up for GST TDS and GST TCS
description: Setting up for GST TDS and GST TCS
author: v-debapd
ms.service: dynamics365-business-central
ms.topic: article
ms.devlang: na
ms.tgt_pltfrm: na
ms.workload: na
ms.search.keywords: India, local, IN, English
ms.date: 10/01/2020
ms.author: v-debapd
ms.openlocfilehash: 5efa1367aba8d2d2f367cb81db20ca28523a9cc2
ms.sourcegitcommit: ddbb5cede750df1baba4b3eab8fbed6744b5b9d6
ms.translationtype: HT
ms.contentlocale: en-IN
ms.lasthandoff: 10/01/2020
ms.locfileid: "3948622"
---
# <a name="setup-for-gst-tds-and-gst-tcs"></a>Setup for GST TDS and GST TCS 

[!INCLUDE[vnext_preview](../../includes/vnext_preview.md)]

This topic explains the requirement and the process of setting up GST TDS and GST TCS.

## <a name="gst-tds"></a>GST TDS 

As per Section 51 of CGST Act, recipient of goods and services shall deduct TDS of 2% on payment amount where contract amount exceeds INR 250000. The recipient will issue a certificate for the tax amount deducted against the payment made for contract to supplier. Recipient will pay the deducted amount to government and the same is reflected in supplier’s electronic ledger entry, which he can further adjust it against liability.

## <a name="gst-tcs"></a>GST TCS

As per Section 52 of CGST Act, 2017, every e-commerce operator is required to collect tax at the rate of 1% (0.5% of CGST and 0.5% of SGST for intra state supply or 1% of IGST on interstate supply) on the net value of taxable supplies provided the supplier is supplying goods or services through e-commerce operator (online market place) and consideration with respect to the supply is to be collected by the said e-commerce operator The taxable supplies includes total sales and returns. The GST TCS amount collected by e-commerce operator shall be paid to GSTIN and the same will be reflected as available credit for supplier in their electronic cash ledger that can be utilised to offset liability.
Corrections are allowed before GST TCS amount is paid to GSTIN by e-commerce operator.
Hence, there will not be any refund or negative credit. If refund of payment is to be paid by supplier to e-commerce operator then, full amount (without GST TCS) shall be considered.
GST TCS to be calculated on Invoice amount excluding GST. The Credit Memo amount excluding GST should be deducted from Invoice amount for the period before calculating GST TCS.
GST TCS can be calculated for a given period, which can be week, fortnight or a month.
GST TDS is applicable only for Registered Suppliers The calculation of GST TCS is provided on Bank or Cash Payment and Receipt Vouchers.


## <a name="to-set-up-gst-tdstcs"></a>To set up GST TDS/TCS

This setup is required for calculation of GST TDS and GST TCS on payment to vendor or receipt from customer.

1. Choose the ![Search for Page or Report](image/search_small.png "Search for Page or Report icon") icon, enter **GST TDS/TCS Setup** , and then choose the related link.
2. Fill in the fields as described in the following table.
    
    |Field|Description| 
    |---------------------------------|  ---------------------------------------| 
    |**Type**|Specify the relevant type, for example: TDS, TCS.|
    |**GST Component**|Specify the relevant GST component, for example: CGST, SGST, IGST etc.|
    |**GST Effective Date**|Specify the effective date.|
    |**GST TDS/TCS %**|Specify the relevant TDS or TCS percentage.|
    |**GST Jurisdiction**|Specify the relevant jurisdiction type.|





















