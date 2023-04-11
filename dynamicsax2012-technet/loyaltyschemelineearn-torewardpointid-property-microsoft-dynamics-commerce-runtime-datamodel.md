---
title: LoyaltySchemeLineEarn.ToRewardPointId Property  (Microsoft.Dynamics.Commerce.Runtime.DataModel)
TOCTitle: ToRewardPointId Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.DataModel.LoyaltySchemeLineEarn.ToRewardPointId
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.datamodel.loyaltyschemelineearn.torewardpointid(v=AX.60)
ms:contentKeyID: 62204983
author: tonyafehr
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataModel.LoyaltySchemeLineEarn.ToRewardPointId
dev_langs:
- CSharp
- C++
- VB
---

# ToRewardPointId Property


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Gets the readable identifier of the earned reward point.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataModel](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Entities (in Microsoft.Dynamics.Commerce.Runtime.Entities.dll)

## Syntax

``` vb
'Declaration
<IgnoreDataMemberAttribute> _
<ColumnAttribute("TOREWARDPOINTID")> _
Public Property ToRewardPointId As String
    Get
    Friend Set
'Usage
Dim instance As LoyaltySchemeLineEarn
Dim value As String

value = instance.ToRewardPointId
```

``` csharp
[IgnoreDataMemberAttribute]
[ColumnAttribute("TOREWARDPOINTID")]
public string ToRewardPointId { get; internal set; }
```

``` c++
[IgnoreDataMemberAttribute]
[ColumnAttribute(L"TOREWARDPOINTID")]
public:
property String^ ToRewardPointId {
    String^ get ();
    internal: void set (String^ value);
}
```

#### Property Value

Type: [System.String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\))  
Returns [String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\)).  

## See Also

#### Reference

[LoyaltySchemeLineEarn Class](loyaltyschemelineearn-class-microsoft-dynamics-commerce-runtime-datamodel.md)

[Microsoft.Dynamics.Commerce.Runtime.DataModel Namespace](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)

