---
title: LoyaltyRewardPointLine.LoyaltyTierRecordId Property  (Microsoft.Dynamics.Commerce.Runtime.DataModel)
TOCTitle: LoyaltyTierRecordId Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.DataModel.LoyaltyRewardPointLine.LoyaltyTierRecordId
ms:mtpsurl: https://technet.microsoft.com/en-us/library/microsoft.dynamics.commerce.runtime.datamodel.loyaltyrewardpointline.loyaltytierrecordid(v=AX.60)
ms:contentKeyID: 62210656
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataModel.LoyaltyRewardPointLine.LoyaltyTierRecordId
dev_langs:
- CSharp
- C++
- VB
---

# LoyaltyTierRecordId Property

Gets or sets the record identifier of the loyalty tier.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataModel](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Entities (in Microsoft.Dynamics.Commerce.Runtime.Entities.dll)

## Syntax

``` vb
'Declaration
<ColumnAttribute("LOYALTYTIER")> _
<DataMemberAttribute> _
Public Property LoyaltyTierRecordId As Long
    Get
    Set
'Usage
Dim instance As LoyaltyRewardPointLine
Dim value As Long

value = instance.LoyaltyTierRecordId

instance.LoyaltyTierRecordId = value
```

``` csharp
[ColumnAttribute("LOYALTYTIER")]
[DataMemberAttribute]
public long LoyaltyTierRecordId { get; set; }
```

``` c++
[ColumnAttribute(L"LOYALTYTIER")]
[DataMemberAttribute]
public:
property long long LoyaltyTierRecordId {
    long long get ();
    void set (long long value);
}
```

#### Property Value

Type: [System.Int64](https://technet.microsoft.com/en-us/library/6yy583ek\(v=ax.60\))  
Returns [Int64](https://technet.microsoft.com/en-us/library/6yy583ek\(v=ax.60\)).  

## See Also

#### Reference

[LoyaltyRewardPointLine Class](loyaltyrewardpointline-class-microsoft-dynamics-commerce-runtime-datamodel.md)

[Microsoft.Dynamics.Commerce.Runtime.DataModel Namespace](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)

