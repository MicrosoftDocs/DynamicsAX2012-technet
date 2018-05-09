---
title: ValidationPeriod.StartingTimeForDay Method  (Microsoft.Dynamics.Commerce.Runtime.DataModel)
TOCTitle: StartingTimeForDay Method
ms:assetid: M:Microsoft.Dynamics.Commerce.Runtime.DataModel.ValidationPeriod.StartingTimeForDay(System.DayOfWeek)
ms:mtpsurl: https://technet.microsoft.com/en-us/library/microsoft.dynamics.commerce.runtime.datamodel.validationperiod.startingtimeforday(v=AX.60)
ms:contentKeyID: 49849816
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataModel.ValidationPeriod.StartingTimeForDay
dev_langs:
- CSharp
- C++
- VB
---

# StartingTimeForDay Method

Gets the starting time for the given day.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataModel](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Entities (in Microsoft.Dynamics.Commerce.Runtime.Entities.dll)

## Syntax

``` vb
'Declaration
Public Function StartingTimeForDay ( _
    day As DayOfWeek _
) As Integer
'Usage
Dim instance As ValidationPeriod
Dim day As DayOfWeek
Dim returnValue As Integer

returnValue = instance.StartingTimeForDay(day)
```

``` csharp
public int StartingTimeForDay(
    DayOfWeek day
)
```

``` c++
public:
int StartingTimeForDay(
    DayOfWeek day
)
```

#### Parameters

  - day  
    Type: [System.DayOfWeek](https://technet.microsoft.com/en-us/library/zh6aacza\(v=ax.60\))  

#### Return Value

Type: [System.Int32](https://technet.microsoft.com/en-us/library/td2s409d\(v=ax.60\))  
Starting time for the given day.  

## See Also

#### Reference

[ValidationPeriod Class](validationperiod-class-microsoft-dynamics-commerce-runtime-datamodel.md)

[Microsoft.Dynamics.Commerce.Runtime.DataModel Namespace](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)

