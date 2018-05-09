---
title: LoyaltyRewardPointLine.RewardPointId Property  (Microsoft.Dynamics.Commerce.Runtime.DataModel)
TOCTitle: RewardPointId Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.DataModel.LoyaltyRewardPointLine.RewardPointId
ms:mtpsurl: https://technet.microsoft.com/en-us/library/microsoft.dynamics.commerce.runtime.datamodel.loyaltyrewardpointline.rewardpointid(v=AX.60)
ms:contentKeyID: 62214897
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataModel.LoyaltyRewardPointLine.RewardPointId
dev_langs:
- CSharp
- C++
- VB
---

# RewardPointId Property

Gets or sets the readable identifier of the loyalty reward point.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataModel](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Entities (in Microsoft.Dynamics.Commerce.Runtime.Entities.dll)

## Syntax

``` vb
'Declaration
<ColumnAttribute("REWARDPOINTID")> _
<DataMemberAttribute> _
Public Property RewardPointId As String
    Get
    Set
'Usage
Dim instance As LoyaltyRewardPointLine
Dim value As String

value = instance.RewardPointId

instance.RewardPointId = value
```

``` csharp
[ColumnAttribute("REWARDPOINTID")]
[DataMemberAttribute]
public string RewardPointId { get; set; }
```

``` c++
[ColumnAttribute(L"REWARDPOINTID")]
[DataMemberAttribute]
public:
property String^ RewardPointId {
    String^ get ();
    void set (String^ value);
}
```

#### Property Value

Type: [System.String](https://technet.microsoft.com/en-us/library/s1wwdcbf\(v=ax.60\))  
Returns [String](https://technet.microsoft.com/en-us/library/s1wwdcbf\(v=ax.60\)).  

## See Also

#### Reference

[LoyaltyRewardPointLine Class](loyaltyrewardpointline-class-microsoft-dynamics-commerce-runtime-datamodel.md)

[Microsoft.Dynamics.Commerce.Runtime.DataModel Namespace](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)

