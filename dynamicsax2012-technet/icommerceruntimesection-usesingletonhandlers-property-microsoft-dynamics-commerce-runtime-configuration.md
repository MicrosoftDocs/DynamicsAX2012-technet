---
title: ICommerceRuntimeSection.UseSingletonHandlers Property  (Microsoft.Dynamics.Commerce.Runtime.Configuration)
TOCTitle: UseSingletonHandlers Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.Configuration.ICommerceRuntimeSection.UseSingletonHandlers
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.configuration.icommerceruntimesection.usesingletonhandlers(v=AX.60)
ms:contentKeyID: 65320841
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.Configuration.ICommerceRuntimeSection.UseSingletonHandlers
dev_langs:
- CSharp
- C++
- VB
---

# UseSingletonHandlers Property

Gets a value indicating whether the composition should use singleton instances of the request handlers.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.Configuration](microsoft-dynamics-commerce-runtime-configuration-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Framework (in Microsoft.Dynamics.Commerce.Runtime.Framework.dll)

## Syntax

``` vb
'Declaration
ReadOnly Property UseSingletonHandlers As Boolean
    Get
'Usage
Dim instance As ICommerceRuntimeSection
Dim value As Boolean

value = instance.UseSingletonHandlers
```

``` csharp
bool UseSingletonHandlers { get; }
```

``` c++
property bool UseSingletonHandlers {
    bool get ();
}
```

#### Property Value

Type: [System.Boolean](https://technet.microsoft.com/library/a28wyd50\(v=ax.60\))  
Returns [Boolean](https://technet.microsoft.com/library/a28wyd50\(v=ax.60\)).  

## See Also

#### Reference

[ICommerceRuntimeSection Interface](icommerceruntimesection-interface-microsoft-dynamics-commerce-runtime-configuration.md)

[Microsoft.Dynamics.Commerce.Runtime.Configuration Namespace](microsoft-dynamics-commerce-runtime-configuration-namespace.md)

