---
title: ISalesOrderV1.CalculateDeposit Method  (Microsoft.Dynamics.Retail.Pos.Contracts.Services)
TOCTitle: CalculateDeposit Method
ms:assetid: M:Microsoft.Dynamics.Retail.Pos.Contracts.Services.ISalesOrderV1.CalculateDeposit(Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity.IRetailTransaction)
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.retail.pos.contracts.services.isalesorderv1.calculatedeposit(v=AX.60)
ms:contentKeyID: 47344284
author: tonyafehr
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Retail.Pos.Contracts.Services.ISalesOrderV1.CalculateDeposit
dev_langs:
- CSharp
- C++
- VB
---

# CalculateDeposit Method


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Computes the total deposit required for this sales order.

**Namespace:**  [Microsoft.Dynamics.Retail.Pos.Contracts.Services](microsoft-dynamics-retail-pos-contracts-services-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Retail.Pos.Contracts (in Microsoft.Dynamics.Retail.Pos.Contracts.dll)

## Syntax

``` vb
'Declaration
Sub CalculateDeposit ( _
    retailTransaction As IRetailTransaction _
)
'Usage
Dim instance As ISalesOrderV1
Dim retailTransaction As IRetailTransaction

instance.CalculateDeposit(retailTransaction)
```

``` csharp
void CalculateDeposit(
    IRetailTransaction retailTransaction
)
```

``` c++
void CalculateDeposit(
    IRetailTransaction^ retailTransaction
)
```

#### Parameters

  - retailTransaction  
    Type: [Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity.IRetailTransaction](iretailtransaction-interface-microsoft-dynamics-retail-pos-contracts-dataentity.md)  

## See Also

#### Reference

[ISalesOrderV1 Interface](isalesorderv1-interface-microsoft-dynamics-retail-pos-contracts-services.md)

[Microsoft.Dynamics.Retail.Pos.Contracts.Services Namespace](microsoft-dynamics-retail-pos-contracts-services-namespace.md)

