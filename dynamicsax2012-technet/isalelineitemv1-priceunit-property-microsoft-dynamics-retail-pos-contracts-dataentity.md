---
title: ISaleLineItemV1.PriceUnit Property  (Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity)
TOCTitle: PriceUnit Property
ms:assetid: P:Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity.ISaleLineItemV1.PriceUnit
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.retail.pos.contracts.dataentity.isalelineitemv1.priceunit(v=AX.60)
ms:contentKeyID: 49840965
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity.ISaleLineItemV1.PriceUnit
dev_langs:
- CSharp
- C++
- VB
---

# PriceUnit Property


[!INCLUDE[archive-banner](includes/archive-banner.md)]

If a price is given for a for more than one unit the price unit tells how many.

If the price if given for six units (priceUnit=6) as 100 EUR, then when 12 units are sold the price will be 200 EUR.

**Namespace:**  [Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity](microsoft-dynamics-retail-pos-contracts-dataentity-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Retail.Pos.Contracts (in Microsoft.Dynamics.Retail.Pos.Contracts.dll)

## Syntax

``` vb
'Declaration
Property PriceUnit As Decimal
    Get
    Set
'Usage
Dim instance As ISaleLineItemV1
Dim value As Decimal

value = instance.PriceUnit

instance.PriceUnit = value
```

``` csharp
decimal PriceUnit { get; set; }
```

``` c++
property Decimal PriceUnit {
    Decimal get ();
    void set (Decimal value);
}
```

#### Property Value

Type: [System.Decimal](https://technet.microsoft.com/library/1k2e8atx\(v=ax.60\))  
Returns [Decimal](https://technet.microsoft.com/library/1k2e8atx\(v=ax.60\)).  

## See Also

#### Reference

[ISaleLineItemV1 Interface](isalelineitemv1-interface-microsoft-dynamics-retail-pos-contracts-dataentity.md)

[Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity Namespace](microsoft-dynamics-retail-pos-contracts-dataentity-namespace.md)

