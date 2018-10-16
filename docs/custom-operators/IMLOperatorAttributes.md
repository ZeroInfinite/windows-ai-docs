---
author: eliotcowley
title: IMLOperatorAttributes interface
description: Represents the values of an operator's attributes, as determined by a model using the operator.
ms.author: elcowle
ms.date: 10/02/2018
ms.topic: article
ms.prod: windows
ms.technology: uwp
keywords: windows 10, windows machine learning, WinML, custom operators, IMLOperatorAttributes
ms.localizationpriority: medium
---

# IMLOperatorAttributes interface

Represents the values of an operator's attributes, as determined by a model using the operator. This interface is called by implementations of custom operator kernels, and by implementations of shape and type inferrers.

## Methods

| Name | Description |
|------|-------------|
| [GetAttribute](IMLOperatorAttributes_GetAttribute.md) | Gets the value of an attribute element which is of a numeric type. |
| [GetAttributeElementCount](IMLOperatorAttributes_GetAttributeElementCount.md) | Gets the count of elements in an attribute. |
| [GetStringAttributeElement](IMLOperatorAttributes_GetStringAttributeElement.md) | Gets the value of an attribute element which is of a string type. |
| [GetStringAttributeElementLength](IMLOperatorAttributes_GetStringAttributeElementLength.md) | Gets the length of an attribute element which is of a string type. |

[!INCLUDE [help](../includes/get-help.md)]