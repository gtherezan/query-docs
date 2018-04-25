---
title: "ASINH Function (DAX) | Microsoft Docs"
ms.prod: dax
ms.date: 4/13/2018
ms.reviewer: owend
ms.topic: reference
author: minewiskan
ms.author: owend
manager: kfile
---
# ASINH Function (DAX)
Returns the inverse hyperbolic sine of a number. The inverse hyperbolic sine is the value whose hyperbolic sine is *number*, so ASINH(SINH(number)) equals *number*.  
  
## Syntax  
  
```  
ASINH(number)  
```  
  
#### Parameters  
  
|Term|Definition|  
|--------|--------------|  
|number|Any real number.|  
  
## Return Value  
Returns the inverse hyperbolic sine of a number.  
  
## Example  
  
|Formula|Description|Result|  
|-----------|---------------|----------|  
|=ASINH(-2.5)|Inverse hyperbolic sine of -2.5|-1.647231146|  
|=ASINH(10)|Inverse hyperbolic sine of 10|2.99822295|  
  