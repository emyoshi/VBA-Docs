---
title: ModelConnection.Application property (Excel)
keywords: vbaxl10.chm921073
f1_keywords:
- vbaxl10.chm921073
ms.assetid: 6d0ff59e-4d5d-c06c-4af8-33a69739f9e1
ms.date: 05/01/2019
ms.localizationpriority: medium
---


# ModelConnection.Application property (Excel)

Returns an **[Application](Excel.Application(object).md)** object that represents the Microsoft Excel application. Read-only.


## Syntax

_expression_.**Application**

_expression_ A variable that represents a **[ModelConnection](Excel.modelconnection.md)** object.


## Property value

**APPLICATION**


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