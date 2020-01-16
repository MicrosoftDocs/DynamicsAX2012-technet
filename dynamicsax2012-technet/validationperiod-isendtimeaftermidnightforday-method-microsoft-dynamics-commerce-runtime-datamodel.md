---
title: ValidationPeriod.IsEndTimeAfterMidnightForDay Method  (Microsoft.Dynamics.Commerce.Runtime.DataModel)
TOCTitle: IsEndTimeAfterMidnightForDay Method
ms:assetid: M:Microsoft.Dynamics.Commerce.Runtime.DataModel.ValidationPeriod.IsEndTimeAfterMidnightForDay(System.DayOfWeek)
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.datamodel.validationperiod.isendtimeaftermidnightforday(v=AX.60)
ms:contentKeyID: 49855219
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataModel.ValidationPeriod.IsEndTimeAfterMidnightForDay
dev_langs:
- CSharp
- C++
- VB
---

# IsEndTimeAfterMidnightForDay Method

Gets whether ending time bound wraps to after midnight for the given day.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataModel](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Entities (in Microsoft.Dynamics.Commerce.Runtime.Entities.dll)

## Syntax

``` vb
'Declaration
Public Function IsEndTimeAfterMidnightForDay ( _
    day As DayOfWeek _
) As Boolean
'Usage
Dim instance As ValidationPeriod
Dim day As DayOfWeek
Dim returnValue As Boolean

returnValue = instance.IsEndTimeAfterMidnightForDay(day)
```

``` csharp
public bool IsEndTimeAfterMidnightForDay(
    DayOfWeek day
)
```

``` c++
public:
bool IsEndTimeAfterMidnightForDay(
    DayOfWeek day
)
```

#### Parameters

  - day  
    Type: [System.DayOfWeek](https://technet.microsoft.com/library/zh6aacza\(v=ax.60\))  

#### Return Value

Type: [System.Boolean](https://technet.microsoft.com/library/a28wyd50\(v=ax.60\))  
True if the ending time wraps to after midnight for the given day.  

## See Also

#### Reference

[ValidationPeriod Class](validationperiod-class-microsoft-dynamics-commerce-runtime-datamodel.md)

[Microsoft.Dynamics.Commerce.Runtime.DataModel Namespace](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)

