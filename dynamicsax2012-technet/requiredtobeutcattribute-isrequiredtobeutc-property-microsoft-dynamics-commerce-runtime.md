---
title: RequiredToBeUtcAttribute.IsRequiredToBeUtc Property  (Microsoft.Dynamics.Commerce.Runtime)
TOCTitle: IsRequiredToBeUtc Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.RequiredToBeUtcAttribute.IsRequiredToBeUtc
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.requiredtobeutcattribute.isrequiredtobeutc(v=AX.60)
ms:contentKeyID: 62208892
author: tonyafehr
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.RequiredToBeUtcAttribute.IsRequiredToBeUtc
dev_langs:
- CSharp
- C++
- VB
---

# IsRequiredToBeUtc Property


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Gets a value indicating whether \[is required to be UTC\].

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime](microsoft-dynamics-commerce-runtime-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Framework (in Microsoft.Dynamics.Commerce.Runtime.Framework.dll)

## Syntax

``` vb
'Declaration
Public Property IsRequiredToBeUtc As Boolean
    Get
    Private Set
'Usage
Dim instance As RequiredToBeUtcAttribute
Dim value As Boolean

value = instance.IsRequiredToBeUtc
```

``` csharp
public bool IsRequiredToBeUtc { get; private set; }
```

``` c++
public:
property bool IsRequiredToBeUtc {
    bool get ();
    private: void set (bool value);
}
```

#### Property Value

Type: [System.Boolean](https://technet.microsoft.com/library/a28wyd50\(v=ax.60\))  
True if \[is required to be UTC\]; otherwise, false.  

## See Also

#### Reference

[RequiredToBeUtcAttribute Class](requiredtobeutcattribute-class-microsoft-dynamics-commerce-runtime.md)

[Microsoft.Dynamics.Commerce.Runtime Namespace](microsoft-dynamics-commerce-runtime-namespace.md)

