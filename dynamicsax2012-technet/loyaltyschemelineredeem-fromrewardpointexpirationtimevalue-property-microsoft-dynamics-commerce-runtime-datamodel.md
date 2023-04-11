---
title: LoyaltySchemeLineRedeem.FromRewardPointExpirationTimeValue Property  (Microsoft.Dynamics.Commerce.Runtime.DataModel)
TOCTitle: FromRewardPointExpirationTimeValue Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.DataModel.LoyaltySchemeLineRedeem.FromRewardPointExpirationTimeValue
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.datamodel.loyaltyschemelineredeem.fromrewardpointexpirationtimevalue(v=AX.60)
ms:contentKeyID: 65317101
author: tonyafehr
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataModel.LoyaltySchemeLineRedeem.FromRewardPointExpirationTimeValue
dev_langs:
- CSharp
- C++
- VB
---

# FromRewardPointExpirationTimeValue Property


[!INCLUDE[archive-banner](includes/archive-banner.md)]

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataModel](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Entities (in Microsoft.Dynamics.Commerce.Runtime.Entities.dll)

## Syntax

``` vb
'Declaration
<IgnoreDataMemberAttribute> _
<ColumnAttribute("FROMREWARDPOINTEXPIRATIONTIMEVALUE")> _
Public Property FromRewardPointExpirationTimeValue As Integer
    Get
    Friend Set
'Usage
Dim instance As LoyaltySchemeLineRedeem
Dim value As Integer

value = instance.FromRewardPointExpirationTimeValue
```

``` csharp
[IgnoreDataMemberAttribute]
[ColumnAttribute("FROMREWARDPOINTEXPIRATIONTIMEVALUE")]
public int FromRewardPointExpirationTimeValue { get; internal set; }
```

``` c++
[IgnoreDataMemberAttribute]
[ColumnAttribute(L"FROMREWARDPOINTEXPIRATIONTIMEVALUE")]
public:
property int FromRewardPointExpirationTimeValue {
    int get ();
    internal: void set (int value);
}
```

#### Property Value

Type: [System.Int32](https://technet.microsoft.com/library/td2s409d\(v=ax.60\))  

## See Also

#### Reference

[LoyaltySchemeLineRedeem Class](loyaltyschemelineredeem-class-microsoft-dynamics-commerce-runtime-datamodel.md)

[Microsoft.Dynamics.Commerce.Runtime.DataModel Namespace](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)

