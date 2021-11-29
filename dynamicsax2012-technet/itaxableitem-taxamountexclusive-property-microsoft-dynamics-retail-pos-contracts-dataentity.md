---
title: ITaxableItem.TaxAmountExclusive Property  (Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity)
TOCTitle: TaxAmountExclusive Property
ms:assetid: P:Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity.ITaxableItem.TaxAmountExclusive
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.retail.pos.contracts.dataentity.itaxableitem.taxamountexclusive(v=AX.60)
ms:contentKeyID: 47128805
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity.ITaxableItem.TaxAmountExclusive
dev_langs:
- CSharp
- C++
- VB
---

# TaxAmountExclusive Property


[!INCLUDE[archive-banner](includes/archive-banner.md)]

The tax amount that comes from an exclusive tax code, which indicates that an item price does not include tax. For example, for an item that is priced at $11.00, a tax exclusive rate equaling 10% would result in a tax of $1.10 (.10\*11.00).

**Namespace:**  [Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity](microsoft-dynamics-retail-pos-contracts-dataentity-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Retail.Pos.Contracts (in Microsoft.Dynamics.Retail.Pos.Contracts.dll)

## Syntax

``` vb
'Declaration
ReadOnly Property TaxAmountExclusive As Decimal
    Get
'Usage
Dim instance As ITaxableItem
Dim value As Decimal

value = instance.TaxAmountExclusive
```

``` csharp
decimal TaxAmountExclusive { get; }
```

``` c++
property Decimal TaxAmountExclusive {
    Decimal get ();
}
```

#### Property Value

Type: [System.Decimal](https://technet.microsoft.com/library/1k2e8atx\(v=ax.60\))  
The [System.Decimal](https://technet.microsoft.com/library/1k2e8atx\(v=ax.60\)) value.  

## See Also

#### Reference

[ITaxableItem Interface](itaxableitem-interface-microsoft-dynamics-retail-pos-contracts-dataentity.md)

[Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity Namespace](microsoft-dynamics-retail-pos-contracts-dataentity-namespace.md)

