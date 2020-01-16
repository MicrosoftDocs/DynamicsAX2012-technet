---
title: ITaxableItem.GrossAmount Property  (Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity)
TOCTitle: GrossAmount Property
ms:assetid: P:Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity.ITaxableItem.GrossAmount
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.retail.pos.contracts.dataentity.itaxableitem.grossamount(v=AX.60)
ms:contentKeyID: 47128595
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity.ITaxableItem.GrossAmount
dev_langs:
- CSharp
- C++
- VB
---

# GrossAmount Property

Gets or sets the gross amount.

**Namespace:**  [Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity](microsoft-dynamics-retail-pos-contracts-dataentity-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Retail.Pos.Contracts (in Microsoft.Dynamics.Retail.Pos.Contracts.dll)

## Syntax

``` vb
'Declaration
Property GrossAmount As Decimal
    Get
    Set
'Usage
Dim instance As ITaxableItem
Dim value As Decimal

value = instance.GrossAmount

instance.GrossAmount = value
```

``` csharp
decimal GrossAmount { get; set; }
```

``` c++
property Decimal GrossAmount {
    Decimal get ();
    void set (Decimal value);
}
```

#### Property Value

Type: [System.Decimal](https://technet.microsoft.com/library/1k2e8atx\(v=ax.60\))  
The gross amount.  

## See Also

#### Reference

[ITaxableItem Interface](itaxableitem-interface-microsoft-dynamics-retail-pos-contracts-dataentity.md)

[Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity Namespace](microsoft-dynamics-retail-pos-contracts-dataentity-namespace.md)

