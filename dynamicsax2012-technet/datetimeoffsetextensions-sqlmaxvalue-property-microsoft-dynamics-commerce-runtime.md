---
title: DateTimeOffsetExtensions.SqlMaxValue Property  (Microsoft.Dynamics.Commerce.Runtime)
TOCTitle: SqlMaxValue Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.DateTimeOffsetExtensions.SqlMaxValue
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.datetimeoffsetextensions.sqlmaxvalue(v=AX.60)
ms:contentKeyID: 62211050
author: tonyafehr
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DateTimeOffsetExtensions.SqlMaxValue
dev_langs:
- CSharp
- C++
- VB
---

# SqlMaxValue Property


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Gets the maximum valid date value which can be stored in CRT database for a [DateTimeOffset](https://technet.microsoft.com/library/bb341783\(v=ax.60\)) structure.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime](microsoft-dynamics-commerce-runtime-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Framework (in Microsoft.Dynamics.Commerce.Runtime.Framework.dll)

## Syntax

``` vb
'Declaration
Public Shared ReadOnly Property SqlMaxValue As DateTimeOffset
    Get
'Usage
Dim value As DateTimeOffset

value = DateTimeOffsetExtensions.SqlMaxValue
```

``` csharp
public static DateTimeOffset SqlMaxValue { get; }
```

``` c++
public:
static property DateTimeOffset SqlMaxValue {
    DateTimeOffset get ();
}
```

#### Property Value

Type: [System.DateTimeOffset](https://technet.microsoft.com/library/bb341783\(v=ax.60\))  
Returns [DateTimeOffset](https://technet.microsoft.com/library/bb341783\(v=ax.60\)).  

## See Also

#### Reference

[DateTimeOffsetExtensions Class](datetimeoffsetextensions-class-microsoft-dynamics-commerce-runtime.md)

[Microsoft.Dynamics.Commerce.Runtime Namespace](microsoft-dynamics-commerce-runtime-namespace.md)

