---
title: CommerceRuntime.CurrentPrincipal Property  (Microsoft.Dynamics.Commerce.Runtime)
TOCTitle: CurrentPrincipal Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.CommerceRuntime.CurrentPrincipal
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.commerceruntime.currentprincipal(v=AX.60)
ms:contentKeyID: 62211659
author: Khairunj
ms.author: daxcpft
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.CommerceRuntime.CurrentPrincipal
dev_langs:
- CSharp
- C++
- VB
---

# CurrentPrincipal Property

Gets the current principal.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime](microsoft-dynamics-commerce-runtime-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime (in Microsoft.Dynamics.Commerce.Runtime.dll)

## Syntax

``` vb
'Declaration
Public ReadOnly Property CurrentPrincipal As CommercePrincipal
    Get
'Usage
Dim instance As CommerceRuntime
Dim value As CommercePrincipal

value = instance.CurrentPrincipal
```

``` csharp
public CommercePrincipal CurrentPrincipal { get; }
```

``` c++
public:
property CommercePrincipal^ CurrentPrincipal {
    CommercePrincipal^ get ();
}
```

#### Property Value

Type: [Microsoft.Dynamics.Commerce.Runtime.Data.CommercePrincipal](commerceprincipal-class-microsoft-dynamics-commerce-runtime-data.md)  
The current principal.  

## See Also

#### Reference

[CommerceRuntime Class](commerceruntime-class-microsoft-dynamics-commerce-runtime.md)

[Microsoft.Dynamics.Commerce.Runtime Namespace](microsoft-dynamics-commerce-runtime-namespace.md)

