---
title: IFiscalPrinterV1.PreCustomer Method  (Microsoft.Dynamics.Retail.Pos.Contracts.Services)
TOCTitle: PreCustomer Method
ms:assetid: M:Microsoft.Dynamics.Retail.Pos.Contracts.Services.IFiscalPrinterV1.PreCustomer(Microsoft.Dynamics.Retail.Pos.Contracts.Triggers.IPreTriggerResult,Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity.IPosTransaction)
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.retail.pos.contracts.services.ifiscalprinterv1.precustomer(v=AX.60)
ms:contentKeyID: 62205206
author: tonyafehr
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Retail.Pos.Contracts.Services.IFiscalPrinterV1.PreCustomer
dev_langs:
- CSharp
- C++
- VB
---

# PreCustomer Method


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Triggered prior to adding a customer to the transaction

**Namespace:**  [Microsoft.Dynamics.Retail.Pos.Contracts.Services](microsoft-dynamics-retail-pos-contracts-services-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Retail.Pos.Contracts (in Microsoft.Dynamics.Retail.Pos.Contracts.dll)

## Syntax

``` vb
'Declaration
Sub PreCustomer ( _
    preTriggerResult As IPreTriggerResult, _
    posTransaction As IPosTransaction _
)
'Usage
Dim instance As IFiscalPrinterV1
Dim preTriggerResult As IPreTriggerResult
Dim posTransaction As IPosTransaction

instance.PreCustomer(preTriggerResult, _
    posTransaction)
```

``` csharp
void PreCustomer(
    IPreTriggerResult preTriggerResult,
    IPosTransaction posTransaction
)
```

``` c++
void PreCustomer(
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

