---
title: LoyaltyRewardPoint.ExpirationTimeValue Property  (Microsoft.Dynamics.Commerce.Runtime.DataModel)
TOCTitle: ExpirationTimeValue Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.DataModel.LoyaltyRewardPoint.ExpirationTimeValue
ms:mtpsurl: https://technet.microsoft.com/en-us/library/microsoft.dynamics.commerce.runtime.datamodel.loyaltyrewardpoint.expirationtimevalue(v=AX.60)
ms:contentKeyID: 62215200
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataModel.LoyaltyRewardPoint.ExpirationTimeValue
dev_langs:
- CSharp
- C++
- VB
---

# ExpirationTimeValue Property

Gets expiration time value of the reward point.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataModel](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Entities (in Microsoft.Dynamics.Commerce.Runtime.Entities.dll)

## Syntax

``` vb
'Declaration
<IgnoreDataMemberAttribute> _
<ColumnAttribute("EXPIRATIONTIMEVALUE")> _
Public Property ExpirationTimeValue As Integer
    Get
    Friend Set
'Usage
Dim instance As LoyaltyRewardPoint
Dim value As Integer

value = instance.ExpirationTimeValue
```

``` csharp
[IgnoreDataMemberAttribute]
[ColumnAttribute("EXPIRATIONTIMEVALUE")]
public int ExpirationTimeValue { get; internal set; }
```

``` c++
[IgnoreDataMemberAttribute]
[ColumnAttribute(L"EXPIRATIONTIMEVALUE")]
public:
property int ExpirationTimeValue {
    int get ();
    internal: void set (int value);
}
```

#### Property Value

Type: [System.Int32](https://technet.microsoft.com/en-us/library/td2s409d\(v=ax.60\))  
Returns [Int32](https://technet.microsoft.com/en-us/library/td2s409d\(v=ax.60\)).  

## See Also

#### Reference

[LoyaltyRewardPoint Class](loyaltyrewardpoint-class-microsoft-dynamics-commerce-runtime-datamodel.md)

[Microsoft.Dynamics.Commerce.Runtime.DataModel Namespace](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)

