---
title: ITenderV1.OpenDrawer Property  (Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity)
TOCTitle: OpenDrawer Property
ms:assetid: P:Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity.ITenderV1.OpenDrawer
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.retail.pos.contracts.dataentity.itenderv1.opendrawer(v=AX.60)
ms:contentKeyID: 49846360
author: tonyafehr
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity.ITenderV1.OpenDrawer
dev_langs:
- CSharp
- C++
- VB
---

# OpenDrawer Property


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Set if using this tender will cause the drawer to open

**Namespace:**  [Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity](microsoft-dynamics-retail-pos-contracts-dataentity-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Retail.Pos.Contracts (in Microsoft.Dynamics.Retail.Pos.Contracts.dll)

## Syntax

``` vb
'Declaration
Property OpenDrawer As Boolean
    Get
    Set
'Usage
Dim instance As ITenderV1
Dim value As Boolean

value = instance.OpenDrawer

instance.OpenDrawer = value
```

``` csharp
bool OpenDrawer { get; set; }
```

``` c++
property bool OpenDrawer {
    bool get ();
    void set (bool value);
}
```

#### Property Value

Type: [System.Boolean](https://technet.microsoft.com/library/a28wyd50\(v=ax.60\))  
Returns [Boolean](https://technet.microsoft.com/library/a28wyd50\(v=ax.60\)).  

## See Also

#### Reference

[ITenderV1 Interface](itenderv1-interface-microsoft-dynamics-retail-pos-contracts-dataentity.md)

[Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity Namespace](microsoft-dynamics-retail-pos-contracts-dataentity-namespace.md)

