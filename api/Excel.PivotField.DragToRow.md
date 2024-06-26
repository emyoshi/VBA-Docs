---
title: PivotField.DragToRow property (Excel)
keywords: vbaxl10.chm240105
f1_keywords:
- vbaxl10.chm240105
api_name:
- Excel.PivotField.DragToRow
ms.assetid: f10da457-1190-6b9f-ecc1-b9916c7fb4c4
ms.date: 05/04/2019
ms.localizationpriority: medium
---


# PivotField.DragToRow property (Excel)

**True** if the field can be dragged to the row position. The default value is **True**. Read/write **Boolean**.


## Syntax

_expression_.**DragToRow**

_expression_ A variable that represents a **[PivotField](Excel.PivotField.md)** object.


## Remarks

For OLAP data sources, the value is **False** for measure fields.


## Example

This example prevents the Year field in the first PivotTable report on worksheet one from being dragged to the row position.

```vb
Worksheets(1).PivotTables("Pivot1") _ 
 .PivotFields("Year").DragToRow = False
```



[!include[Support and feedback](~/includes/feedback-boilerplate.md)]