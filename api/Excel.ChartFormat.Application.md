---
title: ChartFormat.Application property (Excel)
keywords: vbaxl10.chm860073
f1_keywords:
- vbaxl10.chm860073
api_name:
- Excel.ChartFormat.Application
ms.assetid: 72b6e73c-19d8-98c0-bf75-a7b0e95e0996
ms.date: 04/20/2019
ms.localizationpriority: medium
---


# ChartFormat.Application property (Excel)

When used without an object qualifier, this property returns an **[Application](Excel.Application(object).md)** object that represents the Microsoft Excel application. 

When used with an object qualifier, this property returns an **Application** object that represents the creator of the specified object (you can use this property with an OLE Automation object to return the application of that object). Read-only.


## Syntax

_expression_.**Application**

_expression_ A variable that represents a **[ChartFormat](Excel.ChartFormat.md)** object.


## Return value

Application


## Example

This example displays a message about the application that created _myObject_.

```vb
Set myObject = ActiveWorkbook 
If myObject.Application.Value = "Microsoft Excel" Then 
 MsgBox "This is an Excel Application object." 
Else 
 MsgBox "This is not an Excel Application object." 
End If
```




[!include[Support and feedback](~/includes/feedback-boilerplate.md)]