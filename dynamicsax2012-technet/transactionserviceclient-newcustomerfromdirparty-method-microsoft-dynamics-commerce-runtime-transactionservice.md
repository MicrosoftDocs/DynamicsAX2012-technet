---
title: TransactionServiceClient.NewCustomerFromDirParty Method  (Microsoft.Dynamics.Commerce.Runtime.TransactionService)
TOCTitle: NewCustomerFromDirParty Method
ms:assetid: M:Microsoft.Dynamics.Commerce.Runtime.TransactionService.TransactionServiceClient.NewCustomerFromDirParty(Microsoft.Dynamics.Commerce.Runtime.DataModel.Customer@,System.Int64)
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.transactionservice.transactionserviceclient.newcustomerfromdirparty(v=AX.60)
ms:contentKeyID: 62214519
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.TransactionService.TransactionServiceClient.NewCustomerFromDirParty
dev_langs:
- CSharp
- C++
- VB
---

# NewCustomerFromDirParty Method

Create a new customer in AX.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.TransactionService](microsoft-dynamics-commerce-runtime-transactionservice-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.TransactionService (in Microsoft.Dynamics.Commerce.Runtime.TransactionService.dll)

## Syntax

``` vb
'Declaration
Public Sub NewCustomerFromDirParty ( _
    ByRef customer As Customer, _
    storeId As Long _
)
'Usage
Dim instance As TransactionServiceClient
Dim customer As Customer
Dim storeId As Long

instance.NewCustomerFromDirParty(customer, _
    storeId)
```

``` csharp
public void NewCustomerFromDirParty(
    ref Customer customer,
    long storeId
)
```

``` c++
public:
void NewCustomerFromDirParty(
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

