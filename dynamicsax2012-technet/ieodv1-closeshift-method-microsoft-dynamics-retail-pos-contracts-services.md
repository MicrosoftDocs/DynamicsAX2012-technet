---
title: IEODV1.CloseShift Method  (Microsoft.Dynamics.Retail.Pos.Contracts.Services)
TOCTitle: CloseShift Method
ms:assetid: M:Microsoft.Dynamics.Retail.Pos.Contracts.Services.IEODV1.CloseShift(Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity.IPosTransaction)
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.retail.pos.contracts.services.ieodv1.closeshift(v=AX.60)
ms:contentKeyID: 47344353
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Retail.Pos.Contracts.Services.IEODV1.CloseShift
dev_langs:
- CSharp
- C++
- VB
---

# CloseShift Method

Closes the current shift and prints it as Z-Report.

**Namespace:**  [Microsoft.Dynamics.Retail.Pos.Contracts.Services](microsoft-dynamics-retail-pos-contracts-services-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Retail.Pos.Contracts (in Microsoft.Dynamics.Retail.Pos.Contracts.dll)

## Syntax

``` vb
'Declaration
Sub CloseShift ( _
    transaction As IPosTransaction _
)
'Usage
Dim instance As IEODV1
Dim transaction As IPosTransaction

instance.CloseShift(transaction)
```

``` csharp
void CloseShift(
    IPosTransaction transaction
)
```

``` c++
void CloseShift(
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

