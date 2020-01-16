---
title: ILoyaltyCardDataV1.UsedPoints Property  (Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity)
TOCTitle: UsedPoints Property
ms:assetid: P:Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity.ILoyaltyCardDataV1.UsedPoints
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.retail.pos.contracts.dataentity.iloyaltycarddatav1.usedpoints(v=AX.60)
ms:contentKeyID: 62203692
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity.ILoyaltyCardDataV1.UsedPoints
dev_langs:
- CSharp
- C++
- VB
---

# UsedPoints Property

Gets or sets the loyalty card used points.

**Namespace:**  [Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity](microsoft-dynamics-retail-pos-contracts-dataentity-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Retail.Pos.Contracts (in Microsoft.Dynamics.Retail.Pos.Contracts.dll)

## Syntax

``` vb
'Declaration
Property UsedPoints As Decimal
    Get
    Set
'Usage
Dim instance As ILoyaltyCardDataV1
Dim value As Decimal

value = instance.UsedPoints

instance.UsedPoints = value
```

``` csharp
decimal UsedPoints { get; set; }
```

``` c++
property Decimal UsedPoints {
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

