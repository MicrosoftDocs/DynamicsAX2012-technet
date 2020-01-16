---
title: LoyaltySchemeLineRedeem.ToRewardType Property  (Microsoft.Dynamics.Commerce.Runtime.DataModel)
TOCTitle: ToRewardType Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.DataModel.LoyaltySchemeLineRedeem.ToRewardType
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.datamodel.loyaltyschemelineredeem.torewardtype(v=AX.60)
ms:contentKeyID: 62203472
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataModel.LoyaltySchemeLineRedeem.ToRewardType
dev_langs:
- CSharp
- C++
- VB
---

# ToRewardType Property

Gets the loyalty reward type, e.g. Payment by amount, Payment by quantity.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataModel](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Entities (in Microsoft.Dynamics.Commerce.Runtime.Entities.dll)

## Syntax

``` vb
'Declaration
<IgnoreDataMemberAttribute> _
<ColumnAttribute("TOREWARDTYPE")> _
Public Property ToRewardType As LoyaltyRewardType
    Get
    Friend Set
'Usage
Dim instance As LoyaltySchemeLineRedeem
Dim value As LoyaltyRewardType

value = instance.ToRewardType
```

``` csharp
[IgnoreDataMemberAttribute]
[ColumnAttribute("TOREWARDTYPE")]
public LoyaltyRewardType ToRewardType { get; internal set; }
```

``` c++
[IgnoreDataMemberAttribute]
[ColumnAttribute(L"TOREWARDTYPE")]
public:
property LoyaltyRewardType ToRewardType {
    LoyaltyRewardType get ();
    internal: void set (LoyaltyRewardType value);
}
```

#### Property Value

Type: [Microsoft.Dynamics.Commerce.Runtime.DataModel.LoyaltyRewardType](loyaltyrewardtype-enumeration-microsoft-dynamics-commerce-runtime-datamodel.md)  
Returns [LoyaltyRewardType](loyaltyrewardtype-enumeration-microsoft-dynamics-commerce-runtime-datamodel.md).  

## See Also

#### Reference

[LoyaltySchemeLineRedeem Class](loyaltyschemelineredeem-class-microsoft-dynamics-commerce-runtime-datamodel.md)

[Microsoft.Dynamics.Commerce.Runtime.DataModel Namespace](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)

