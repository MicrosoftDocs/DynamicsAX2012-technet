---
title: IDiscountV1.AddDiscountLine Method  (Microsoft.Dynamics.Retail.Pos.Contracts.Services)
TOCTitle: AddDiscountLine Method
ms:assetid: M:Microsoft.Dynamics.Retail.Pos.Contracts.Services.IDiscountV1.AddDiscountLine(Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity.ISaleLineItem,Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity.IDiscountItem)
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.retail.pos.contracts.services.idiscountv1.adddiscountline(v=AX.60)
ms:contentKeyID: 62204387
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Retail.Pos.Contracts.Services.IDiscountV1.AddDiscountLine
dev_langs:
- CSharp
- C++
- VB
---

# AddDiscountLine Method


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Add discount line

**Namespace:**  [Microsoft.Dynamics.Retail.Pos.Contracts.Services](microsoft-dynamics-retail-pos-contracts-services-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Retail.Pos.Contracts (in Microsoft.Dynamics.Retail.Pos.Contracts.dll)

## Syntax

``` vb
'Declaration
Sub AddDiscountLine ( _
    lineItem As ISaleLineItem, _
    discountItem As IDiscountItem _
)
'Usage
Dim instance As IDiscountV1
Dim lineItem As ISaleLineItem
Dim discountItem As IDiscountItem

instance.AddDiscountLine(lineItem, discountItem)
```

``` csharp
void AddDiscountLine(
    ISaleLineItem lineItem,
    IDiscountItem discountItem
)
```

``` c++
void AddDiscountLine(
    ISaleLineItem^ lineItem, 
    IDiscountItem^ discountItem
)
```

#### Parameters

  - lineItem  
    Type: [Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity.ISaleLineItem](isalelineitem-interface-microsoft-dynamics-retail-pos-contracts-dataentity.md)  

<!-- end list -->

  - discountItem  
    Type: [Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity.IDiscountItem](idiscountitem-interface-microsoft-dynamics-retail-pos-contracts-dataentity.md)  

## See Also

#### Reference

[IDiscountV1 Interface](idiscountv1-interface-microsoft-dynamics-retail-pos-contracts-services.md)

[Microsoft.Dynamics.Retail.Pos.Contracts.Services Namespace](microsoft-dynamics-retail-pos-contracts-services-namespace.md)

