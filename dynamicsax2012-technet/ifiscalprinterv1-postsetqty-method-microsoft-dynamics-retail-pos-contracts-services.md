---
title: IFiscalPrinterV1.PostSetQty Method  (Microsoft.Dynamics.Retail.Pos.Contracts.Services)
TOCTitle: PostSetQty Method
ms:assetid: M:Microsoft.Dynamics.Retail.Pos.Contracts.Services.IFiscalPrinterV1.PostSetQty(Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity.IPosTransaction,Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity.ISaleLineItem)
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.retail.pos.contracts.services.ifiscalprinterv1.postsetqty(v=AX.60)
ms:contentKeyID: 62204506
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Retail.Pos.Contracts.Services.IFiscalPrinterV1.PostSetQty
dev_langs:
- CSharp
- C++
- VB
---

# PostSetQty Method

Triggered after setting the quantity of a sale line item at the transaction.

**Namespace:**  [Microsoft.Dynamics.Retail.Pos.Contracts.Services](microsoft-dynamics-retail-pos-contracts-services-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Retail.Pos.Contracts (in Microsoft.Dynamics.Retail.Pos.Contracts.dll)

## Syntax

``` vb
'Declaration
Sub PostSetQty ( _
    posTransaction As IPosTransaction, _
    saleLineItem As ISaleLineItem _
)
'Usage
Dim instance As IFiscalPrinterV1
Dim posTransaction As IPosTransaction
Dim saleLineItem As ISaleLineItem

instance.PostSetQty(posTransaction, saleLineItem)
```

``` csharp
void PostSetQty(
    IPosTransaction posTransaction,
    ISaleLineItem saleLineItem
)
```

``` c++
void PostSetQty(
    IPosTransaction^ posTransaction, 
    ISaleLineItem^ saleLineItem
)
```

#### Parameters

  - posTransaction  
    Type: [Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity.IPosTransaction](ipostransaction-interface-microsoft-dynamics-retail-pos-contracts-dataentity.md)  

<!-- end list -->

  - saleLineItem  
    Type: [Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity.ISaleLineItem](isalelineitem-interface-microsoft-dynamics-retail-pos-contracts-dataentity.md)  

## See Also

#### Reference

[IFiscalPrinterV1 Interface](ifiscalprinterv1-interface-microsoft-dynamics-retail-pos-contracts-services.md)

[Microsoft.Dynamics.Retail.Pos.Contracts.Services Namespace](microsoft-dynamics-retail-pos-contracts-services-namespace.md)

