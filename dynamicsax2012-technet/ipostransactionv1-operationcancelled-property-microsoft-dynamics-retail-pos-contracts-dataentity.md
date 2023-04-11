---
title: IPosTransactionV1.OperationCancelled Property  (Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity)
TOCTitle: OperationCancelled Property
ms:assetid: P:Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity.IPosTransactionV1.OperationCancelled
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.retail.pos.contracts.dataentity.ipostransactionv1.operationcancelled(v=AX.60)
ms:contentKeyID: 47128612
author: tonyafehr
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity.IPosTransactionV1.OperationCancelled
dev_langs:
- CSharp
- C++
- VB
---

# OperationCancelled Property


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Gets or sets the status of the operation.

**Namespace:**  [Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity](microsoft-dynamics-retail-pos-contracts-dataentity-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Retail.Pos.Contracts (in Microsoft.Dynamics.Retail.Pos.Contracts.dll)

## Syntax

``` vb
'Declaration
Property OperationCancelled As Boolean
    Get
    Set
'Usage
Dim instance As IPosTransactionV1
Dim value As Boolean

value = instance.OperationCancelled

instance.OperationCancelled = value
```

``` csharp
bool OperationCancelled { get; set; }
```

``` c++
property bool OperationCancelled {
    bool get ();
    void set (bool value);
}
```

#### Property Value

Type: [System.Boolean](https://technet.microsoft.com/library/a28wyd50\(v=ax.60\))  
The [System.Boolean](https://technet.microsoft.com/library/a28wyd50\(v=ax.60\)) value.  

## See Also

#### Reference

[IPosTransactionV1 Interface](ipostransactionv1-interface-microsoft-dynamics-retail-pos-contracts-dataentity.md)

[Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity Namespace](microsoft-dynamics-retail-pos-contracts-dataentity-namespace.md)

