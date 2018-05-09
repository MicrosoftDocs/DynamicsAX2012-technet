---
title: DateTimeOffsetExtensions.TotalSeconds Method  (Microsoft.Dynamics.Commerce.Runtime)
TOCTitle: TotalSeconds Method
ms:assetid: M:Microsoft.Dynamics.Commerce.Runtime.DateTimeOffsetExtensions.TotalSeconds(System.DateTimeOffset)
ms:mtpsurl: https://technet.microsoft.com/en-us/library/microsoft.dynamics.commerce.runtime.datetimeoffsetextensions.totalseconds(v=AX.60)
ms:contentKeyID: 62214039
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DateTimeOffsetExtensions.TotalSeconds
dev_langs:
- CSharp
- C++
- VB
---

# TotalSeconds Method

Gets the value of the current [DateTimeOffset](https://technet.microsoft.com/en-us/library/bb341783\(v=ax.60\)) structure expressed in whole and fractional seconds.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime](microsoft-dynamics-commerce-runtime-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Framework (in Microsoft.Dynamics.Commerce.Runtime.Framework.dll)

## Syntax

``` vb
'Declaration
<ExtensionAttribute> _
Public Shared Function TotalSeconds ( _
    dateTimeOffset As DateTimeOffset _
) As Integer
'Usage
Dim dateTimeOffset As DateTimeOffset
Dim returnValue As Integer

returnValue = dateTimeOffset.TotalSeconds()
```

``` csharp
public static int TotalSeconds(
    this DateTimeOffset dateTimeOffset
)
```

``` c++
[ExtensionAttribute]
public:
static int TotalSeconds(
    DateTimeOffset dateTimeOffset
)
```

#### Parameters

  - dateTimeOffset  
    Type: [System.DateTimeOffset](https://technet.microsoft.com/en-us/library/bb341783\(v=ax.60\))  

#### Return Value

Type: [System.Int32](https://technet.microsoft.com/en-us/library/td2s409d\(v=ax.60\))  
The total number of seconds represented by this instance.  

#### Usage Note

In Visual Basic and C\#, you can call this method as an instance method on any object of type [DateTimeOffset](https://technet.microsoft.com/en-us/library/bb341783\(v=ax.60\)). When you use instance method syntax to call this method, omit the first parameter. For more information, see b8020aae-374d-46a9-bcb7-8cc2390b93b6 or 175ce3ff-9bbf-4e64-8421-faeb81a0bb51.

## See Also

#### Reference

[DateTimeOffsetExtensions Class](datetimeoffsetextensions-class-microsoft-dynamics-commerce-runtime.md)

[Microsoft.Dynamics.Commerce.Runtime Namespace](microsoft-dynamics-commerce-runtime-namespace.md)

