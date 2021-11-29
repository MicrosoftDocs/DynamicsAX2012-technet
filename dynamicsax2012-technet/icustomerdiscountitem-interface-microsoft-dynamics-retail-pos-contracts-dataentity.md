---
title: ICustomerDiscountItem Interface (Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity)
TOCTitle: ICustomerDiscountItem Interface
ms:assetid: T:Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity.ICustomerDiscountItem
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.retail.pos.contracts.dataentity.icustomerdiscountitem(v=AX.60)
ms:contentKeyID: 49846338
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity.ICustomerDiscountItem
dev_langs:
- CSharp
- C++
- VB
---

# ICustomerDiscountItem Interface


[!INCLUDE[archive-banner](includes/archive-banner.md)]

ICustomerDiscountItem interface.

**Namespace:**  [Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity](microsoft-dynamics-retail-pos-contracts-dataentity-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Retail.Pos.Contracts (in Microsoft.Dynamics.Retail.Pos.Contracts.dll)

## Syntax

``` vb
'Declaration
<GuidAttribute("19513F0C-E966-4683-B052-7B74B993CA2E")> _
Public Interface ICustomerDiscountItem _
    Inherits ILineDiscountItem, IDiscountItem, IDiscountItemV1, IDiscountItemV2,  _
    ICustomerDiscountItemV1
'Usage
Dim instance As ICustomerDiscountItem
```

``` csharp
[GuidAttribute("19513F0C-E966-4683-B052-7B74B993CA2E")]
public interface ICustomerDiscountItem : ILineDiscountItem, 
    IDiscountItem, IDiscountItemV1, IDiscountItemV2, ICustomerDiscountItemV1
```

``` c++
[GuidAttribute(L"19513F0C-E966-4683-B052-7B74B993CA2E")]
public interface class ICustomerDiscountItem : ILineDiscountItem, 
    IDiscountItem, IDiscountItemV1, IDiscountItemV2, ICustomerDiscountItemV1
```

## See Also

#### Reference

[Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity Namespace](microsoft-dynamics-retail-pos-contracts-dataentity-namespace.md)

