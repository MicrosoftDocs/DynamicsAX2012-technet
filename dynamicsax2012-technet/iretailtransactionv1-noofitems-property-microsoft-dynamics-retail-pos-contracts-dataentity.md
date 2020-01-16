---
title: IRetailTransactionV1.NoOfItems Property  (Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity)
TOCTitle: NoOfItems Property
ms:assetid: P:Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity.IRetailTransactionV1.NoOfItems
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.retail.pos.contracts.dataentity.iretailtransactionv1.noofitems(v=AX.60)
ms:contentKeyID: 49831012
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity.IRetailTransactionV1.NoOfItems
dev_langs:
- CSharp
- C++
- VB
---

# NoOfItems Property

Number of items in the transaction - the total quantity.

**Namespace:**  [Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity](microsoft-dynamics-retail-pos-contracts-dataentity-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Retail.Pos.Contracts (in Microsoft.Dynamics.Retail.Pos.Contracts.dll)

## Syntax

``` vb
'Declaration
Property NoOfItems As Decimal
    Get
    Set
'Usage
Dim instance As IRetailTransactionV1
Dim value As Decimal

value = instance.NoOfItems

instance.NoOfItems = value
```

``` csharp
decimal NoOfItems { get; set; }
```

``` c++
property Decimal NoOfItems {
    Decimal get ();
    void set (Decimal value);
}
```

#### Property Value

Type: [System.Decimal](https://technet.microsoft.com/library/1k2e8atx\(v=ax.60\))  
Returns [Decimal](https://technet.microsoft.com/library/1k2e8atx\(v=ax.60\)).  

## See Also

#### Reference

[IRetailTransactionV1 Interface](iretailtransactionv1-interface-microsoft-dynamics-retail-pos-contracts-dataentity.md)

[Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity Namespace](microsoft-dynamics-retail-pos-contracts-dataentity-namespace.md)

