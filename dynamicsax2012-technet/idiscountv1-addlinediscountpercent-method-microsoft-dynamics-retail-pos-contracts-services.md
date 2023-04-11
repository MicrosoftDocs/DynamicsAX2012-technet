---
title: IDiscountV1.AddLineDiscountPercent Method  (Microsoft.Dynamics.Retail.Pos.Contracts.Services)
TOCTitle: AddLineDiscountPercent Method
ms:assetid: M:Microsoft.Dynamics.Retail.Pos.Contracts.Services.IDiscountV1.AddLineDiscountPercent(Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity.ISaleLineItem,Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity.ILineDiscountItem)
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.retail.pos.contracts.services.idiscountv1.addlinediscountpercent(v=AX.60)
ms:contentKeyID: 47344466
author: tonyafehr
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Retail.Pos.Contracts.Services.IDiscountV1.AddLineDiscountPercent
dev_langs:
- CSharp
- C++
- VB
---

# AddLineDiscountPercent Method


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Applies the percentage value to a specific line in a transaction.

**Namespace:**  [Microsoft.Dynamics.Retail.Pos.Contracts.Services](microsoft-dynamics-retail-pos-contracts-services-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Retail.Pos.Contracts (in Microsoft.Dynamics.Retail.Pos.Contracts.dll)

## Syntax

``` vb
'Declaration
Sub AddLineDiscountPercent ( _
    lineItem As ISaleLineItem, _
    discountItem As ILineDiscountItem _
)
'Usage
Dim instance As IDiscountV1
Dim lineItem As ISaleLineItem
Dim discountItem As ILineDiscountItem

instance.AddLineDiscountPercent(lineItem, _
    discountItem)
```

``` csharp
void AddLineDiscountPercent(
    ISaleLineItem lineItem,
    ILineDiscountItem discountItem
)
```

``` c++
void AddLineDiscountPercent(
    ISaleLineItem^ lineItem, 
    ILineDiscountItem^ discountItem
)
```

#### Parameters

  - lineItem  
    Type: [Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity.ISaleLineItem](isalelineitem-interface-microsoft-dynamics-retail-pos-contracts-dataentity.md)  

<!-- end list -->

  - discountItem  
    Type: [Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity.ILineDiscountItem](ilinediscountitem-interface-microsoft-dynamics-retail-pos-contracts-dataentity.md)  

## Remarks

This method is invoked by the line discount percentage operation.

## See Also

#### Reference

[IDiscountV1 Interface](idiscountv1-interface-microsoft-dynamics-retail-pos-contracts-services.md)

[Microsoft.Dynamics.Retail.Pos.Contracts.Services Namespace](microsoft-dynamics-retail-pos-contracts-services-namespace.md)

