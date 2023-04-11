---
title: IPeriodicDiscountItem Interface (Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity)
TOCTitle: IPeriodicDiscountItem Interface
ms:assetid: T:Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity.IPeriodicDiscountItem
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.retail.pos.contracts.dataentity.iperiodicdiscountitem(v=AX.60)
ms:contentKeyID: 49840391
author: tonyafehr
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity.IPeriodicDiscountItem
dev_langs:
- CSharp
- C++
- VB
---

# IPeriodicDiscountItem Interface


[!INCLUDE[archive-banner](includes/archive-banner.md)]

IPeriodicDiscountItem interface.

**Namespace:**  [Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity](microsoft-dynamics-retail-pos-contracts-dataentity-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Retail.Pos.Contracts (in Microsoft.Dynamics.Retail.Pos.Contracts.dll)

## Syntax

``` vb
'Declaration
<GuidAttribute("DDC36F5E-82CD-4AE5-8924-9853F963F2D1")> _
Public Interface IPeriodicDiscountItem _
    Inherits ILineDiscountItem, IDiscountItem, IDiscountItemV1, IDiscountItemV2,  _
    IPeriodicDiscountItemV1
'Usage
Dim instance As IPeriodicDiscountItem
```

``` csharp
[GuidAttribute("DDC36F5E-82CD-4AE5-8924-9853F963F2D1")]
public interface IPeriodicDiscountItem : ILineDiscountItem, 
    IDiscountItem, IDiscountItemV1, IDiscountItemV2, IPeriodicDiscountItemV1
```

``` c++
[GuidAttribute(L"DDC36F5E-82CD-4AE5-8924-9853F963F2D1")]
public interface class IPeriodicDiscountItem : ILineDiscountItem, 
    IDiscountItem, IDiscountItemV1, IDiscountItemV2, IPeriodicDiscountItemV1
```

## See Also

#### Reference

[Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity Namespace](microsoft-dynamics-retail-pos-contracts-dataentity-namespace.md)

