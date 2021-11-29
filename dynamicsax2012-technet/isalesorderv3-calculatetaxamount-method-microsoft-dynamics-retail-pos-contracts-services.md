---
title: ISalesOrderV3.CalculateTaxAmount Method  (Microsoft.Dynamics.Retail.Pos.Contracts.Services)
TOCTitle: CalculateTaxAmount Method
ms:assetid: M:Microsoft.Dynamics.Retail.Pos.Contracts.Services.ISalesOrderV3.CalculateTaxAmount(Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity.IRetailTransaction)
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.retail.pos.contracts.services.isalesorderv3.calculatetaxamount(v=AX.60)
ms:contentKeyID: 51677227
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Retail.Pos.Contracts.Services.ISalesOrderV3.CalculateTaxAmount
dev_langs:
- CSharp
- C++
- VB
---

# CalculateTaxAmount Method


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Compute the tax amount for this Sales Order

**Namespace:**  [Microsoft.Dynamics.Retail.Pos.Contracts.Services](microsoft-dynamics-retail-pos-contracts-services-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Retail.Pos.Contracts (in Microsoft.Dynamics.Retail.Pos.Contracts.dll)

## Syntax

``` vb
'Declaration
Sub CalculateTaxAmount ( _
    retailTransaction As IRetailTransaction _
)
'Usage
Dim instance As ISalesOrderV3
Dim retailTransaction As IRetailTransaction

instance.CalculateTaxAmount(retailTransaction)
```

``` csharp
void CalculateTaxAmount(
    IRetailTransaction retailTransaction
)
```

``` c++
void CalculateTaxAmount(
    IRetailTransaction^ retailTransaction
)
```

#### Parameters

  - retailTransaction  
    Type: [Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity.IRetailTransaction](iretailtransaction-interface-microsoft-dynamics-retail-pos-contracts-dataentity.md)  

## See Also

#### Reference

[ISalesOrderV3 Interface](isalesorderv3-interface-microsoft-dynamics-retail-pos-contracts-services.md)

[Microsoft.Dynamics.Retail.Pos.Contracts.Services Namespace](microsoft-dynamics-retail-pos-contracts-services-namespace.md)

