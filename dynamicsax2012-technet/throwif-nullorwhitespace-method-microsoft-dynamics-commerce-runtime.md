---
title: ThrowIf.NullOrWhiteSpace Method  (Microsoft.Dynamics.Commerce.Runtime)
TOCTitle: NullOrWhiteSpace Method
ms:assetid: M:Microsoft.Dynamics.Commerce.Runtime.ThrowIf.NullOrWhiteSpace(System.String,System.String)
ms:mtpsurl: https://technet.microsoft.com/en-us/library/microsoft.dynamics.commerce.runtime.throwif.nullorwhitespace(v=AX.60)
ms:contentKeyID: 65322643
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.ThrowIf.NullOrWhiteSpace
dev_langs:
- CSharp
- C++
- VB
---

# NullOrWhiteSpace Method

Throws an ArgumentNullException if the string is null or only whitespace.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime](microsoft-dynamics-commerce-runtime-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Framework (in Microsoft.Dynamics.Commerce.Runtime.Framework.dll)

## Syntax

``` vb
'Declaration
Public Shared Sub NullOrWhiteSpace ( _
    arg As String, _
    parameterName As String _
)
'Usage
Dim arg As String
Dim parameterName As String

ThrowIf.NullOrWhiteSpace(arg, parameterName)
```

``` csharp
public static void NullOrWhiteSpace(
    string arg,
    string parameterName
)
```

``` c++
public:
static void NullOrWhiteSpace(
    String^ arg, 
    String^ parameterName
)
```

#### Parameters

  - arg  
    Type: [System.String](https://technet.microsoft.com/en-us/library/s1wwdcbf\(v=ax.60\))  

<!-- end list -->

  - parameterName  
    Type: [System.String](https://technet.microsoft.com/en-us/library/s1wwdcbf\(v=ax.60\))  

## See Also

#### Reference

[ThrowIf Class](throwif-class-microsoft-dynamics-commerce-runtime.md)

[Microsoft.Dynamics.Commerce.Runtime Namespace](microsoft-dynamics-commerce-runtime-namespace.md)

