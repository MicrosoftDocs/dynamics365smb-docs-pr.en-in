---
title: Tax Engine - Script Activity
description: Tax Engine - Script Activity
author: v-debapd
ms.service: dynamics365-business-central
ms.topic: article
ms.devlang: na
ms.tgt_pltfrm: na
ms.workload: na
ms.search.keywords: India, local, IN, English
ms.date: 10/01/2020
ms.author: v-debapd
ms.openlocfilehash: 476fc112933e194cbf5035851549d51eccd961d8
ms.sourcegitcommit: ddbb5cede750df1baba4b3eab8fbed6744b5b9d6
ms.translationtype: HT
ms.contentlocale: en-IN
ms.lasthandoff: 10/01/2020
ms.locfileid: "3948598"
---
# <a name="tax-engine---script-activity"></a><span data-ttu-id="08ef9-103">Tax Engine - Script Activity</span><span class="sxs-lookup"><span data-stu-id="08ef9-103">Tax Engine - Script Activity</span></span>

[!INCLUDE[vnext_preview](../../includes/vnext_preview.md)]

<span data-ttu-id="08ef9-104">Script extension contains UI elements and tables which are used in scripting of Business logics within a use case.</span><span class="sxs-lookup"><span data-stu-id="08ef9-104">Script extension contains UI elements and tables which are used in scripting of Business logics within a use case.</span></span>

### <a name="string--text"></a><span data-ttu-id="08ef9-105">String / Text</span><span class="sxs-lookup"><span data-stu-id="08ef9-105">String / Text</span></span>

- <span data-ttu-id="08ef9-106">**Concatenate** : Concatenates list values and outputs to a variable.</span><span class="sxs-lookup"><span data-stu-id="08ef9-106">**Concatenate** : Concatenates list values and outputs to a variable.</span></span>

- <span data-ttu-id="08ef9-107">**String Expression** : It is used to compose string.</span><span class="sxs-lookup"><span data-stu-id="08ef9-107">**String Expression** : It is used to compose string.</span></span> <span data-ttu-id="08ef9-108">Names that are enclosed within curly braces are treated as tokens.</span><span class="sxs-lookup"><span data-stu-id="08ef9-108">Names that are enclosed within curly braces are treated as tokens.</span></span> <span data-ttu-id="08ef9-109">Values can be assigned to tokens using lookups, whereas on the Value tab,  source of that token can be defined.</span><span class="sxs-lookup"><span data-stu-id="08ef9-109">Values can be assigned to tokens using lookups, whereas on the Value tab,  source of that token can be defined.</span></span>

- <span data-ttu-id="08ef9-110">**Length of String** : Calculates the length of the string and assigns it to the output variable.</span><span class="sxs-lookup"><span data-stu-id="08ef9-110">**Length of String** : Calculates the length of the string and assigns it to the output variable.</span></span>

  |<span data-ttu-id="08ef9-111">Type</span><span class="sxs-lookup"><span data-stu-id="08ef9-111">Type</span></span>|<span data-ttu-id="08ef9-112">Description</span><span class="sxs-lookup"><span data-stu-id="08ef9-112">Description</span></span>|
  |--------------------|-----------------------|
  |<span data-ttu-id="08ef9-113">Output Variable</span><span class="sxs-lookup"><span data-stu-id="08ef9-113">Output Variable</span></span>|<span data-ttu-id="08ef9-114">Specifies the name of variable in which value of the length is stored.</span><span class="sxs-lookup"><span data-stu-id="08ef9-114">Specifies the name of variable in which value of the length is stored.</span></span>|
  |<span data-ttu-id="08ef9-115">String</span><span class="sxs-lookup"><span data-stu-id="08ef9-115">String</span></span>|<span data-ttu-id="08ef9-116">Specifies the string for which length is to be calculated, hard coded text or/and expression can be entered.</span><span class="sxs-lookup"><span data-stu-id="08ef9-116">Specifies the string for which length is to be calculated, hard coded text or/and expression can be entered.</span></span>|

- <span data-ttu-id="08ef9-117">**Convert Case of String** : Converts the case of the string and assigns to the output variable.</span><span class="sxs-lookup"><span data-stu-id="08ef9-117">**Convert Case of String** : Converts the case of the string and assigns to the output variable.</span></span>

  |<span data-ttu-id="08ef9-118">Type</span><span class="sxs-lookup"><span data-stu-id="08ef9-118">Type</span></span>|<span data-ttu-id="08ef9-119">Description</span><span class="sxs-lookup"><span data-stu-id="08ef9-119">Description</span></span>|
  |--------------------|-----------------------|
  |<span data-ttu-id="08ef9-120">Output Variable</span><span class="sxs-lookup"><span data-stu-id="08ef9-120">Output Variable</span></span>|<span data-ttu-id="08ef9-121">Specifies the name of variable in which value of converted case will be stored.</span><span class="sxs-lookup"><span data-stu-id="08ef9-121">Specifies the name of variable in which value of converted case will be stored.</span></span>|
  |<span data-ttu-id="08ef9-122">String</span><span class="sxs-lookup"><span data-stu-id="08ef9-122">String</span></span>|<span data-ttu-id="08ef9-123">Specifies the string for which case will be converted, hard coded text or/and expression can be entered.</span><span class="sxs-lookup"><span data-stu-id="08ef9-123">Specifies the string for which case will be converted, hard coded text or/and expression can be entered.</span></span>|
  |<span data-ttu-id="08ef9-124">Convert to Case</span><span class="sxs-lookup"><span data-stu-id="08ef9-124">Convert to Case</span></span>|<span data-ttu-id="08ef9-125">Converts case of the string, it can be either Upper Case or Lower Case.</span><span class="sxs-lookup"><span data-stu-id="08ef9-125">Converts case of the string, it can be either Upper Case or Lower Case.</span></span>|

- <span data-ttu-id="08ef9-126">**Find Substring in String** : Finds the substring in string and assigns the position of the substring to output variable.</span><span class="sxs-lookup"><span data-stu-id="08ef9-126">**Find Substring in String** : Finds the substring in string and assigns the position of the substring to output variable.</span></span>

  |<span data-ttu-id="08ef9-127">Type</span><span class="sxs-lookup"><span data-stu-id="08ef9-127">Type</span></span>|<span data-ttu-id="08ef9-128">Description</span><span class="sxs-lookup"><span data-stu-id="08ef9-128">Description</span></span>|
  |--------------------|-----------------------|
  |<span data-ttu-id="08ef9-129">Output Variable</span><span class="sxs-lookup"><span data-stu-id="08ef9-129">Output Variable</span></span>|<span data-ttu-id="08ef9-130">Specifies the name of variable in which value of substring will be stored.</span><span class="sxs-lookup"><span data-stu-id="08ef9-130">Specifies the name of variable in which value of substring will be stored.</span></span>|
  |<span data-ttu-id="08ef9-131">String</span><span class="sxs-lookup"><span data-stu-id="08ef9-131">String</span></span>|<span data-ttu-id="08ef9-132">This will be the string for which value of substring will be searched, hard coded text or/and expression can be entered.</span><span class="sxs-lookup"><span data-stu-id="08ef9-132">This will be the string for which value of substring will be searched, hard coded text or/and expression can be entered.</span></span>|
  |<span data-ttu-id="08ef9-133">Substring</span><span class="sxs-lookup"><span data-stu-id="08ef9-133">Substring</span></span>|<span data-ttu-id="08ef9-134">Specifies the string or expression which needs to be identified from String value.</span><span class="sxs-lookup"><span data-stu-id="08ef9-134">Specifies the string or expression which needs to be identified from String value.</span></span>|

- <span data-ttu-id="08ef9-135">**Replace Substring in String** : Replace substring in a string with a new string and assigns to output variable.</span><span class="sxs-lookup"><span data-stu-id="08ef9-135">**Replace Substring in String** : Replace substring in a string with a new string and assigns to output variable.</span></span>

  |<span data-ttu-id="08ef9-136">Type</span><span class="sxs-lookup"><span data-stu-id="08ef9-136">Type</span></span>|<span data-ttu-id="08ef9-137">Description</span><span class="sxs-lookup"><span data-stu-id="08ef9-137">Description</span></span>|
  |--------------------|-----------------------|
  |<span data-ttu-id="08ef9-138">Output Variable</span><span class="sxs-lookup"><span data-stu-id="08ef9-138">Output Variable</span></span>|<span data-ttu-id="08ef9-139">Specifies the name of variable in which the value of Replaced String will be stored.</span><span class="sxs-lookup"><span data-stu-id="08ef9-139">Specifies the name of variable in which the value of Replaced String will be stored.</span></span>|
  |<span data-ttu-id="08ef9-140">Sub String</span><span class="sxs-lookup"><span data-stu-id="08ef9-140">Sub String</span></span>|<span data-ttu-id="08ef9-141">This will be the string content which will be replaced from 'In String', hard coded text or/and expression can be entered.</span><span class="sxs-lookup"><span data-stu-id="08ef9-141">This will be the string content which will be replaced from 'In String', hard coded text or/and expression can be entered.</span></span>|
  |<span data-ttu-id="08ef9-142">With String</span><span class="sxs-lookup"><span data-stu-id="08ef9-142">With String</span></span>|<span data-ttu-id="08ef9-143">This will be the string content which will be replaced with 'Sub String', hard coded text or/and expression can be entered.</span><span class="sxs-lookup"><span data-stu-id="08ef9-143">This will be the string content which will be replaced with 'Sub String', hard coded text or/and expression can be entered.</span></span>|
  |<span data-ttu-id="08ef9-144">In String</span><span class="sxs-lookup"><span data-stu-id="08ef9-144">In String</span></span>|<span data-ttu-id="08ef9-145">This will be the string on which replacement of character will happen.</span><span class="sxs-lookup"><span data-stu-id="08ef9-145">This will be the string on which replacement of character will happen.</span></span>|

- <span data-ttu-id="08ef9-146">**Extract Substring** : Extracts substring of a length from a string from start/ end and assigns to output variable.</span><span class="sxs-lookup"><span data-stu-id="08ef9-146">**Extract Substring** : Extracts substring of a length from a string from start/ end and assigns to output variable.</span></span>

  |<span data-ttu-id="08ef9-147">Type</span><span class="sxs-lookup"><span data-stu-id="08ef9-147">Type</span></span>|<span data-ttu-id="08ef9-148">Description</span><span class="sxs-lookup"><span data-stu-id="08ef9-148">Description</span></span>|
  |--------------------|-----------------------|
  |<span data-ttu-id="08ef9-149">Output Variable</span><span class="sxs-lookup"><span data-stu-id="08ef9-149">Output Variable</span></span>|<span data-ttu-id="08ef9-150">Specifies the name of variable in which value of Extracted Sub String will be stored.</span><span class="sxs-lookup"><span data-stu-id="08ef9-150">Specifies the name of variable in which value of Extracted Sub String will be stored.</span></span>|
  |<span data-ttu-id="08ef9-151">String</span><span class="sxs-lookup"><span data-stu-id="08ef9-151">String</span></span>|<span data-ttu-id="08ef9-152">This will be the string for which value of Substring will be extracted, hard coded text or/and expression can be entered.</span><span class="sxs-lookup"><span data-stu-id="08ef9-152">This will be the string for which value of Substring will be extracted, hard coded text or/and expression can be entered.</span></span>|
  |<span data-ttu-id="08ef9-153">From</span><span class="sxs-lookup"><span data-stu-id="08ef9-153">From</span></span>|<span data-ttu-id="08ef9-154">Starting point of extraction, it can be either start or end.</span><span class="sxs-lookup"><span data-stu-id="08ef9-154">Starting point of extraction, it can be either start or end.</span></span>|
  |<span data-ttu-id="08ef9-155">Length</span><span class="sxs-lookup"><span data-stu-id="08ef9-155">Length</span></span>|<span data-ttu-id="08ef9-156">Length of the character to extract.</span><span class="sxs-lookup"><span data-stu-id="08ef9-156">Length of the character to extract.</span></span>|

- <span data-ttu-id="08ef9-157">**Extract Substring from Index of String** : Extracts substring of a length from a string with an index and assigns to output variable.</span><span class="sxs-lookup"><span data-stu-id="08ef9-157">**Extract Substring from Index of String** : Extracts substring of a length from a string with an index and assigns to output variable.</span></span>

  |<span data-ttu-id="08ef9-158">Type</span><span class="sxs-lookup"><span data-stu-id="08ef9-158">Type</span></span>|<span data-ttu-id="08ef9-159">Description</span><span class="sxs-lookup"><span data-stu-id="08ef9-159">Description</span></span>|
  |--------------------|-----------------------|
  |<span data-ttu-id="08ef9-160">Output Variable</span><span class="sxs-lookup"><span data-stu-id="08ef9-160">Output Variable</span></span>|<span data-ttu-id="08ef9-161">Specifies the variable name in which value of Extracted Sub String will be stored.</span><span class="sxs-lookup"><span data-stu-id="08ef9-161">Specifies the variable name in which value of Extracted Sub String will be stored.</span></span>|
  |<span data-ttu-id="08ef9-162">In String</span><span class="sxs-lookup"><span data-stu-id="08ef9-162">In String</span></span>|<span data-ttu-id="08ef9-163">This will be the string for which value of Substring will be extracted, hard coded text or/and expression can be entered.</span><span class="sxs-lookup"><span data-stu-id="08ef9-163">This will be the string for which value of Substring will be extracted, hard coded text or/and expression can be entered.</span></span>|
  |<span data-ttu-id="08ef9-164">From Index</span><span class="sxs-lookup"><span data-stu-id="08ef9-164">From Index</span></span>|<span data-ttu-id="08ef9-165">Starting point of extraction as Index.</span><span class="sxs-lookup"><span data-stu-id="08ef9-165">Starting point of extraction as Index.</span></span>|
  |<span data-ttu-id="08ef9-166">Length</span><span class="sxs-lookup"><span data-stu-id="08ef9-166">Length</span></span>|<span data-ttu-id="08ef9-167">Length of the character to extract.</span><span class="sxs-lookup"><span data-stu-id="08ef9-167">Length of the character to extract.</span></span>|

### <a name="number"></a><span data-ttu-id="08ef9-168">Number</span><span class="sxs-lookup"><span data-stu-id="08ef9-168">Number</span></span>

- <span data-ttu-id="08ef9-169">**Number Calculation** : Calculates the number based on values and the operator.</span><span class="sxs-lookup"><span data-stu-id="08ef9-169">**Number Calculation** : Calculates the number based on values and the operator.</span></span> <span data-ttu-id="08ef9-170">It is assigned to output variable.</span><span class="sxs-lookup"><span data-stu-id="08ef9-170">It is assigned to output variable.</span></span>

  |<span data-ttu-id="08ef9-171">Type</span><span class="sxs-lookup"><span data-stu-id="08ef9-171">Type</span></span>|<span data-ttu-id="08ef9-172">Description</span><span class="sxs-lookup"><span data-stu-id="08ef9-172">Description</span></span>|
  |--------------------|-----------------------|
  |<span data-ttu-id="08ef9-173">Output Variable</span><span class="sxs-lookup"><span data-stu-id="08ef9-173">Output Variable</span></span>|<span data-ttu-id="08ef9-174">Specifies the variable name in which value of Calculated Number will be stored.</span><span class="sxs-lookup"><span data-stu-id="08ef9-174">Specifies the variable name in which value of Calculated Number will be stored.</span></span>|
  |<span data-ttu-id="08ef9-175">Value</span><span class="sxs-lookup"><span data-stu-id="08ef9-175">Value</span></span>|<span data-ttu-id="08ef9-176">This will be the Left-Hand Side (LHS) of the Number Calculation.</span><span class="sxs-lookup"><span data-stu-id="08ef9-176">This will be the Left-Hand Side (LHS) of the Number Calculation.</span></span>| 
  |<span data-ttu-id="08ef9-177">Operator</span><span class="sxs-lookup"><span data-stu-id="08ef9-177">Operator</span></span>|<span data-ttu-id="08ef9-178">Operator to be used for calculation, it can be Addition, Subtraction, Division, Multiplication.</span><span class="sxs-lookup"><span data-stu-id="08ef9-178">Operator to be used for calculation, it can be Addition, Subtraction, Division, Multiplication.</span></span>|
  |<span data-ttu-id="08ef9-179">Value 2</span><span class="sxs-lookup"><span data-stu-id="08ef9-179">Value 2</span></span>|<span data-ttu-id="08ef9-180">This will be the Right-Hand Side (RHS) of the Number Calculation.</span><span class="sxs-lookup"><span data-stu-id="08ef9-180">This will be the Right-Hand Side (RHS) of the Number Calculation.</span></span>|

- <span data-ttu-id="08ef9-181">**Numeric Expression** : Numeric Expression is to evaluate expression into number and assign it to output variable.</span><span class="sxs-lookup"><span data-stu-id="08ef9-181">**Numeric Expression** : Numeric Expression is to evaluate expression into number and assign it to output variable.</span></span> <span data-ttu-id="08ef9-182">Text token will be extracted and replaced with values from Lookups, whereas on the value tab source of that token can be defined.</span><span class="sxs-lookup"><span data-stu-id="08ef9-182">Text token will be extracted and replaced with values from Lookups, whereas on the value tab source of that token can be defined.</span></span>

- <span data-ttu-id="08ef9-183">**Round Number** : Round Number is used to round decimal places to a precision and direction could be nearest, up or down.</span><span class="sxs-lookup"><span data-stu-id="08ef9-183">**Round Number** : Round Number is used to round decimal places to a precision and direction could be nearest, up or down.</span></span>

  |<span data-ttu-id="08ef9-184">Type</span><span class="sxs-lookup"><span data-stu-id="08ef9-184">Type</span></span>|<span data-ttu-id="08ef9-185">Description</span><span class="sxs-lookup"><span data-stu-id="08ef9-185">Description</span></span>|
  |--------------------|-----------------------|
  |<span data-ttu-id="08ef9-186">Output Variable</span><span class="sxs-lookup"><span data-stu-id="08ef9-186">Output Variable</span></span>|<span data-ttu-id="08ef9-187">Specifies the variable name in which value of Rounded Number will be stored.</span><span class="sxs-lookup"><span data-stu-id="08ef9-187">Specifies the variable name in which value of Rounded Number will be stored.</span></span>|
  |<span data-ttu-id="08ef9-188">Number</span><span class="sxs-lookup"><span data-stu-id="08ef9-188">Number</span></span>|<span data-ttu-id="08ef9-189">Value that will be rounded.</span><span class="sxs-lookup"><span data-stu-id="08ef9-189">Value that will be rounded.</span></span>|
  |<span data-ttu-id="08ef9-190">Precision</span><span class="sxs-lookup"><span data-stu-id="08ef9-190">Precision</span></span>|<span data-ttu-id="08ef9-191">Rounding precision.</span><span class="sxs-lookup"><span data-stu-id="08ef9-191">Rounding precision.</span></span>|
  |<span data-ttu-id="08ef9-192">Direction</span><span class="sxs-lookup"><span data-stu-id="08ef9-192">Direction</span></span>|<span data-ttu-id="08ef9-193">Direction of rounding, it can be Nearest, Up or Down.</span><span class="sxs-lookup"><span data-stu-id="08ef9-193">Direction of rounding, it can be Nearest, Up or Down.</span></span>|

### <a name="date"></a><span data-ttu-id="08ef9-194">Date</span><span class="sxs-lookup"><span data-stu-id="08ef9-194">Date</span></span>

- <span data-ttu-id="08ef9-195">**Date Calculation** : ‘Date Calculation’ is used to manipulate dates by adding or subtracting number of days / months / years and it is assigned to output variable.</span><span class="sxs-lookup"><span data-stu-id="08ef9-195">**Date Calculation** : ‘Date Calculation’ is used to manipulate dates by adding or subtracting number of days / months / years and it is assigned to output variable.</span></span>

  |<span data-ttu-id="08ef9-196">Type</span><span class="sxs-lookup"><span data-stu-id="08ef9-196">Type</span></span>|<span data-ttu-id="08ef9-197">Description</span><span class="sxs-lookup"><span data-stu-id="08ef9-197">Description</span></span>|
  |--------------------|-----------------------|
  |<span data-ttu-id="08ef9-198">Output Variable</span><span class="sxs-lookup"><span data-stu-id="08ef9-198">Output Variable</span></span>|<span data-ttu-id="08ef9-199">Specifies the name of variable in which value of ‘Calculated Date’ will be stored.</span><span class="sxs-lookup"><span data-stu-id="08ef9-199">Specifies the name of variable in which value of ‘Calculated Date’ will be stored.</span></span>|
  |<span data-ttu-id="08ef9-200">Date</span><span class="sxs-lookup"><span data-stu-id="08ef9-200">Date</span></span>|<span data-ttu-id="08ef9-201">This will be the date on which calculation will be done.</span><span class="sxs-lookup"><span data-stu-id="08ef9-201">This will be the date on which calculation will be done.</span></span>|
  |<span data-ttu-id="08ef9-202">Operator</span><span class="sxs-lookup"><span data-stu-id="08ef9-202">Operator</span></span>|<span data-ttu-id="08ef9-203">This will be the operator that will be applied on ‘Date for calculation’.</span><span class="sxs-lookup"><span data-stu-id="08ef9-203">This will be the operator that will be applied on ‘Date for calculation’.</span></span>|
  |<span data-ttu-id="08ef9-204">Number</span><span class="sxs-lookup"><span data-stu-id="08ef9-204">Number</span></span>|<span data-ttu-id="08ef9-205">This will be the number that will added or subtracted to date.</span><span class="sxs-lookup"><span data-stu-id="08ef9-205">This will be the number that will added or subtracted to date.</span></span>|
  |<span data-ttu-id="08ef9-206">Period</span><span class="sxs-lookup"><span data-stu-id="08ef9-206">Period</span></span>|<span data-ttu-id="08ef9-207">This will be the type that will be added or subtracted to date as Number.</span><span class="sxs-lookup"><span data-stu-id="08ef9-207">This will be the type that will be added or subtracted to date as Number.</span></span> <span data-ttu-id="08ef9-208">It can be Days, Week, Months, Year.</span><span class="sxs-lookup"><span data-stu-id="08ef9-208">It can be Days, Week, Months, Year.</span></span>|

- <span data-ttu-id="08ef9-209">**Extract Date Part** : ‘Extract Date Part’ is used to extract day / month / year from a date and assign it to output variable.</span><span class="sxs-lookup"><span data-stu-id="08ef9-209">**Extract Date Part** : ‘Extract Date Part’ is used to extract day / month / year from a date and assign it to output variable.</span></span>

  |<span data-ttu-id="08ef9-210">Type</span><span class="sxs-lookup"><span data-stu-id="08ef9-210">Type</span></span>|<span data-ttu-id="08ef9-211">Description</span><span class="sxs-lookup"><span data-stu-id="08ef9-211">Description</span></span>|
  |--------------------|-----------------------|
  |<span data-ttu-id="08ef9-212">Output Variable</span><span class="sxs-lookup"><span data-stu-id="08ef9-212">Output Variable</span></span>|<span data-ttu-id="08ef9-213">Specifies the variable name in which value of Extracted Date will be stored.</span><span class="sxs-lookup"><span data-stu-id="08ef9-213">Specifies the variable name in which value of Extracted Date will be stored.</span></span>|
  |<span data-ttu-id="08ef9-214">Date</span><span class="sxs-lookup"><span data-stu-id="08ef9-214">Date</span></span>|<span data-ttu-id="08ef9-215">This will be the Date on which extraction will be done.</span><span class="sxs-lookup"><span data-stu-id="08ef9-215">This will be the Date on which extraction will be done.</span></span>|
  |<span data-ttu-id="08ef9-216">Part</span><span class="sxs-lookup"><span data-stu-id="08ef9-216">Part</span></span>|<span data-ttu-id="08ef9-217">Type of extraction, it can be Year, Month, Day.</span><span class="sxs-lookup"><span data-stu-id="08ef9-217">Type of extraction, it can be Year, Month, Day.</span></span>|

- <span data-ttu-id="08ef9-218">**Find Interval between Dates** : Find Interval between dates is used to find number of days / hours / minutes between dates and assign it to output variable.</span><span class="sxs-lookup"><span data-stu-id="08ef9-218">**Find Interval between Dates** : Find Interval between dates is used to find number of days / hours / minutes between dates and assign it to output variable.</span></span>

  |<span data-ttu-id="08ef9-219">Type</span><span class="sxs-lookup"><span data-stu-id="08ef9-219">Type</span></span>|<span data-ttu-id="08ef9-220">Description</span><span class="sxs-lookup"><span data-stu-id="08ef9-220">Description</span></span>|
  |--------------------|-----------------------|
  |<span data-ttu-id="08ef9-221">Output Variable</span><span class="sxs-lookup"><span data-stu-id="08ef9-221">Output Variable</span></span>|<span data-ttu-id="08ef9-222">Specifies the variable name in which value of Interval will be stored.</span><span class="sxs-lookup"><span data-stu-id="08ef9-222">Specifies the variable name in which value of Interval will be stored.</span></span>|
  |<span data-ttu-id="08ef9-223">From Date</span><span class="sxs-lookup"><span data-stu-id="08ef9-223">From Date</span></span>|<span data-ttu-id="08ef9-224">This will be starting date of date range.</span><span class="sxs-lookup"><span data-stu-id="08ef9-224">This will be starting date of date range.</span></span>|
  |<span data-ttu-id="08ef9-225">To Date</span><span class="sxs-lookup"><span data-stu-id="08ef9-225">To Date</span></span>|<span data-ttu-id="08ef9-226">This will be ending date of date range.</span><span class="sxs-lookup"><span data-stu-id="08ef9-226">This will be ending date of date range.</span></span>|

- <span data-ttu-id="08ef9-227">**Extract Date Time Part** : Extracts the date or time from a 'date time value'.</span><span class="sxs-lookup"><span data-stu-id="08ef9-227">**Extract Date Time Part** : Extracts the date or time from a 'date time value'.</span></span>

  |<span data-ttu-id="08ef9-228">Type</span><span class="sxs-lookup"><span data-stu-id="08ef9-228">Type</span></span>|<span data-ttu-id="08ef9-229">Description</span><span class="sxs-lookup"><span data-stu-id="08ef9-229">Description</span></span>|
  |--------------------|-----------------------| 
  |<span data-ttu-id="08ef9-230">Output Variable</span><span class="sxs-lookup"><span data-stu-id="08ef9-230">Output Variable</span></span>|<span data-ttu-id="08ef9-231">Specifies the name of variable in which value of date or time will be stored.</span><span class="sxs-lookup"><span data-stu-id="08ef9-231">Specifies the name of variable in which value of date or time will be stored.</span></span>|
  |<span data-ttu-id="08ef9-232">Date Time</span><span class="sxs-lookup"><span data-stu-id="08ef9-232">Date Time</span></span>|<span data-ttu-id="08ef9-233">This will be the date time value from which extraction will be done.</span><span class="sxs-lookup"><span data-stu-id="08ef9-233">This will be the date time value from which extraction will be done.</span></span>|
  |<span data-ttu-id="08ef9-234">Part</span><span class="sxs-lookup"><span data-stu-id="08ef9-234">Part</span></span>|<span data-ttu-id="08ef9-235">Part that will be extracted, it can be either date or time.</span><span class="sxs-lookup"><span data-stu-id="08ef9-235">Part that will be extracted, it can be either date or time.</span></span>|

- <span data-ttu-id="08ef9-236">**Date to Date Time** : Converts a ‘Date’ value to ‘Date Time’</span><span class="sxs-lookup"><span data-stu-id="08ef9-236">**Date to Date Time** : Converts a ‘Date’ value to ‘Date Time’</span></span>

  |<span data-ttu-id="08ef9-237">Type</span><span class="sxs-lookup"><span data-stu-id="08ef9-237">Type</span></span>|<span data-ttu-id="08ef9-238">Description</span><span class="sxs-lookup"><span data-stu-id="08ef9-238">Description</span></span>|
  |--------------------|-----------------------|
  |<span data-ttu-id="08ef9-239">Output Variable</span><span class="sxs-lookup"><span data-stu-id="08ef9-239">Output Variable</span></span>|<span data-ttu-id="08ef9-240">Specifies the name of variable in which value of ‘date time’ will be stored.</span><span class="sxs-lookup"><span data-stu-id="08ef9-240">Specifies the name of variable in which value of ‘date time’ will be stored.</span></span>|
  |<span data-ttu-id="08ef9-241">Date</span><span class="sxs-lookup"><span data-stu-id="08ef9-241">Date</span></span>|<span data-ttu-id="08ef9-242">This will be the date value which will be part of 'date time'.</span><span class="sxs-lookup"><span data-stu-id="08ef9-242">This will be the date value which will be part of 'date time'.</span></span>|
  |<span data-ttu-id="08ef9-243">Time</span><span class="sxs-lookup"><span data-stu-id="08ef9-243">Time</span></span>|<span data-ttu-id="08ef9-244">This will be the time value which will be part of ‘date time’.</span><span class="sxs-lookup"><span data-stu-id="08ef9-244">This will be the time value which will be part of ‘date time’.</span></span>|

#### <a name="condition"></a><span data-ttu-id="08ef9-245">Condition</span><span class="sxs-lookup"><span data-stu-id="08ef9-245">Condition</span></span>

- <span data-ttu-id="08ef9-246">**If Statement** : Activities within the "If" statement will be executed when the defined conditions are evaluated to be true.</span><span class="sxs-lookup"><span data-stu-id="08ef9-246">**If Statement** : Activities within the "If" statement will be executed when the defined conditions are evaluated to be true.</span></span> <span data-ttu-id="08ef9-247">If the conditions are evaluated to false, activities in the “Else” branch will be executed.</span><span class="sxs-lookup"><span data-stu-id="08ef9-247">If the conditions are evaluated to false, activities in the “Else” branch will be executed.</span></span> <span data-ttu-id="08ef9-248">Conditions can be specified in “Else” branch.</span><span class="sxs-lookup"><span data-stu-id="08ef9-248">Conditions can be specified in “Else” branch.</span></span> <span data-ttu-id="08ef9-249">There can be more than one else branch for an “If Statement”.</span><span class="sxs-lookup"><span data-stu-id="08ef9-249">There can be more than one else branch for an “If Statement”.</span></span>

### <a name="loops"></a><span data-ttu-id="08ef9-250">Loops</span><span class="sxs-lookup"><span data-stu-id="08ef9-250">Loops</span></span>

- <span data-ttu-id="08ef9-251">**Loop n Times** : Executes activities in the loop block for n number of times.</span><span class="sxs-lookup"><span data-stu-id="08ef9-251">**Loop n Times** : Executes activities in the loop block for n number of times.</span></span> <span data-ttu-id="08ef9-252">"N" can be a constant value, or it can be a variable.</span><span class="sxs-lookup"><span data-stu-id="08ef9-252">"N" can be a constant value, or it can be a variable.</span></span>

- <span data-ttu-id="08ef9-253">**Loop with Condition** : Executes activities in the loop block until condition is evaluated to be false.</span><span class="sxs-lookup"><span data-stu-id="08ef9-253">**Loop with Condition** : Executes activities in the loop block until condition is evaluated to be false.</span></span>

- <span data-ttu-id="08ef9-254">**Loop through Records** : Loop through all records and execute activities in the Loop block.</span><span class="sxs-lookup"><span data-stu-id="08ef9-254">**Loop through Records** : Loop through all records and execute activities in the Loop block.</span></span>

  |<span data-ttu-id="08ef9-255">Type</span><span class="sxs-lookup"><span data-stu-id="08ef9-255">Type</span></span>|<span data-ttu-id="08ef9-256">Description</span><span class="sxs-lookup"><span data-stu-id="08ef9-256">Description</span></span>|
  |--------------------|-----------------------|
  |<span data-ttu-id="08ef9-257">Table Name</span><span class="sxs-lookup"><span data-stu-id="08ef9-257">Table Name</span></span>|<span data-ttu-id="08ef9-258">Name of table whose records need to be iterated.</span><span class="sxs-lookup"><span data-stu-id="08ef9-258">Name of table whose records need to be iterated.</span></span>| 
  |<span data-ttu-id="08ef9-259">Sorting</span><span class="sxs-lookup"><span data-stu-id="08ef9-259">Sorting</span></span>|<span data-ttu-id="08ef9-260">Sorting order of the records.</span><span class="sxs-lookup"><span data-stu-id="08ef9-260">Sorting order of the records.</span></span>|
  |<span data-ttu-id="08ef9-261">Order</span><span class="sxs-lookup"><span data-stu-id="08ef9-261">Order</span></span>|<span data-ttu-id="08ef9-262">Ascending or Descending.</span><span class="sxs-lookup"><span data-stu-id="08ef9-262">Ascending or Descending.</span></span>|
  |<span data-ttu-id="08ef9-263">Distinct</span><span class="sxs-lookup"><span data-stu-id="08ef9-263">Distinct</span></span>|<span data-ttu-id="08ef9-264">To skip duplicate records.</span><span class="sxs-lookup"><span data-stu-id="08ef9-264">To skip duplicate records.</span></span>|
  |<span data-ttu-id="08ef9-265">Table Filters</span><span class="sxs-lookup"><span data-stu-id="08ef9-265">Table Filters</span></span>|<span data-ttu-id="08ef9-266">Filters to be applied on the table records.</span><span class="sxs-lookup"><span data-stu-id="08ef9-266">Filters to be applied on the table records.</span></span>| 
  |<span data-ttu-id="08ef9-267">Record Value</span><span class="sxs-lookup"><span data-stu-id="08ef9-267">Record Value</span></span>|<span data-ttu-id="08ef9-268">Variable that holds the current record of the table.</span><span class="sxs-lookup"><span data-stu-id="08ef9-268">Variable that holds the current record of the table.</span></span>|
  |<span data-ttu-id="08ef9-269">Index Variable</span><span class="sxs-lookup"><span data-stu-id="08ef9-269">Index Variable</span></span>|<span data-ttu-id="08ef9-270">Loop index starts from 1.</span><span class="sxs-lookup"><span data-stu-id="08ef9-270">Loop index starts from 1.</span></span>|
  |<span data-ttu-id="08ef9-271">Count Variable</span><span class="sxs-lookup"><span data-stu-id="08ef9-271">Count Variable</span></span>|<span data-ttu-id="08ef9-272">Count of records after applying filters.</span><span class="sxs-lookup"><span data-stu-id="08ef9-272">Count of records after applying filters.</span></span>| 
  |<span data-ttu-id="08ef9-273">Set Variables</span><span class="sxs-lookup"><span data-stu-id="08ef9-273">Set Variables</span></span>|<span data-ttu-id="08ef9-274">To assign field values to a variable.</span><span class="sxs-lookup"><span data-stu-id="08ef9-274">To assign field values to a variable.</span></span>|


- <span data-ttu-id="08ef9-275">**Exit Loop** : Breaks loop and executes activates after the loop block.</span><span class="sxs-lookup"><span data-stu-id="08ef9-275">**Exit Loop** : Breaks loop and executes activates after the loop block.</span></span>

- <span data-ttu-id="08ef9-276">**Skip Next Activities** : Skips next activities in the loop block and continues execution of the next iteration.</span><span class="sxs-lookup"><span data-stu-id="08ef9-276">**Skip Next Activities** : Skips next activities in the loop block and continues execution of the next iteration.</span></span>

### <a name="misc"></a><span data-ttu-id="08ef9-277">Misc.</span><span class="sxs-lookup"><span data-stu-id="08ef9-277">Misc.</span></span>

- <span data-ttu-id="08ef9-278">**Set Variable** : To assign Variable value.</span><span class="sxs-lookup"><span data-stu-id="08ef9-278">**Set Variable** : To assign Variable value.</span></span>

  |<span data-ttu-id="08ef9-279">Type</span><span class="sxs-lookup"><span data-stu-id="08ef9-279">Type</span></span>|<span data-ttu-id="08ef9-280">Description</span><span class="sxs-lookup"><span data-stu-id="08ef9-280">Description</span></span>|
  |--------------------|-----------------------|
  |<span data-ttu-id="08ef9-281">Output Variable</span><span class="sxs-lookup"><span data-stu-id="08ef9-281">Output Variable</span></span>|<span data-ttu-id="08ef9-282">The variable which will be assigned with value.</span><span class="sxs-lookup"><span data-stu-id="08ef9-282">The variable which will be assigned with value.</span></span>
  |<span data-ttu-id="08ef9-283">Value</span><span class="sxs-lookup"><span data-stu-id="08ef9-283">Value</span></span>|<span data-ttu-id="08ef9-284">The value of variable, this can be constant or lookup.</span><span class="sxs-lookup"><span data-stu-id="08ef9-284">The value of variable, this can be constant or lookup.</span></span>

- <span data-ttu-id="08ef9-285">**Alert Message** : Message dialogue will be displayed while execution rule.</span><span class="sxs-lookup"><span data-stu-id="08ef9-285">**Alert Message** : Message dialog will be displayed while execution rule.</span></span> <span data-ttu-id="08ef9-286">This is helpful to debug, and this can also be used for throwing errors.</span><span class="sxs-lookup"><span data-stu-id="08ef9-286">This is helpful to debug, and this can also be used for throwing errors.</span></span>

  |<span data-ttu-id="08ef9-287">Type</span><span class="sxs-lookup"><span data-stu-id="08ef9-287">Type</span></span>|<span data-ttu-id="08ef9-288">Description</span><span class="sxs-lookup"><span data-stu-id="08ef9-288">Description</span></span>|
  |--------------------|-----------------------|
  |<span data-ttu-id="08ef9-289">Message</span><span class="sxs-lookup"><span data-stu-id="08ef9-289">Message</span></span>|<span data-ttu-id="08ef9-290">Message that is to be displayed.</span><span class="sxs-lookup"><span data-stu-id="08ef9-290">Message that is to be displayed.</span></span>
  |<span data-ttu-id="08ef9-291">Throw Error</span><span class="sxs-lookup"><span data-stu-id="08ef9-291">Throw Error</span></span>|<span data-ttu-id="08ef9-292">Check this flag to throw error message.</span><span class="sxs-lookup"><span data-stu-id="08ef9-292">Check this flag to throw error message.</span></span>