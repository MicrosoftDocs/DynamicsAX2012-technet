---
title: IRFIDV1.MarkProcessedRFIDs Method  (Microsoft.Dynamics.Retail.Pos.Contracts.Services)
TOCTitle: MarkProcessedRFIDs Method
ms:assetid: M:Microsoft.Dynamics.Retail.Pos.Contracts.Services.IRFIDV1.MarkProcessedRFIDs(Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity.IRetailTransaction)
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.retail.pos.contracts.services.irfidv1.markprocessedrfids(v=AX.60)
ms:contentKeyID: 47344239
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Retail.Pos.Contracts.Services.IRFIDV1.MarkProcessedRFIDs
dev_langs:
- CSharp
- C++
- VB
---

# MarkProcessedRFIDs Method


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Associates a transaction with scanned items that are sent to retail POS in the GetUnProcessedRFID.

**Namespace:**  [Microsoft.Dynamics.Retail.Pos.Contracts.Services](microsoft-dynamics-retail-pos-contracts-services-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Retail.Pos.Contracts (in Microsoft.Dynamics.Retail.Pos.Contracts.dll)

## Syntax

``` vb
'Declaration
Sub MarkProcessedRFIDs ( _
    transaction As IRetailTransaction _
)
'Usage
Dim instance As IRFIDV1
Dim transaction As IRetailTransaction

instance.MarkProcessedRFIDs(transaction)
```

``` csharp
void MarkProcessedRFIDs(
    IRetailTransaction transaction
)
```

``` c++
void MarkProcessedRFIDs(
    IRetailTransaction^ transaction
)
```

#### Parameters

  - transaction  
    Type: [Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity.IRetailTransaction](iretailtransaction-interface-microsoft-dynamics-retail-pos-contracts-dataentity.md)  

## See Also

#### Reference

[IRFIDV1 Interface](irfidv1-interface-microsoft-dynamics-retail-pos-contracts-services.md)

[Microsoft.Dynamics.Retail.Pos.Contracts.Services Namespace](microsoft-dynamics-retail-pos-contracts-services-namespace.md)

