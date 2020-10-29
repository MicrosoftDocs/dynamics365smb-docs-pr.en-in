---
title: Tax Engine Overview
description: Tax Engine Overview
author: v-debapd
ms.service: dynamics365-business-central
ms.topic: article
ms.devlang: na
ms.tgt_pltfrm: na
ms.workload: na
ms.search.keywords: India, local, IN, English
ms.date: 10/01/2020
ms.author: v-debapd
ms.openlocfilehash: 69ea2221f56b8eba96b1c720feaf81c6c62f5d29
ms.sourcegitcommit: ddbb5cede750df1baba4b3eab8fbed6744b5b9d6
ms.translationtype: HT
ms.contentlocale: en-IN
ms.lasthandoff: 10/01/2020
ms.locfileid: "3948601"
---
# <a name="tax-engine-overview"></a>Tax Engine Overview
[!INCLUDE[vnext_preview](../../includes/vnext_preview.md)]

In a country, where tax reforms are happening at a fast pace, it is natural to expect frequent changes. These changes may pertain to change in rate of tax, calculation method, tax     filing or reporting etc. To manage such changes with least effort, it is necessary to manage, as much as possible through configuration. 

Tax Engine is a suite of extensions to enable configuration of tax rules and its computation. It consists of a use case designer, which allows modification of existing use cases or creation of new use cases. Use case contains the description of business scenario, conditions to be met and event that will trigger calculation of tax. A use case can be enabled or disabled as per the business need.

Tax Engine extension is a combination of 6 smaller extensions or modules. Extensions are packaged to deliver functionality related to configuration of tax, tax calculation, import and export of configuration etc.



|Particulars|Description|
|---------|---------|
|**Tax Engine Core Extension**| Core extension contains the UI elements and related tables which are commonly used throughout Tax Engine. Also, it has library functions, which can be used by other extensions other than Tax Engine, to get any value.|
|**Tax Engine Tax Type Handler Extension**|Tax Type Handler extension contains UI elements and related tables which enables definition of a new tax type, its attributes and map business entities involved with this tax type.|
|**Tax Engine Tax Use Case Handler Extension**|Tax Use Case Handler extension contains UI elements and related tables which are used for configuring a tax use case. Use case definition includes primary business entity like Sales Order or Purchase Order line table, conditions for execution of use case, rules and formulae for calculation of tax and functionality to script business logic.|
|**Tax Engine Scripting Extension**|Script extension contains UI elements and related tables which are used in scripting of Business logic within a use case.|
|**Tax Engine Tax Posting Handler Extension**|Posting Handler extension contains UI elements and related tables which are used to configure posting of tax components to G/L Accounts and related tax ledgers.|
|**Tax Engine Json Exchange Extension**|Json Exchange extension enables import or export of configuration data of tax engine in json format.|


> [!NOTE]
> The Tax engine functionality is only available for legal entities with a primary address in India.







































