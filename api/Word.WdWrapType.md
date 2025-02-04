---
title: WdWrapType enumeration (Word)
ms.prod: word
api_name:
- Word.WdWrapType
ms.assetid: b572e6e5-707e-be2f-afd5-158369ed6e8e
ms.date: 06/08/2017
ms.localizationpriority: medium
---


# WdWrapType enumeration (Word)

Specifies how to wrap text around a shape.



|Name|Value|Description|
|:-----|:-----|:-----|
| **wdWrapInline**|7|Places shapes in line with text.|
| **wdWrapNone**|3|Places shape in front of text. See also  **wdWrapFront**.|
| **wdWrapSquare**|0|Wraps text around the shape. Line continuation is on the opposite side of the shape.|
| **wdWrapThrough**|2|Wraps text around the shape.|
| **wdWrapTight**|1|Wraps text close to the shape.|
| **wdWrapTopBottom**|4|Places text above and below the shape.|
| **wdWrapBehind**|5|Places shape behind text.|
| **wdWrapFront**|3|Places shape in front of text. See also **wdWrapNone**.|

## Remarks

Used with the **Type** property of the **WrapFormat** object. You can view what each wrap type looks like on the **Text Wrapping** tab of the **Advanced Layout** dialog box.


> [!NOTE] 
>  **wdWrapSquare**, **wdWrapTight**, and **wdWrapThrough** all function in essentially the same way. \
>  **wdWrapFront** and **wdWrapNone** have the same effect and have the value 3. The value 6 has the same effect as 3. 

[!include[Support and feedback](~/includes/feedback-boilerplate.md)]
