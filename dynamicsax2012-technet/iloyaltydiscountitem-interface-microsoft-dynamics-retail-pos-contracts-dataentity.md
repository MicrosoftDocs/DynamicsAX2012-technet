---
title: ILoyaltyDiscountItem Interface (Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity)
TOCTitle: ILoyaltyDiscountItem Interface
ms:assetid: T:Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity.ILoyaltyDiscountItem
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.retail.pos.contracts.dataentity.iloyaltydiscountitem(v=AX.60)
ms:contentKeyID: 62202865
author: tonyafehr
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity.ILoyaltyDiscountItem
dev_langs:
- CSharp
- C++
- VB
---

# ILoyaltyDiscountItem Interface


[!INCLUDE[archive-banner](includes/archive-banner.md)]

ILoyaltyDiscountItem interface.

**Namespace:**  [Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity](microsoft-dynamics-retail-pos-contracts-dataentity-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Retail.Pos.Contracts (in Microsoft.Dynamics.Retail.Pos.Contracts.dll)

## Syntax

``` vb
'Declaration
<GuidAttribute("56E9C33E-3B9B-47C5-B85D-35FF63AA90F3")> _
Public Interface ILoyaltyDiscountItem _
    Inherits IDiscountItem, IDiscountItemV1, IDiscountItemV2
'Usage
Dim instance As ILoyaltyDiscountItem
```

``` csharp
[GuidAttribute("56E9C33E-3B9B-47C5-B85D-35FF63AA90F3")]
public interface ILoyaltyDiscountItem : IDiscountItem, 
    IDiscountItemV1, IDiscountItemV2
```

``` c++
[GuidAttribute(L"56E9C33E-3B9B-47C5-B85D-35FF63AA90F3")]
public interface class ILoyaltyDiscountItem : IDiscountItem, 
    IDiscountItemV1, IDiscountItemV2
```

## See Also

#### Reference

[Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity Namespace](microsoft-dynamics-retail-pos-contracts-dataentity-namespace.md)

