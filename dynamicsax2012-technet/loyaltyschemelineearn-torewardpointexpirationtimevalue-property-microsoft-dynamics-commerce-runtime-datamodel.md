---
title: LoyaltySchemeLineEarn.ToRewardPointExpirationTimeValue Property  (Microsoft.Dynamics.Commerce.Runtime.DataModel)
TOCTitle: ToRewardPointExpirationTimeValue Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.DataModel.LoyaltySchemeLineEarn.ToRewardPointExpirationTimeValue
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.datamodel.loyaltyschemelineearn.torewardpointexpirationtimevalue(v=AX.60)
ms:contentKeyID: 62212735
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataModel.LoyaltySchemeLineEarn.ToRewardPointExpirationTimeValue
dev_langs:
- CSharp
- C++
- VB
---

# ToRewardPointExpirationTimeValue Property


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Gets expiration time value of the reward point.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataModel](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Entities (in Microsoft.Dynamics.Commerce.Runtime.Entities.dll)

## Syntax

``` vb
'Declaration
<IgnoreDataMemberAttribute> _
<ColumnAttribute("TOREWARDPOINTEXPIRATIONTIMEVALUE")> _
Public Property ToRewardPointExpirationTimeValue As Integer
    Get
    Friend Set
'Usage
Dim instance As LoyaltySchemeLineEarn
Dim value As Integer

value = instance.ToRewardPointExpirationTimeValue
```

``` csharp
[IgnoreDataMemberAttribute]
[ColumnAttribute("TOREWARDPOINTEXPIRATIONTIMEVALUE")]
public int ToRewardPointExpirationTimeValue { get; internal set; }
```

``` c++
[IgnoreDataMemberAttribute]
[ColumnAttribute(L"TOREWARDPOINTEXPIRATIONTIMEVALUE")]
public:
property int ToRewardPointExpirationTimeValue {
    int get ();
    internal: void set (int value);
}
```

#### Property Value

Type: [System.Int32](https://technet.microsoft.com/library/td2s409d\(v=ax.60\))  
Returns [Int32](https://technet.microsoft.com/library/td2s409d\(v=ax.60\)).  

## See Also

#### Reference

[LoyaltySchemeLineEarn Class](loyaltyschemelineearn-class-microsoft-dynamics-commerce-runtime-datamodel.md)

[Microsoft.Dynamics.Commerce.Runtime.DataModel Namespace](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)

