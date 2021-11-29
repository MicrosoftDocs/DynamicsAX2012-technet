---
title: LoyaltyRewardPoint.ExpirationTimeUnit Property  (Microsoft.Dynamics.Commerce.Runtime.DataModel)
TOCTitle: ExpirationTimeUnit Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.DataModel.LoyaltyRewardPoint.ExpirationTimeUnit
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.datamodel.loyaltyrewardpoint.expirationtimeunit(v=AX.60)
ms:contentKeyID: 62214491
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataModel.LoyaltyRewardPoint.ExpirationTimeUnit
dev_langs:
- CSharp
- C++
- VB
---

# ExpirationTimeUnit Property


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Gets expiration time unit of the reward point.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataModel](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Entities (in Microsoft.Dynamics.Commerce.Runtime.Entities.dll)

## Syntax

``` vb
'Declaration
<IgnoreDataMemberAttribute> _
<ColumnAttribute("EXPIRATIONTIMEUNIT")> _
Public Property ExpirationTimeUnit As DayMonthYear
    Get
    Friend Set
'Usage
Dim instance As LoyaltyRewardPoint
Dim value As DayMonthYear

value = instance.ExpirationTimeUnit
```

``` csharp
[IgnoreDataMemberAttribute]
[ColumnAttribute("EXPIRATIONTIMEUNIT")]
public DayMonthYear ExpirationTimeUnit { get; internal set; }
```

``` c++
[IgnoreDataMemberAttribute]
[ColumnAttribute(L"EXPIRATIONTIMEUNIT")]
public:
property DayMonthYear ExpirationTimeUnit {
    DayMonthYear get ();
    internal: void set (DayMonthYear value);
}
```

#### Property Value

Type: [Microsoft.Dynamics.Commerce.Runtime.DataModel.DayMonthYear](daymonthyear-enumeration-microsoft-dynamics-commerce-runtime-datamodel.md)  
Returns [DayMonthYear](daymonthyear-enumeration-microsoft-dynamics-commerce-runtime-datamodel.md).  

## See Also

#### Reference

[LoyaltyRewardPoint Class](loyaltyrewardpoint-class-microsoft-dynamics-commerce-runtime-datamodel.md)

[Microsoft.Dynamics.Commerce.Runtime.DataModel Namespace](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)

