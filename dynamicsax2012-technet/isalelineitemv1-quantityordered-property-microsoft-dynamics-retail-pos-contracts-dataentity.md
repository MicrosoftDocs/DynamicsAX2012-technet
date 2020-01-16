---
title: ISaleLineItemV1.QuantityOrdered Property  (Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity)
TOCTitle: QuantityOrdered Property
ms:assetid: P:Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity.ISaleLineItemV1.QuantityOrdered
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.retail.pos.contracts.dataentity.isalelineitemv1.quantityordered(v=AX.60)
ms:contentKeyID: 49846011
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity.ISaleLineItemV1.QuantityOrdered
dev_langs:
- CSharp
- C++
- VB
---

# QuantityOrdered Property

Quantity of items ordered

**Namespace:**  [Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity](microsoft-dynamics-retail-pos-contracts-dataentity-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Retail.Pos.Contracts (in Microsoft.Dynamics.Retail.Pos.Contracts.dll)

## Syntax

``` vb
'Declaration
Property QuantityOrdered As Decimal
    Get
    Set
'Usage
Dim instance As ISaleLineItemV1
Dim value As Decimal

value = instance.QuantityOrdered

instance.QuantityOrdered = value
```

``` csharp
decimal QuantityOrdered { get; set; }
```

``` c++
property Decimal QuantityOrdered {
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

