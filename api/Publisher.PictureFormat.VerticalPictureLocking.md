---
title: PictureFormat.VerticalPictureLocking property (Publisher)
keywords: vbapb10.chm3604745
f1_keywords:
- vbapb10.chm3604745
ms.prod: publisher
api_name:
- Publisher.PictureFormat.VerticalPictureLocking
ms.assetid: 0575d733-b515-2256-7136-6ec07532ab67
ms.date: 06/13/2019
ms.localizationpriority: medium
---


# PictureFormat.VerticalPictureLocking property (Publisher)

Returns or sets a **[PbVerticalPictureLocking](publisher.pbverticalpicturelocking.md)** constant indicating where newly inserted pictures appear in relation to the specified frame. Read/write.


## Syntax

_expression_.**VerticalPictureLocking**

_expression_ A variable that represents a **[PictureFormat](Publisher.PictureFormat.md)** object.


## Return value

PbVerticalPictureLocking


## Remarks

The **Vertical PictureLocking** property value can be one of the **PbVerticalPictureLocking** constants declared in the Microsoft Publisher type library.

## Example

The following example locks the specified picture to the upper-left corner of the picture frame. Shape one on page one of the active publication must be a picture frame for this example to work.

```vb
With ActiveDocument.Pages(1).Shapes(1).PictureFormat 
 .HorizontalPictureLocking = pbHorizontalLockingLeft 
 .VerticalPictureLocking = pbVerticalLockingTop 
End With
```

[!include[Support and feedback](~/includes/feedback-boilerplate.md)]