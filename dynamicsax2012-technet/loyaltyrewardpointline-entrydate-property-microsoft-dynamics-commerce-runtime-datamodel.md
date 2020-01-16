---
title: LoyaltyRewardPointLine.EntryDate Property  (Microsoft.Dynamics.Commerce.Runtime.DataModel)
TOCTitle: EntryDate Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.DataModel.LoyaltyRewardPointLine.EntryDate
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.datamodel.loyaltyrewardpointline.entrydate(v=AX.60)
ms:contentKeyID: 62204781
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataModel.LoyaltyRewardPointLine.EntryDate
dev_langs:
- CSharp
- C++
- VB
---

# EntryDate Property

Gets or sets the entry date of the reward points.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataModel](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Entities (in Microsoft.Dynamics.Commerce.Runtime.Entities.dll)

## Syntax

``` vb
'Declaration
<DataMemberAttribute> _
<ColumnAttribute("ENTRYDATE")> _
Public Property EntryDate As DateTimeOffset
    Get
    Set
'Usage
Dim instance As LoyaltyRewardPointLine
Dim value As DateTimeOffset

value = instance.EntryDate

instance.EntryDate = value
```

``` csharp
[DataMemberAttribute]
[ColumnAttribute("ENTRYDATE")]
public DateTimeOffset EntryDate { get; set; }
```

``` c++
[DataMemberAttribute]
[ColumnAttribute(L"ENTRYDATE")]
public:
property DateTimeOffset EntryDate {
    DateTimeOffset get ();
    void set (DateTimeOffset value);
}
```

#### Property Value

Type: [System.DateTimeOffset](https://technet.microsoft.com/library/bb341783\(v=ax.60\))  
Returns [DateTimeOffset](https://technet.microsoft.com/library/bb341783\(v=ax.60\)).  

## See Also

#### Reference

[LoyaltyRewardPointLine Class](loyaltyrewardpointline-class-microsoft-dynamics-commerce-runtime-datamodel.md)

[Microsoft.Dynamics.Commerce.Runtime.DataModel Namespace](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)

