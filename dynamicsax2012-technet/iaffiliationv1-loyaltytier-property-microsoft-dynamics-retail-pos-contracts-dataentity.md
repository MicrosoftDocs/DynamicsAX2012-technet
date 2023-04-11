---
title: IAffiliationV1.LoyaltyTier Property  (Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity)
TOCTitle: LoyaltyTier Property
ms:assetid: P:Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity.IAffiliationV1.LoyaltyTier
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.retail.pos.contracts.dataentity.iaffiliationv1.loyaltytier(v=AX.60)
ms:contentKeyID: 62203705
author: tonyafehr
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity.IAffiliationV1.LoyaltyTier
dev_langs:
- CSharp
- C++
- VB
---

# LoyaltyTier Property


[!INCLUDE[archive-banner](includes/archive-banner.md)]

LoyaltyTier

**Namespace:**  [Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity](microsoft-dynamics-retail-pos-contracts-dataentity-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Retail.Pos.Contracts (in Microsoft.Dynamics.Retail.Pos.Contracts.dll)

## Syntax

``` vb
'Declaration
Property LoyaltyTier As Long
    Get
    Set
'Usage
Dim instance As IAffiliationV1
Dim value As Long

value = instance.LoyaltyTier

instance.LoyaltyTier = value
```

``` csharp
long LoyaltyTier { get; set; }
```

``` c++
property long long LoyaltyTier {
    long long get ();
    void set (long long value);
}
```

#### Property Value

Type: [System.Int64](https://technet.microsoft.com/library/6yy583ek\(v=ax.60\))  
Returns [Int64](https://technet.microsoft.com/library/6yy583ek\(v=ax.60\)).  

## See Also

#### Reference

[IAffiliationV1 Interface](iaffiliationv1-interface-microsoft-dynamics-retail-pos-contracts-dataentity.md)

[Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity Namespace](microsoft-dynamics-retail-pos-contracts-dataentity-namespace.md)

