---
title: LoyaltySchemeLineEarn.ToRewardPointAmountQuantity Property  (Microsoft.Dynamics.Commerce.Runtime.DataModel)
TOCTitle: ToRewardPointAmountQuantity Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.DataModel.LoyaltySchemeLineEarn.ToRewardPointAmountQuantity
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.datamodel.loyaltyschemelineearn.torewardpointamountquantity(v=AX.60)
ms:contentKeyID: 62206145
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataModel.LoyaltySchemeLineEarn.ToRewardPointAmountQuantity
dev_langs:
- CSharp
- C++
- VB
---

# ToRewardPointAmountQuantity Property

Gets the amount or the quantity of the reward point.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataModel](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Entities (in Microsoft.Dynamics.Commerce.Runtime.Entities.dll)

## Syntax

``` vb
'Declaration
<ColumnAttribute("TOREWARDPOINTAMOUNTQTY")> _
<IgnoreDataMemberAttribute> _
Public Property ToRewardPointAmountQuantity As Decimal
    Get
    Friend Set
'Usage
Dim instance As LoyaltySchemeLineEarn
Dim value As Decimal

value = instance.ToRewardPointAmountQuantity
```

``` csharp
[ColumnAttribute("TOREWARDPOINTAMOUNTQTY")]
[IgnoreDataMemberAttribute]
public decimal ToRewardPointAmountQuantity { get; internal set; }
```

``` c++
[ColumnAttribute(L"TOREWARDPOINTAMOUNTQTY")]
[IgnoreDataMemberAttribute]
public:
property Decimal ToRewardPointAmountQuantity {
    Decimal get ();
    internal: void set (Decimal value);
}
```

#### Property Value

Type: [System.Decimal](https://technet.microsoft.com/library/1k2e8atx\(v=ax.60\))  
Returns [Decimal](https://technet.microsoft.com/library/1k2e8atx\(v=ax.60\)).  

## See Also

#### Reference

[LoyaltySchemeLineEarn Class](loyaltyschemelineearn-class-microsoft-dynamics-commerce-runtime-datamodel.md)

[Microsoft.Dynamics.Commerce.Runtime.DataModel Namespace](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)

