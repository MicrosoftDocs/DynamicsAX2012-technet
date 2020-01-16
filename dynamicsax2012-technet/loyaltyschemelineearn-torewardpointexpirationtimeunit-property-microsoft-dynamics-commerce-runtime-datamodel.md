---
title: LoyaltySchemeLineEarn.ToRewardPointExpirationTimeUnit Property  (Microsoft.Dynamics.Commerce.Runtime.DataModel)
TOCTitle: ToRewardPointExpirationTimeUnit Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.DataModel.LoyaltySchemeLineEarn.ToRewardPointExpirationTimeUnit
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.datamodel.loyaltyschemelineearn.torewardpointexpirationtimeunit(v=AX.60)
ms:contentKeyID: 62211230
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataModel.LoyaltySchemeLineEarn.ToRewardPointExpirationTimeUnit
dev_langs:
- CSharp
- C++
- VB
---

# ToRewardPointExpirationTimeUnit Property

Gets expiration time unit of the reward point.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataModel](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Entities (in Microsoft.Dynamics.Commerce.Runtime.Entities.dll)

## Syntax

``` vb
'Declaration
<ColumnAttribute("TOREWARDPOINTEXPIRATIONTIMEUNIT")> _
<IgnoreDataMemberAttribute> _
Public Property ToRewardPointExpirationTimeUnit As DayMonthYear
    Get
    Friend Set
'Usage
Dim instance As LoyaltySchemeLineEarn
Dim value As DayMonthYear

value = instance.ToRewardPointExpirationTimeUnit
```

``` csharp
[ColumnAttribute("TOREWARDPOINTEXPIRATIONTIMEUNIT")]
[IgnoreDataMemberAttribute]
public DayMonthYear ToRewardPointExpirationTimeUnit { get; internal set; }
```

``` c++
[ColumnAttribute(L"TOREWARDPOINTEXPIRATIONTIMEUNIT")]
[IgnoreDataMemberAttribute]
public:
property DayMonthYear ToRewardPointExpirationTimeUnit {
    DayMonthYear get ();
    internal: void set (DayMonthYear value);
}
```

#### Property Value

Type: [Microsoft.Dynamics.Commerce.Runtime.DataModel.DayMonthYear](daymonthyear-enumeration-microsoft-dynamics-commerce-runtime-datamodel.md)  
Returns [DayMonthYear](daymonthyear-enumeration-microsoft-dynamics-commerce-runtime-datamodel.md).  

## See Also

#### Reference

[LoyaltySchemeLineEarn Class](loyaltyschemelineearn-class-microsoft-dynamics-commerce-runtime-datamodel.md)

[Microsoft.Dynamics.Commerce.Runtime.DataModel Namespace](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)

