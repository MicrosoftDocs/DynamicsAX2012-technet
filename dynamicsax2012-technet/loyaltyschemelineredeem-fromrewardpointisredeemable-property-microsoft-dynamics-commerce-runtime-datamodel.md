---
title: LoyaltySchemeLineRedeem.FromRewardPointIsRedeemable Property  (Microsoft.Dynamics.Commerce.Runtime.DataModel)
TOCTitle: FromRewardPointIsRedeemable Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.DataModel.LoyaltySchemeLineRedeem.FromRewardPointIsRedeemable
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.datamodel.loyaltyschemelineredeem.fromrewardpointisredeemable(v=AX.60)
ms:contentKeyID: 62206069
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataModel.LoyaltySchemeLineRedeem.FromRewardPointIsRedeemable
dev_langs:
- CSharp
- C++
- VB
---

# FromRewardPointIsRedeemable Property

Gets a value indicating whether the reward point is redeemable.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataModel](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Entities (in Microsoft.Dynamics.Commerce.Runtime.Entities.dll)

## Syntax

``` vb
'Declaration
<ColumnAttribute("FROMREWARDPOINTREDEEMABLE")> _
<IgnoreDataMemberAttribute> _
Public Property FromRewardPointIsRedeemable As Boolean
    Get
    Friend Set
'Usage
Dim instance As LoyaltySchemeLineRedeem
Dim value As Boolean

value = instance.FromRewardPointIsRedeemable
```

``` csharp
[ColumnAttribute("FROMREWARDPOINTREDEEMABLE")]
[IgnoreDataMemberAttribute]
public bool FromRewardPointIsRedeemable { get; internal set; }
```

``` c++
[ColumnAttribute(L"FROMREWARDPOINTREDEEMABLE")]
[IgnoreDataMemberAttribute]
public:
property bool FromRewardPointIsRedeemable {
    bool get ();
    internal: void set (bool value);
}
```

#### Property Value

Type: [System.Boolean](https://technet.microsoft.com/library/a28wyd50\(v=ax.60\))  
Returns [Boolean](https://technet.microsoft.com/library/a28wyd50\(v=ax.60\)).  

## See Also

#### Reference

[LoyaltySchemeLineRedeem Class](loyaltyschemelineredeem-class-microsoft-dynamics-commerce-runtime-datamodel.md)

[Microsoft.Dynamics.Commerce.Runtime.DataModel Namespace](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)

