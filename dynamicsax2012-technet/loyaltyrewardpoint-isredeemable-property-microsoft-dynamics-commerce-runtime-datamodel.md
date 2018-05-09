---
title: LoyaltyRewardPoint.IsRedeemable Property  (Microsoft.Dynamics.Commerce.Runtime.DataModel)
TOCTitle: IsRedeemable Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.DataModel.LoyaltyRewardPoint.IsRedeemable
ms:mtpsurl: https://technet.microsoft.com/en-us/library/microsoft.dynamics.commerce.runtime.datamodel.loyaltyrewardpoint.isredeemable(v=AX.60)
ms:contentKeyID: 62211168
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataModel.LoyaltyRewardPoint.IsRedeemable
dev_langs:
- CSharp
- C++
- VB
---

# IsRedeemable Property

Gets a value indicating whether the reward point is redeemable.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataModel](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Entities (in Microsoft.Dynamics.Commerce.Runtime.Entities.dll)

## Syntax

``` vb
'Declaration
<DataMemberAttribute> _
<ColumnAttribute("REDEEMABLE")> _
Public Property IsRedeemable As Boolean
    Get
    Friend Set
'Usage
Dim instance As LoyaltyRewardPoint
Dim value As Boolean

value = instance.IsRedeemable
```

``` csharp
[DataMemberAttribute]
[ColumnAttribute("REDEEMABLE")]
public bool IsRedeemable { get; internal set; }
```

``` c++
[DataMemberAttribute]
[ColumnAttribute(L"REDEEMABLE")]
public:
property bool IsRedeemable {
    bool get ();
    internal: void set (bool value);
}
```

#### Property Value

Type: [System.Boolean](https://technet.microsoft.com/en-us/library/a28wyd50\(v=ax.60\))  
Returns [Boolean](https://technet.microsoft.com/en-us/library/a28wyd50\(v=ax.60\)).  

## See Also

#### Reference

[LoyaltyRewardPoint Class](loyaltyrewardpoint-class-microsoft-dynamics-commerce-runtime-datamodel.md)

[Microsoft.Dynamics.Commerce.Runtime.DataModel Namespace](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)

