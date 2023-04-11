---
title: ITaxableItem.TaxAmountInclusive Property  (Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity)
TOCTitle: TaxAmountInclusive Property
ms:assetid: P:Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity.ITaxableItem.TaxAmountInclusive
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.retail.pos.contracts.dataentity.itaxableitem.taxamountinclusive(v=AX.60)
ms:contentKeyID: 47128864
author: tonyafehr
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity.ITaxableItem.TaxAmountInclusive
dev_langs:
- CSharp
- C++
- VB
---

# TaxAmountInclusive Property


[!INCLUDE[archive-banner](includes/archive-banner.md)]

The tax amount coming from inclusive tax codes, which indicates that an item price includes sales tax. For example, for an item that is priced at $11.00, a tax inclusive rate equaling 10% would indicate a tax of 1.00 added to a base price of 10.00.

**Namespace:**  [Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity](microsoft-dynamics-retail-pos-contracts-dataentity-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Retail.Pos.Contracts (in Microsoft.Dynamics.Retail.Pos.Contracts.dll)

## Syntax

``` vb
'Declaration
ReadOnly Property TaxAmountInclusive As Decimal
    Get
'Usage
Dim instance As ITaxableItem
Dim value As Decimal

value = instance.TaxAmountInclusive
```

``` csharp
decimal TaxAmountInclusive { get; }
```

``` c++
property Decimal TaxAmountInclusive {
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

