---
title: ITaxableItem.TaxAmount Property  (Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity)
TOCTitle: TaxAmount Property
ms:assetid: P:Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity.ITaxableItem.TaxAmount
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.retail.pos.contracts.dataentity.itaxableitem.taxamount(v=AX.60)
ms:contentKeyID: 47129315
author: tonyafehr
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity.ITaxableItem.TaxAmount
dev_langs:
- CSharp
- C++
- VB
---

# TaxAmount Property


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Gets the total tax amount, which is the accumulation of TaxAmountInclusive + TaxAmountExclusive.

**Namespace:**  [Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity](microsoft-dynamics-retail-pos-contracts-dataentity-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Retail.Pos.Contracts (in Microsoft.Dynamics.Retail.Pos.Contracts.dll)

## Syntax

``` vb
'Declaration
ReadOnly Property TaxAmount As Decimal
    Get
'Usage
Dim instance As ITaxableItem
Dim value As Decimal

value = instance.TaxAmount
```

``` csharp
decimal TaxAmount { get; }
```

``` c++
property Decimal TaxAmount {
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

