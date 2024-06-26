---
title: Characters.Creator property (Excel)
keywords: vbaxl10.chm251074
f1_keywords:
- vbaxl10.chm251074
api_name:
- Excel.Characters.Creator
ms.assetid: 99eb693a-3b61-5cb2-2f61-e0ead578aa57
ms.date: 04/16/2019
ms.localizationpriority: medium
---


# Characters.Creator property (Excel)

Returns a 32-bit integer that indicates the application in which this object was created. Read-only **Long**.


## Syntax

_expression_.**Creator**

_expression_ A variable that represents a **[Characters](Excel.Characters.md)** object.


## Remarks

If the object was created in Microsoft Excel, this property returns the string XCEL, which is equivalent to the hexadecimal number 5843454C. The **Creator** property is designed to be used in Microsoft Excel for the Macintosh, where each application has a four-character creator code. For example, Microsoft Excel has the creator code XCEL.




[!include[Support and feedback](~/includes/feedback-boilerplate.md)]