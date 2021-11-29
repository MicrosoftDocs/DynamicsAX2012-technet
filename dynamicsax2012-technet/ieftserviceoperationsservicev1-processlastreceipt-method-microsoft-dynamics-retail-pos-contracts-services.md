---
title: IEFTServiceOperationsServiceV1.ProcessLastReceipt Method  (Microsoft.Dynamics.Retail.Pos.Contracts.Services)
TOCTitle: ProcessLastReceipt Method
ms:assetid: M:Microsoft.Dynamics.Retail.Pos.Contracts.Services.IEFTServiceOperationsServiceV1.ProcessLastReceipt(Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity.IPosTransaction)
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.retail.pos.contracts.services.ieftserviceoperationsservicev1.processlastreceipt(v=AX.60)
ms:contentKeyID: 62202869
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Retail.Pos.Contracts.Services.IEFTServiceOperationsServiceV1.ProcessLastReceipt
dev_langs:
- CSharp
- C++
- VB
---

# ProcessLastReceipt Method


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Get bank cards last operation receipt

**Namespace:**  [Microsoft.Dynamics.Retail.Pos.Contracts.Services](microsoft-dynamics-retail-pos-contracts-services-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Retail.Pos.Contracts (in Microsoft.Dynamics.Retail.Pos.Contracts.dll)

## Syntax

``` vb
'Declaration
Sub ProcessLastReceipt ( _
    posTransaction As IPosTransaction _
)
'Usage
Dim instance As IEFTServiceOperationsServiceV1
Dim posTransaction As IPosTransaction

instance.ProcessLastReceipt(posTransaction)
```

``` csharp
void ProcessLastReceipt(
    IPosTransaction posTransaction
)
```

``` c++
void ProcessLastReceipt(
    IPosTransaction^ posTransaction
)
```

#### Parameters

  - posTransaction  
    Type: [Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity.IPosTransaction](ipostransaction-interface-microsoft-dynamics-retail-pos-contracts-dataentity.md)  

## See Also

#### Reference

[IEFTServiceOperationsServiceV1 Interface](ieftserviceoperationsservicev1-interface-microsoft-dynamics-retail-pos-contracts-services.md)

[Microsoft.Dynamics.Retail.Pos.Contracts.Services Namespace](microsoft-dynamics-retail-pos-contracts-services-namespace.md)

