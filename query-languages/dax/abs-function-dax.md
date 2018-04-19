---
title: "ABS Function (DAX) | Microsoft Docs"
ms.prod: dax
ms.date: 4/13/2018
ms.reviewer: owend
ms.topic: reference
author: minewiskan
ms.author: owend
manager: kfile
---
# ABS Function (DAX)
Returns the absolute value of a number.  
  
## Syntax  
  
```  
ABS(<number>)  
```  
  
#### Parameters  
  
|Term|Definition|  
|--------|--------------|  
|**number**|The number for which you want the absolute value.|  
  
## Return Value  
A decimal number.  
  
## Remarks  
The absolute value of a number is a decimal number, whole or decimal, without its sign. You can use the ABS function to ensure that only non-negative numbers are returned from expressions when nested in functions that require a positive number.  
  
## Example  
The following example returns the absolute value of the difference between the list price and the dealer price, which you might use in a new calculated column, **DealerMarkup**.  
  
```  
=ABS([DealerPrice]-[ListPrice])  
```  
  
## See Also  
[Math and Trig Functions &#40;DAX&#41;](math-and-trig-functions-dax.md)  
[SIGN Function &#40;DAX&#41;](sign-function-dax.md)  
  