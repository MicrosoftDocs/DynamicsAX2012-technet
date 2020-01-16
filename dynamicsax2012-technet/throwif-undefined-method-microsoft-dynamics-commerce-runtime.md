---
title: ThrowIf.Undefined Method  (Microsoft.Dynamics.Commerce.Runtime)
TOCTitle: Undefined Method
ms:assetid: M:Microsoft.Dynamics.Commerce.Runtime.ThrowIf.Undefined(System.Enum,System.String)
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.throwif.undefined(v=AX.60)
ms:contentKeyID: 65319306
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.ThrowIf.Undefined
dev_langs:
- CSharp
- C++
- VB
---

# Undefined Method

Throws ArgumentOutOfRangeException if the enumeration value is undefined.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime](microsoft-dynamics-commerce-runtime-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Framework (in Microsoft.Dynamics.Commerce.Runtime.Framework.dll)

## Syntax

``` vb
'Declaration
Public Shared Sub Undefined ( _
    enumeration As Enum, _
    parameterName As String _
)
'Usage
Dim enumeration As Enum
Dim parameterName As String

ThrowIf.Undefined(enumeration, parameterName)
```

``` csharp
public static void Undefined(
    Enum enumeration,
    string parameterName
)
```

``` c++
public:
static void Undefined(
    Enum^ enumeration, 
    String^ parameterName
)
```

#### Parameters

  - enumeration  
    Type: [System.Enum](https://technet.microsoft.com/library/1zt1ybx4\(v=ax.60\))  

<!-- end list -->

  - parameterName  
    Type: [System.String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\))  

## See Also

#### Reference

[ThrowIf Class](throwif-class-microsoft-dynamics-commerce-runtime.md)

[Microsoft.Dynamics.Commerce.Runtime Namespace](microsoft-dynamics-commerce-runtime-namespace.md)

