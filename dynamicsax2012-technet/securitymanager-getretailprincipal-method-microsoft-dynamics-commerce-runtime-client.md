---
title: SecurityManager.GetRetailPrincipal Method  (Microsoft.Dynamics.Commerce.Runtime.Client)
TOCTitle: GetRetailPrincipal Method
ms:assetid: M:Microsoft.Dynamics.Commerce.Runtime.Client.SecurityManager.GetRetailPrincipal(Microsoft.Dynamics.Commerce.Runtime.Data.CommerceIdentity)
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.client.securitymanager.getretailprincipal(v=AX.60)
ms:contentKeyID: 62212868
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.Client.SecurityManager.GetRetailPrincipal
dev_langs:
- CSharp
- C++
- VB
---

# GetRetailPrincipal Method

Get customized principal for the specified user.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.Client](microsoft-dynamics-commerce-runtime-client-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Client (in Microsoft.Dynamics.Commerce.Runtime.Client.dll)

## Syntax

``` vb
'Declaration
Public Function GetRetailPrincipal ( _
    identity As CommerceIdentity _
) As CommercePrincipal
'Usage
Dim instance As SecurityManager
Dim identity As CommerceIdentity
Dim returnValue As CommercePrincipal

returnValue = instance.GetRetailPrincipal(identity)
```

``` csharp
public CommercePrincipal GetRetailPrincipal(
    CommerceIdentity identity
)
```

``` c++
public:
CommercePrincipal^ GetRetailPrincipal(
    CommerceIdentity^ identity
)
```

#### Parameters

  - identity  
    Type: [Microsoft.Dynamics.Commerce.Runtime.Data.CommerceIdentity](commerceidentity-class-microsoft-dynamics-commerce-runtime-data.md)  

#### Return Value

Type: [Microsoft.Dynamics.Commerce.Runtime.Data.CommercePrincipal](commerceprincipal-class-microsoft-dynamics-commerce-runtime-data.md)  
A customized pricinpal for retail commerce runtime.  

## See Also

#### Reference

[SecurityManager Class](securitymanager-class-microsoft-dynamics-commerce-runtime-client.md)

[Microsoft.Dynamics.Commerce.Runtime.Client Namespace](microsoft-dynamics-commerce-runtime-client-namespace.md)

