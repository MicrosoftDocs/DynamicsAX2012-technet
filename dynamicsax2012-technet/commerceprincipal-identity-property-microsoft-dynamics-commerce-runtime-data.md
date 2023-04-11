---
title: CommercePrincipal.Identity Property  (Microsoft.Dynamics.Commerce.Runtime.Data)
TOCTitle: Identity Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.Data.CommercePrincipal.Identity
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.data.commerceprincipal.identity(v=AX.60)
ms:contentKeyID: 65316272
author: tonyafehr
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.Data.CommercePrincipal.Identity
dev_langs:
- CSharp
- C++
- VB
---

# Identity Property


[!INCLUDE[archive-banner](includes/archive-banner.md)]

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.Data](microsoft-dynamics-commerce-runtime-data-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Entities (in Microsoft.Dynamics.Commerce.Runtime.Entities.dll)

## Syntax

``` vb
'Declaration
Public ReadOnly Property Identity As IIdentity
    Get
'Usage
Dim instance As CommercePrincipal
Dim value As IIdentity

value = instance.Identity
```

``` csharp
public IIdentity Identity { get; }
```

``` c++
public:
virtual property IIdentity^ Identity {
    IIdentity^ get () sealed;
}
```

#### Property Value

Type: [System.Security.Principal.IIdentity](https://technet.microsoft.com/library/cfh703cy\(v=ax.60\))  

#### Implements

[IPrincipal.Identity](https://technet.microsoft.com/library/499z5w4e\(v=ax.60\))  

## See Also

#### Reference

[CommercePrincipal Class](commerceprincipal-class-microsoft-dynamics-commerce-runtime-data.md)

[Microsoft.Dynamics.Commerce.Runtime.Data Namespace](microsoft-dynamics-commerce-runtime-data-namespace.md)

