---
title: Range.AllocateChanges method (Excel)
keywords: vbaxl10.chm144253
f1_keywords:
- vbaxl10.chm144253
api_name:
- Excel.Range.AllocateChanges
ms.assetid: c751c5fb-ce22-64d1-669c-fdb064cf0408
ms.date: 05/10/2019
ms.localizationpriority: medium
---


# Range.AllocateChanges method (Excel)

Performs a writeback operation for all edited cells in a range based on an OLAP data source.


## Syntax

_expression_.**AllocateChanges**

_expression_ A variable that represents a **[Range](Excel.Range(object).md)** object.


## Remarks

The **AllocateChanges** method executes an **UPDATE CUBE** statement for all changes made in the range since the last apply changes operation was committed. This method generates a run-time error if it is executed on a range based on a non-OLAP data source.




[!include[Support and feedback](~/includes/feedback-boilerplate.md)]