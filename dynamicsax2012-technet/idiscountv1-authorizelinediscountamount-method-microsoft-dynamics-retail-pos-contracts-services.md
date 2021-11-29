---
title: IDiscountV1.AuthorizeLineDiscountAmount Method  (Microsoft.Dynamics.Retail.Pos.Contracts.Services)
TOCTitle: AuthorizeLineDiscountAmount Method
ms:assetid: M:Microsoft.Dynamics.Retail.Pos.Contracts.Services.IDiscountV1.AuthorizeLineDiscountAmount(Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity.ISaleLineItem,Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity.ILineDiscountItem,System.Decimal)
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.retail.pos.contracts.services.idiscountv1.authorizelinediscountamount(v=AX.60)
ms:contentKeyID: 47344220
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Retail.Pos.Contracts.Services.IDiscountV1.AuthorizeLineDiscountAmount
dev_langs:
- CSharp
- C++
- VB
---

# AuthorizeLineDiscountAmount Method


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Indicates whether the given line discount amount is allowed.

**Namespace:**  [Microsoft.Dynamics.Retail.Pos.Contracts.Services](microsoft-dynamics-retail-pos-contracts-services-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Retail.Pos.Contracts (in Microsoft.Dynamics.Retail.Pos.Contracts.dll)

## Syntax

``` vb
'Declaration
Function AuthorizeLineDiscountAmount ( _
    saleLineItem As ISaleLineItem, _
    lineDiscountItem As ILineDiscountItem, _
    maximumDiscountAmt As Decimal _
) As Boolean
'Usage
Dim instance As IDiscountV1
Dim saleLineItem As ISaleLineItem
Dim lineDiscountItem As ILineDiscountItem
Dim maximumDiscountAmt As Decimal
Dim returnValue As Boolean

returnValue = instance.AuthorizeLineDiscountAmount(saleLineItem, _
    lineDiscountItem, maximumDiscountAmt)
```

``` csharp
bool AuthorizeLineDiscountAmount(
    ISaleLineItem saleLineItem,
    ILineDiscountItem lineDiscountItem,
    decimal maximumDiscountAmt
)
```

``` c++
bool AuthorizeLineDiscountAmount(
    ISaleLineItem^ saleLineItem, 
    ILineDiscountItem^ lineDiscountItem, 
    Decimal maximumDiscountAmt
)
```

#### Parameters

  - saleLineItem  
    Type: [Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity.ISaleLineItem](isalelineitem-interface-microsoft-dynamics-retail-pos-contracts-dataentity.md)  

<!-- end list -->

  - lineDiscountItem  
    Type: [Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity.ILineDiscountItem](ilinediscountitem-interface-microsoft-dynamics-retail-pos-contracts-dataentity.md)  

<!-- end list -->

  - maximumDiscountAmt  
    Type: [System.Decimal](https://technet.microsoft.com/library/1k2e8atx\(v=ax.60\))  

#### Return Value

Type: [System.Boolean](https://technet.microsoft.com/library/a28wyd50\(v=ax.60\))  
true if discount amount is allowed; otherwise, false.  

## Remarks

This method is invoked by the line discount amount operation before calling the AuthorizeTotalDiscountAmount method.

## See Also

#### Reference

[IDiscountV1 Interface](idiscountv1-interface-microsoft-dynamics-retail-pos-contracts-services.md)

[Microsoft.Dynamics.Retail.Pos.Contracts.Services Namespace](microsoft-dynamics-retail-pos-contracts-services-namespace.md)

