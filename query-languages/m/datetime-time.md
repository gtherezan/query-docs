---
title: "DateTime.Time | Microsoft Docs"
ms.date: 4/16/2018
ms.prod: power-query
ms.reviewer: owend
ms.topic: reference
author: minewiskan
ms.author: owend
manager: kfile
---
# DateTime.Time

  
## About  
Returns a time part from a DateTime value.  
  
```  
DateTime.Time(dateTime as datetime) as nullable time  
```  
  
## Arguments  
  
|Argument|Description|  
|------------|---------------|  
|dateTime|The **DateTime** to parse.|  
  
## Example  
  
```  
DateTime.Time(#datetime(2010, 5, 4, 6, 5, 4)) equals #time(6, 5, 4)  
```  