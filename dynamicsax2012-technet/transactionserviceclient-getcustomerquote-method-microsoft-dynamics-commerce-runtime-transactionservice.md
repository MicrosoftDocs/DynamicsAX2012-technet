---
title: TransactionServiceClient.GetCustomerQuote Method  (Microsoft.Dynamics.Commerce.Runtime.TransactionService)
TOCTitle: GetCustomerQuote Method
ms:assetid: M:Microsoft.Dynamics.Commerce.Runtime.TransactionService.TransactionServiceClient.GetCustomerQuote(System.String)
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.transactionservice.transactionserviceclient.getcustomerquote(v=AX.60)
ms:contentKeyID: 62214279
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.TransactionService.TransactionServiceClient.GetCustomerQuote
dev_langs:
- CSharp
- C++
- VB
---

# GetCustomerQuote Method

Gets the customer quote by identifier.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.TransactionService](microsoft-dynamics-commerce-runtime-transactionservice-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.TransactionService (in Microsoft.Dynamics.Commerce.Runtime.TransactionService.dll)

## Syntax

``` vb
'Declaration
Public Function GetCustomerQuote ( _
    quoteId As String _
) As ReadOnlyCollection(Of Object)
'Usage
Dim instance As TransactionServiceClient
Dim quoteId As String
Dim returnValue As ReadOnlyCollection(Of Object)

returnValue = instance.GetCustomerQuote(quoteId)
```

``` csharp
public ReadOnlyCollection<Object> GetCustomerQuote(
    string quoteId
)
```

``` c++
public:
ReadOnlyCollection<Object^>^ GetCustomerQuote(
    String^ quoteId
)
```

#### Parameters

  - quoteId  
    Type: [System.String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\))  

#### Return Value

Type: [System.Collections.ObjectModel.ReadOnlyCollection](https://technet.microsoft.com/library/ms132474\(v=ax.60\))\<[Object](https://technet.microsoft.com/library/e5kfa45b\(v=ax.60\))\>  
The collection results from the transaction service call.  

## See Also

#### Reference

[TransactionServiceClient Class](transactionserviceclient-class-microsoft-dynamics-commerce-runtime-transactionservice.md)

[Microsoft.Dynamics.Commerce.Runtime.TransactionService Namespace](microsoft-dynamics-commerce-runtime-transactionservice-namespace.md)

