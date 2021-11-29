---
title: IDiscountV1.AuthorizeLineDiscountPercent Method  (Microsoft.Dynamics.Retail.Pos.Contracts.Services)
TOCTitle: AuthorizeLineDiscountPercent Method
ms:assetid: M:Microsoft.Dynamics.Retail.Pos.Contracts.Services.IDiscountV1.AuthorizeLineDiscountPercent(Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity.ISaleLineItem,Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity.ILineDiscountItem,System.Decimal)
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.retail.pos.contracts.services.idiscountv1.authorizelinediscountpercent(v=AX.60)
ms:contentKeyID: 47344327
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Retail.Pos.Contracts.Services.IDiscountV1.AuthorizeLineDiscountPercent
dev_langs:
- CSharp
- C++
- VB
---

# AuthorizeLineDiscountPercent Method


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Indicates whether the given percentage discount is allowed.

This method is invoked by the line discount percentage operation.

**Namespace:**  [Microsoft.Dynamics.Retail.Pos.Contracts.Services](microsoft-dynamics-retail-pos-contracts-services-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Retail.Pos.Contracts (in Microsoft.Dynamics.Retail.Pos.Contracts.dll)

## Syntax

``` vb
'Declaration
Function AuthorizeLineDiscountPercent ( _
    saleLineItem As ISaleLineItem, _
    lineDiscountItem As ILineDiscountItem, _
    maximumDiscountPct As Decimal _
) As Boolean
'Usage
Dim instance As IDiscountV1
Dim saleLineItem As ISaleLineItem
Dim lineDiscountItem As ILineDiscountItem
Dim maximumDiscountPct As Decimal
Dim returnValue As Boolean

returnValue = instance.AuthorizeLineDiscountPercent(saleLineItem, _
    lineDiscountItem, maximumDiscountPct)
```

``` csharp
bool AuthorizeLineDiscountPercent(
    ISaleLineItem saleLineItem,
    ILineDiscountItem lineDiscountItem,
    decimal maximumDiscountPct
)
```

``` c++
bool AuthorizeLineDiscountPercent(
    ISaleLineItem^ saleLineItem, 
    ILineDiscountItem^ lineDiscountItem, 
    Decimal maximumDiscountPct
)
```

#### Parameters

  - saleLineItem  
    Type: [Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity.ISaleLineItem](isalelineitem-interface-microsoft-dynamics-retail-pos-contracts-dataentity.md)  

<!-- end list -->

  - lineDiscountItem  
    Type: [Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity.ILineDiscountItem](ilinediscountitem-interface-microsoft-dynamics-retail-pos-contracts-dataentity.md)  

<!-- end list -->

  - maximumDiscountPct  
    Type: [System.Decimal](https://technet.microsoft.com/library/1k2e8atx\(v=ax.60\))  

#### Return Value

Type: [System.Boolean](https://technet.microsoft.com/library/a28wyd50\(v=ax.60\))  
true, if the discount percent is allowed otherwise, false.  

## See Also

#### Reference

[IDiscountV1 Interface](idiscountv1-interface-microsoft-dynamics-retail-pos-contracts-services.md)

[Microsoft.Dynamics.Retail.Pos.Contracts.Services Namespace](microsoft-dynamics-retail-pos-contracts-services-namespace.md)

