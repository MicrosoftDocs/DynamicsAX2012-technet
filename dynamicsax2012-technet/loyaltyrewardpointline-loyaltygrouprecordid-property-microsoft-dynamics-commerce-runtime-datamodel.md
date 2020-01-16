---
title: LoyaltyRewardPointLine.LoyaltyGroupRecordId Property  (Microsoft.Dynamics.Commerce.Runtime.DataModel)
TOCTitle: LoyaltyGroupRecordId Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.DataModel.LoyaltyRewardPointLine.LoyaltyGroupRecordId
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.datamodel.loyaltyrewardpointline.loyaltygrouprecordid(v=AX.60)
ms:contentKeyID: 62213184
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataModel.LoyaltyRewardPointLine.LoyaltyGroupRecordId
dev_langs:
- CSharp
- C++
- VB
---

# LoyaltyGroupRecordId Property

Gets or sets the record identifier of the loyalty group.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataModel](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Entities (in Microsoft.Dynamics.Commerce.Runtime.Entities.dll)

## Syntax

``` vb
'Declaration
<ColumnAttribute("AFFILIATION")> _
<DataMemberAttribute> _
Public Property LoyaltyGroupRecordId As Long
    Get
    Set
'Usage
Dim instance As LoyaltyRewardPointLine
Dim value As Long

value = instance.LoyaltyGroupRecordId

instance.LoyaltyGroupRecordId = value
```

``` csharp
[ColumnAttribute("AFFILIATION")]
[DataMemberAttribute]
public long LoyaltyGroupRecordId { get; set; }
```

``` c++
[ColumnAttribute(L"AFFILIATION")]
[DataMemberAttribute]
public:
property long long LoyaltyGroupRecordId {
    long long get ();
    void set (long long value);
}
```

#### Property Value

Type: [System.Int64](https://technet.microsoft.com/library/6yy583ek\(v=ax.60\))  
Returns [Int64](https://technet.microsoft.com/library/6yy583ek\(v=ax.60\)).  

## See Also

#### Reference

[LoyaltyRewardPointLine Class](loyaltyrewardpointline-class-microsoft-dynamics-commerce-runtime-datamodel.md)

[Microsoft.Dynamics.Commerce.Runtime.DataModel Namespace](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)

