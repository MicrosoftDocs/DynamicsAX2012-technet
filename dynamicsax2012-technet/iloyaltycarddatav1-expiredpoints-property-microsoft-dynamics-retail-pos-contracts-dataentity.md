---
title: ILoyaltyCardDataV1.ExpiredPoints Property  (Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity)
TOCTitle: ExpiredPoints Property
ms:assetid: P:Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity.ILoyaltyCardDataV1.ExpiredPoints
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.retail.pos.contracts.dataentity.iloyaltycarddatav1.expiredpoints(v=AX.60)
ms:contentKeyID: 62202948
author: tonyafehr
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity.ILoyaltyCardDataV1.ExpiredPoints
dev_langs:
- CSharp
- C++
- VB
---

# ExpiredPoints Property


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Gets or sets the loyalty card expired points.

**Namespace:**  [Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity](microsoft-dynamics-retail-pos-contracts-dataentity-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Retail.Pos.Contracts (in Microsoft.Dynamics.Retail.Pos.Contracts.dll)

## Syntax

``` vb
'Declaration
Property ExpiredPoints As Decimal
    Get
    Set
'Usage
Dim instance As ILoyaltyCardDataV1
Dim value As Decimal

value = instance.ExpiredPoints

instance.ExpiredPoints = value
```

``` csharp
decimal ExpiredPoints { get; set; }
```

``` c++
property Decimal ExpiredPoints {
    Decimal get ();
    void set (Decimal value);
}
```

#### Property Value

Type: [System.Decimal](https://technet.microsoft.com/library/1k2e8atx\(v=ax.60\))  
Returns [Decimal](https://technet.microsoft.com/library/1k2e8atx\(v=ax.60\)).  

## See Also

#### Reference

[ILoyaltyCardDataV1 Interface](iloyaltycarddatav1-interface-microsoft-dynamics-retail-pos-contracts-dataentity.md)

[Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity Namespace](microsoft-dynamics-retail-pos-contracts-dataentity-namespace.md)

