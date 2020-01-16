---
title: ThrowIf.EmptyGuid Method  (Microsoft.Dynamics.Commerce.Runtime)
TOCTitle: EmptyGuid Method
ms:assetid: M:Microsoft.Dynamics.Commerce.Runtime.ThrowIf.EmptyGuid(System.Guid,System.String)
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.throwif.emptyguid(v=AX.60)
ms:contentKeyID: 65316813
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.ThrowIf.EmptyGuid
dev_langs:
- CSharp
- C++
- VB
---

# EmptyGuid Method

Throws ArgumentOutOfRangeException if the argument is empty GUID.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime](microsoft-dynamics-commerce-runtime-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Framework (in Microsoft.Dynamics.Commerce.Runtime.Framework.dll)

## Syntax

``` vb
'Declaration
Public Shared Sub EmptyGuid ( _
    value As Guid, _
    parameterName As String _
)
'Usage
Dim value As Guid
Dim parameterName As String

ThrowIf.EmptyGuid(value, parameterName)
```

``` csharp
public static void EmptyGuid(
    Guid value,
    string parameterName
)
```

``` c++
public:
static void EmptyGuid(
    Guid value, 
    String^ parameterName
)
```

#### Parameters

  - value  
    Type: [System.Guid](https://technet.microsoft.com/library/cey1zx63\(v=ax.60\))  

<!-- end list -->

  - parameterName  
    Type: [System.String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\))  

## See Also

#### Reference

[ThrowIf Class](throwif-class-microsoft-dynamics-commerce-runtime.md)

[Microsoft.Dynamics.Commerce.Runtime Namespace](microsoft-dynamics-commerce-runtime-namespace.md)

