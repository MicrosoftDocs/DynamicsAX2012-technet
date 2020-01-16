---
title: LoyaltyRewardPointLine.EntryType Property  (Microsoft.Dynamics.Commerce.Runtime.DataModel)
TOCTitle: EntryType Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.DataModel.LoyaltyRewardPointLine.EntryType
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.datamodel.loyaltyrewardpointline.entrytype(v=AX.60)
ms:contentKeyID: 62209274
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataModel.LoyaltyRewardPointLine.EntryType
dev_langs:
- CSharp
- C++
- VB
---

# EntryType Property

Gets or sets the entry type (e.g. Earn, Redeem).

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataModel](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Entities (in Microsoft.Dynamics.Commerce.Runtime.Entities.dll)

## Syntax

``` vb
'Declaration
<IgnoreDataMemberAttribute> _
<ColumnAttribute("ENTRYTYPE")> _
Public Property EntryType As LoyaltyRewardPointEntryType
    Get
    Set
'Usage
Dim instance As LoyaltyRewardPointLine
Dim value As LoyaltyRewardPointEntryType

value = instance.EntryType

instance.EntryType = value
```

``` csharp
[IgnoreDataMemberAttribute]
[ColumnAttribute("ENTRYTYPE")]
public LoyaltyRewardPointEntryType EntryType { get; set; }
```

``` c++
[IgnoreDataMemberAttribute]
[ColumnAttribute(L"ENTRYTYPE")]
public:
property LoyaltyRewardPointEntryType EntryType {
    LoyaltyRewardPointEntryType get ();
    void set (LoyaltyRewardPointEntryType value);
}
```

#### Property Value

Type: [Microsoft.Dynamics.Commerce.Runtime.DataModel.LoyaltyRewardPointEntryType](loyaltyrewardpointentrytype-enumeration-microsoft-dynamics-commerce-runtime-datamodel.md)  
Returns [LoyaltyRewardPointEntryType](loyaltyrewardpointentrytype-enumeration-microsoft-dynamics-commerce-runtime-datamodel.md).  

## See Also

#### Reference

[LoyaltyRewardPointLine Class](loyaltyrewardpointline-class-microsoft-dynamics-commerce-runtime-datamodel.md)

[Microsoft.Dynamics.Commerce.Runtime.DataModel Namespace](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)

