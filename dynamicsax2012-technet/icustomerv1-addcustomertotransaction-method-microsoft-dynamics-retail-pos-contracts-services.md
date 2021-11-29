---
title: ICustomerV1.AddCustomerToTransaction Method  (Microsoft.Dynamics.Retail.Pos.Contracts.Services)
TOCTitle: AddCustomerToTransaction Method
ms:assetid: M:Microsoft.Dynamics.Retail.Pos.Contracts.Services.ICustomerV1.AddCustomerToTransaction(Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity.ICustomer,Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity.IPosTransaction)
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.retail.pos.contracts.services.icustomerv1.addcustomertotransaction(v=AX.60)
ms:contentKeyID: 47344259
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Retail.Pos.Contracts.Services.ICustomerV1.AddCustomerToTransaction
dev_langs:
- CSharp
- C++
- VB
---

# AddCustomerToTransaction Method


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Adds customer to transaction.

**Namespace:**  [Microsoft.Dynamics.Retail.Pos.Contracts.Services](microsoft-dynamics-retail-pos-contracts-services-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Retail.Pos.Contracts (in Microsoft.Dynamics.Retail.Pos.Contracts.dll)

## Syntax

``` vb
'Declaration
Sub AddCustomerToTransaction ( _
    customer As ICustomer, _
    posTransaction As IPosTransaction _
)
'Usage
Dim instance As ICustomerV1
Dim customer As ICustomer
Dim posTransaction As IPosTransaction

instance.AddCustomerToTransaction(customer, _
    posTransaction)
```

``` csharp
void AddCustomerToTransaction(
    ICustomer customer,
    IPosTransaction posTransaction
)
```

``` c++
void AddCustomerToTransaction(
    ICustomer^ customer, 
    IPosTransaction^ posTransaction
)
```

#### Parameters

  - customer  
    Type: [Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity.ICustomer](icustomer-interface-microsoft-dynamics-retail-pos-contracts-dataentity.md)  

<!-- end list -->

  - posTransaction  
    Type: [Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity.IPosTransaction](ipostransaction-interface-microsoft-dynamics-retail-pos-contracts-dataentity.md)  

## See Also

#### Reference

[ICustomerV1 Interface](icustomerv1-interface-microsoft-dynamics-retail-pos-contracts-services.md)

[Microsoft.Dynamics.Retail.Pos.Contracts.Services Namespace](microsoft-dynamics-retail-pos-contracts-services-namespace.md)

