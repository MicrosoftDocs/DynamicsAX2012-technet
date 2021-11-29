---
title: ValidationPeriod.AnyDayHasEndingTime Method  (Microsoft.Dynamics.Commerce.Runtime.DataModel)
TOCTitle: AnyDayHasEndingTime Method
ms:assetid: M:Microsoft.Dynamics.Commerce.Runtime.DataModel.ValidationPeriod.AnyDayHasEndingTime
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.datamodel.validationperiod.anydayhasendingtime(v=AX.60)
ms:contentKeyID: 49828440
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataModel.ValidationPeriod.AnyDayHasEndingTime
dev_langs:
- CSharp
- C++
- VB
---

# AnyDayHasEndingTime Method


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Gets whether any day in this period has an ending time specified.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataModel](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Entities (in Microsoft.Dynamics.Commerce.Runtime.Entities.dll)

## Syntax

``` vb
'Declaration
Public Function AnyDayHasEndingTime As Boolean
'Usage
Dim instance As ValidationPeriod
Dim returnValue As Boolean

returnValue = instance.AnyDayHasEndingTime()
```

``` csharp
public bool AnyDayHasEndingTime()
```

``` c++
public:
bool AnyDayHasEndingTime()
```

#### Return Value

Type: [System.Boolean](https://technet.microsoft.com/library/a28wyd50\(v=ax.60\))  
True if any day in this period has an ending time specified.  

## See Also

#### Reference

[ValidationPeriod Class](validationperiod-class-microsoft-dynamics-commerce-runtime-datamodel.md)

[Microsoft.Dynamics.Commerce.Runtime.DataModel Namespace](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)

