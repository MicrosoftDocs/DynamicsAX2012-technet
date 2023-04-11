---
title: ICardInfoV1.CardType Property  (Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity)
TOCTitle: CardType Property
ms:assetid: P:Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity.ICardInfoV1.CardType
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.retail.pos.contracts.dataentity.icardinfov1.cardtype(v=AX.60)
ms:contentKeyID: 47128214
author: tonyafehr
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity.ICardInfoV1.CardType
dev_langs:
- CSharp
- C++
- VB
---

# CardType Property


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Gets or sets the types of cards that are supported by the system.

**Namespace:**  [Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity](microsoft-dynamics-retail-pos-contracts-dataentity-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Retail.Pos.Contracts (in Microsoft.Dynamics.Retail.Pos.Contracts.dll)

## Syntax

``` vb
'Declaration
Property CardType As CardTypes
    Get
    Set
'Usage
Dim instance As ICardInfoV1
Dim value As CardTypes

value = instance.CardType

instance.CardType = value
```

``` csharp
CardTypes CardType { get; set; }
```

``` c++
property CardTypes CardType {
    CardTypes get ();
    void set (CardTypes value);
}
```

#### Property Value

Type: [Microsoft.Dynamics.Retail.Pos.Contracts.Services.CardTypes](cardtypes-enumeration-microsoft-dynamics-retail-pos-contracts-services.md)  
The [Microsoft.Dynamics.Retail.Pos.Contracts.Services.CardTypes](cardtypes-enumeration-microsoft-dynamics-retail-pos-contracts-services.md) value.  

## See Also

#### Reference

[ICardInfoV1 Interface](icardinfov1-interface-microsoft-dynamics-retail-pos-contracts-dataentity.md)

[Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity Namespace](microsoft-dynamics-retail-pos-contracts-dataentity-namespace.md)

