---
title: ParameterSet.Remove Method  (Microsoft.Dynamics.Commerce.Runtime)
TOCTitle: Remove Method
ms:assetid: M:Microsoft.Dynamics.Commerce.Runtime.ParameterSet.Remove(System.String)
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.parameterset.remove(v=AX.60)
ms:contentKeyID: 65315485
author: tonyafehr
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.ParameterSet.Remove
dev_langs:
- CSharp
- C++
- VB
---

# Remove Method


[!INCLUDE[archive-banner](includes/archive-banner.md)]

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime](microsoft-dynamics-commerce-runtime-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Framework (in Microsoft.Dynamics.Commerce.Runtime.Framework.dll)

## Syntax

``` vb
'Declaration
Public Function Remove ( _
    key As String _
) As Boolean
'Usage
Dim instance As ParameterSet
Dim key As String
Dim returnValue As Boolean

returnValue = instance.Remove(key)
```

``` csharp
public bool Remove(
    string key
)
```

``` c++
public:
bool Remove(
    String^ key
)
```

#### Parameters

  - key  
    Type: [System.String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\))  

#### Return Value

Type: [System.Boolean](https://technet.microsoft.com/library/a28wyd50\(v=ax.60\))  

## See Also

#### Reference

[ParameterSet Class](parameterset-class-microsoft-dynamics-commerce-runtime.md)

[Microsoft.Dynamics.Commerce.Runtime Namespace](microsoft-dynamics-commerce-runtime-namespace.md)

