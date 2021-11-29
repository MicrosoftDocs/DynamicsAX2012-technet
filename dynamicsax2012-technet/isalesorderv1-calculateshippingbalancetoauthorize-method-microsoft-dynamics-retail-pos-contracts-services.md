---
title: ISalesOrderV1.CalculateShippingBalanceToAuthorize Method  (Microsoft.Dynamics.Retail.Pos.Contracts.Services)
TOCTitle: CalculateShippingBalanceToAuthorize Method
ms:assetid: M:Microsoft.Dynamics.Retail.Pos.Contracts.Services.ISalesOrderV1.CalculateShippingBalanceToAuthorize(Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity.ICustomerOrderTransaction)
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.retail.pos.contracts.services.isalesorderv1.calculateshippingbalancetoauthorize(v=AX.60)
ms:contentKeyID: 47344277
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Retail.Pos.Contracts.Services.ISalesOrderV1.CalculateShippingBalanceToAuthorize
dev_langs:
- CSharp
- C++
- VB
---

# CalculateShippingBalanceToAuthorize Method


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Computes the balance to be authorized for shipping.

**Namespace:**  [Microsoft.Dynamics.Retail.Pos.Contracts.Services](microsoft-dynamics-retail-pos-contracts-services-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Retail.Pos.Contracts (in Microsoft.Dynamics.Retail.Pos.Contracts.dll)

## Syntax

``` vb
'Declaration
Function CalculateShippingBalanceToAuthorize ( _
    transaction As ICustomerOrderTransaction _
) As Decimal
'Usage
Dim instance As ISalesOrderV1
Dim transaction As ICustomerOrderTransaction
Dim returnValue As Decimal

returnValue = instance.CalculateShippingBalanceToAuthorize(transaction)
```

``` csharp
decimal CalculateShippingBalanceToAuthorize(
    ICustomerOrderTransaction transaction
)
```

``` c++
Decimal CalculateShippingBalanceToAuthorize(
    ICustomerOrderTransaction^ transaction
)
```

#### Parameters

  - transaction  
    Type: [Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity.ICustomerOrderTransaction](icustomerordertransaction-interface-microsoft-dynamics-retail-pos-contracts-dataentity.md)  

#### Return Value

Type: [System.Decimal](https://technet.microsoft.com/library/1k2e8atx\(v=ax.60\))  
Returns remaining balance to authorize for shipping.  

## See Also

#### Reference

[ISalesOrderV1 Interface](isalesorderv1-interface-microsoft-dynamics-retail-pos-contracts-services.md)

[Microsoft.Dynamics.Retail.Pos.Contracts.Services Namespace](microsoft-dynamics-retail-pos-contracts-services-namespace.md)

