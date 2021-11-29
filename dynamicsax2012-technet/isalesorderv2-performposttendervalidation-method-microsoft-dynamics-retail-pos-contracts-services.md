---
title: ISalesOrderV2.PerformPostTenderValidation Method  (Microsoft.Dynamics.Retail.Pos.Contracts.Services)
TOCTitle: PerformPostTenderValidation Method
ms:assetid: M:Microsoft.Dynamics.Retail.Pos.Contracts.Services.ISalesOrderV2.PerformPostTenderValidation(Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity.IRetailTransaction)
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.retail.pos.contracts.services.isalesorderv2.performposttendervalidation(v=AX.60)
ms:contentKeyID: 49833893
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Retail.Pos.Contracts.Services.ISalesOrderV2.PerformPostTenderValidation
dev_langs:
- CSharp
- C++
- VB
---

# PerformPostTenderValidation Method


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Perform any required post-tender validation on the Customer Order

**Namespace:**  [Microsoft.Dynamics.Retail.Pos.Contracts.Services](microsoft-dynamics-retail-pos-contracts-services-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Retail.Pos.Contracts (in Microsoft.Dynamics.Retail.Pos.Contracts.dll)

## Syntax

``` vb
'Declaration
Function PerformPostTenderValidation ( _
    retailTransaction As IRetailTransaction _
) As Boolean
'Usage
Dim instance As ISalesOrderV2
Dim retailTransaction As IRetailTransaction
Dim returnValue As Boolean

returnValue = instance.PerformPostTenderValidation(retailTransaction)
```

``` csharp
bool PerformPostTenderValidation(
    IRetailTransaction retailTransaction
)
```

``` c++
bool PerformPostTenderValidation(
    IRetailTransaction^ retailTransaction
)
```

#### Parameters

  - retailTransaction  
    Type: [Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity.IRetailTransaction](iretailtransaction-interface-microsoft-dynamics-retail-pos-contracts-dataentity.md)  

#### Return Value

Type: [System.Boolean](https://technet.microsoft.com/library/a28wyd50\(v=ax.60\))  
True if the validation succeeded, False otherwise.  

## See Also

#### Reference

[ISalesOrderV2 Interface](isalesorderv2-interface-microsoft-dynamics-retail-pos-contracts-services.md)

[Microsoft.Dynamics.Retail.Pos.Contracts.Services Namespace](microsoft-dynamics-retail-pos-contracts-services-namespace.md)

