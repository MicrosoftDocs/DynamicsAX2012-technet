---
title: ILoyaltyCardDataV2.CardType Property  (Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity)
TOCTitle: CardType Property
ms:assetid: P:Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity.ILoyaltyCardDataV2.CardType
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.retail.pos.contracts.dataentity.iloyaltycarddatav2.cardtype(v=AX.60)
ms:contentKeyID: 62206016
author: tonyafehr
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity.ILoyaltyCardDataV2.CardType
dev_langs:
- CSharp
- C++
- VB
---

# CardType Property


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Card tender type

**Namespace:**  [Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity](microsoft-dynamics-retail-pos-contracts-dataentity-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Retail.Pos.Contracts (in Microsoft.Dynamics.Retail.Pos.Contracts.dll)

## Syntax

``` vb
'Declaration
Property CardType As LoyaltyCardTenderType
    Get
    Set
'Usage
Dim instance As ILoyaltyCardDataV2
Dim value As LoyaltyCardTenderType

value = instance.CardType

instance.CardType = value
```

``` csharp
LoyaltyCardTenderType CardType { get; set; }
```

``` c++
property LoyaltyCardTenderType CardType {
    LoyaltyCardTenderType get ();
    void set (LoyaltyCardTenderType value);
}
```

#### Property Value

Type: [Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity.LoyaltyCardTenderType](loyaltycardtendertype-enumeration-microsoft-dynamics-retail-pos-contracts-dataentity.md)  
Returns [LoyaltyCardTenderType](loyaltycardtendertype-enumeration-microsoft-dynamics-retail-pos-contracts-dataentity.md).  

## See Also

#### Reference

[ILoyaltyCardDataV2 Interface](iloyaltycarddatav2-interface-microsoft-dynamics-retail-pos-contracts-dataentity.md)

[Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity Namespace](microsoft-dynamics-retail-pos-contracts-dataentity-namespace.md)

