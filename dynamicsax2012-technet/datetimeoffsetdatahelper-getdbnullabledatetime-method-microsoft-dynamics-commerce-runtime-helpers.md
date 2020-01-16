---
title: DateTimeOffsetDataHelper.GetDbNullableDateTime Method  (Microsoft.Dynamics.Commerce.Runtime.Helpers)
TOCTitle: GetDbNullableDateTime Method
ms:assetid: M:Microsoft.Dynamics.Commerce.Runtime.Helpers.DateTimeOffsetDataHelper.GetDbNullableDateTime(System.Nullable{System.DateTimeOffset})
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.helpers.datetimeoffsetdatahelper.getdbnullabledatetime(v=AX.60)
ms:contentKeyID: 65315745
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.Helpers.DateTimeOffsetDataHelper.GetDbNullableDateTime
dev_langs:
- CSharp
- C++
- VB
---

# GetDbNullableDateTime Method

Gets DB nullable date/time.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.Helpers](microsoft-dynamics-commerce-runtime-helpers-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Data (in Microsoft.Dynamics.Commerce.Runtime.Data.dll)

## Syntax

``` vb
'Declaration
Public Shared Function GetDbNullableDateTime ( _
    dateTime As Nullable(Of DateTimeOffset) _
) As Object
'Usage
Dim dateTime As Nullable(Of DateTimeOffset)
Dim returnValue As Object

returnValue = DateTimeOffsetDataHelper.GetDbNullableDateTime(dateTime)
```

``` csharp
public static Object GetDbNullableDateTime(
    Nullable<DateTimeOffset> dateTime
)
```

``` c++
public:
static Object^ GetDbNullableDateTime(
    Nullable<DateTimeOffset> dateTime
)
```

#### Parameters

  - dateTime  
    Type: [System.Nullable](https://technet.microsoft.com/library/b3h38hb0\(v=ax.60\))\<[DateTimeOffset](https://technet.microsoft.com/library/bb341783\(v=ax.60\))\>  

#### Return Value

Type: [System.Object](https://technet.microsoft.com/library/e5kfa45b\(v=ax.60\))  
The date/time or DBNULL.value when the provided parameter is null.  

## See Also

#### Reference

[DateTimeOffsetDataHelper Class](datetimeoffsetdatahelper-class-microsoft-dynamics-commerce-runtime-helpers.md)

[Microsoft.Dynamics.Commerce.Runtime.Helpers Namespace](microsoft-dynamics-commerce-runtime-helpers-namespace.md)

