---
title: LoyaltySchemeLineRedeem.FromRewardPointType Property  (Microsoft.Dynamics.Commerce.Runtime.DataModel)
TOCTitle: FromRewardPointType Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.DataModel.LoyaltySchemeLineRedeem.FromRewardPointType
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.datamodel.loyaltyschemelineredeem.fromrewardpointtype(v=AX.60)
ms:contentKeyID: 62213898
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataModel.LoyaltySchemeLineRedeem.FromRewardPointType
dev_langs:
- CSharp
- C++
- VB
---

# FromRewardPointType Property

Gets the reward point unit type.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataModel](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Entities (in Microsoft.Dynamics.Commerce.Runtime.Entities.dll)

## Syntax

``` vb
'Declaration
<IgnoreDataMemberAttribute> _
<ColumnAttribute("FROMREWARDPOINTTYPE")> _
Public Property FromRewardPointType As LoyaltyRewardPointType
    Get
    Friend Set
'Usage
Dim instance As LoyaltySchemeLineRedeem
Dim value As LoyaltyRewardPointType

value = instance.FromRewardPointType
```

``` csharp
[IgnoreDataMemberAttribute]
[ColumnAttribute("FROMREWARDPOINTTYPE")]
public LoyaltyRewardPointType FromRewardPointType { get; internal set; }
```

``` c++
[IgnoreDataMemberAttribute]
[ColumnAttribute(L"FROMREWARDPOINTTYPE")]
public:
property LoyaltyRewardPointType FromRewardPointType {
    LoyaltyRewardPointType get ();
    internal: void set (LoyaltyRewardPointType value);
}
```

#### Property Value

Type: [Microsoft.Dynamics.Commerce.Runtime.DataModel.LoyaltyRewardPointType](loyaltyrewardpointtype-enumeration-microsoft-dynamics-commerce-runtime-datamodel.md)  
Returns [LoyaltyRewardPointType](loyaltyrewardpointtype-enumeration-microsoft-dynamics-commerce-runtime-datamodel.md).  

## See Also

#### Reference

[LoyaltySchemeLineRedeem Class](loyaltyschemelineredeem-class-microsoft-dynamics-commerce-runtime-datamodel.md)

[Microsoft.Dynamics.Commerce.Runtime.DataModel Namespace](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)

