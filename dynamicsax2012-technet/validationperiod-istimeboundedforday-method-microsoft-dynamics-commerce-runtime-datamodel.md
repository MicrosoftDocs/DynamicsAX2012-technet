---
title: ValidationPeriod.IsTimeBoundedForDay Method  (Microsoft.Dynamics.Commerce.Runtime.DataModel)
TOCTitle: IsTimeBoundedForDay Method
ms:assetid: M:Microsoft.Dynamics.Commerce.Runtime.DataModel.ValidationPeriod.IsTimeBoundedForDay(System.DayOfWeek)
ms:mtpsurl: https://technet.microsoft.com/en-us/library/microsoft.dynamics.commerce.runtime.datamodel.validationperiod.istimeboundedforday(v=AX.60)
ms:contentKeyID: 49827243
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataModel.ValidationPeriod.IsTimeBoundedForDay
dev_langs:
- CSharp
- C++
- VB
---

# IsTimeBoundedForDay Method

Gets whether the given day is valid within or outside its bounds.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataModel](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Entities (in Microsoft.Dynamics.Commerce.Runtime.Entities.dll)

## Syntax

``` vb
'Declaration
Public Function IsTimeBoundedForDay ( _
    day As DayOfWeek _
) As Boolean
'Usage
Dim instance As ValidationPeriod
Dim day As DayOfWeek
Dim returnValue As Boolean

returnValue = instance.IsTimeBoundedForDay(day)
```

``` csharp
public bool IsTimeBoundedForDay(
    DayOfWeek day
)
```

``` c++
public:
bool IsTimeBoundedForDay(
    DayOfWeek day
)
```

#### Parameters

  - day  
    Type: [System.DayOfWeek](https://technet.microsoft.com/en-us/library/zh6aacza\(v=ax.60\))  

#### Return Value

Type: [System.Boolean](https://technet.microsoft.com/en-us/library/a28wyd50\(v=ax.60\))  
True if the day is valid within the bounds that have been specified.  

## See Also

#### Reference

[ValidationPeriod Class](validationperiod-class-microsoft-dynamics-commerce-runtime-datamodel.md)

[Microsoft.Dynamics.Commerce.Runtime.DataModel Namespace](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)

