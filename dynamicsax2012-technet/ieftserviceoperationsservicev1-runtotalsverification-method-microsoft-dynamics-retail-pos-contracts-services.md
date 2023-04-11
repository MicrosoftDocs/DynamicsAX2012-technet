---
title: IEFTServiceOperationsServiceV1.RunTotalsVerification Method  (Microsoft.Dynamics.Retail.Pos.Contracts.Services)
TOCTitle: RunTotalsVerification Method
ms:assetid: M:Microsoft.Dynamics.Retail.Pos.Contracts.Services.IEFTServiceOperationsServiceV1.RunTotalsVerification(Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity.IPosTransaction)
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.retail.pos.contracts.services.ieftserviceoperationsservicev1.runtotalsverification(v=AX.60)
ms:contentKeyID: 62203118
author: tonyafehr
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Retail.Pos.Contracts.Services.IEFTServiceOperationsServiceV1.RunTotalsVerification
dev_langs:
- CSharp
- C++
- VB
---

# RunTotalsVerification Method


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Run bank totals verification procedure

**Namespace:**  [Microsoft.Dynamics.Retail.Pos.Contracts.Services](microsoft-dynamics-retail-pos-contracts-services-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Retail.Pos.Contracts (in Microsoft.Dynamics.Retail.Pos.Contracts.dll)

## Syntax

``` vb
'Declaration
Sub RunTotalsVerification ( _
    posTransaction As IPosTransaction _
)
'Usage
Dim instance As IEFTServiceOperationsServiceV1
Dim posTransaction As IPosTransaction

instance.RunTotalsVerification(posTransaction)
```

``` csharp
void RunTotalsVerification(
    IPosTransaction posTransaction
)
```

``` c++
void RunTotalsVerification(
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

