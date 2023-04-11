---
title: DateTimeOffsetExtensions.ConvertDateTimeToDateTimeOffset Method  (Microsoft.Dynamics.Commerce.Runtime)
TOCTitle: ConvertDateTimeToDateTimeOffset Method
ms:assetid: M:Microsoft.Dynamics.Commerce.Runtime.DateTimeOffsetExtensions.ConvertDateTimeToDateTimeOffset(System.DateTime,System.TimeSpan,System.Boolean)
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.datetimeoffsetextensions.convertdatetimetodatetimeoffset(v=AX.60)
ms:contentKeyID: 65322213
author: tonyafehr
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DateTimeOffsetExtensions.ConvertDateTimeToDateTimeOffset
dev_langs:
- CSharp
- C++
- VB
---

# ConvertDateTimeToDateTimeOffset Method


[!INCLUDE[archive-banner](includes/archive-banner.md)]

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime](microsoft-dynamics-commerce-runtime-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Framework (in Microsoft.Dynamics.Commerce.Runtime.Framework.dll)

## Syntax

``` vb
'Declaration
Public Shared Function ConvertDateTimeToDateTimeOffset ( _
    dateTime As DateTime, _
    timeZoneOffset As TimeSpan, _
    useUtc As Boolean _
) As DateTimeOffset
'Usage
Dim dateTime As DateTime
Dim timeZoneOffset As TimeSpan
Dim useUtc As Boolean
Dim returnValue As DateTimeOffset

returnValue = DateTimeOffsetExtensions.ConvertDateTimeToDateTimeOffset(dateTime, _
    timeZoneOffset, useUtc)
```

``` csharp
public static DateTimeOffset ConvertDateTimeToDateTimeOffset(
    DateTime dateTime,
    TimeSpan timeZoneOffset,
    bool useUtc
)
```

``` c++
public:
static DateTimeOffset ConvertDateTimeToDateTimeOffset(
    DateTime dateTime, 
    TimeSpan timeZoneOffset, 
    bool useUtc
)
```

#### Parameters

  - dateTime  
    Type: [System.DateTime](https://technet.microsoft.com/library/03ybds8y\(v=ax.60\))  

<!-- end list -->

  - timeZoneOffset  
    Type: [System.TimeSpan](https://technet.microsoft.com/library/269ew577\(v=ax.60\))  

<!-- end list -->

  - useUtc  
    Type: [System.Boolean](https://technet.microsoft.com/library/a28wyd50\(v=ax.60\))  

#### Return Value

Type: [System.DateTimeOffset](https://technet.microsoft.com/library/bb341783\(v=ax.60\))  

## See Also

#### Reference

[DateTimeOffsetExtensions Class](datetimeoffsetextensions-class-microsoft-dynamics-commerce-runtime.md)

[Microsoft.Dynamics.Commerce.Runtime Namespace](microsoft-dynamics-commerce-runtime-namespace.md)

