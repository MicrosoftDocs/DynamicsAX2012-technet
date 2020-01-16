---
title: IPosTransactionV1.OpenDrawer Property  (Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity)
TOCTitle: OpenDrawer Property
ms:assetid: P:Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity.IPosTransactionV1.OpenDrawer
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.retail.pos.contracts.dataentity.ipostransactionv1.opendrawer(v=AX.60)
ms:contentKeyID: 47129176
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity.IPosTransactionV1.OpenDrawer
dev_langs:
- CSharp
- C++
- VB
---

# OpenDrawer Property

Gets whether the drawer opened during the transaction.

**Namespace:**  [Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity](microsoft-dynamics-retail-pos-contracts-dataentity-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Retail.Pos.Contracts (in Microsoft.Dynamics.Retail.Pos.Contracts.dll)

## Syntax

``` vb
'Declaration
ReadOnly Property OpenDrawer As Boolean
    Get
'Usage
Dim instance As IPosTransactionV1
Dim value As Boolean

value = instance.OpenDrawer
```

``` csharp
bool OpenDrawer { get; }
```

``` c++
property bool OpenDrawer {
    bool get ();
}
```

#### Property Value

Type: [System.Boolean](https://technet.microsoft.com/library/a28wyd50\(v=ax.60\))  
The [System.Boolean](https://technet.microsoft.com/library/a28wyd50\(v=ax.60\)) value.  

## See Also

#### Reference

[IPosTransactionV1 Interface](ipostransactionv1-interface-microsoft-dynamics-retail-pos-contracts-dataentity.md)

[Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity Namespace](microsoft-dynamics-retail-pos-contracts-dataentity-namespace.md)

