---
title: IFiscalPrinterV1.PreReturnTransaction Method  (Microsoft.Dynamics.Retail.Pos.Contracts.Services)
TOCTitle: PreReturnTransaction Method
ms:assetid: M:Microsoft.Dynamics.Retail.Pos.Contracts.Services.IFiscalPrinterV1.PreReturnTransaction(Microsoft.Dynamics.Retail.Pos.Contracts.Triggers.IPreTriggerResult,Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity.IRetailTransaction,Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity.IPosTransaction)
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.retail.pos.contracts.services.ifiscalprinterv1.prereturntransaction(v=AX.60)
ms:contentKeyID: 62202029
author: tonyafehr
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Retail.Pos.Contracts.Services.IFiscalPrinterV1.PreReturnTransaction
dev_langs:
- CSharp
- C++
- VB
---

# PreReturnTransaction Method


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Triggered prior to returning.

**Namespace:**  [Microsoft.Dynamics.Retail.Pos.Contracts.Services](microsoft-dynamics-retail-pos-contracts-services-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Retail.Pos.Contracts (in Microsoft.Dynamics.Retail.Pos.Contracts.dll)

## Syntax

``` vb
'Declaration
Sub PreReturnTransaction ( _
    preTriggerResult As IPreTriggerResult, _
    originalTransaction As IRetailTransaction, _
    posTransaction As IPosTransaction _
)
'Usage
Dim instance As IFiscalPrinterV1
Dim preTriggerResult As IPreTriggerResult
Dim originalTransaction As IRetailTransaction
Dim posTransaction As IPosTransaction

instance.PreReturnTransaction(preTriggerResult, _
    originalTransaction, posTransaction)
```

``` csharp
void PreReturnTransaction(
    IPreTriggerResult preTriggerResult,
    IRetailTransaction originalTransaction,
    IPosTransaction posTransaction
)
```

``` c++
void PreReturnTransaction(
    IPreTriggerResult^ preTriggerResult, 
    IRetailTransaction^ originalTransaction, 
    IPosTransaction^ posTransaction
)
```

#### Parameters

  - preTriggerResult  
    Type: [Microsoft.Dynamics.Retail.Pos.Contracts.Triggers.IPreTriggerResult](ipretriggerresult-interface-microsoft-dynamics-retail-pos-contracts-triggers.md)  

<!-- end list -->

  - originalTransaction  
    Type: [Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity.IRetailTransaction](iretailtransaction-interface-microsoft-dynamics-retail-pos-contracts-dataentity.md)  

<!-- end list -->

  - posTransaction  
    Type: [Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity.IPosTransaction](ipostransaction-interface-microsoft-dynamics-retail-pos-contracts-dataentity.md)  

## See Also

#### Reference

[IFiscalPrinterV1 Interface](ifiscalprinterv1-interface-microsoft-dynamics-retail-pos-contracts-services.md)

[Microsoft.Dynamics.Retail.Pos.Contracts.Services Namespace](microsoft-dynamics-retail-pos-contracts-services-namespace.md)

