---
title: "RANDBETWEEN Function (DAX) | Microsoft Docs"
ms.prod: dax
ms.date: 4/13/2018
ms.reviewer: owend
ms.topic: reference
author: minewiskan
ms.author: owend
manager: kfile
---
# RANDBETWEEN Function (DAX)
Returns a random number in the range between two numbers you specify.  
  
## Syntax  
  
```  
RANDBETWEEN(<bottom>,<top>)  
```  
  
#### Parameters  
  
|Term|Definition|  
|--------|--------------|  
|**Bottom**|The smallest integer the function will return.|  
|**Top**|The largest integer the function will return.|  
  
## Return Value  
A whole number.  
  
## Remarks  
This DAX function is not supported for use in DirectQuery mode. For more information about limitations in DirectQuery models, see  [http://go.microsoft.com/fwlink/?LinkId=219172](http://go.microsoft.com/fwlink/?LinkId=219172).  
  
## Example  
The following formula returns a random number between 1 and 10.  
  
```  
=RANDBETWEEN(1,10)  
```  
  
## See Also  
[Math and Trig Functions &#40;DAX&#41;](math-and-trig-functions-dax.md)  
[Statistical Functions &#40;DAX&#41;](statistical-functions-dax.md)  
  