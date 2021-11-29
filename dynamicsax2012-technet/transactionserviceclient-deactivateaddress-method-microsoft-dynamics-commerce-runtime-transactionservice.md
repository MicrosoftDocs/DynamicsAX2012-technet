---
title: TransactionServiceClient.DeactivateAddress Method  (Microsoft.Dynamics.Commerce.Runtime.TransactionService)
TOCTitle: DeactivateAddress Method
ms:assetid: M:Microsoft.Dynamics.Commerce.Runtime.TransactionService.TransactionServiceClient.DeactivateAddress(System.Int64,System.Int64)
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.transactionservice.transactionserviceclient.deactivateaddress(v=AX.60)
ms:contentKeyID: 49830292
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.TransactionService.TransactionServiceClient.DeactivateAddress
dev_langs:
- CSharp
- C++
- VB
---

# DeactivateAddress Method


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Deactivate an Address in AX.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.TransactionService](microsoft-dynamics-commerce-runtime-transactionservice-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.TransactionService (in Microsoft.Dynamics.Commerce.Runtime.TransactionService.dll)

## Syntax

``` vb
'Declaration
Public Sub DeactivateAddress ( _
    addressId As Long, _
    customerId As Long _
)
'Usage
Dim instance As TransactionServiceClient
Dim addressId As Long
Dim customerId As Long

instance.DeactivateAddress(addressId, _
    customerId)
```

``` csharp
public void DeactivateAddress(
    long addressId,
    long customerId
)
```

``` c++
public:
void DeactivateAddress(
    long long addressId, 
    long long customerId
)
```

#### Parameters

  - addressId  
    Type: [System.Int64](https://technet.microsoft.com/library/6yy583ek\(v=ax.60\))  

<!-- end list -->

  - customerId  
    Type: [System.Int64](https://technet.microsoft.com/library/6yy583ek\(v=ax.60\))  

## See Also

#### Reference

[TransactionServiceClient Class](transactionserviceclient-class-microsoft-dynamics-commerce-runtime-transactionservice.md)

[Microsoft.Dynamics.Commerce.Runtime.TransactionService Namespace](microsoft-dynamics-commerce-runtime-transactionservice-namespace.md)

