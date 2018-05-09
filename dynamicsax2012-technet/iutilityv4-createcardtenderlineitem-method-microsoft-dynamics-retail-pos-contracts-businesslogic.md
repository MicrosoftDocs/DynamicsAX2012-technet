---
title: IUtilityV4.CreateCardTenderLineItem Method  (Microsoft.Dynamics.Retail.Pos.Contracts.BusinessLogic)
TOCTitle: CreateCardTenderLineItem Method
ms:assetid: M:Microsoft.Dynamics.Retail.Pos.Contracts.BusinessLogic.IUtilityV4.CreateCardTenderLineItem
ms:mtpsurl: https://technet.microsoft.com/en-us/library/microsoft.dynamics.retail.pos.contracts.businesslogic.iutilityv4.createcardtenderlineitem(v=AX.60)
ms:contentKeyID: 62202367
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Retail.Pos.Contracts.BusinessLogic.IUtilityV4.CreateCardTenderLineItem
dev_langs:
- CSharp
- C++
- VB
---

# CreateCardTenderLineItem Method

Creates a tender line of type card

**Namespace:**  [Microsoft.Dynamics.Retail.Pos.Contracts.BusinessLogic](microsoft-dynamics-retail-pos-contracts-businesslogic-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Retail.Pos.Contracts (in Microsoft.Dynamics.Retail.Pos.Contracts.dll)

## Syntax

``` vb
'Declaration
Function CreateCardTenderLineItem As ICardTenderLineItem
'Usage
Dim instance As IUtilityV4
Dim returnValue As ICardTenderLineItem

returnValue = instance.CreateCardTenderLineItem()
```

``` csharp
ICardTenderLineItem CreateCardTenderLineItem()
```

``` c++
ICardTenderLineItem^ CreateCardTenderLineItem()
```

#### Return Value

Type: [Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity.ICardTenderLineItem](icardtenderlineitem-interface-microsoft-dynamics-retail-pos-contracts-dataentity.md)  
a card tender line  

## See Also

#### Reference

[IUtilityV4 Interface](iutilityv4-interface-microsoft-dynamics-retail-pos-contracts-businesslogic.md)

[Microsoft.Dynamics.Retail.Pos.Contracts.BusinessLogic Namespace](microsoft-dynamics-retail-pos-contracts-businesslogic-namespace.md)

