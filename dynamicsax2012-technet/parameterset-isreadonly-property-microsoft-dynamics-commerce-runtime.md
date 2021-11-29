---
title: ParameterSet.IsReadOnly Property  (Microsoft.Dynamics.Commerce.Runtime)
TOCTitle: IsReadOnly Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.ParameterSet.IsReadOnly
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.parameterset.isreadonly(v=AX.60)
ms:contentKeyID: 49832017
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.ParameterSet.IsReadOnly
dev_langs:
- CSharp
- C++
- VB
---

# IsReadOnly Property


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Gets a value indicating whether the collection has been marked as read-only.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime](microsoft-dynamics-commerce-runtime-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Framework (in Microsoft.Dynamics.Commerce.Runtime.Framework.dll)

## Syntax

``` vb
'Declaration
Public Property IsReadOnly As Boolean
    Get
    Private Set
'Usage
Dim instance As ParameterSet
Dim value As Boolean

value = instance.IsReadOnly
```

``` csharp
public bool IsReadOnly { get; private set; }
```

``` c++
public:
property bool IsReadOnly {
    bool get ();
    private: void set (bool value);
}
```

#### Property Value

Type: [System.Boolean](https://technet.microsoft.com/library/a28wyd50\(v=ax.60\))  
If true the collection has been marked as read-only; otherwise, false.  

## See Also

#### Reference

[ParameterSet Class](parameterset-class-microsoft-dynamics-commerce-runtime.md)

[Microsoft.Dynamics.Commerce.Runtime Namespace](microsoft-dynamics-commerce-runtime-namespace.md)

