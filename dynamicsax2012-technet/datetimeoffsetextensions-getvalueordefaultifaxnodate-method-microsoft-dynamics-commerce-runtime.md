---
title: DateTimeOffsetExtensions.GetValueOrDefaultIfAxNoDate Method  (Microsoft.Dynamics.Commerce.Runtime)
TOCTitle: GetValueOrDefaultIfAxNoDate Method
ms:assetid: M:Microsoft.Dynamics.Commerce.Runtime.DateTimeOffsetExtensions.GetValueOrDefaultIfAxNoDate(System.DateTimeOffset,System.DateTimeOffset)
ms:mtpsurl: https://technet.microsoft.com/en-us/library/microsoft.dynamics.commerce.runtime.datetimeoffsetextensions.getvalueordefaultifaxnodate(v=AX.60)
ms:contentKeyID: 65318584
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DateTimeOffsetExtensions.GetValueOrDefaultIfAxNoDate
dev_langs:
- CSharp
- C++
- VB
---

# GetValueOrDefaultIfAxNoDate Method

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime](microsoft-dynamics-commerce-runtime-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Framework (in Microsoft.Dynamics.Commerce.Runtime.Framework.dll)

## Syntax

``` vb
'Declaration
<ExtensionAttribute> _
Public Shared Function GetValueOrDefaultIfAxNoDate ( _
    value As DateTimeOffset, _
    defaultValue As DateTimeOffset _
) As DateTimeOffset
'Usage
Dim value As DateTimeOffset
Dim defaultValue As DateTimeOffset
Dim returnValue As DateTimeOffset

returnValue = value.GetValueOrDefaultIfAxNoDate(defaultValue)
```

``` csharp
public static DateTimeOffset GetValueOrDefaultIfAxNoDate(
    this DateTimeOffset value,
    DateTimeOffset defaultValue
)
```

``` c++
[ExtensionAttribute]
public:
static DateTimeOffset GetValueOrDefaultIfAxNoDate(
    DateTimeOffset value, 
    DateTimeOffset defaultValue
)
```

#### Parameters

  - value  
    Type: [System.DateTimeOffset](https://technet.microsoft.com/en-us/library/bb341783\(v=ax.60\))  

<!-- end list -->

  - defaultValue  
    Type: [System.DateTimeOffset](https://technet.microsoft.com/en-us/library/bb341783\(v=ax.60\))  

#### Return Value

Type: [System.DateTimeOffset](https://technet.microsoft.com/en-us/library/bb341783\(v=ax.60\))  

#### Usage Note

In Visual Basic and C\#, you can call this method as an instance method on any object of type [DateTimeOffset](https://technet.microsoft.com/en-us/library/bb341783\(v=ax.60\)). When you use instance method syntax to call this method, omit the first parameter. For more information, see b8020aae-374d-46a9-bcb7-8cc2390b93b6 or 175ce3ff-9bbf-4e64-8421-faeb81a0bb51.

## See Also

#### Reference

[DateTimeOffsetExtensions Class](datetimeoffsetextensions-class-microsoft-dynamics-commerce-runtime.md)

[Microsoft.Dynamics.Commerce.Runtime Namespace](microsoft-dynamics-commerce-runtime-namespace.md)

