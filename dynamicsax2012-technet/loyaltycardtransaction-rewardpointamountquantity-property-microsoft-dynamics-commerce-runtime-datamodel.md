---
title: LoyaltyCardTransaction.RewardPointAmountQuantity Property  (Microsoft.Dynamics.Commerce.Runtime.DataModel)
TOCTitle: RewardPointAmountQuantity Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.DataModel.LoyaltyCardTransaction.RewardPointAmountQuantity
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.datamodel.loyaltycardtransaction.rewardpointamountquantity(v=AX.60)
ms:contentKeyID: 62212206
author: tonyafehr
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataModel.LoyaltyCardTransaction.RewardPointAmountQuantity
dev_langs:
- CSharp
- C++
- VB
---

# RewardPointAmountQuantity Property


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Gets the amount or the quantity of the reward point.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataModel](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Entities (in Microsoft.Dynamics.Commerce.Runtime.Entities.dll)

## Syntax

``` vb
'Declaration
<DataMemberAttribute> _
Public Property RewardPointAmountQuantity As Decimal
    Get
    Friend Set
'Usage
Dim instance As LoyaltyCardTransaction
Dim value As Decimal

value = instance.RewardPointAmountQuantity
```

``` csharp
[DataMemberAttribute]
public decimal RewardPointAmountQuantity { get; internal set; }
```

``` c++
[DataMemberAttribute]
public:
property Decimal RewardPointAmountQuantity {
    Decimal get ();
    internal: void set (Decimal value);
}
```

#### Property Value

Type: [System.Decimal](https://technet.microsoft.com/library/1k2e8atx\(v=ax.60\))  
Returns [Decimal](https://technet.microsoft.com/library/1k2e8atx\(v=ax.60\)).  

## See Also

#### Reference

[LoyaltyCardTransaction Class](loyaltycardtransaction-class-microsoft-dynamics-commerce-runtime-datamodel.md)

[Microsoft.Dynamics.Commerce.Runtime.DataModel Namespace](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)

