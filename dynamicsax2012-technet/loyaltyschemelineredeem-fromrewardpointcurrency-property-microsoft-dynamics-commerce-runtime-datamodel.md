---
title: LoyaltySchemeLineRedeem.FromRewardPointCurrency Property  (Microsoft.Dynamics.Commerce.Runtime.DataModel)
TOCTitle: FromRewardPointCurrency Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.DataModel.LoyaltySchemeLineRedeem.FromRewardPointCurrency
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.datamodel.loyaltyschemelineredeem.fromrewardpointcurrency(v=AX.60)
ms:contentKeyID: 62211605
author: tonyafehr
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataModel.LoyaltySchemeLineRedeem.FromRewardPointCurrency
dev_langs:
- CSharp
- C++
- VB
---

# FromRewardPointCurrency Property


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Gets the currency of the reward point if the reward point is amount type.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataModel](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Entities (in Microsoft.Dynamics.Commerce.Runtime.Entities.dll)

## Syntax

``` vb
'Declaration
<IgnoreDataMemberAttribute> _
<ColumnAttribute("FROMREWARDPOINTCURRENCY")> _
Public Property FromRewardPointCurrency As String
    Get
    Friend Set
'Usage
Dim instance As LoyaltySchemeLineRedeem
Dim value As String

value = instance.FromRewardPointCurrency
```

``` csharp
[IgnoreDataMemberAttribute]
[ColumnAttribute("FROMREWARDPOINTCURRENCY")]
public string FromRewardPointCurrency { get; internal set; }
```

``` c++
[IgnoreDataMemberAttribute]
[ColumnAttribute(L"FROMREWARDPOINTCURRENCY")]
public:
property String^ FromRewardPointCurrency {
    String^ get ();
    internal: void set (String^ value);
}
```

#### Property Value

Type: [System.String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\))  
Returns [String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\)).  

## See Also

#### Reference

[LoyaltySchemeLineRedeem Class](loyaltyschemelineredeem-class-microsoft-dynamics-commerce-runtime-datamodel.md)

[Microsoft.Dynamics.Commerce.Runtime.DataModel Namespace](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)

