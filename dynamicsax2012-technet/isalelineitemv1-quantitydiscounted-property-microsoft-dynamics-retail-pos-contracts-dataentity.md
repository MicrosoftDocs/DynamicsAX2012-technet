---
title: ISaleLineItemV1.QuantityDiscounted Property  (Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity)
TOCTitle: QuantityDiscounted Property
ms:assetid: P:Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity.ISaleLineItemV1.QuantityDiscounted
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.retail.pos.contracts.dataentity.isalelineitemv1.quantitydiscounted(v=AX.60)
ms:contentKeyID: 49839913
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity.ISaleLineItemV1.QuantityDiscounted
dev_langs:
- CSharp
- C++
- VB
---

# QuantityDiscounted Property


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Used in calculation of the periodic discount. Keeps track of how many items have been discounted.

**Namespace:**  [Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity](microsoft-dynamics-retail-pos-contracts-dataentity-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Retail.Pos.Contracts (in Microsoft.Dynamics.Retail.Pos.Contracts.dll)

## Syntax

``` vb
'Declaration
Property QuantityDiscounted As Decimal
    Get
    Set
'Usage
Dim instance As ISaleLineItemV1
Dim value As Decimal

value = instance.QuantityDiscounted

instance.QuantityDiscounted = value
```

``` csharp
decimal QuantityDiscounted { get; set; }
```

``` c++
property Decimal QuantityDiscounted {
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

