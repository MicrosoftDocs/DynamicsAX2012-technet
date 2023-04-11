---
title: ILoyaltyCardDataV1.IssuedPoints Property  (Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity)
TOCTitle: IssuedPoints Property
ms:assetid: P:Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity.ILoyaltyCardDataV1.IssuedPoints
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.retail.pos.contracts.dataentity.iloyaltycarddatav1.issuedpoints(v=AX.60)
ms:contentKeyID: 62203141
author: tonyafehr
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity.ILoyaltyCardDataV1.IssuedPoints
dev_langs:
- CSharp
- C++
- VB
---

# IssuedPoints Property


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Gets or sets the loyalty card issued points.

**Namespace:**  [Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity](microsoft-dynamics-retail-pos-contracts-dataentity-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Retail.Pos.Contracts (in Microsoft.Dynamics.Retail.Pos.Contracts.dll)

## Syntax

``` vb
'Declaration
Property IssuedPoints As Decimal
    Get
    Set
'Usage
Dim instance As ILoyaltyCardDataV1
Dim value As Decimal

value = instance.IssuedPoints

instance.IssuedPoints = value
```

``` csharp
decimal IssuedPoints { get; set; }
```

``` c++
property Decimal IssuedPoints {
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

