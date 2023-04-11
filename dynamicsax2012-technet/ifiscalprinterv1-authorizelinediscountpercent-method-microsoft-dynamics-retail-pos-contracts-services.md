---
title: IFiscalPrinterV1.AuthorizeLineDiscountPercent Method  (Microsoft.Dynamics.Retail.Pos.Contracts.Services)
TOCTitle: AuthorizeLineDiscountPercent Method
ms:assetid: M:Microsoft.Dynamics.Retail.Pos.Contracts.Services.IFiscalPrinterV1.AuthorizeLineDiscountPercent(Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity.ISaleLineItem,Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity.ILineDiscountItem,System.Decimal)
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.retail.pos.contracts.services.ifiscalprinterv1.authorizelinediscountpercent(v=AX.60)
ms:contentKeyID: 62202371
author: tonyafehr
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Retail.Pos.Contracts.Services.IFiscalPrinterV1.AuthorizeLineDiscountPercent
dev_langs:
- CSharp
- C++
- VB
---

# AuthorizeLineDiscountPercent Method


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Returns true if discount percent is correct.

**Namespace:**  [Microsoft.Dynamics.Retail.Pos.Contracts.Services](microsoft-dynamics-retail-pos-contracts-services-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Retail.Pos.Contracts (in Microsoft.Dynamics.Retail.Pos.Contracts.dll)

## Syntax

``` vb
'Declaration
Function AuthorizeLineDiscountPercent ( _
    lineItem As ISaleLineItem, _
    discountItem As ILineDiscountItem, _
    maximumDiscountPct As Decimal _
) As Boolean
'Usage
Dim instance As IFiscalPrinterV1
Dim lineItem As ISaleLineItem
Dim discountItem As ILineDiscountItem
Dim maximumDiscountPct As Decimal
Dim returnValue As Boolean

returnValue = instance.AuthorizeLineDiscountPercent(lineItem, _
    discountItem, maximumDiscountPct)
```

``` csharp
bool AuthorizeLineDiscountPercent(
    ISaleLineItem lineItem,
    ILineDiscountItem discountItem,
    decimal maximumDiscountPct
)
```

``` c++
bool AuthorizeLineDiscountPercent(
    ISaleLineItem^ lineItem, 
    ILineDiscountItem^ discountItem, 
    Decimal maximumDiscountPct
)
```

#### Parameters

  - lineItem  
    Type: [Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity.ISaleLineItem](isalelineitem-interface-microsoft-dynamics-retail-pos-contracts-dataentity.md)  

<!-- end list -->

  - discountItem  
    Type: [Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity.ILineDiscountItem](ilinediscountitem-interface-microsoft-dynamics-retail-pos-contracts-dataentity.md)  

<!-- end list -->

  - maximumDiscountPct  
    Type: [System.Decimal](https://technet.microsoft.com/library/1k2e8atx\(v=ax.60\))  

#### Return Value

Type: [System.Boolean](https://technet.microsoft.com/library/a28wyd50\(v=ax.60\))  

## See Also

#### Reference

[IFiscalPrinterV1 Interface](ifiscalprinterv1-interface-microsoft-dynamics-retail-pos-contracts-services.md)

[Microsoft.Dynamics.Retail.Pos.Contracts.Services Namespace](microsoft-dynamics-retail-pos-contracts-services-namespace.md)

