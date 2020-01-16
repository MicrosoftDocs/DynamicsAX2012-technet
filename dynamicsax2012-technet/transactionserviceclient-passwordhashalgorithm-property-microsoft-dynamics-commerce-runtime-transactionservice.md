---
title: TransactionServiceClient.PasswordHashAlgorithm Property  (Microsoft.Dynamics.Commerce.Runtime.TransactionService)
TOCTitle: PasswordHashAlgorithm Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.TransactionService.TransactionServiceClient.PasswordHashAlgorithm
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.transactionservice.transactionserviceclient.passwordhashalgorithm(v=AX.60)
ms:contentKeyID: 62213560
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.TransactionService.TransactionServiceClient.PasswordHashAlgorithm
dev_langs:
- CSharp
- C++
- VB
---

# PasswordHashAlgorithm Property

Gets the algorithm used in password hashing from the channel configuration.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.TransactionService](microsoft-dynamics-commerce-runtime-transactionservice-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.TransactionService (in Microsoft.Dynamics.Commerce.Runtime.TransactionService.dll)

## Syntax

``` vb
'Declaration
Public ReadOnly Property PasswordHashAlgorithm As String
    Get
'Usage
Dim instance As TransactionServiceClient
Dim value As String

value = instance.PasswordHashAlgorithm
```

``` csharp
public string PasswordHashAlgorithm { get; }
```

``` c++
public:
property String^ PasswordHashAlgorithm {
    String^ get ();
}
```

#### Property Value

Type: [System.String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\))  
Returns [String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\)).  

## See Also

#### Reference

[TransactionServiceClient Class](transactionserviceclient-class-microsoft-dynamics-commerce-runtime-transactionservice.md)

[Microsoft.Dynamics.Commerce.Runtime.TransactionService Namespace](microsoft-dynamics-commerce-runtime-transactionservice-namespace.md)

