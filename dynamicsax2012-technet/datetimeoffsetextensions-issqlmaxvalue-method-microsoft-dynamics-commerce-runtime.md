---
title: DateTimeOffsetExtensions.IsSqlMaxValue Method  (Microsoft.Dynamics.Commerce.Runtime)
TOCTitle: IsSqlMaxValue Method
ms:assetid: M:Microsoft.Dynamics.Commerce.Runtime.DateTimeOffsetExtensions.IsSqlMaxValue(System.DateTimeOffset)
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.datetimeoffsetextensions.issqlmaxvalue(v=AX.60)
ms:contentKeyID: 62214911
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DateTimeOffsetExtensions.IsSqlMaxValue
dev_langs:
- CSharp
- C++
- VB
---

# IsSqlMaxValue Method

Determines whether the specified date time offset is SQL maximum value.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime](microsoft-dynamics-commerce-runtime-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Framework (in Microsoft.Dynamics.Commerce.Runtime.Framework.dll)

## Syntax

``` vb
'Declaration
<ExtensionAttribute> _
Public Shared Function IsSqlMaxValue ( _
    dateTimeOffset As DateTimeOffset _
) As Boolean
'Usage
Dim dateTimeOffset As DateTimeOffset
Dim returnValue As Boolean

returnValue = dateTimeOffset.IsSqlMaxValue()
```

``` csharp
public static bool IsSqlMaxValue(
    this DateTimeOffset dateTimeOffset
)
```

``` c++
[ExtensionAttribute]
public:
static bool IsSqlMaxValue(
    DateTimeOffset dateTimeOffset
)
```

#### Parameters

  - dateTimeOffset  
    Type: [System.DateTimeOffset](https://technet.microsoft.com/library/bb341783\(v=ax.60\))  

#### Return Value

Type: [System.Boolean](https://technet.microsoft.com/library/a28wyd50\(v=ax.60\))  
True, if its DateTime value equals SqlDateTime.MaxValue and Offset is Zero; Otherwise, false.  

#### Usage Note

In Visual Basic and C\#, you can call this method as an instance method on any object of type [DateTimeOffset](https://technet.microsoft.com/library/bb341783\(v=ax.60\)). When you use instance method syntax to call this method, omit the first parameter. For more information, see b8020aae-374d-46a9-bcb7-8cc2390b93b6 or 175ce3ff-9bbf-4e64-8421-faeb81a0bb51.

## See Also

#### Reference

[DateTimeOffsetExtensions Class](datetimeoffsetextensions-class-microsoft-dynamics-commerce-runtime.md)

[Microsoft.Dynamics.Commerce.Runtime Namespace](microsoft-dynamics-commerce-runtime-namespace.md)

