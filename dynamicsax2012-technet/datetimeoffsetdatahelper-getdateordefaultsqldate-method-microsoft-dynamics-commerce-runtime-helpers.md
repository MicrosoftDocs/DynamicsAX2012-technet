---
title: DateTimeOffsetDataHelper.GetDateOrDefaultSqlDate Method  (Microsoft.Dynamics.Commerce.Runtime.Helpers)
TOCTitle: GetDateOrDefaultSqlDate Method
ms:assetid: M:Microsoft.Dynamics.Commerce.Runtime.Helpers.DateTimeOffsetDataHelper.GetDateOrDefaultSqlDate(System.Nullable{System.DateTimeOffset})
ms:mtpsurl: https://technet.microsoft.com/en-us/library/microsoft.dynamics.commerce.runtime.helpers.datetimeoffsetdatahelper.getdateordefaultsqldate(v=AX.60)
ms:contentKeyID: 65323097
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.Helpers.DateTimeOffsetDataHelper.GetDateOrDefaultSqlDate
dev_langs:
- CSharp
- C++
- VB
---

# GetDateOrDefaultSqlDate Method

Get date or SqlDateTime.MinValue.Value as default non-null SQL date.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.Helpers](microsoft-dynamics-commerce-runtime-helpers-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Data (in Microsoft.Dynamics.Commerce.Runtime.Data.dll)

## Syntax

``` vb
'Declaration
Public Shared Function GetDateOrDefaultSqlDate ( _
    dateTimeOffset As Nullable(Of DateTimeOffset) _
) As DateTime
'Usage
Dim dateTimeOffset As Nullable(Of DateTimeOffset)
Dim returnValue As DateTime

returnValue = DateTimeOffsetDataHelper.GetDateOrDefaultSqlDate(dateTimeOffset)
```

``` csharp
public static DateTime GetDateOrDefaultSqlDate(
    Nullable<DateTimeOffset> dateTimeOffset
)
```

``` c++
public:
static DateTime GetDateOrDefaultSqlDate(
    Nullable<DateTimeOffset> dateTimeOffset
)
```

#### Parameters

  - dateTimeOffset  
    Type: [System.Nullable](https://technet.microsoft.com/en-us/library/b3h38hb0\(v=ax.60\))\<[DateTimeOffset](https://technet.microsoft.com/en-us/library/bb341783\(v=ax.60\))\>  

#### Return Value

Type: [System.DateTime](https://technet.microsoft.com/en-us/library/03ybds8y\(v=ax.60\))  
The date/time value.  

## See Also

#### Reference

[DateTimeOffsetDataHelper Class](datetimeoffsetdatahelper-class-microsoft-dynamics-commerce-runtime-helpers.md)

[Microsoft.Dynamics.Commerce.Runtime.Helpers Namespace](microsoft-dynamics-commerce-runtime-helpers-namespace.md)

