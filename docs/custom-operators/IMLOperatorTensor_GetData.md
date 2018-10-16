---
author: eliotcowley
title: IMLOperatorTensor.GetData method
description: Returns a pointer to byte-addressable memory for the tensor.
ms.author: elcowle
ms.date: 10/02/2018
ms.topic: article
ms.prod: windows
ms.technology: uwp
keywords: windows 10, windows machine learning, WinML, custom operators, GetData
ms.localizationpriority: medium
---

# IMLOperatorTensor.GetData method

Returns a pointer to byte-addressable memory for the tensor. This may be used when [IMLOperatorTensor::IsDataInterface](IMLOperatorTensor_IsDataInterface.md) returns false, because the kernel was registered using [MLOperatorExecutionType::Cpu](MLOperatorExecutionType.md). The data size is derived from the tensor's shape. It is fully packed in memory.

```cpp
void* GetData()
```

[!INCLUDE [help](../includes/get-help.md)]