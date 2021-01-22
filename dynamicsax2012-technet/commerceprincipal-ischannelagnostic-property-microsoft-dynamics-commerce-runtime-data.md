---
title: CommercePrincipal.IsChannelAgnostic Property  (Microsoft.Dynamics.Commerce.Runtime.Data)
TOCTitle: IsChannelAgnostic Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.Data.CommercePrincipal.IsChannelAgnostic
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.data.commerceprincipal.ischannelagnostic(v=AX.60)
ms:contentKeyID: 62202874
author: Khairunj
ms.author: daxcpft
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.Data.CommercePrincipal.IsChannelAgnostic
dev_langs:
- CSharp
- C++
- VB
---

# IsChannelAgnostic Property

Gets a value indicating whether channel is agnostic.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.Data](microsoft-dynamics-commerce-runtime-data-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Entities (in Microsoft.Dynamics.Commerce.Runtime.Entities.dll)

## Syntax

``` vb
'Declaration
<IgnoreDataMemberAttribute> _
Public ReadOnly Property IsChannelAgnostic As Boolean
    Get
'Usage
Dim instance As CommercePrincipal
Dim value As Boolean

value = instance.IsChannelAgnostic
```

``` csharp
[IgnoreDataMemberAttribute]
public bool IsChannelAgnostic { get; }
```

``` c++
[IgnoreDataMemberAttribute]
public:
property bool IsChannelAgnostic {
    bool get ();
}
```

#### Property Value

Type: [System.Boolean](https://technet.microsoft.com/library/a28wyd50\(v=ax.60\))  
Returns [Boolean](https://technet.microsoft.com/library/a28wyd50\(v=ax.60\)).  

## See Also

#### Reference

[CommercePrincipal Class](commerceprincipal-class-microsoft-dynamics-commerce-runtime-data.md)

[Microsoft.Dynamics.Commerce.Runtime.Data Namespace](microsoft-dynamics-commerce-runtime-data-namespace.md)

