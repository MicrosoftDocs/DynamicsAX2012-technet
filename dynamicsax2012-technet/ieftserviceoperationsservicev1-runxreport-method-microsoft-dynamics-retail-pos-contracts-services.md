---
title: IEFTServiceOperationsServiceV1.RunXReport Method  (Microsoft.Dynamics.Retail.Pos.Contracts.Services)
TOCTitle: RunXReport Method
ms:assetid: M:Microsoft.Dynamics.Retail.Pos.Contracts.Services.IEFTServiceOperationsServiceV1.RunXReport(Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity.IPosTransaction)
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.retail.pos.contracts.services.ieftserviceoperationsservicev1.runxreport(v=AX.60)
ms:contentKeyID: 62203531
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Retail.Pos.Contracts.Services.IEFTServiceOperationsServiceV1.RunXReport
dev_langs:
- CSharp
- C++
- VB
---

# RunXReport Method


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Run bank X Report

**Namespace:**  [Microsoft.Dynamics.Retail.Pos.Contracts.Services](microsoft-dynamics-retail-pos-contracts-services-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Retail.Pos.Contracts (in Microsoft.Dynamics.Retail.Pos.Contracts.dll)

## Syntax

``` vb
'Declaration
Sub RunXReport ( _
    posTransaction As IPosTransaction _
)
'Usage
Dim instance As IEFTServiceOperationsServiceV1
Dim posTransaction As IPosTransaction

instance.RunXReport(posTransaction)
```

``` csharp
void RunXReport(
    IPosTransaction posTransaction
)
```

``` c++
void RunXReport(
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

