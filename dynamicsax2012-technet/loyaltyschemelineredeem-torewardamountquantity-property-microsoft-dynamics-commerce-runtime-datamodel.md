---
title: LoyaltySchemeLineRedeem.ToRewardAmountQuantity Property  (Microsoft.Dynamics.Commerce.Runtime.DataModel)
TOCTitle: ToRewardAmountQuantity Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.DataModel.LoyaltySchemeLineRedeem.ToRewardAmountQuantity
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.datamodel.loyaltyschemelineredeem.torewardamountquantity(v=AX.60)
ms:contentKeyID: 62211231
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataModel.LoyaltySchemeLineRedeem.ToRewardAmountQuantity
dev_langs:
- CSharp
- C++
- VB
---

# ToRewardAmountQuantity Property

Gets or sets the amount or the quantity of the reward.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataModel](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Entities (in Microsoft.Dynamics.Commerce.Runtime.Entities.dll)

## Syntax

``` vb
'Declaration
<IgnoreDataMemberAttribute> _
<ColumnAttribute("TOREWARDAMOUNTQTY")> _
Public Property ToRewardAmountQuantity As Decimal
    Get
    Set
'Usage
Dim instance As LoyaltySchemeLineRedeem
Dim value As Decimal

value = instance.ToRewardAmountQuantity

instance.ToRewardAmountQuantity = value
```

``` csharp
[IgnoreDataMemberAttribute]
[ColumnAttribute("TOREWARDAMOUNTQTY")]
public decimal ToRewardAmountQuantity { get; set; }
```

``` c++
[IgnoreDataMemberAttribute]
[ColumnAttribute(L"TOREWARDAMOUNTQTY")]
public:
property Decimal ToRewardAmountQuantity {
    Decimal get ();
    void set (Decimal value);
}
```

#### Property Value

Type: [System.Decimal](https://technet.microsoft.com/library/1k2e8atx\(v=ax.60\))  
Returns [Decimal](https://technet.microsoft.com/library/1k2e8atx\(v=ax.60\)).  

## See Also

#### Reference

[LoyaltySchemeLineRedeem Class](loyaltyschemelineredeem-class-microsoft-dynamics-commerce-runtime-datamodel.md)

[Microsoft.Dynamics.Commerce.Runtime.DataModel Namespace](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)

