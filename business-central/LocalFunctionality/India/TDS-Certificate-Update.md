---
title: TDS Certificate Tracking
description: Specifies the TDS Certificate Tracking
author: v-debapd
ms.service: dynamics365-business-central
ms.topic: article
ms.devlang: na
ms.tgt_pltfrm: na
ms.workload: na
ms.search.keywords: India, local, IN, English
ms.date: 10/01/2020
ms.author: v-debapd
ms.openlocfilehash: 2b12ae2c17d10be20a71f927ca2b54ef102048a8
ms.sourcegitcommit: ddbb5cede750df1baba4b3eab8fbed6744b5b9d6
ms.translationtype: HT
ms.contentlocale: en-IN
ms.lasthandoff: 10/01/2020
ms.locfileid: "3948610"
---
# <a name="tds-certificate-tracking"></a>TDS Certificate Tracking

[!INCLUDE[vnext_preview](../../includes/vnext_preview.md)]

This topic explains how to track and update the TDS certificate receivable or received from a customer.

## <a name="tds-certificate-details-assign-update-and-rectification-process"></a>TDS certificate details assign, update and rectification process

- Assign TDS certificate details

  Customer Ledger entries, which are not marked, against which TDS certificate is receivable can be assigned separately. Provision is available to mark the posted customer transactions (invoices or payments) for which TDS certificate is receivable.

   1. Choose the ![Search for Page or Report](image/search_small.png "Search for Page or Report icon") icon, enter **Update TDS Certificate Details** , and then choose the related link. 
   2. Select relevant customer code in **Customer No.** field then Acton -> Function -> Assign TDS Cert. Details, system will open the customer ledger entry of the customer. Select and update the relevant documents by marking 'TDS Certificate Receivable' field true. Marked document will be removed from the 'Assign TDS Cert. Details' page and will be added in 'Update TDS Cert. Details' page.
   3. System will update the 'TDS Certificate Receivable' field as true in Customer Ledger Entry.

- Update TDS certificate details

  After receiving the TDS Certificate, it is required to update the TDS certificate details.

  1. Choose the ![Search for Page or Report](image/search_small.png "Search for Page or Report icon") icon, enter **Update TDS Certificate Details** , and then choose the related link. 
  2. Select relevant information in **Customer No.** , **Certificate No.** , **Date of Receipt** , **Certificate TDS Amount** , **Financial Year** , **TDS Receivable Group** , the Acton -> Function -> Update TDS Cert. Details, system will open the customer ledger entry of the customer for which 'TDS Receivable for Customer' is marked true.
  3. Select and update the relevant documents for which company has received the TDS Certificate by marking 'TDS Certificate Received' field true and update. Marked document will be removed from the 'Update TDS Cert. Details' page and will be added in 'Rectify TDS Cert. Details' page.
  4. System will update the customer ledger entry of the selected document with the input data.

- Rectify TDS certificate details

  Rectification of updated details may also be required just in case some wrong information is provided earlier.

   1. Choose the ![Search for Page or Report](image/search_small.png "Search for Page or Report icon") icon, enter **Update TDS Certificate Details** , and then choose the related link. 
   2. Select relevant customer code in **Customer No.** field then Acton -> Function -> Rectify TDS Cert. Details, system will open the customer ledger entry for which TDS certificate details are updated. 
   3. Select and update the relevant documents by marking 'TDS Certificate Receivable' field false. Marked document will be removed from the 'Rectify TDS Cert. Details' page and will be added in 'Update TDS Cert. Details' page.
   4. System will remove the details related to TDS certificate from Customer Ledger Entry.