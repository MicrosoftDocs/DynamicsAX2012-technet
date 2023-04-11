---
title: IEODV1.SuspendShift Method  (Microsoft.Dynamics.Retail.Pos.Contracts.Services)
TOCTitle: SuspendShift Method
ms:assetid: M:Microsoft.Dynamics.Retail.Pos.Contracts.Services.IEODV1.SuspendShift(Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity.IPosTransaction)
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.retail.pos.contracts.services.ieodv1.suspendshift(v=AX.60)
ms:contentKeyID: 47344263
author: tonyafehr
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Retail.Pos.Contracts.Services.IEODV1.SuspendShift
dev_langs:
- CSharp
- C++
- VB
---

# SuspendShift Method


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Suspends the current shift.

**Namespace:**  [Microsoft.Dynamics.Retail.Pos.Contracts.Services](microsoft-dynamics-retail-pos-contracts-services-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Retail.Pos.Contracts (in Microsoft.Dynamics.Retail.Pos.Contracts.dll)

## Syntax

``` vb
'Declaration
Sub SuspendShift ( _
    transaction As IPosTransaction _
)
'Usage
Dim instance As IEODV1
Dim transaction As IPosTransaction

instance.SuspendShift(transaction)
```

``` csharp
void SuspendShift(
    IPosTransaction transaction
)
```

``` c++
void SuspendShift(
    IPosTransaction^ transaction
)
```

#### Parameters

  - transaction  
    Type: [Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity.IPosTransaction](ipostransaction-interface-microsoft-dynamics-retail-pos-contracts-dataentity.md)  

## See Also

#### Reference

[IEODV1 Interface](ieodv1-interface-microsoft-dynamics-retail-pos-contracts-services.md)

[Microsoft.Dynamics.Retail.Pos.Contracts.Services Namespace](microsoft-dynamics-retail-pos-contracts-services-namespace.md)

