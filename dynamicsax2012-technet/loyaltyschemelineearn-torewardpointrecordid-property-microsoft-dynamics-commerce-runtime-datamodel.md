---
title: LoyaltySchemeLineEarn.ToRewardPointRecordId Property  (Microsoft.Dynamics.Commerce.Runtime.DataModel)
TOCTitle: ToRewardPointRecordId Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.DataModel.LoyaltySchemeLineEarn.ToRewardPointRecordId
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.datamodel.loyaltyschemelineearn.torewardpointrecordid(v=AX.60)
ms:contentKeyID: 62204196
author: tonyafehr
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataModel.LoyaltySchemeLineEarn.ToRewardPointRecordId
dev_langs:
- CSharp
- C++
- VB
---

# ToRewardPointRecordId Property


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Gets the record identifier of the earned reward point.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataModel](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Entities (in Microsoft.Dynamics.Commerce.Runtime.Entities.dll)

## Syntax

``` vb
'Declaration
<ColumnAttribute("TOREWARDPOINT")> _
<IgnoreDataMemberAttribute> _
Public Property ToRewardPointRecordId As Long
    Get
    Friend Set
'Usage
Dim instance As LoyaltySchemeLineEarn
Dim value As Long

value = instance.ToRewardPointRecordId
```

``` csharp
[ColumnAttribute("TOREWARDPOINT")]
[IgnoreDataMemberAttribute]
public long ToRewardPointRecordId { get; internal set; }
```

``` c++
[ColumnAttribute(L"TOREWARDPOINT")]
[IgnoreDataMemberAttribute]
public:
property long long ToRewardPointRecordId {
    long long get ();
    internal: void set (long long value);
}
```

#### Property Value

Type: [System.Int64](https://technet.microsoft.com/library/6yy583ek\(v=ax.60\))  
Returns [Int64](https://technet.microsoft.com/library/6yy583ek\(v=ax.60\)).  

## See Also

#### Reference

[LoyaltySchemeLineEarn Class](loyaltyschemelineearn-class-microsoft-dynamics-commerce-runtime-datamodel.md)

[Microsoft.Dynamics.Commerce.Runtime.DataModel Namespace](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)

