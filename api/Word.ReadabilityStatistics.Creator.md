---
title: ReadabilityStatistics.Creator property (Word)
keywords: vbawd10.chm162399209
f1_keywords:
- vbawd10.chm162399209
ms.prod: word
api_name:
- Word.ReadabilityStatistics.Creator
ms.assetid: 13d16225-ec95-64bf-13e5-8205eb923ece
ms.date: 06/08/2017
ms.localizationpriority: medium
---


# ReadabilityStatistics.Creator property (Word)

Returns a 32-bit integer that indicates the application in which the specified object was created. Read-only  **Long**.


## Syntax

_expression_.**Creator**

_expression_ Required. A variable that represents a '[ReadabilityStatistics](Word.readabilitystatistics.md)' collection.


## Remarks

If the object was created in Microsoft Word, the **Creator** property returns the hexadecimal number 4D535744, which represents the string "MSWD." This property was primarily designed to be used on the Macintosh, where each application has a four-character creator code. For example, Microsoft Word has the creator code MSWD. For additional information about this property, consult the language reference Help included with Microsoft Office Macintosh Edition.


## See also


[ReadabilityStatistics Collection Object](Word.readabilitystatistics.md)

[!include[Support and feedback](~/includes/feedback-boilerplate.md)]