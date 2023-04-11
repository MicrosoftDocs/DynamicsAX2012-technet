---
title: TransactionServiceClient.GetCustomerBalance Method  (Microsoft.Dynamics.Commerce.Runtime.TransactionService)
TOCTitle: GetCustomerBalance Method
ms:assetid: M:Microsoft.Dynamics.Commerce.Runtime.TransactionService.TransactionServiceClient.GetCustomerBalance(System.String,System.String,System.String)
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.transactionservice.transactionserviceclient.getcustomerbalance(v=AX.60)
ms:contentKeyID: 62207826
author: tonyafehr
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.TransactionService.TransactionServiceClient.GetCustomerBalance
dev_langs:
- CSharp
- C++
- VB
---

# GetCustomerBalance Method


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Gets the customer balance.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.TransactionService](microsoft-dynamics-commerce-runtime-transactionservice-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.TransactionService (in Microsoft.Dynamics.Commerce.Runtime.TransactionService.dll)

## Syntax

``` vb
'Declaration
Public Function GetCustomerBalance ( _
    accountNumber As String, _
    currencyCode As String, _
    storeId As String _
) As CustomerBalances
'Usage
Dim instance As TransactionServiceClient
Dim accountNumber As String
Dim currencyCode As String
Dim storeId As String
Dim returnValue As CustomerBalances

returnValue = instance.GetCustomerBalance(accountNumber, _
    currencyCode, storeId)
```

``` csharp
public CustomerBalances GetCustomerBalance(
    string accountNumber,
    string currencyCode,
    string storeId
)
```

``` c++
public:
CustomerBalances^ GetCustomerBalance(
    String^ accountNumber, 
    String^ currencyCode, 
    String^ storeId
)
```

#### Parameters

  - accountNumber  
    Type: [System.String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\))  

<!-- end list -->

  - currencyCode  
    Type: [System.String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\))  

<!-- end list -->

  - storeId  
    Type: [System.String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\))  

#### Return Value

Type: [Microsoft.Dynamics.Commerce.Runtime.DataModel.CustomerBalances](customerbalances-class-microsoft-dynamics-commerce-runtime-datamodel.md)  
A customer balance object.  

## See Also

#### Reference

[TransactionServiceClient Class](transactionserviceclient-class-microsoft-dynamics-commerce-runtime-transactionservice.md)

[Microsoft.Dynamics.Commerce.Runtime.TransactionService Namespace](microsoft-dynamics-commerce-runtime-transactionservice-namespace.md)

