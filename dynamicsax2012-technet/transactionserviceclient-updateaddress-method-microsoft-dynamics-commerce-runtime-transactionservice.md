---
title: TransactionServiceClient.UpdateAddress Method  (Microsoft.Dynamics.Commerce.Runtime.TransactionService)
TOCTitle: UpdateAddress Method
ms:assetid: M:Microsoft.Dynamics.Commerce.Runtime.TransactionService.TransactionServiceClient.UpdateAddress(Microsoft.Dynamics.Commerce.Runtime.DataModel.Customer@,Microsoft.Dynamics.Commerce.Runtime.DataModel.Address@)
ms:mtpsurl: https://technet.microsoft.com/en-us/library/microsoft.dynamics.commerce.runtime.transactionservice.transactionserviceclient.updateaddress(v=AX.60)
ms:contentKeyID: 62202669
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.TransactionService.TransactionServiceClient.UpdateAddress
dev_langs:
- CSharp
- C++
- VB
---

# UpdateAddress Method

Update a postal address in AX.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.TransactionService](microsoft-dynamics-commerce-runtime-transactionservice-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.TransactionService (in Microsoft.Dynamics.Commerce.Runtime.TransactionService.dll)

## Syntax

``` vb
'Declaration
Public Sub UpdateAddress ( _
    ByRef customer As Customer, _
    ByRef address As Address _
)
'Usage
Dim instance As TransactionServiceClient
Dim customer As Customer
Dim address As Address

instance.UpdateAddress(customer, address)
```

``` csharp
public void UpdateAddress(
    ref Customer customer,
    ref Address address
)
```

``` c++
public:
void UpdateAddress(
    Customer^% customer, 
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

