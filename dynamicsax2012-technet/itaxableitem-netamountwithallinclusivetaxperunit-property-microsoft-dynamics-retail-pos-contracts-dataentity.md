---
title: ITaxableItem.NetAmountWithAllInclusiveTaxPerUnit Property  (Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity)
TOCTitle: NetAmountWithAllInclusiveTaxPerUnit Property
ms:assetid: P:Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity.ITaxableItem.NetAmountWithAllInclusiveTaxPerUnit
ms:mtpsurl: https://technet.microsoft.com/en-us/library/microsoft.dynamics.retail.pos.contracts.dataentity.itaxableitem.netamountwithallinclusivetaxperunit(v=AX.60)
ms:contentKeyID: 47128015
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity.ITaxableItem.NetAmountWithAllInclusiveTaxPerUnit
dev_langs:
- CSharp
- C++
- VB
---

# NetAmountWithAllInclusiveTaxPerUnit Property

Gets the net amount per unit with all inclusive taxes (even non-exempt).

**Namespace:**  [Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity](microsoft-dynamics-retail-pos-contracts-dataentity-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Retail.Pos.Contracts (in Microsoft.Dynamics.Retail.Pos.Contracts.dll)

## Syntax

``` vb
'Declaration
ReadOnly Property NetAmountWithAllInclusiveTaxPerUnit As Decimal
    Get
'Usage
Dim instance As ITaxableItem
Dim value As Decimal

value = instance.NetAmountWithAllInclusiveTaxPerUnit
```

``` csharp
decimal NetAmountWithAllInclusiveTaxPerUnit { get; }
```

``` c++
property Decimal NetAmountWithAllInclusiveTaxPerUnit {
    Decimal get ();
}
```

#### Property Value

Type: [System.Decimal](https://technet.microsoft.com/en-us/library/1k2e8atx\(v=ax.60\))  
The [System.Decimal](https://technet.microsoft.com/en-us/library/1k2e8atx\(v=ax.60\)) value.  

## See Also

#### Reference

[ITaxableItem Interface](itaxableitem-interface-microsoft-dynamics-retail-pos-contracts-dataentity.md)

[Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity Namespace](microsoft-dynamics-retail-pos-contracts-dataentity-namespace.md)

