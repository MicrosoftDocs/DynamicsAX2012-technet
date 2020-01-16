---
title: DateTimeOffsetDataHelper.GetDbNullableTimeInSeconds Method  (Microsoft.Dynamics.Commerce.Runtime.Helpers)
TOCTitle: GetDbNullableTimeInSeconds Method
ms:assetid: M:Microsoft.Dynamics.Commerce.Runtime.Helpers.DateTimeOffsetDataHelper.GetDbNullableTimeInSeconds(System.Nullable{System.DateTimeOffset})
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.helpers.datetimeoffsetdatahelper.getdbnullabletimeinseconds(v=AX.60)
ms:contentKeyID: 65316502
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.Helpers.DateTimeOffsetDataHelper.GetDbNullableTimeInSeconds
dev_langs:
- CSharp
- C++
- VB
---

# GetDbNullableTimeInSeconds Method

Gets DB nullable time in seconds.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.Helpers](microsoft-dynamics-commerce-runtime-helpers-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Data (in Microsoft.Dynamics.Commerce.Runtime.Data.dll)

## Syntax

``` vb
'Declaration
Public Shared Function GetDbNullableTimeInSeconds ( _
    dateTime As Nullable(Of DateTimeOffset) _
) As Object
'Usage
Dim dateTime As Nullable(Of DateTimeOffset)
Dim returnValue As Object

returnValue = DateTimeOffsetDataHelper.GetDbNullableTimeInSeconds(dateTime)
```

``` csharp
public static Object GetDbNullableTimeInSeconds(
    Nullable<DateTimeOffset> dateTime
)
```

``` c++
public:
static Object^ GetDbNullableTimeInSeconds(
    Nullable<DateTimeOffset> dateTime
)
```

#### Parameters

  - dateTime  
    Type: [System.Nullable](https://technet.microsoft.com/library/b3h38hb0\(v=ax.60\))\<[DateTimeOffset](https://technet.microsoft.com/library/bb341783\(v=ax.60\))\>  

#### Return Value

Type: [System.Object](https://technet.microsoft.com/library/e5kfa45b\(v=ax.60\))  
The time in seconds or DBNULL.value when DateTime parameter is null.  

## See Also

#### Reference

[DateTimeOffsetDataHelper Class](datetimeoffsetdatahelper-class-microsoft-dynamics-commerce-runtime-helpers.md)

[Microsoft.Dynamics.Commerce.Runtime.Helpers Namespace](microsoft-dynamics-commerce-runtime-helpers-namespace.md)

