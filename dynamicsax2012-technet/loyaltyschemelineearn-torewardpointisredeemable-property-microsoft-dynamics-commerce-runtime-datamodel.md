---
title: LoyaltySchemeLineEarn.ToRewardPointIsRedeemable Property  (Microsoft.Dynamics.Commerce.Runtime.DataModel)
TOCTitle: ToRewardPointIsRedeemable Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.DataModel.LoyaltySchemeLineEarn.ToRewardPointIsRedeemable
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.datamodel.loyaltyschemelineearn.torewardpointisredeemable(v=AX.60)
ms:contentKeyID: 62213950
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataModel.LoyaltySchemeLineEarn.ToRewardPointIsRedeemable
dev_langs:
- CSharp
- C++
- VB
---

# ToRewardPointIsRedeemable Property


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Gets a value indicating whether the reward point is redeemable.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataModel](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Entities (in Microsoft.Dynamics.Commerce.Runtime.Entities.dll)

## Syntax

``` vb
'Declaration
<IgnoreDataMemberAttribute> _
<ColumnAttribute("TOREWARDPOINTREDEEMABLE")> _
Public Property ToRewardPointIsRedeemable As Boolean
    Get
    Friend Set
'Usage
Dim instance As LoyaltySchemeLineEarn
Dim value As Boolean

value = instance.ToRewardPointIsRedeemable
```

``` csharp
[IgnoreDataMemberAttribute]
[ColumnAttribute("TOREWARDPOINTREDEEMABLE")]
public bool ToRewardPointIsRedeemable { get; internal set; }
```

``` c++
[IgnoreDataMemberAttribute]
[ColumnAttribute(L"TOREWARDPOINTREDEEMABLE")]
public:
property bool ToRewardPointIsRedeemable {
    bool get ();
    internal: void set (bool value);
}
```

#### Property Value

Type: [System.Boolean](https://technet.microsoft.com/library/a28wyd50\(v=ax.60\))  
Returns [Boolean](https://technet.microsoft.com/library/a28wyd50\(v=ax.60\)).  

## See Also

#### Reference

[LoyaltySchemeLineEarn Class](loyaltyschemelineearn-class-microsoft-dynamics-commerce-runtime-datamodel.md)

[Microsoft.Dynamics.Commerce.Runtime.DataModel Namespace](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)

