---
title: ILoyaltyTenderLineItem Interface (Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity)
TOCTitle: ILoyaltyTenderLineItem Interface
ms:assetid: T:Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity.ILoyaltyTenderLineItem
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.retail.pos.contracts.dataentity.iloyaltytenderlineitem(v=AX.60)
ms:contentKeyID: 47128619
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity.ILoyaltyTenderLineItem
dev_langs:
- CSharp
- C++
- VB
---

# ILoyaltyTenderLineItem Interface


[!INCLUDE[archive-banner](includes/archive-banner.md)]

The ILoyaltyTenderLineItem interface.

**Namespace:**  [Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity](microsoft-dynamics-retail-pos-contracts-dataentity-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Retail.Pos.Contracts (in Microsoft.Dynamics.Retail.Pos.Contracts.dll)

## Syntax

``` vb
'Declaration
<GuidAttribute("020E554F-16E0-4981-ABB6-64ADB8CC7BF8")> _
Public Interface ILoyaltyTenderLineItem _
    Inherits ICardTenderLineItem, ITenderLineItem, ILineItem, ILineItemV1,  _
    ITenderLineItemV1, ITenderLineItemV2, ICardTenderLineItemV1, ILoyaltyTenderLineItemV1
'Usage
Dim instance As ILoyaltyTenderLineItem
```

``` csharp
[GuidAttribute("020E554F-16E0-4981-ABB6-64ADB8CC7BF8")]
public interface ILoyaltyTenderLineItem : ICardTenderLineItem, 
    ITenderLineItem, ILineItem, ILineItemV1, ITenderLineItemV1, ITenderLineItemV2, 
    ICardTenderLineItemV1, ILoyaltyTenderLineItemV1
```

``` c++
[GuidAttribute(L"020E554F-16E0-4981-ABB6-64ADB8CC7BF8")]
public interface class ILoyaltyTenderLineItem : ICardTenderLineItem, 
    ITenderLineItem, ILineItem, ILineItemV1, ITenderLineItemV1, ITenderLineItemV2, 
    ICardTenderLineItemV1, ILoyaltyTenderLineItemV1
```

## See Also

#### Reference

[Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity Namespace](microsoft-dynamics-retail-pos-contracts-dataentity-namespace.md)

