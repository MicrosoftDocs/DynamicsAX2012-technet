---
title: ITenderV2.SigCapMinAmount Property  (Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity)
TOCTitle: SigCapMinAmount Property
ms:assetid: P:Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity.ITenderV2.SigCapMinAmount
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.retail.pos.contracts.dataentity.itenderv2.sigcapminamount(v=AX.60)
ms:contentKeyID: 49839535
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity.ITenderV2.SigCapMinAmount
dev_langs:
- CSharp
- C++
- VB
---

# SigCapMinAmount Property

Gets or sets minimum amount for signature capture.

**Namespace:**  [Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity](microsoft-dynamics-retail-pos-contracts-dataentity-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Retail.Pos.Contracts (in Microsoft.Dynamics.Retail.Pos.Contracts.dll)

## Syntax

``` vb
'Declaration
Property SigCapMinAmount As Decimal
    Get
    Set
'Usage
Dim instance As ITenderV2
Dim value As Decimal

value = instance.SigCapMinAmount

instance.SigCapMinAmount = value
```

``` csharp
decimal SigCapMinAmount { get; set; }
```

``` c++
property Decimal SigCapMinAmount {
    Decimal get ();
    void set (Decimal value);
}
```

#### Property Value

Type: [System.Decimal](https://technet.microsoft.com/library/1k2e8atx\(v=ax.60\))  
Returns [Decimal](https://technet.microsoft.com/library/1k2e8atx\(v=ax.60\)).  

## See Also

#### Reference

[ITenderV2 Interface](itenderv2-interface-microsoft-dynamics-retail-pos-contracts-dataentity.md)

[Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity Namespace](microsoft-dynamics-retail-pos-contracts-dataentity-namespace.md)

