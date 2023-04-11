---
title: ITaxableItem.TaxAmountExemptInclusive Property  (Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity)
TOCTitle: TaxAmountExemptInclusive Property
ms:assetid: P:Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity.ITaxableItem.TaxAmountExemptInclusive
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.retail.pos.contracts.dataentity.itaxableitem.taxamountexemptinclusive(v=AX.60)
ms:contentKeyID: 47128655
author: tonyafehr
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity.ITaxableItem.TaxAmountExemptInclusive
dev_langs:
- CSharp
- C++
- VB
---

# TaxAmountExemptInclusive Property


[!INCLUDE[archive-banner](includes/archive-banner.md)]

The tax amount coming from inclusive tax codes that is exempt for a particular transaction. This can occur if the customer is a non-taxed organization.

**Namespace:**  [Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity](microsoft-dynamics-retail-pos-contracts-dataentity-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Retail.Pos.Contracts (in Microsoft.Dynamics.Retail.Pos.Contracts.dll)

## Syntax

``` vb
'Declaration
ReadOnly Property TaxAmountExemptInclusive As Decimal
    Get
'Usage
Dim instance As ITaxableItem
Dim value As Decimal

value = instance.TaxAmountExemptInclusive
```

``` csharp
decimal TaxAmountExemptInclusive { get; }
```

``` c++
property Decimal TaxAmountExemptInclusive {
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

