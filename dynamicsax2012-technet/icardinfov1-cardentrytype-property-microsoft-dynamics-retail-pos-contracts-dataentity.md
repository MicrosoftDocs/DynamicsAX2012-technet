---
title: ICardInfoV1.CardEntryType Property  (Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity)
TOCTitle: CardEntryType Property
ms:assetid: P:Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity.ICardInfoV1.CardEntryType
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.retail.pos.contracts.dataentity.icardinfov1.cardentrytype(v=AX.60)
ms:contentKeyID: 47129214
author: tonyafehr
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity.ICardInfoV1.CardEntryType
dev_langs:
- CSharp
- C++
- VB
---

# CardEntryType Property


[!INCLUDE[archive-banner](includes/archive-banner.md)]

An enumerated constant that indicates the card entry types.

How was the card number received: manually or by swiping the card?

**Namespace:**  [Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity](microsoft-dynamics-retail-pos-contracts-dataentity-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Retail.Pos.Contracts (in Microsoft.Dynamics.Retail.Pos.Contracts.dll)

## Syntax

``` vb
'Declaration
Property CardEntryType As CardEntryTypes
    Get
    Set
'Usage
Dim instance As ICardInfoV1
Dim value As CardEntryTypes

value = instance.CardEntryType

instance.CardEntryType = value
```

``` csharp
CardEntryTypes CardEntryType { get; set; }
```

``` c++
property CardEntryTypes CardEntryType {
    CardEntryTypes get ();
    void set (CardEntryTypes value);
}
```

#### Property Value

Type: [Microsoft.Dynamics.Retail.Pos.Contracts.Services.CardEntryTypes](cardentrytypes-enumeration-microsoft-dynamics-retail-pos-contracts-services.md)  
The [Microsoft.Dynamics.Retail.Pos.Contracts.Services.CardEntryTypes](cardentrytypes-enumeration-microsoft-dynamics-retail-pos-contracts-services.md) value.  

## See Also

#### Reference

[ICardInfoV1 Interface](icardinfov1-interface-microsoft-dynamics-retail-pos-contracts-dataentity.md)

[Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity Namespace](microsoft-dynamics-retail-pos-contracts-dataentity-namespace.md)

