---
title: DateTimeOffsetExtensions.IsValidSqlDateTime Method (Nullable(DateTime)) (Microsoft.Dynamics.Commerce.Runtime)
TOCTitle: IsValidSqlDateTime Method (Nullable(DateTime))
ms:assetid: M:Microsoft.Dynamics.Commerce.Runtime.DateTimeOffsetExtensions.IsValidSqlDateTime(System.Nullable{System.DateTime})
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.datetimeoffsetextensions.isvalidsqldatetime(v=AX.60)
ms:contentKeyID: 65320127
author: tonyafehr
ms.date: 05/18/2015
mtps_version: v=AX.60
dev_langs:
- vb
- csharp
- c++
---

# IsValidSqlDateTime Method (Nullable(DateTime))


[!INCLUDE[archive-banner](includes/archive-banner.md)]

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime](microsoft-dynamics-commerce-runtime-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Framework (in Microsoft.Dynamics.Commerce.Runtime.Framework.dll)

## Syntax

``` vb
'Declaration
<ExtensionAttribute> _
Public Shared Function IsValidSqlDateTime ( _
    dateTime As Nullable(Of DateTime) _
) As Boolean
'Usage
Dim dateTime As Nullable(Of DateTime)
Dim returnValue As Boolean

returnValue = dateTime.IsValidSqlDateTime()
```

``` csharp
public static bool IsValidSqlDateTime(
    this Nullable<DateTime> dateTime
)
```

``` c++
[ExtensionAttribute]
public:
static bool IsValidSqlDateTime(
    Nullable<DateTime> dateTime
)
```

#### Parameters

  - dateTime  
    Type: [System.Nullable](https://technet.microsoft.com/library/b3h38hb0\(v=ax.60\))\<[DateTime](https://technet.microsoft.com/library/03ybds8y\(v=ax.60\))\>  

#### Return Value

Type: [System.Boolean](https://technet.microsoft.com/library/a28wyd50\(v=ax.60\))  

#### Usage Note

In Visual Basic and C\#, you can call this method as an instance method on any object of type [Nullable](https://technet.microsoft.com/library/b3h38hb0\(v=ax.60\))\<[DateTime](https://technet.microsoft.com/library/03ybds8y\(v=ax.60\))\>. When you use instance method syntax to call this method, omit the first parameter. For more information, see b8020aae-374d-46a9-bcb7-8cc2390b93b6 or 175ce3ff-9bbf-4e64-8421-faeb81a0bb51.

## See Also

#### Reference

[DateTimeOffsetExtensions Class](datetimeoffsetextensions-class-microsoft-dynamics-commerce-runtime.md)

[IsValidSqlDateTime Overload](datetimeoffsetextensions-isvalidsqldatetime-method-microsoft-dynamics-commerce-runtime.md)

[Microsoft.Dynamics.Commerce.Runtime Namespace](microsoft-dynamics-commerce-runtime-namespace.md)

