---
title: ILoyaltyRewardPointLineV1.EntryType Property  (Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity)
TOCTitle: EntryType Property
ms:assetid: P:Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity.ILoyaltyRewardPointLineV1.EntryType
ms:mtpsurl: https://technet.microsoft.com/en-us/library/microsoft.dynamics.retail.pos.contracts.dataentity.iloyaltyrewardpointlinev1.entrytype(v=AX.60)
ms:contentKeyID: 62205780
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity.ILoyaltyRewardPointLineV1.EntryType
dev_langs:
- CSharp
- C++
- VB
---

# EntryType Property

Gets or sets the entry type (e.g. Earn, Redeem).

**Namespace:**  [Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity](microsoft-dynamics-retail-pos-contracts-dataentity-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Retail.Pos.Contracts (in Microsoft.Dynamics.Retail.Pos.Contracts.dll)

## Syntax

``` vb
'Declaration
Property EntryType As LoyaltyRewardPointEntryType
    Get
    Set
'Usage
Dim instance As ILoyaltyRewardPointLineV1
Dim value As LoyaltyRewardPointEntryType

value = instance.EntryType

instance.EntryType = value
```

``` csharp
LoyaltyRewardPointEntryType EntryType { get; set; }
```

``` c++
property LoyaltyRewardPointEntryType EntryType {
    LoyaltyRewardPointEntryType get ();
    void set (LoyaltyRewardPointEntryType value);
}
```

#### Property Value

Type: [Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity.LoyaltyRewardPointEntryType](loyaltyrewardpointentrytype-enumeration-microsoft-dynamics-retail-pos-contracts-dataentity.md)  
Returns [LoyaltyRewardPointEntryType](loyaltyrewardpointentrytype-enumeration-microsoft-dynamics-retail-pos-contracts-dataentity.md).  

## See Also

#### Reference

[ILoyaltyRewardPointLineV1 Interface](iloyaltyrewardpointlinev1-interface-microsoft-dynamics-retail-pos-contracts-dataentity.md)

[Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity Namespace](microsoft-dynamics-retail-pos-contracts-dataentity-namespace.md)

