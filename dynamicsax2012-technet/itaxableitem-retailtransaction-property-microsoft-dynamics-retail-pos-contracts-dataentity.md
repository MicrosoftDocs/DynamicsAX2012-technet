---
title: ITaxableItem.RetailTransaction Property  (Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity)
TOCTitle: RetailTransaction Property
ms:assetid: P:Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity.ITaxableItem.RetailTransaction
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.retail.pos.contracts.dataentity.itaxableitem.retailtransaction(v=AX.60)
ms:contentKeyID: 47129178
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity.ITaxableItem.RetailTransaction
dev_langs:
- CSharp
- C++
- VB
---

# RetailTransaction Property

Gets or sets the transaction.

**Namespace:**  [Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity](microsoft-dynamics-retail-pos-contracts-dataentity-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Retail.Pos.Contracts (in Microsoft.Dynamics.Retail.Pos.Contracts.dll)

## Syntax

``` vb
'Declaration
ReadOnly Property RetailTransaction As IRetailTransaction
    Get
'Usage
Dim instance As ITaxableItem
Dim value As IRetailTransaction

value = instance.RetailTransaction
```

``` csharp
IRetailTransaction RetailTransaction { get; }
```

``` c++
property IRetailTransaction^ RetailTransaction {
    IRetailTransaction^ get ();
}
```

#### Property Value

Type: [Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity.IRetailTransaction](iretailtransaction-interface-microsoft-dynamics-retail-pos-contracts-dataentity.md)  
The retail transaction.  

## See Also

#### Reference

[ITaxableItem Interface](itaxableitem-interface-microsoft-dynamics-retail-pos-contracts-dataentity.md)

[Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity Namespace](microsoft-dynamics-retail-pos-contracts-dataentity-namespace.md)

