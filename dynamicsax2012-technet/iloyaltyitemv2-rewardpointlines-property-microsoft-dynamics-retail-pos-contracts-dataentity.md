---
title: ILoyaltyItemV2.RewardPointLines Property  (Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity)
TOCTitle: RewardPointLines Property
ms:assetid: P:Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity.ILoyaltyItemV2.RewardPointLines
ms:mtpsurl: https://technet.microsoft.com/en-us/library/microsoft.dynamics.retail.pos.contracts.dataentity.iloyaltyitemv2.rewardpointlines(v=AX.60)
ms:contentKeyID: 62205591
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity.ILoyaltyItemV2.RewardPointLines
dev_langs:
- CSharp
- C++
- VB
---

# RewardPointLines Property

Loyalty reward point lines.

**Namespace:**  [Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity](microsoft-dynamics-retail-pos-contracts-dataentity-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Retail.Pos.Contracts (in Microsoft.Dynamics.Retail.Pos.Contracts.dll)

## Syntax

``` vb
'Declaration
Property RewardPointLines As IEnumerable(Of ILoyaltyRewardPointLine)
    Get
    Set
'Usage
Dim instance As ILoyaltyItemV2
Dim value As IEnumerable(Of ILoyaltyRewardPointLine)

value = instance.RewardPointLines

instance.RewardPointLines = value
```

``` csharp
IEnumerable<ILoyaltyRewardPointLine> RewardPointLines { get; set; }
```

``` c++
property IEnumerable<ILoyaltyRewardPointLine^>^ RewardPointLines {
    IEnumerable<ILoyaltyRewardPointLine^>^ get ();
    void set (IEnumerable<ILoyaltyRewardPointLine^>^ value);
}
```

#### Property Value

Type: [System.Collections.Generic.IEnumerable](https://technet.microsoft.com/en-us/library/9eekhta0\(v=ax.60\))\<[ILoyaltyRewardPointLine](iloyaltyrewardpointline-interface-microsoft-dynamics-retail-pos-contracts-dataentity.md)\>  
Returns [IEnumerable\<T\>](https://technet.microsoft.com/en-us/library/9eekhta0\(v=ax.60\)).  

## See Also

#### Reference

[ILoyaltyItemV2 Interface](iloyaltyitemv2-interface-microsoft-dynamics-retail-pos-contracts-dataentity.md)

[Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity Namespace](microsoft-dynamics-retail-pos-contracts-dataentity-namespace.md)

