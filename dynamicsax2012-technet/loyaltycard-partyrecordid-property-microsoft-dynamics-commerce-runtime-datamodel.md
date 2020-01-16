---
title: LoyaltyCard.PartyRecordId Property  (Microsoft.Dynamics.Commerce.Runtime.DataModel)
TOCTitle: PartyRecordId Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.DataModel.LoyaltyCard.PartyRecordId
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.datamodel.loyaltycard.partyrecordid(v=AX.60)
ms:contentKeyID: 62209191
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataModel.LoyaltyCard.PartyRecordId
dev_langs:
- CSharp
- C++
- VB
---

# PartyRecordId Property

Gets the record identifier of the party of the card owner.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataModel](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Entities (in Microsoft.Dynamics.Commerce.Runtime.Entities.dll)

## Syntax

``` vb
'Declaration
<IgnoreDataMemberAttribute> _
<ColumnAttribute("PARTY")> _
Public Property PartyRecordId As Long
    Get
    Friend Set
'Usage
Dim instance As LoyaltyCard
Dim value As Long

value = instance.PartyRecordId
```

``` csharp
[IgnoreDataMemberAttribute]
[ColumnAttribute("PARTY")]
public long PartyRecordId { get; internal set; }
```

``` c++
[IgnoreDataMemberAttribute]
[ColumnAttribute(L"PARTY")]
public:
property long long PartyRecordId {
    long long get ();
    internal: void set (long long value);
}
```

#### Property Value

Type: [System.Int64](https://technet.microsoft.com/library/6yy583ek\(v=ax.60\))  
Returns [Int64](https://technet.microsoft.com/library/6yy583ek\(v=ax.60\)).  

## See Also

#### Reference

[LoyaltyCard Class](loyaltycard-class-microsoft-dynamics-commerce-runtime-datamodel.md)

[Microsoft.Dynamics.Commerce.Runtime.DataModel Namespace](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)

