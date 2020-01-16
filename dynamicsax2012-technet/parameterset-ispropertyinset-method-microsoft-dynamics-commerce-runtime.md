---
title: ParameterSet.IsPropertyInSet Method  (Microsoft.Dynamics.Commerce.Runtime)
TOCTitle: IsPropertyInSet Method
ms:assetid: M:Microsoft.Dynamics.Commerce.Runtime.ParameterSet.IsPropertyInSet(System.String)
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.parameterset.ispropertyinset(v=AX.60)
ms:contentKeyID: 62213188
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.ParameterSet.IsPropertyInSet
dev_langs:
- CSharp
- C++
- VB
---

# IsPropertyInSet Method

Checks whether a property is defined in this property set or not.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime](microsoft-dynamics-commerce-runtime-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Framework (in Microsoft.Dynamics.Commerce.Runtime.Framework.dll)

## Syntax

``` vb
'Declaration
Public Function IsPropertyInSet ( _
    key As String _
) As Boolean
'Usage
Dim instance As ParameterSet
Dim key As String
Dim returnValue As Boolean

returnValue = instance.IsPropertyInSet(key)
```

``` csharp
public bool IsPropertyInSet(
    string key
)
```

``` c++
public:
bool IsPropertyInSet(
    String^ key
)
```

#### Parameters

  - key  
    Type: [System.String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\))  

#### Return Value

Type: [System.Boolean](https://technet.microsoft.com/library/a28wyd50\(v=ax.60\))  
Whether the property is defined in this property set or not.  

## See Also

#### Reference

[ParameterSet Class](parameterset-class-microsoft-dynamics-commerce-runtime.md)

[Microsoft.Dynamics.Commerce.Runtime Namespace](microsoft-dynamics-commerce-runtime-namespace.md)

