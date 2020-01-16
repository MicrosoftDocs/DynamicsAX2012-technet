---
title: ValidationPeriod.EndingTimeForDay Method  (Microsoft.Dynamics.Commerce.Runtime.DataModel)
TOCTitle: EndingTimeForDay Method
ms:assetid: M:Microsoft.Dynamics.Commerce.Runtime.DataModel.ValidationPeriod.EndingTimeForDay(System.DayOfWeek)
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.datamodel.validationperiod.endingtimeforday(v=AX.60)
ms:contentKeyID: 49840384
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataModel.ValidationPeriod.EndingTimeForDay
dev_langs:
- CSharp
- C++
- VB
---

# EndingTimeForDay Method

Gets the ending time for the given day.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataModel](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Entities (in Microsoft.Dynamics.Commerce.Runtime.Entities.dll)

## Syntax

``` vb
'Declaration
Public Function EndingTimeForDay ( _
    day As DayOfWeek _
) As Integer
'Usage
Dim instance As ValidationPeriod
Dim day As DayOfWeek
Dim returnValue As Integer

returnValue = instance.EndingTimeForDay(day)
```

``` csharp
public int EndingTimeForDay(
    DayOfWeek day
)
```

``` c++
public:
int EndingTimeForDay(
    DayOfWeek day
)
```

#### Parameters

  - day  
    Type: [System.DayOfWeek](https://technet.microsoft.com/library/zh6aacza\(v=ax.60\))  

#### Return Value

Type: [System.Int32](https://technet.microsoft.com/library/td2s409d\(v=ax.60\))  
Ending time for the given day.  

## See Also

#### Reference

[ValidationPeriod Class](validationperiod-class-microsoft-dynamics-commerce-runtime-datamodel.md)

[Microsoft.Dynamics.Commerce.Runtime.DataModel Namespace](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)

