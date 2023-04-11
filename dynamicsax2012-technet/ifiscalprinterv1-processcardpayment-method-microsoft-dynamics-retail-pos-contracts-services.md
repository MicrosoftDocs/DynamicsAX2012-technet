---
title: IFiscalPrinterV1.ProcessCardPayment Method  (Microsoft.Dynamics.Retail.Pos.Contracts.Services)
TOCTitle: ProcessCardPayment Method
ms:assetid: M:Microsoft.Dynamics.Retail.Pos.Contracts.Services.IFiscalPrinterV1.ProcessCardPayment(Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity.IEFTInfo,Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity.IRetailTransaction)
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.retail.pos.contracts.services.ifiscalprinterv1.processcardpayment(v=AX.60)
ms:contentKeyID: 62204843
author: tonyafehr
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Retail.Pos.Contracts.Services.IFiscalPrinterV1.ProcessCardPayment
dev_langs:
- CSharp
- C++
- VB
---

# ProcessCardPayment Method


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Processes the card payment for the EFT provider.

**Namespace:**  [Microsoft.Dynamics.Retail.Pos.Contracts.Services](microsoft-dynamics-retail-pos-contracts-services-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Retail.Pos.Contracts (in Microsoft.Dynamics.Retail.Pos.Contracts.dll)

## Syntax

``` vb
'Declaration
Sub ProcessCardPayment ( _
    info As IEFTInfo, _
    transaction As IRetailTransaction _
)
'Usage
Dim instance As IFiscalPrinterV1
Dim info As IEFTInfo
Dim transaction As IRetailTransaction

instance.ProcessCardPayment(info, transaction)
```

``` csharp
void ProcessCardPayment(
    IEFTInfo info,
    IRetailTransaction transaction
)
```

``` c++
void ProcessCardPayment(
    IEFTInfo^ info, 
    IRetailTransaction^ transaction
)
```

#### Parameters

  - info  
    Type: [Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity.IEFTInfo](ieftinfo-interface-microsoft-dynamics-retail-pos-contracts-dataentity.md)  

<!-- end list -->

  - transaction  
    Type: [Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity.IRetailTransaction](iretailtransaction-interface-microsoft-dynamics-retail-pos-contracts-dataentity.md)  

## See Also

#### Reference

[IFiscalPrinterV1 Interface](ifiscalprinterv1-interface-microsoft-dynamics-retail-pos-contracts-services.md)

[Microsoft.Dynamics.Retail.Pos.Contracts.Services Namespace](microsoft-dynamics-retail-pos-contracts-services-namespace.md)

