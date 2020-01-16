---
title: ThrowIf.NullOrEmpty Method  (Microsoft.Dynamics.Commerce.Runtime)
TOCTitle: NullOrEmpty Method
ms:assetid: M:Microsoft.Dynamics.Commerce.Runtime.ThrowIf.NullOrEmpty(System.Collections.ICollection,System.String)
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.throwif.nullorempty(v=AX.60)
ms:contentKeyID: 65321332
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.ThrowIf.NullOrEmpty
dev_langs:
- CSharp
- C++
- VB
---

# NullOrEmpty Method

Throws an ArgumentException if the argument is null or empty.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime](microsoft-dynamics-commerce-runtime-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Framework (in Microsoft.Dynamics.Commerce.Runtime.Framework.dll)

## Syntax

``` vb
'Declaration
Public Shared Sub NullOrEmpty ( _
    arg As ICollection, _
    parameterName As String _
)
'Usage
Dim arg As ICollection
Dim parameterName As String

ThrowIf.NullOrEmpty(arg, parameterName)
```

``` csharp
public static void NullOrEmpty(
    ICollection arg,
    string parameterName
)
```

``` c++
public:
static void NullOrEmpty(
    ICollection^ arg, 
    String^ parameterName
)
```

#### Parameters

  - arg  
    Type: [System.Collections.ICollection](https://technet.microsoft.com/library/b1ht6113\(v=ax.60\))  

<!-- end list -->

  - parameterName  
    Type: [System.String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\))  

## See Also

#### Reference

[ThrowIf Class](throwif-class-microsoft-dynamics-commerce-runtime.md)

[Microsoft.Dynamics.Commerce.Runtime Namespace](microsoft-dynamics-commerce-runtime-namespace.md)

