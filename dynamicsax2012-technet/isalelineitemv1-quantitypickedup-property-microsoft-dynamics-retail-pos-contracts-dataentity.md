---
title: ISaleLineItemV1.QuantityPickedUp Property  (Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity)
TOCTitle: QuantityPickedUp Property
ms:assetid: P:Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity.ISaleLineItemV1.QuantityPickedUp
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.retail.pos.contracts.dataentity.isalelineitemv1.quantitypickedup(v=AX.60)
ms:contentKeyID: 49855590
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity.ISaleLineItemV1.QuantityPickedUp
dev_langs:
- CSharp
- C++
- VB
---

# QuantityPickedUp Property


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Number of items picked up from order

**Namespace:**  [Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity](microsoft-dynamics-retail-pos-contracts-dataentity-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Retail.Pos.Contracts (in Microsoft.Dynamics.Retail.Pos.Contracts.dll)

## Syntax

``` vb
'Declaration
Property QuantityPickedUp As Decimal
    Get
    Set
'Usage
Dim instance As ISaleLineItemV1
Dim value As Decimal

value = instance.QuantityPickedUp

instance.QuantityPickedUp = value
```

``` csharp
decimal QuantityPickedUp { get; set; }
```

``` c++
property Decimal QuantityPickedUp {
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

