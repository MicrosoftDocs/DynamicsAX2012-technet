---
title: LoyaltySchemeLineRedeem.FromRewardPointId Property  (Microsoft.Dynamics.Commerce.Runtime.DataModel)
TOCTitle: FromRewardPointId Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.DataModel.LoyaltySchemeLineRedeem.FromRewardPointId
ms:mtpsurl: https://technet.microsoft.com/en-us/library/microsoft.dynamics.commerce.runtime.datamodel.loyaltyschemelineredeem.fromrewardpointid(v=AX.60)
ms:contentKeyID: 62211344
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataModel.LoyaltySchemeLineRedeem.FromRewardPointId
dev_langs:
- CSharp
- C++
- VB
---

# FromRewardPointId Property

Gets the readable identifier of the loyalty reward point.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataModel](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Entities (in Microsoft.Dynamics.Commerce.Runtime.Entities.dll)

## Syntax

``` vb
'Declaration
<ColumnAttribute("FROMREWARDPOINTID")> _
<IgnoreDataMemberAttribute> _
Public Property FromRewardPointId As String
    Get
    Friend Set
'Usage
Dim instance As LoyaltySchemeLineRedeem
Dim value As String

value = instance.FromRewardPointId
```

``` csharp
[ColumnAttribute("FROMREWARDPOINTID")]
[IgnoreDataMemberAttribute]
public string FromRewardPointId { get; internal set; }
```

``` c++
[ColumnAttribute(L"FROMREWARDPOINTID")]
[IgnoreDataMemberAttribute]
public:
property String^ FromRewardPointId {
    String^ get ();
    internal: void set (String^ value);
}
```

#### Property Value

Type: [System.String](https://technet.microsoft.com/en-us/library/s1wwdcbf\(v=ax.60\))  
Returns [String](https://technet.microsoft.com/en-us/library/s1wwdcbf\(v=ax.60\)).  

## See Also

#### Reference

[LoyaltySchemeLineRedeem Class](loyaltyschemelineredeem-class-microsoft-dynamics-commerce-runtime-datamodel.md)

[Microsoft.Dynamics.Commerce.Runtime.DataModel Namespace](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)

