---
title: "Table.Combine | Microsoft Docs"
ms.date: 4/16/2018
ms.prod: power-query
ms.reviewer: owend
ms.topic: reference
author: minewiskan
ms.author: owend
manager: kfile
---
# Table.Combine

  
## About  
Returns a table that is the result of merging a list of tables. The tables must all have the same row type structure.  
  
```  
Table.Combine(tables as list) as table  
```  
  
## Arguments  
  
|Argument|Description|  
|------------|---------------|  
|tables|The List of tables to combine.|  
  
## Example  
  
```  
Table.Combine({  
  
    Table.FromRecords({  
  
        [CustomerID = 1, Name = "Bob", Phone = "123-4567"],  
  
        [CustomerID = 2, Name = "Jim", Phone = "987-6543"] }),  
  
    Table.FromRecords({  
  
        [CustomerID = 3, Name = "Paul", Phone = "543-7890"]})  
  
    })  
```  
  
|CustomerID|Name|Phone|  
|--------------|--------|---------|  
|1|Bob|123-4567|  
|2|Jim|987-6543|  
|3|Paul|543-7890|  
  