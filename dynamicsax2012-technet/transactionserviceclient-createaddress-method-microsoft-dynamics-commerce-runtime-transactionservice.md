---
title: TransactionServiceClient.CreateAddress Method  (Microsoft.Dynamics.Commerce.Runtime.TransactionService)
TOCTitle: CreateAddress Method
ms:assetid: M:Microsoft.Dynamics.Commerce.Runtime.TransactionService.TransactionServiceClient.CreateAddress(Microsoft.Dynamics.Commerce.Runtime.DataModel.Customer,Microsoft.Dynamics.Commerce.Runtime.DataModel.Address@)
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.transactionservice.transactionserviceclient.createaddress(v=AX.60)
ms:contentKeyID: 62212929
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.TransactionService.TransactionServiceClient.CreateAddress
dev_langs:
- CSharp
- C++
- VB
---

# CreateAddress Method


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Create a new postal address in AX.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.TransactionService](microsoft-dynamics-commerce-runtime-transactionservice-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.TransactionService (in Microsoft.Dynamics.Commerce.Runtime.TransactionService.dll)

## Syntax

``` vb
'Declaration
Public Sub CreateAddress ( _
    customer As Customer, _
    ByRef address As Address _
)
'Usage
Dim instance As TransactionServiceClient
Dim customer As Customer
Dim address As Address

instance.CreateAddress(customer, address)
```

``` csharp
public void CreateAddress(
    Customer customer,
    ref Address address
)
```

``` c++
public:
void CreateAddress(
    Customer^ customer, 
    Address^% address
)
```

#### Parameters

  - customer  
    Type: [Microsoft.Dynamics.Commerce.Runtime.DataModel.Customer](customer-class-microsoft-dynamics-commerce-runtime-datamodel.md)  

<!-- end list -->

  - address  
    Type: [Microsoft.Dynamics.Commerce.Runtime.DataModel.Address](address-class-microsoft-dynamics-commerce-runtime-datamodel.md)  

## See Also

#### Reference

[TransactionServiceClient Class](transactionserviceclient-class-microsoft-dynamics-commerce-runtime-transactionservice.md)

[Microsoft.Dynamics.Commerce.Runtime.TransactionService Namespace](microsoft-dynamics-commerce-runtime-transactionservice-namespace.md)

