---
title: LoyaltySchemeLineEarn.ToRewardPointType Property  (Microsoft.Dynamics.Commerce.Runtime.DataModel)
TOCTitle: ToRewardPointType Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.DataModel.LoyaltySchemeLineEarn.ToRewardPointType
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.datamodel.loyaltyschemelineearn.torewardpointtype(v=AX.60)
ms:contentKeyID: 62204361
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataModel.LoyaltySchemeLineEarn.ToRewardPointType
dev_langs:
- CSharp
- C++
- VB
---

# ToRewardPointType Property

Gets the reward point unit type.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataModel](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Entities (in Microsoft.Dynamics.Commerce.Runtime.Entities.dll)

## Syntax

``` vb
'Declaration
<ColumnAttribute("TOREWARDPOINTTYPE")> _
<IgnoreDataMemberAttribute> _
Public Property ToRewardPointType As LoyaltyRewardPointType
    Get
    Friend Set
'Usage
Dim instance As LoyaltySchemeLineEarn
Dim value As LoyaltyRewardPointType

value = instance.ToRewardPointType
```

``` csharp
[ColumnAttribute("TOREWARDPOINTTYPE")]
[IgnoreDataMemberAttribute]
public LoyaltyRewardPointType ToRewardPointType { get; internal set; }
```

``` c++
[ColumnAttribute(L"TOREWARDPOINTTYPE")]
[IgnoreDataMemberAttribute]
public:
property LoyaltyRewardPointType ToRewardPointType {
    LoyaltyRewardPointType get ();
    internal: void set (LoyaltyRewardPointType value);
}
```

#### Property Value

Type: [Microsoft.Dynamics.Commerce.Runtime.DataModel.LoyaltyRewardPointType](loyaltyrewardpointtype-enumeration-microsoft-dynamics-commerce-runtime-datamodel.md)  
Returns [LoyaltyRewardPointType](loyaltyrewardpointtype-enumeration-microsoft-dynamics-commerce-runtime-datamodel.md).  

## See Also

#### Reference

[LoyaltySchemeLineEarn Class](loyaltyschemelineearn-class-microsoft-dynamics-commerce-runtime-datamodel.md)

[Microsoft.Dynamics.Commerce.Runtime.DataModel Namespace](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)

