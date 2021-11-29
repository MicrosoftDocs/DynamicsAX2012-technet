---
title: ILoyaltyRewardPointLineV1.LineNumber Property  (Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity)
TOCTitle: LineNumber Property
ms:assetid: P:Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity.ILoyaltyRewardPointLineV1.LineNumber
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.retail.pos.contracts.dataentity.iloyaltyrewardpointlinev1.linenumber(v=AX.60)
ms:contentKeyID: 62202214
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity.ILoyaltyRewardPointLineV1.LineNumber
dev_langs:
- CSharp
- C++
- VB
---

# LineNumber Property


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Gets or sets the line number.

**Namespace:**  [Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity](microsoft-dynamics-retail-pos-contracts-dataentity-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Retail.Pos.Contracts (in Microsoft.Dynamics.Retail.Pos.Contracts.dll)

## Syntax

``` vb
'Declaration
Property LineNumber As Decimal
    Get
    Set
'Usage
Dim instance As ILoyaltyRewardPointLineV1
Dim value As Decimal

value = instance.LineNumber

instance.LineNumber = value
```

``` csharp
decimal LineNumber { get; set; }
```

``` c++
property Decimal LineNumber {
    Decimal get ();
    void set (Decimal value);
}
```

#### Property Value

Type: [System.Decimal](https://technet.microsoft.com/library/1k2e8atx\(v=ax.60\))  
Returns [Decimal](https://technet.microsoft.com/library/1k2e8atx\(v=ax.60\)).  

## See Also

#### Reference

[ILoyaltyRewardPointLineV1 Interface](iloyaltyrewardpointlinev1-interface-microsoft-dynamics-retail-pos-contracts-dataentity.md)

[Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity Namespace](microsoft-dynamics-retail-pos-contracts-dataentity-namespace.md)

