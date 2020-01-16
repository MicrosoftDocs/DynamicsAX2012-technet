---
title: LogonCredentials.Identity Property  (Microsoft.Dynamics.Commerce.Runtime.Entities)
TOCTitle: Identity Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.Entities.LogonCredentials.Identity
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.entities.logoncredentials.identity(v=AX.60)
ms:contentKeyID: 65319341
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.Entities.LogonCredentials.Identity
dev_langs:
- CSharp
- C++
- VB
---

# Identity Property

Gets or sets the identity information.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.Entities](microsoft-dynamics-commerce-runtime-entities-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Entities (in Microsoft.Dynamics.Commerce.Runtime.Entities.dll)

## Syntax

``` vb
'Declaration
<DataMemberAttribute> _
Public Property Identity As CommerceIdentity
    Get
    Set
'Usage
Dim instance As LogonCredentials
Dim value As CommerceIdentity

value = instance.Identity

instance.Identity = value
```

``` csharp
[DataMemberAttribute]
public CommerceIdentity Identity { get; set; }
```

``` c++
[DataMemberAttribute]
public:
property CommerceIdentity^ Identity {
    CommerceIdentity^ get ();
    void set (CommerceIdentity^ value);
}
```

#### Property Value

Type: [Microsoft.Dynamics.Commerce.Runtime.Data.CommerceIdentity](commerceidentity-class-microsoft-dynamics-commerce-runtime-data.md)  
Returns [CommerceIdentity](commerceidentity-class-microsoft-dynamics-commerce-runtime-data.md).  

## See Also

#### Reference

[LogonCredentials Class](logoncredentials-class-microsoft-dynamics-commerce-runtime-entities.md)

[Microsoft.Dynamics.Commerce.Runtime.Entities Namespace](microsoft-dynamics-commerce-runtime-entities-namespace.md)

