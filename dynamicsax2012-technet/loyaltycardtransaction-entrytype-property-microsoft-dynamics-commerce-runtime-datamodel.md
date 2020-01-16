---
title: LoyaltyCardTransaction.EntryType Property  (Microsoft.Dynamics.Commerce.Runtime.DataModel)
TOCTitle: EntryType Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.DataModel.LoyaltyCardTransaction.EntryType
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.datamodel.loyaltycardtransaction.entrytype(v=AX.60)
ms:contentKeyID: 62209238
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataModel.LoyaltyCardTransaction.EntryType
dev_langs:
- CSharp
- C++
- VB
---

# EntryType Property

Gets the entry type of the reward point, e.g. Earn, Redeem.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataModel](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Entities (in Microsoft.Dynamics.Commerce.Runtime.Entities.dll)

## Syntax

``` vb
'Declaration
<IgnoreDataMemberAttribute> _
Public Property EntryType As LoyaltyRewardPointEntryType
    Get
    Friend Set
'Usage
Dim instance As LoyaltyCardTransaction
Dim value As LoyaltyRewardPointEntryType

value = instance.EntryType
```

``` csharp
[IgnoreDataMemberAttribute]
public LoyaltyRewardPointEntryType EntryType { get; internal set; }
```

``` c++
[IgnoreDataMemberAttribute]
public:
property LoyaltyRewardPointEntryType EntryType {
    LoyaltyRewardPointEntryType get ();
    internal: void set (LoyaltyRewardPointEntryType value);
}
```

#### Property Value

Type: [Microsoft.Dynamics.Commerce.Runtime.DataModel.LoyaltyRewardPointEntryType](loyaltyrewardpointentrytype-enumeration-microsoft-dynamics-commerce-runtime-datamodel.md)  
Returns [LoyaltyRewardPointEntryType](loyaltyrewardpointentrytype-enumeration-microsoft-dynamics-commerce-runtime-datamodel.md).  

## See Also

#### Reference

[LoyaltyCardTransaction Class](loyaltycardtransaction-class-microsoft-dynamics-commerce-runtime-datamodel.md)

[Microsoft.Dynamics.Commerce.Runtime.DataModel Namespace](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)

