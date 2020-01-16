---
title: ParameterSet Class (Microsoft.Dynamics.Commerce.Runtime)
TOCTitle: ParameterSet Class
ms:assetid: T:Microsoft.Dynamics.Commerce.Runtime.ParameterSet
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.parameterset(v=AX.60)
ms:contentKeyID: 49853298
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.ParameterSet
dev_langs:
- CSharp
- C++
- VB
---

# ParameterSet Class

Encapsulates a collection of named parameters represented as key/value pairs.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime](microsoft-dynamics-commerce-runtime-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Framework (in Microsoft.Dynamics.Commerce.Runtime.Framework.dll)

## Syntax

``` vb
'Declaration
<DataContractAttribute> _
Public Class ParameterSet _
    Inherits Dictionary(Of String, Object)
'Usage
Dim instance As ParameterSet
```

``` csharp
[DataContractAttribute]
public class ParameterSet : Dictionary<string, Object>
```

``` c++
[DataContractAttribute]
public ref class ParameterSet : public Dictionary<String^, Object^>
```

## Remarks

Keys are case insensitive. Duplicates are not allowed.

## Inheritance Hierarchy

[System.Object](https://technet.microsoft.com/library/e5kfa45b\(v=ax.60\))  
  [System.Collections.Generic.Dictionary](https://technet.microsoft.com/library/xfhwa508\(v=ax.60\))\<[String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\)), [Object](https://technet.microsoft.com/library/e5kfa45b\(v=ax.60\))\>  
    Microsoft.Dynamics.Commerce.Runtime.ParameterSet  

## Thread Safety

Any public static (Shared in Visual Basic) members of this type are thread safe. Any instance members are not guaranteed to be thread safe.

## See Also

#### Reference

[Microsoft.Dynamics.Commerce.Runtime Namespace](microsoft-dynamics-commerce-runtime-namespace.md)

