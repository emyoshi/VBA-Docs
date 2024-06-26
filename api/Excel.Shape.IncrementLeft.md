---
title: Shape.IncrementLeft method (Excel)
keywords: vbaxl10.chm636078
f1_keywords:
- vbaxl10.chm636078
api_name:
- Excel.Shape.IncrementLeft
ms.assetid: 2e9081f0-c11a-7c42-486e-53cb32d6d99c
ms.date: 05/14/2019
ms.localizationpriority: medium
---


# Shape.IncrementLeft method (Excel)

Moves the specified shape horizontally by the specified number of [points](../language/glossary/vbe-glossary.md#point).


## Syntax

_expression_.**IncrementLeft** (_Increment_)

_expression_ A variable that represents a **[Shape](Excel.Shape.md)** object.


## Parameters

|Name|Required/Optional|Data type|Description|
|:-----|:-----|:-----|:-----|
| _Increment_|Required| **Single**|Specifies how far the shape is to be moved horizontally, in points. A positive value moves the shape to the right; a negative value moves it to the left.|

## Example

This example duplicates shape one on _myDocument_, sets the fill for the duplicate, moves it 70 points to the right and 50 points up, and rotates it 30 degrees clockwise.

```vb
Set myDocument = Worksheets(1) 
With myDocument.Shapes(1).Duplicate 
 .Fill.PresetTextured msoTextureGranite 
 .IncrementLeft 70 
 .IncrementTop -50 
 .IncrementRotation 30 
End With
```




[!include[Support and feedback](~/includes/feedback-boilerplate.md)]
