---
title: IFiscalPrinterV1.PreClearQty Method  (Microsoft.Dynamics.Retail.Pos.Contracts.Services)
TOCTitle: PreClearQty Method
ms:assetid: M:Microsoft.Dynamics.Retail.Pos.Contracts.Services.IFiscalPrinterV1.PreClearQty(Microsoft.Dynamics.Retail.Pos.Contracts.Triggers.IPreTriggerResult,Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity.ISaleLineItem,Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity.IPosTransaction,System.Int32)
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.retail.pos.contracts.services.ifiscalprinterv1.preclearqty(v=AX.60)
ms:contentKeyID: 62205198
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Retail.Pos.Contracts.Services.IFiscalPrinterV1.PreClearQty
dev_langs:
- CSharp
- C++
- VB
---

# PreClearQty Method

Triggered prior to clearing the quantity of a sale line item at the transaction.

**Namespace:**  [Microsoft.Dynamics.Retail.Pos.Contracts.Services](microsoft-dynamics-retail-pos-contracts-services-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Retail.Pos.Contracts (in Microsoft.Dynamics.Retail.Pos.Contracts.dll)

## Syntax

``` vb
'Declaration
Sub PreClearQty ( _
    preTriggerResult As IPreTriggerResult, _
    saleLineItem As ISaleLineItem, _
    posTransaction As IPosTransaction, _
    lineId As Integer _
)
'Usage
Dim instance As IFiscalPrinterV1
Dim preTriggerResult As IPreTriggerResult
Dim saleLineItem As ISaleLineItem
Dim posTransaction As IPosTransaction
Dim lineId As Integer

instance.PreClearQty(preTriggerResult, _
    saleLineItem, posTransaction, lineId)
```

``` csharp
void PreClearQty(
    IPreTriggerResult preTriggerResult,
    ISaleLineItem saleLineItem,
    IPosTransaction posTransaction,
    int lineId
)
```

``` c++
void PreClearQty(
    IPreTriggerResult^ preTriggerResult, 
    ISaleLineItem^ saleLineItem, 
    IPosTransaction^ posTransaction, 
    int lineId
)
```

#### Parameters

  - preTriggerResult  
    Type: [Microsoft.Dynamics.Retail.Pos.Contracts.Triggers.IPreTriggerResult](ipretriggerresult-interface-microsoft-dynamics-retail-pos-contracts-triggers.md)  

<!-- end list -->

  - saleLineItem  
    Type: [Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity.ISaleLineItem](isalelineitem-interface-microsoft-dynamics-retail-pos-contracts-dataentity.md)  

<!-- end list -->

  - posTransaction  
    Type: [Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity.IPosTransaction](ipostransaction-interface-microsoft-dynamics-retail-pos-contracts-dataentity.md)  

<!-- end list -->

  - lineId  
    Type: [System.Int32](https://technet.microsoft.com/library/td2s409d\(v=ax.60\))  

## See Also

#### Reference

[IFiscalPrinterV1 Interface](ifiscalprinterv1-interface-microsoft-dynamics-retail-pos-contracts-services.md)

[Microsoft.Dynamics.Retail.Pos.Contracts.Services Namespace](microsoft-dynamics-retail-pos-contracts-services-namespace.md)

