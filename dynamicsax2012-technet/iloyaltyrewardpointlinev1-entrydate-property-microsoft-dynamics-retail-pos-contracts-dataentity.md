---
title: ILoyaltyRewardPointLineV1.EntryDate Property  (Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity)
TOCTitle: EntryDate Property
ms:assetid: P:Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity.ILoyaltyRewardPointLineV1.EntryDate
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.retail.pos.contracts.dataentity.iloyaltyrewardpointlinev1.entrydate(v=AX.60)
ms:contentKeyID: 62205940
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity.ILoyaltyRewardPointLineV1.EntryDate
dev_langs:
- CSharp
- C++
- VB
---

# EntryDate Property

Gets or sets the entry local date of the reward points.

**Namespace:**  [Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity](microsoft-dynamics-retail-pos-contracts-dataentity-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Retail.Pos.Contracts (in Microsoft.Dynamics.Retail.Pos.Contracts.dll)

## Syntax

``` vb
'Declaration
Property EntryDate As DateTime
    Get
    Set
'Usage
Dim instance As ILoyaltyRewardPointLineV1
Dim value As DateTime

value = instance.EntryDate

instance.EntryDate = value
```

``` csharp
DateTime EntryDate { get; set; }
```

``` c++
property DateTime EntryDate {
    DateTime get ();
    void set (DateTime value);
}
```

#### Property Value

Type: [System.DateTime](https://technet.microsoft.com/library/03ybds8y\(v=ax.60\))  
Returns [DateTime](https://technet.microsoft.com/library/03ybds8y\(v=ax.60\)).  

## See Also

#### Reference

[ILoyaltyRewardPointLineV1 Interface](iloyaltyrewardpointlinev1-interface-microsoft-dynamics-retail-pos-contracts-dataentity.md)

[Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity Namespace](microsoft-dynamics-retail-pos-contracts-dataentity-namespace.md)

