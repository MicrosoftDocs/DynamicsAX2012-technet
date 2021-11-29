---
title: ICustomerV1.EnterCustomerId Method  (Microsoft.Dynamics.Retail.Pos.Contracts.Services)
TOCTitle: EnterCustomerId Method
ms:assetid: M:Microsoft.Dynamics.Retail.Pos.Contracts.Services.ICustomerV1.EnterCustomerId(Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity.IRetailTransaction)
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.retail.pos.contracts.services.icustomerv1.entercustomerid(v=AX.60)
ms:contentKeyID: 47344250
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Retail.Pos.Contracts.Services.ICustomerV1.EnterCustomerId
dev_langs:
- CSharp
- C++
- VB
---

# EnterCustomerId Method


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Enter the customer ID and add the customer to the transaction.

**Namespace:**  [Microsoft.Dynamics.Retail.Pos.Contracts.Services](microsoft-dynamics-retail-pos-contracts-services-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Retail.Pos.Contracts (in Microsoft.Dynamics.Retail.Pos.Contracts.dll)

## Syntax

``` vb
'Declaration
Sub EnterCustomerId ( _
    retailTransaction As IRetailTransaction _
)
'Usage
Dim instance As ICustomerV1
Dim retailTransaction As IRetailTransaction

instance.EnterCustomerId(retailTransaction)
```

``` csharp
void EnterCustomerId(
    IRetailTransaction retailTransaction
)
```

``` c++
void EnterCustomerId(
    IRetailTransaction^ retailTransaction
)
```

#### Parameters

  - retailTransaction  
    Type: [Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity.IRetailTransaction](iretailtransaction-interface-microsoft-dynamics-retail-pos-contracts-dataentity.md)  

## See Also

#### Reference

[ICustomerV1 Interface](icustomerv1-interface-microsoft-dynamics-retail-pos-contracts-services.md)

[Microsoft.Dynamics.Retail.Pos.Contracts.Services Namespace](microsoft-dynamics-retail-pos-contracts-services-namespace.md)

