---
title: Setting up GST for Bank Charges
description: Setting up GST for Bank Charges
author: v-debapd
ms.service: dynamics365-business-central
ms.topic: article
ms.devlang: na
ms.tgt_pltfrm: na
ms.workload: na
ms.search.keywords: India, local, IN, English
ms.date: 10/01/2020
ms.author: v-debapd
ms.openlocfilehash: 18c110cac1df24e746eb5b0114e9ccd27ef8724a
ms.sourcegitcommit: ddbb5cede750df1baba4b3eab8fbed6744b5b9d6
ms.translationtype: HT
ms.contentlocale: en-IN
ms.lasthandoff: 10/01/2020
ms.locfileid: "3948653"
---
# <a name="setting-up-gst-for-bank-charges"></a><span data-ttu-id="94526-103">Setting Up GST for Bank Charges</span><span class="sxs-lookup"><span data-stu-id="94526-103">Setting Up GST for Bank Charges</span></span> 

[!INCLUDE[vnext_preview](../../includes/vnext_preview.md)]


<span data-ttu-id="94526-104">As per GST Law, GST is applicable on bank charges and ITC can be availed for specified services.</span><span class="sxs-lookup"><span data-stu-id="94526-104">As per GST Law, GST is applicable on bank charges and ITC can be availed for specified services.</span></span>  <span data-ttu-id="94526-105">As per Rule 54(2) of CGST Rules, 2017, Banks shall issue a tax invoice or any other document in lieu of tax invoice.</span><span class="sxs-lookup"><span data-stu-id="94526-105">As per Rule 54(2) of CGST Rules, 2017, Banks shall issue a tax invoice or any other document in lieu of tax invoice.</span></span> <span data-ttu-id="94526-106">In case if an invoice is not provided by the bank, then the bank statement shall be deemed to be an invoice.</span><span class="sxs-lookup"><span data-stu-id="94526-106">In case if an invoice is not provided by the bank, then the bank statement shall be deemed to be an invoice.</span></span> <span data-ttu-id="94526-107">Such document shall be construed as Tax invoice even if it is not serially numbered and whether or not it contains the address of recipient of taxable service.</span><span class="sxs-lookup"><span data-stu-id="94526-107">Such document shall be construed as Tax invoice even if it is not serially numbered and whether or not it contains the address of recipient of taxable service.</span></span> 

<span data-ttu-id="94526-108">Bank charges can be Intrastate or Interstate.</span><span class="sxs-lookup"><span data-stu-id="94526-108">Bank charges can be Intrastate or Interstate.</span></span> <span data-ttu-id="94526-109">CGST & SGST are applicable if the bank and customer are located in the same state.</span><span class="sxs-lookup"><span data-stu-id="94526-109">CGST & SGST are applicable if the bank and customer are located in the same state.</span></span> <span data-ttu-id="94526-110">IGST is applicable if both are in different states.</span><span class="sxs-lookup"><span data-stu-id="94526-110">IGST is applicable if both are in different states.</span></span> 

<span data-ttu-id="94526-111">The place of supply of banking and other financial services to any person shall be the location of the recipient of services on the records of the supplier of services.</span><span class="sxs-lookup"><span data-stu-id="94526-111">The place of supply of banking and other financial services to any person shall be the location of the recipient of services on the records of the supplier of services.</span></span> <span data-ttu-id="94526-112">If the location of recipient of services is not on the records of the supplier, the place of supply shall be the location of the supplier of services.</span><span class="sxs-lookup"><span data-stu-id="94526-112">If the location of recipient of services is not on the records of the supplier, the place of supply shall be the location of the supplier of services.</span></span> 

<span data-ttu-id="94526-113">The place of supply of banking and other financial services shall be the location of the supplier of services.</span><span class="sxs-lookup"><span data-stu-id="94526-113">The place of supply of banking and other financial services shall be the location of the supplier of services.</span></span> <span data-ttu-id="94526-114">If any services are received from a foreign bank by an Indian customer, then the place of supply for such services becomes the place where the foreign bank is located i.e. outside India and hence any charges collected towards such services are not subject to India GST.</span><span class="sxs-lookup"><span data-stu-id="94526-114">If any services are received from a foreign bank by an Indian customer, then the place of supply for such services becomes the place where the foreign bank is located i.e. outside India and hence any charges collected towards such services are not subject to India GST.</span></span>


### <a name="the-following-setups-are-required"></a><span data-ttu-id="94526-115">The following setups are required:</span><span class="sxs-lookup"><span data-stu-id="94526-115">The following setups are required:</span></span> 

- [<span data-ttu-id="94526-116">Bank Accounts</span><span class="sxs-lookup"><span data-stu-id="94526-116">Bank Accounts</span></span>](gst-bank-charges-overview.md#to-set-up-gst-on-a-bank-account)
- [<span data-ttu-id="94526-117">Bank Charges Master</span><span class="sxs-lookup"><span data-stu-id="94526-117">Bank Charges Master</span></span>](gst-bank-charges-overview.md#to-set-up-gst-on-bank-charges-master)
- [<span data-ttu-id="94526-118">Bank Charges Deemed Value Setup</span><span class="sxs-lookup"><span data-stu-id="94526-118">Bank Charges Deemed Value Setup</span></span>](gst-bank-charges-overview.md#to-set-up-gst-on-bank-charges-deemed-value-setup)


## <a name="to-set-up-gst-on-a-bank-account"></a><span data-ttu-id="94526-119">To set up GST on a bank account</span><span class="sxs-lookup"><span data-stu-id="94526-119">To set up GST on a bank account</span></span>

<span data-ttu-id="94526-120">This setup is required to specify that this bank is eligible to calculate GST on bank charges.</span><span class="sxs-lookup"><span data-stu-id="94526-120">This setup is required to specify that this bank is eligible to calculate GST on bank charges.</span></span>

1. <span data-ttu-id="94526-121">Choose the ![Search for Page or Report](image/search_small.png "Search for Page or Report icon") icon, enter **Bank Account** , and then choose the related link.</span><span class="sxs-lookup"><span data-stu-id="94526-121">Choose the ![Search for Page or Report](image/search_small.png "Search for Page or Report icon") icon, enter **Bank Account** , and then choose the related link.</span></span>
2. <span data-ttu-id="94526-122">Fill in the fields as described in the following table.</span><span class="sxs-lookup"><span data-stu-id="94526-122">Fill in the fields as described in the following table.</span></span>
    
    |<span data-ttu-id="94526-123">Field</span><span class="sxs-lookup"><span data-stu-id="94526-123">Field</span></span>|<span data-ttu-id="94526-124">Description</span><span class="sxs-lookup"><span data-stu-id="94526-124">Description</span></span>| 
    |---------------------------------|  ---------------------------------------| 
    |<span data-ttu-id="94526-125">**State Code**</span><span class="sxs-lookup"><span data-stu-id="94526-125">**State Code**</span></span>|<span data-ttu-id="94526-126">This field is required for GST calculation in Bank Charges transactions.</span><span class="sxs-lookup"><span data-stu-id="94526-126">This field is required for GST calculation in Bank Charges transactions.</span></span>|
    |<span data-ttu-id="94526-127">**GST Registration Status**</span><span class="sxs-lookup"><span data-stu-id="94526-127">**GST Registration Status**</span></span>|<span data-ttu-id="94526-128">GST Registration type can be Blank or Registered.</span><span class="sxs-lookup"><span data-stu-id="94526-128">GST Registration type can be Blank or Registered.</span></span> <span data-ttu-id="94526-129">If GST registration No. is added in Bank Account Master the status will be updated as Registered.</span><span class="sxs-lookup"><span data-stu-id="94526-129">If GST registration No. is added in Bank Account Master the status will be updated as Registered.</span></span>|
    |<span data-ttu-id="94526-130">**GST Registration No.**</span><span class="sxs-lookup"><span data-stu-id="94526-130">**GST Registration No.**</span></span>|<span data-ttu-id="94526-131">Registration No. of Bank shall be entered here.</span><span class="sxs-lookup"><span data-stu-id="94526-131">Registration No. of Bank shall be entered here.</span></span> <span data-ttu-id="94526-132">Registration number is mandatory, if GST Registration Status is Registered.</span><span class="sxs-lookup"><span data-stu-id="94526-132">Registration number is mandatory, if GST Registration Status is Registered.</span></span> <span data-ttu-id="94526-133">Registration No. comprises 15-digits.</span><span class="sxs-lookup"><span data-stu-id="94526-133">Registration No. comprises 15-digits.</span></span>|

## <a name="to-set-up-gst-on-bank-charges-master"></a><span data-ttu-id="94526-134">To set up GST on bank charges master</span><span class="sxs-lookup"><span data-stu-id="94526-134">To set up GST on bank charges master</span></span>

<span data-ttu-id="94526-135">This setup is required to calculate GST on bank charges.</span><span class="sxs-lookup"><span data-stu-id="94526-135">This setup is required to calculate GST on bank charges.</span></span>

1. <span data-ttu-id="94526-136">Choose the ![Search for Page or Report](image/search_small.png "Search for Page or Report icon") icon, enter **Bank Charges** , and then choose the related link.</span><span class="sxs-lookup"><span data-stu-id="94526-136">Choose the ![Search for Page or Report](image/search_small.png "Search for Page or Report icon") icon, enter **Bank Charges** , and then choose the related link.</span></span>
2. <span data-ttu-id="94526-137">Fill in the fields as described in the following table.</span><span class="sxs-lookup"><span data-stu-id="94526-137">Fill in the fields as described in the following table.</span></span>
    
    |<span data-ttu-id="94526-138">Field</span><span class="sxs-lookup"><span data-stu-id="94526-138">Field</span></span>|<span data-ttu-id="94526-139">Description</span><span class="sxs-lookup"><span data-stu-id="94526-139">Description</span></span>| 
    |---------------------------------|  ---------------------------------------| 
    |<span data-ttu-id="94526-140">**Code**</span><span class="sxs-lookup"><span data-stu-id="94526-140">**Code**</span></span>|<span data-ttu-id="94526-141">Specifies the unique identification code of Bank Charge.</span><span class="sxs-lookup"><span data-stu-id="94526-141">Specifies the unique identification code of Bank Charge.</span></span>|
    |<span data-ttu-id="94526-142">**Description**</span><span class="sxs-lookup"><span data-stu-id="94526-142">**Description**</span></span>|<span data-ttu-id="94526-143">Specifies the description of the Bank Charge.</span><span class="sxs-lookup"><span data-stu-id="94526-143">Specifies the description of the Bank Charge.</span></span>|
    |<span data-ttu-id="94526-144">**Account**</span><span class="sxs-lookup"><span data-stu-id="94526-144">**Account**</span></span>|<span data-ttu-id="94526-145">Specifies the general ledger account for Bank Charge.</span><span class="sxs-lookup"><span data-stu-id="94526-145">Specifies the general ledger account for Bank Charge.</span></span>|
    |<span data-ttu-id="94526-146">**Foreign Exchange**</span><span class="sxs-lookup"><span data-stu-id="94526-146">**Foreign Exchange**</span></span>|<span data-ttu-id="94526-147">Specifies the Bank Charges that are applicable on Foreign Exchange Sales or Purchase under GST.</span><span class="sxs-lookup"><span data-stu-id="94526-147">Specifies the Bank Charges that are applicable on Foreign Exchange Sales or Purchase under GST.</span></span> <span data-ttu-id="94526-148">For foreign Exchange bank charges, the GST calculation is based on Deemed Value of purchase or sale.</span><span class="sxs-lookup"><span data-stu-id="94526-148">For foreign Exchange bank charges, the GST calculation is based on Deemed Value of purchase or sale.</span></span>|
    |<span data-ttu-id="94526-149">**GST Group Code**</span><span class="sxs-lookup"><span data-stu-id="94526-149">**GST Group Code**</span></span>|<span data-ttu-id="94526-150">Specifies the relevant GST Group Code.</span><span class="sxs-lookup"><span data-stu-id="94526-150">Specifies the relevant GST Group Code.</span></span>|
    |<span data-ttu-id="94526-151">**GST Credit**</span><span class="sxs-lookup"><span data-stu-id="94526-151">**GST Credit**</span></span>|<span data-ttu-id="94526-152">GST Credit can be Availment or Non-Availment.</span><span class="sxs-lookup"><span data-stu-id="94526-152">GST Credit can be Availment or Non-Availment.</span></span> <span data-ttu-id="94526-153">This field by default displays Availment.</span><span class="sxs-lookup"><span data-stu-id="94526-153">This field by default displays Availment.</span></span> <span data-ttu-id="94526-154">If credit cannot be availed on any Bank Charges, then Non-Availment shall be selected manually from the drop down.</span><span class="sxs-lookup"><span data-stu-id="94526-154">If credit cannot be availed on any Bank Charges, then Non-Availment shall be selected manually from the drop down.</span></span> |
    |<span data-ttu-id="94526-155">**HSN/SAC**</span><span class="sxs-lookup"><span data-stu-id="94526-155">**HSN/SAC**</span></span>|<span data-ttu-id="94526-156">All HSN/SAC Codes for GST Group code selected above shall be displayed as a dropdown for this field, business user has to select appropriate code.</span><span class="sxs-lookup"><span data-stu-id="94526-156">All HSN/SAC Codes for GST Group code selected above shall be displayed as a dropdown for this field, business user has to select appropriate code.</span></span>|
    |<span data-ttu-id="94526-157">**Exempted**</span><span class="sxs-lookup"><span data-stu-id="94526-157">**Exempted**</span></span>|<span data-ttu-id="94526-158">This field is checked if the Bank Charges are exempted from payment of GST.</span><span class="sxs-lookup"><span data-stu-id="94526-158">This field is checked if the Bank Charges are exempted from payment of GST.</span></span>|

## <a name="to-set-up-gst-on-bank-charges-deemed-value-setup"></a><span data-ttu-id="94526-159">To set up GST on bank charges deemed value setup</span><span class="sxs-lookup"><span data-stu-id="94526-159">To set up GST on bank charges deemed value setup</span></span>

<span data-ttu-id="94526-160">This setup is required to estimate the Deemed Value for calculation of GST on foreign exchange purchases.</span><span class="sxs-lookup"><span data-stu-id="94526-160">This setup is required to estimate the Deemed Value for calculation of GST on foreign exchange purchases.</span></span>

1. <span data-ttu-id="94526-161">Choose the ![Search for Page or Report](image/search_small.png "Search for Page or Report icon") icon, enter **Bank Charges Deemed Value Setup** , and then choose the related link.</span><span class="sxs-lookup"><span data-stu-id="94526-161">Choose the ![Search for Page or Report](image/search_small.png "Search for Page or Report icon") icon, enter **Bank Charges Deemed Value Setup** , and then choose the related link.</span></span>
2. <span data-ttu-id="94526-162">Fill in the fields as described in the following table.</span><span class="sxs-lookup"><span data-stu-id="94526-162">Fill in the fields as described in the following table.</span></span>
    
    |<span data-ttu-id="94526-163">Field</span><span class="sxs-lookup"><span data-stu-id="94526-163">Field</span></span>|<span data-ttu-id="94526-164">Description</span><span class="sxs-lookup"><span data-stu-id="94526-164">Description</span></span>| 
    |---------------------------------|  ---------------------------------------| 
    |<span data-ttu-id="94526-165">**Bank Charges Code**</span><span class="sxs-lookup"><span data-stu-id="94526-165">**Bank Charges Code**</span></span>|<span data-ttu-id="94526-166">Specifies the code of Bank Charge from drop down list.</span><span class="sxs-lookup"><span data-stu-id="94526-166">Specifies the code of Bank Charge from drop down list.</span></span>|
    |<span data-ttu-id="94526-167">**Lower Limit**</span><span class="sxs-lookup"><span data-stu-id="94526-167">**Lower Limit**</span></span>|<span data-ttu-id="94526-168">Specifies the lower limit of the bank charge code.</span><span class="sxs-lookup"><span data-stu-id="94526-168">Specifies the lower limit of the bank charge code.</span></span>|
    |<span data-ttu-id="94526-169">**Upper Limit**</span><span class="sxs-lookup"><span data-stu-id="94526-169">**Upper Limit**</span></span>|<span data-ttu-id="94526-170">Specifies the upper limit of the bank charge code.</span><span class="sxs-lookup"><span data-stu-id="94526-170">Specifies the upper limit of the bank charge code.</span></span>|
    |<span data-ttu-id="94526-171">**Formula**</span><span class="sxs-lookup"><span data-stu-id="94526-171">**Formula**</span></span>|<span data-ttu-id="94526-172">Specifies the formula of the charge calculation.</span><span class="sxs-lookup"><span data-stu-id="94526-172">Specifies the formula of the charge calculation.</span></span>|
    |<span data-ttu-id="94526-173">**Min. Deemed Value**</span><span class="sxs-lookup"><span data-stu-id="94526-173">**Min. Deemed Value**</span></span>|<span data-ttu-id="94526-174">Specifies the minimum value.</span><span class="sxs-lookup"><span data-stu-id="94526-174">Specifies the minimum value.</span></span>|
    |<span data-ttu-id="94526-175">**Max. Deemed Value**</span><span class="sxs-lookup"><span data-stu-id="94526-175">**Max. Deemed Value**</span></span>|<span data-ttu-id="94526-176">Specifies the maximum value.</span><span class="sxs-lookup"><span data-stu-id="94526-176">Specifies the maximum value.</span></span>|
    |<span data-ttu-id="94526-177">**Deemed %**</span><span class="sxs-lookup"><span data-stu-id="94526-177">**Deemed %**</span></span>|<span data-ttu-id="94526-178">Specifies the percentage of calculation.</span><span class="sxs-lookup"><span data-stu-id="94526-178">Specifies the percentage of calculation.</span></span>|
    |<span data-ttu-id="94526-179">**Fixed Amount**</span><span class="sxs-lookup"><span data-stu-id="94526-179">**Fixed Amount**</span></span>|<span data-ttu-id="94526-180">Specifies the fixed deemed value.</span><span class="sxs-lookup"><span data-stu-id="94526-180">Specifies the fixed deemed value.</span></span>|





















