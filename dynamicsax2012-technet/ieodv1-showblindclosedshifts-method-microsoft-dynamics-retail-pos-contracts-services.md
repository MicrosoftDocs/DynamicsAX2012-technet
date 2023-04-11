---
title: IEODV1.ShowBlindClosedShifts Method  (Microsoft.Dynamics.Retail.Pos.Contracts.Services)
TOCTitle: ShowBlindClosedShifts Method
ms:assetid: M:Microsoft.Dynamics.Retail.Pos.Contracts.Services.IEODV1.ShowBlindClosedShifts(Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity.IPosTransaction)
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.retail.pos.contracts.services.ieodv1.showblindclosedshifts(v=AX.60)
ms:contentKeyID: 47344040
author: tonyafehr
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Retail.Pos.Contracts.Services.IEODV1.ShowBlindClosedShifts
dev_langs:
- CSharp
- C++
- VB
---

# ShowBlindClosedShifts Method


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Displays UI with a list of the current blind closed shifts.

**Namespace:**  [Microsoft.Dynamics.Retail.Pos.Contracts.Services](microsoft-dynamics-retail-pos-contracts-services-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Retail.Pos.Contracts (in Microsoft.Dynamics.Retail.Pos.Contracts.dll)

## Syntax

``` vb
'Declaration
Sub ShowBlindClosedShifts ( _
    transaction As IPosTransaction _
)
'Usage
Dim instance As IEODV1
Dim transaction As IPosTransaction

instance.ShowBlindClosedShifts(transaction)
```

``` csharp
void ShowBlindClosedShifts(
    IPosTransaction transaction
)
```

``` c++
void ShowBlindClosedShifts(
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

