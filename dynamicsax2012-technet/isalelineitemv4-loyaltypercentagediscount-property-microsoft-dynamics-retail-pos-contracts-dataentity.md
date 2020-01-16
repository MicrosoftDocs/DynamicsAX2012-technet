---
title: ISaleLineItemV4.LoyaltyPercentageDiscount Property  (Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity)
TOCTitle: LoyaltyPercentageDiscount Property
ms:assetid: P:Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity.ISaleLineItemV4.LoyaltyPercentageDiscount
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.retail.pos.contracts.dataentity.isalelineitemv4.loyaltypercentagediscount(v=AX.60)
ms:contentKeyID: 62205589
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity.ISaleLineItemV4.LoyaltyPercentageDiscount
dev_langs:
- CSharp
- C++
- VB
---

# LoyaltyPercentageDiscount Property

The loyalty percentage discount given in this line

**Namespace:**  [Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity](microsoft-dynamics-retail-pos-contracts-dataentity-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Retail.Pos.Contracts (in Microsoft.Dynamics.Retail.Pos.Contracts.dll)

## Syntax

``` vb
'Declaration
Property LoyaltyPercentageDiscount As Decimal
    Get
    Set
'Usage
Dim instance As ISaleLineItemV4
Dim value As Decimal

value = instance.LoyaltyPercentageDiscount

instance.LoyaltyPercentageDiscount = value
```

``` csharp
decimal LoyaltyPercentageDiscount { get; set; }
```

``` c++
property Decimal LoyaltyPercentageDiscount {
    Decimal get ();
    void set (Decimal value);
}
```

#### Property Value

Type: [System.Decimal](https://technet.microsoft.com/library/1k2e8atx\(v=ax.60\))  
Returns [Decimal](https://technet.microsoft.com/library/1k2e8atx\(v=ax.60\)).  

## See Also

#### Reference

[ISaleLineItemV4 Interface](isalelineitemv4-interface-microsoft-dynamics-retail-pos-contracts-dataentity.md)

[Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity Namespace](microsoft-dynamics-retail-pos-contracts-dataentity-namespace.md)

