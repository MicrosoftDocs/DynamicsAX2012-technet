---
title: DateTimeOffsetExtensions.IsValidSqlDateTime Method (DateTimeOffset) (Microsoft.Dynamics.Commerce.Runtime)
TOCTitle: IsValidSqlDateTime Method (DateTimeOffset)
ms:assetid: M:Microsoft.Dynamics.Commerce.Runtime.DateTimeOffsetExtensions.IsValidSqlDateTime(System.DateTimeOffset)
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.datetimeoffsetextensions.isvalidsqldatetime(v=AX.60)
ms:contentKeyID: 62214330
author: tonyafehr
ms.date: 05/18/2015
mtps_version: v=AX.60
dev_langs:
- vb
- csharp
- c++
---

# IsValidSqlDateTime Method (DateTimeOffset)


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Gets a value indicating whether the specified [DateTimeOffset](https://technet.microsoft.com/library/bb341783\(v=ax.60\)) is valid within the allowed range of a [SqlDateTime](https://technet.microsoft.com/library/f1ys9ehh\(v=ax.60\)) data type.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime](microsoft-dynamics-commerce-runtime-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Framework (in Microsoft.Dynamics.Commerce.Runtime.Framework.dll)

## Syntax

``` vb
'Declaration
<ExtensionAttribute> _
Public Shared Function IsValidSqlDateTime ( _
    dateTimeOffset As DateTimeOffset _
) As Boolean
'Usage
Dim dateTimeOffset As DateTimeOffset
Dim returnValue As Boolean

returnValue = dateTimeOffset.IsValidSqlDateTime()
```

``` csharp
public static bool IsValidSqlDateTime(
    this DateTimeOffset dateTimeOffset
)
```

``` c++
[ExtensionAttribute]
public:
static bool IsValidSqlDateTime(
    DateTimeOffset dateTimeOffset
)
```

#### Parameters

  - dateTimeOffset  
    Type: [System.DateTimeOffset](https://technet.microsoft.com/library/bb341783\(v=ax.60\))  

#### Return Value

Type: [System.Boolean](https://technet.microsoft.com/library/a28wyd50\(v=ax.60\))  
A value indicating whether the specified instance is in range.  

#### Usage Note

In Visual Basic and C\#, you can call this method as an instance method on any object of type [DateTimeOffset](https://technet.microsoft.com/library/bb341783\(v=ax.60\)). When you use instance method syntax to call this method, omit the first parameter. For more information, see b8020aae-374d-46a9-bcb7-8cc2390b93b6 or 175ce3ff-9bbf-4e64-8421-faeb81a0bb51.

## See Also

#### Reference

[DateTimeOffsetExtensions Class](datetimeoffsetextensions-class-microsoft-dynamics-commerce-runtime.md)

[IsValidSqlDateTime Overload](datetimeoffsetextensions-isvalidsqldatetime-method-microsoft-dynamics-commerce-runtime.md)

[Microsoft.Dynamics.Commerce.Runtime Namespace](microsoft-dynamics-commerce-runtime-namespace.md)

