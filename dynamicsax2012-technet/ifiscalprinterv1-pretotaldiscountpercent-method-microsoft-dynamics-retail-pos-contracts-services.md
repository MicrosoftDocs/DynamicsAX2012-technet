---
title: IFiscalPrinterV1.PreTotalDiscountPercent Method  (Microsoft.Dynamics.Retail.Pos.Contracts.Services)
TOCTitle: PreTotalDiscountPercent Method
ms:assetid: M:Microsoft.Dynamics.Retail.Pos.Contracts.Services.IFiscalPrinterV1.PreTotalDiscountPercent(Microsoft.Dynamics.Retail.Pos.Contracts.Triggers.IPreTriggerResult,Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity.IPosTransaction)
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.retail.pos.contracts.services.ifiscalprinterv1.pretotaldiscountpercent(v=AX.60)
ms:contentKeyID: 62201739
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Retail.Pos.Contracts.Services.IFiscalPrinterV1.PreTotalDiscountPercent
dev_langs:
- CSharp
- C++
- VB
---

# PreTotalDiscountPercent Method


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Triggered prior to setting a total discount percent to the transaction.

**Namespace:**  [Microsoft.Dynamics.Retail.Pos.Contracts.Services](microsoft-dynamics-retail-pos-contracts-services-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Retail.Pos.Contracts (in Microsoft.Dynamics.Retail.Pos.Contracts.dll)

## Syntax

``` vb
'Declaration
Sub PreTotalDiscountPercent ( _
    preTriggerResult As IPreTriggerResult, _
    posTransaction As IPosTransaction _
)
'Usage
Dim instance As IFiscalPrinterV1
Dim preTriggerResult As IPreTriggerResult
Dim posTransaction As IPosTransaction

instance.PreTotalDiscountPercent(preTriggerResult, _
    posTransaction)
```

``` csharp
void PreTotalDiscountPercent(
    IPreTriggerResult preTriggerResult,
    IPosTransaction posTransaction
)
```

``` c++
void PreTotalDiscountPercent(
    IPreTriggerResult^ preTriggerResult, 
    IPosTransaction^ posTransaction
)
```

#### Parameters

  - preTriggerResult  
    Type: [Microsoft.Dynamics.Retail.Pos.Contracts.Triggers.IPreTriggerResult](ipretriggerresult-interface-microsoft-dynamics-retail-pos-contracts-triggers.md)  

<!-- end list -->

  - posTransaction  
    Type: [Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity.IPosTransaction](ipostransaction-interface-microsoft-dynamics-retail-pos-contracts-dataentity.md)  

## See Also

#### Reference

[IFiscalPrinterV1 Interface](ifiscalprinterv1-interface-microsoft-dynamics-retail-pos-contracts-services.md)

[Microsoft.Dynamics.Retail.Pos.Contracts.Services Namespace](microsoft-dynamics-retail-pos-contracts-services-namespace.md)

