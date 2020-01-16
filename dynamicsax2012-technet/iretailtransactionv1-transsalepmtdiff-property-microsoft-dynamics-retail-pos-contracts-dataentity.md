---
title: IRetailTransactionV1.TransSalePmtDiff Property  (Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity)
TOCTitle: TransSalePmtDiff Property
ms:assetid: P:Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity.IRetailTransactionV1.TransSalePmtDiff
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.retail.pos.contracts.dataentity.iretailtransactionv1.transsalepmtdiff(v=AX.60)
ms:contentKeyID: 49841933
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity.IRetailTransactionV1.TransSalePmtDiff
dev_langs:
- CSharp
- C++
- VB
---

# TransSalePmtDiff Property

The difference between payment and grossAmount plus rounded

**Namespace:**  [Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity](microsoft-dynamics-retail-pos-contracts-dataentity-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Retail.Pos.Contracts (in Microsoft.Dynamics.Retail.Pos.Contracts.dll)

## Syntax

``` vb
'Declaration
ReadOnly Property TransSalePmtDiff As Decimal
    Get
'Usage
Dim instance As IRetailTransactionV1
Dim value As Decimal

value = instance.TransSalePmtDiff
```

``` csharp
decimal TransSalePmtDiff { get; }
```

``` c++
property Decimal TransSalePmtDiff {
    Decimal get ();
}
```

#### Property Value

Type: [System.Decimal](https://technet.microsoft.com/library/1k2e8atx\(v=ax.60\))  
Returns [Decimal](https://technet.microsoft.com/library/1k2e8atx\(v=ax.60\)).  

## See Also

#### Reference

[IRetailTransactionV1 Interface](iretailtransactionv1-interface-microsoft-dynamics-retail-pos-contracts-dataentity.md)

[Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity Namespace](microsoft-dynamics-retail-pos-contracts-dataentity-namespace.md)

