---
title: IFiscalPrinterV1.PreVoidItem Method  (Microsoft.Dynamics.Retail.Pos.Contracts.Services)
TOCTitle: PreVoidItem Method
ms:assetid: M:Microsoft.Dynamics.Retail.Pos.Contracts.Services.IFiscalPrinterV1.PreVoidItem(Microsoft.Dynamics.Retail.Pos.Contracts.Triggers.IPreTriggerResult,Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity.IPosTransaction,System.Int32)
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.retail.pos.contracts.services.ifiscalprinterv1.prevoiditem(v=AX.60)
ms:contentKeyID: 62203720
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Retail.Pos.Contracts.Services.IFiscalPrinterV1.PreVoidItem
dev_langs:
- CSharp
- C++
- VB
---

# PreVoidItem Method

Triggered prior to voiding a sale line item at the transaction.

**Namespace:**  [Microsoft.Dynamics.Retail.Pos.Contracts.Services](microsoft-dynamics-retail-pos-contracts-services-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Retail.Pos.Contracts (in Microsoft.Dynamics.Retail.Pos.Contracts.dll)

## Syntax

``` vb
'Declaration
Sub PreVoidItem ( _
    preTriggerResult As IPreTriggerResult, _
    posTransaction As IPosTransaction, _
    lineId As Integer _
)
'Usage
Dim instance As IFiscalPrinterV1
Dim preTriggerResult As IPreTriggerResult
Dim posTransaction As IPosTransaction
Dim lineId As Integer

instance.PreVoidItem(preTriggerResult, _
    posTransaction, lineId)
```

``` csharp
void PreVoidItem(
    IPreTriggerResult preTriggerResult,
    IPosTransaction posTransaction,
    int lineId
)
```

``` c++
void PreVoidItem(
    IPreTriggerResult^ preTriggerResult, 
    IPosTransaction^ posTransaction, 
    int lineId
)
```

#### Parameters

  - preTriggerResult  
    Type: [Microsoft.Dynamics.Retail.Pos.Contracts.Triggers.IPreTriggerResult](ipretriggerresult-interface-microsoft-dynamics-retail-pos-contracts-triggers.md)  

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

