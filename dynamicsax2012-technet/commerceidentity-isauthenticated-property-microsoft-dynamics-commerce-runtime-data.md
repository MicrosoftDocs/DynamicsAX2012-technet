---
title: CommerceIdentity.IsAuthenticated Property  (Microsoft.Dynamics.Commerce.Runtime.Data)
TOCTitle: IsAuthenticated Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.Data.CommerceIdentity.IsAuthenticated
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.data.commerceidentity.isauthenticated(v=AX.60)
ms:contentKeyID: 65319471
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.Data.CommerceIdentity.IsAuthenticated
dev_langs:
- CSharp
- C++
- VB
---

# IsAuthenticated Property

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.Data](microsoft-dynamics-commerce-runtime-data-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Entities (in Microsoft.Dynamics.Commerce.Runtime.Entities.dll)

## Syntax

``` vb
'Declaration
<DataMemberAttribute> _
Public ReadOnly Property IsAuthenticated As Boolean
    Get
'Usage
Dim instance As CommerceIdentity
Dim value As Boolean

value = instance.IsAuthenticated
```

``` csharp
[DataMemberAttribute]
public bool IsAuthenticated { get; }
```

``` c++
[DataMemberAttribute]
public:
virtual property bool IsAuthenticated {
    bool get () sealed;
}
```

#### Property Value

Type: [System.Boolean](https://technet.microsoft.com/library/a28wyd50\(v=ax.60\))  

#### Implements

[IIdentity.IsAuthenticated](https://technet.microsoft.com/library/z2x1475h\(v=ax.60\))  

## See Also

#### Reference

[CommerceIdentity Class](commerceidentity-class-microsoft-dynamics-commerce-runtime-data.md)

[Microsoft.Dynamics.Commerce.Runtime.Data Namespace](microsoft-dynamics-commerce-runtime-data-namespace.md)

