---
title: ILoyaltyItemV1.AccumulatedLoyaltyPoints Property  (Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity)
TOCTitle: AccumulatedLoyaltyPoints Property
ms:assetid: P:Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity.ILoyaltyItemV1.AccumulatedLoyaltyPoints
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.retail.pos.contracts.dataentity.iloyaltyitemv1.accumulatedloyaltypoints(v=AX.60)
ms:contentKeyID: 49842709
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity.ILoyaltyItemV1.AccumulatedLoyaltyPoints
dev_langs:
- CSharp
- C++
- VB
---

# AccumulatedLoyaltyPoints Property

**Note: This API is now obsolete.**

**Namespace:**  [Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity](microsoft-dynamics-retail-pos-contracts-dataentity-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Retail.Pos.Contracts (in Microsoft.Dynamics.Retail.Pos.Contracts.dll)

## Syntax

``` vb
'Declaration
<ObsoleteAttribute("Not used any more.")> _
Property AccumulatedLoyaltyPoints As Decimal
    Get
    Set
'Usage
Dim instance As ILoyaltyItemV1
Dim value As Decimal

value = instance.AccumulatedLoyaltyPoints

instance.AccumulatedLoyaltyPoints = value
```

``` csharp
[ObsoleteAttribute("Not used any more.")]
decimal AccumulatedLoyaltyPoints { get; set; }
```

``` c++
[ObsoleteAttribute(L"Not used any more.")]
property Decimal AccumulatedLoyaltyPoints {
    Decimal get ();
    void set (Decimal value);
}
```

#### Property Value

Type: [System.Decimal](https://technet.microsoft.com/library/1k2e8atx\(v=ax.60\))  
Returns [Decimal](https://technet.microsoft.com/library/1k2e8atx\(v=ax.60\)).  

## See Also

#### Reference

[ILoyaltyItemV1 Interface](iloyaltyitemv1-interface-microsoft-dynamics-retail-pos-contracts-dataentity.md)

[Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity Namespace](microsoft-dynamics-retail-pos-contracts-dataentity-namespace.md)

