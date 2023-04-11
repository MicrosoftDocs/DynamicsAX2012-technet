---
title: TransactionServiceClient.NewCustomer Method  (Microsoft.Dynamics.Commerce.Runtime.TransactionService)
TOCTitle: NewCustomer Method
ms:assetid: M:Microsoft.Dynamics.Commerce.Runtime.TransactionService.TransactionServiceClient.NewCustomer(Microsoft.Dynamics.Commerce.Runtime.DataModel.Customer@,System.Int64)
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.transactionservice.transactionserviceclient.newcustomer(v=AX.60)
ms:contentKeyID: 62214246
author: tonyafehr
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.TransactionService.TransactionServiceClient.NewCustomer
dev_langs:
- CSharp
- C++
- VB
---

# NewCustomer Method


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Create a new customer in AX.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.TransactionService](microsoft-dynamics-commerce-runtime-transactionservice-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.TransactionService (in Microsoft.Dynamics.Commerce.Runtime.TransactionService.dll)

## Syntax

``` vb
'Declaration
Public Sub NewCustomer ( _
    ByRef customer As Customer, _
    storeId As Long _
)
'Usage
Dim instance As TransactionServiceClient
Dim customer As Customer
Dim storeId As Long

instance.NewCustomer(customer, storeId)
```

``` csharp
public void NewCustomer(
    ref Customer customer,
    long storeId
)
```

``` c++
public:
void NewCustomer(
    Customer^% customer, 
    long long storeId
)
```

#### Parameters

  - customer  
    Type: [Microsoft.Dynamics.Commerce.Runtime.DataModel.Customer](customer-class-microsoft-dynamics-commerce-runtime-datamodel.md)  

<!-- end list -->

  - storeId  
    Type: [System.Int64](https://technet.microsoft.com/library/6yy583ek\(v=ax.60\))  

## See Also

#### Reference

[TransactionServiceClient Class](transactionserviceclient-class-microsoft-dynamics-commerce-runtime-transactionservice.md)

[Microsoft.Dynamics.Commerce.Runtime.TransactionService Namespace](microsoft-dynamics-commerce-runtime-transactionservice-namespace.md)

