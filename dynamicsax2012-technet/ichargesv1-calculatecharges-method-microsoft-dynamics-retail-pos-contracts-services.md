---
title: IChargesV1.CalculateCharges Method  (Microsoft.Dynamics.Retail.Pos.Contracts.Services)
TOCTitle: CalculateCharges Method
ms:assetid: M:Microsoft.Dynamics.Retail.Pos.Contracts.Services.IChargesV1.CalculateCharges(Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity.IRetailTransaction)
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.retail.pos.contracts.services.ichargesv1.calculatecharges(v=AX.60)
ms:contentKeyID: 49855265
author: tonyafehr
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Retail.Pos.Contracts.Services.IChargesV1.CalculateCharges
dev_langs:
- CSharp
- C++
- VB
---

# CalculateCharges Method


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Calculates the charges.

**Namespace:**  [Microsoft.Dynamics.Retail.Pos.Contracts.Services](microsoft-dynamics-retail-pos-contracts-services-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Retail.Pos.Contracts (in Microsoft.Dynamics.Retail.Pos.Contracts.dll)

## Syntax

``` vb
'Declaration
Sub CalculateCharges ( _
    transaction As IRetailTransaction _
)
'Usage
Dim instance As IChargesV1
Dim transaction As IRetailTransaction

instance.CalculateCharges(transaction)
```

``` csharp
void CalculateCharges(
    IRetailTransaction transaction
)
```

``` c++
void CalculateCharges(
    IRetailTransaction^ transaction
)
```

#### Parameters

  - transaction  
    Type: [Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity.IRetailTransaction](iretailtransaction-interface-microsoft-dynamics-retail-pos-contracts-dataentity.md)  

## See Also

#### Reference

[IChargesV1 Interface](ichargesv1-interface-microsoft-dynamics-retail-pos-contracts-services.md)

[Microsoft.Dynamics.Retail.Pos.Contracts.Services Namespace](microsoft-dynamics-retail-pos-contracts-services-namespace.md)

