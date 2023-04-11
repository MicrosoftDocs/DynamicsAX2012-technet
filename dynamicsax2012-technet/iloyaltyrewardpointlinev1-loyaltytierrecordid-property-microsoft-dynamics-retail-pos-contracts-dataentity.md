---
title: ILoyaltyRewardPointLineV1.LoyaltyTierRecordId Property  (Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity)
TOCTitle: LoyaltyTierRecordId Property
ms:assetid: P:Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity.ILoyaltyRewardPointLineV1.LoyaltyTierRecordId
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.retail.pos.contracts.dataentity.iloyaltyrewardpointlinev1.loyaltytierrecordid(v=AX.60)
ms:contentKeyID: 62204108
author: tonyafehr
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity.ILoyaltyRewardPointLineV1.LoyaltyTierRecordId
dev_langs:
- CSharp
- C++
- VB
---

# LoyaltyTierRecordId Property


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Gets or sets the record identifier of the loyalty tier.

**Namespace:**  [Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity](microsoft-dynamics-retail-pos-contracts-dataentity-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Retail.Pos.Contracts (in Microsoft.Dynamics.Retail.Pos.Contracts.dll)

## Syntax

``` vb
'Declaration
Property LoyaltyTierRecordId As Long
    Get
    Set
'Usage
Dim instance As ILoyaltyRewardPointLineV1
Dim value As Long

value = instance.LoyaltyTierRecordId

instance.LoyaltyTierRecordId = value
```

``` csharp
long LoyaltyTierRecordId { get; set; }
```

``` c++
property long long LoyaltyTierRecordId {
    long long get ();
    void set (long long value);
}
```

#### Property Value

Type: [System.Int64](https://technet.microsoft.com/library/6yy583ek\(v=ax.60\))  
Returns [Int64](https://technet.microsoft.com/library/6yy583ek\(v=ax.60\)).  

## See Also

#### Reference

[ILoyaltyRewardPointLineV1 Interface](iloyaltyrewardpointlinev1-interface-microsoft-dynamics-retail-pos-contracts-dataentity.md)

[Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity Namespace](microsoft-dynamics-retail-pos-contracts-dataentity-namespace.md)

