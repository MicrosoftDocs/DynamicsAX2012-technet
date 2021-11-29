---
title: IFiscalPrinterV1.PreLineDiscountAmount Method  (Microsoft.Dynamics.Retail.Pos.Contracts.Services)
TOCTitle: PreLineDiscountAmount Method
ms:assetid: M:Microsoft.Dynamics.Retail.Pos.Contracts.Services.IFiscalPrinterV1.PreLineDiscountAmount(Microsoft.Dynamics.Retail.Pos.Contracts.Triggers.IPreTriggerResult,Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity.IPosTransaction,System.Int32)
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.retail.pos.contracts.services.ifiscalprinterv1.prelinediscountamount(v=AX.60)
ms:contentKeyID: 62205207
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Retail.Pos.Contracts.Services.IFiscalPrinterV1.PreLineDiscountAmount
dev_langs:
- CSharp
- C++
- VB
---

# PreLineDiscountAmount Method


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Triggered prior to setting a line discount amount to the transaction.

**Namespace:**  [Microsoft.Dynamics.Retail.Pos.Contracts.Services](microsoft-dynamics-retail-pos-contracts-services-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Retail.Pos.Contracts (in Microsoft.Dynamics.Retail.Pos.Contracts.dll)

## Syntax

``` vb
'Declaration
Sub PreLineDiscountAmount ( _
    preTriggerResult As IPreTriggerResult, _
    transaction As IPosTransaction, _
    lineId As Integer _
)
'Usage
Dim instance As IFiscalPrinterV1
Dim preTriggerResult As IPreTriggerResult
Dim transaction As IPosTransaction
Dim lineId As Integer

instance.PreLineDiscountAmount(preTriggerResult, _
    transaction, lineId)
```

``` csharp
void PreLineDiscountAmount(
    IPreTriggerResult preTriggerResult,
    IPosTransaction transaction,
    int lineId
)
```

``` c++
void PreLineDiscountAmount(
    IPreTriggerResult^ preTriggerResult, 
    IPosTransaction^ transaction, 
    int lineId
)
```

#### Parameters

  - preTriggerResult  
    Type: [Microsoft.Dynamics.Retail.Pos.Contracts.Triggers.IPreTriggerResult](ipretriggerresult-interface-microsoft-dynamics-retail-pos-contracts-triggers.md)  

<!-- end list -->

  - transaction  
    Type: [Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity.IPosTransaction](ipostransaction-interface-microsoft-dynamics-retail-pos-contracts-dataentity.md)  

<!-- end list -->

  - lineId  
    Type: [System.Int32](https://technet.microsoft.com/library/td2s409d\(v=ax.60\))  

## See Also

#### Reference

[IFiscalPrinterV1 Interface](ifiscalprinterv1-interface-microsoft-dynamics-retail-pos-contracts-services.md)

[Microsoft.Dynamics.Retail.Pos.Contracts.Services Namespace](microsoft-dynamics-retail-pos-contracts-services-namespace.md)

