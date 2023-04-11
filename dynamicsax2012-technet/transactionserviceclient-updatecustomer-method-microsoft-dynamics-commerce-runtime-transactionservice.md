---
title: TransactionServiceClient.UpdateCustomer Method  (Microsoft.Dynamics.Commerce.Runtime.TransactionService)
TOCTitle: UpdateCustomer Method
ms:assetid: M:Microsoft.Dynamics.Commerce.Runtime.TransactionService.TransactionServiceClient.UpdateCustomer(Microsoft.Dynamics.Commerce.Runtime.DataModel.Customer)
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.transactionservice.transactionserviceclient.updatecustomer(v=AX.60)
ms:contentKeyID: 62206278
author: tonyafehr
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.TransactionService.TransactionServiceClient.UpdateCustomer
dev_langs:
- CSharp
- C++
- VB
---

# UpdateCustomer Method


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Update Customer in AX.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.TransactionService](microsoft-dynamics-commerce-runtime-transactionservice-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.TransactionService (in Microsoft.Dynamics.Commerce.Runtime.TransactionService.dll)

## Syntax

``` vb
'Declaration
Public Function UpdateCustomer ( _
    customer As Customer _
) As Customer
'Usage
Dim instance As TransactionServiceClient
Dim customer As Customer
Dim returnValue As Customer

returnValue = instance.UpdateCustomer(customer)
```

``` csharp
public Customer UpdateCustomer(
    Customer customer
)
```

``` c++
public:
Customer^ UpdateCustomer(
    Customer^ customer
)
```

#### Parameters

  - customer  
    Type: [Microsoft.Dynamics.Commerce.Runtime.DataModel.Customer](customer-class-microsoft-dynamics-commerce-runtime-datamodel.md)  

#### Return Value

Type: [Microsoft.Dynamics.Commerce.Runtime.DataModel.Customer](customer-class-microsoft-dynamics-commerce-runtime-datamodel.md)  
An updated customer.  

## See Also

#### Reference

[TransactionServiceClient Class](transactionserviceclient-class-microsoft-dynamics-commerce-runtime-transactionservice.md)

[Microsoft.Dynamics.Commerce.Runtime.TransactionService Namespace](microsoft-dynamics-commerce-runtime-transactionservice-namespace.md)

