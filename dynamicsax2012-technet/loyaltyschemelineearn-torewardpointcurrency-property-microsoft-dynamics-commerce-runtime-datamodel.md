---
title: LoyaltySchemeLineEarn.ToRewardPointCurrency Property  (Microsoft.Dynamics.Commerce.Runtime.DataModel)
TOCTitle: ToRewardPointCurrency Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.DataModel.LoyaltySchemeLineEarn.ToRewardPointCurrency
ms:mtpsurl: https://technet.microsoft.com/en-us/library/microsoft.dynamics.commerce.runtime.datamodel.loyaltyschemelineearn.torewardpointcurrency(v=AX.60)
ms:contentKeyID: 62213364
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataModel.LoyaltySchemeLineEarn.ToRewardPointCurrency
dev_langs:
- CSharp
- C++
- VB
---

# ToRewardPointCurrency Property

Gets the currency of the reward point if the reward point is amount type.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataModel](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Entities (in Microsoft.Dynamics.Commerce.Runtime.Entities.dll)

## Syntax

``` vb
'Declaration
<ColumnAttribute("TOREWARDPOINTCURRENCY")> _
<IgnoreDataMemberAttribute> _
Public Property ToRewardPointCurrency As String
    Get
    Friend Set
'Usage
Dim instance As LoyaltySchemeLineEarn
Dim value As String

value = instance.ToRewardPointCurrency
```

``` csharp
[ColumnAttribute("TOREWARDPOINTCURRENCY")]
[IgnoreDataMemberAttribute]
public string ToRewardPointCurrency { get; internal set; }
```

``` c++
[ColumnAttribute(L"TOREWARDPOINTCURRENCY")]
[IgnoreDataMemberAttribute]
public:
property String^ ToRewardPointCurrency {
    String^ get ();
    internal: void set (String^ value);
}
```

#### Property Value

Type: [System.String](https://technet.microsoft.com/en-us/library/s1wwdcbf\(v=ax.60\))  
Returns [String](https://technet.microsoft.com/en-us/library/s1wwdcbf\(v=ax.60\)).  

## See Also

#### Reference

[LoyaltySchemeLineEarn Class](loyaltyschemelineearn-class-microsoft-dynamics-commerce-runtime-datamodel.md)

[Microsoft.Dynamics.Commerce.Runtime.DataModel Namespace](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)

