---
title: TransactionServiceClient.GetSalesInvoices Method (String) (Microsoft.Dynamics.Commerce.Runtime.TransactionService)
TOCTitle: GetSalesInvoices Method (String)
ms:assetid: M:Microsoft.Dynamics.Commerce.Runtime.TransactionService.TransactionServiceClient.GetSalesInvoices(System.String)
ms:mtpsurl: https://technet.microsoft.com/en-us/library/microsoft.dynamics.commerce.runtime.transactionservice.transactionserviceclient.getsalesinvoices(v=AX.60)
ms:contentKeyID: 62205543
ms.date: 05/18/2015
mtps_version: v=AX.60
dev_langs:
- vb
- csharp
- c++
---

# GetSalesInvoices Method (String)

Gets the sales invoice collection for a given customer.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.TransactionService](microsoft-dynamics-commerce-runtime-transactionservice-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.TransactionService (in Microsoft.Dynamics.Commerce.Runtime.TransactionService.dll)

## Syntax

``` vb
'Declaration
Public Function GetSalesInvoices ( _
    customerAccountNumber As String _
) As ReadOnlyCollection(Of Object)
'Usage
Dim instance As TransactionServiceClient
Dim customerAccountNumber As String
Dim returnValue As ReadOnlyCollection(Of Object)

returnValue = instance.GetSalesInvoices(customerAccountNumber)
```

``` csharp
public ReadOnlyCollection<Object> GetSalesInvoices(
    string customerAccountNumber
)
```

``` c++
public:
ReadOnlyCollection<Object^>^ GetSalesInvoices(
    String^ customerAccountNumber
)
```

#### Parameters

  - customerAccountNumber  
    Type: [System.String](https://technet.microsoft.com/en-us/library/s1wwdcbf\(v=ax.60\))  

#### Return Value

Type: [System.Collections.ObjectModel.ReadOnlyCollection](https://technet.microsoft.com/en-us/library/ms132474\(v=ax.60\))\<[Object](https://technet.microsoft.com/en-us/library/e5kfa45b\(v=ax.60\))\>  
The collection results from the transaction service call.  

## See Also

#### Reference

[TransactionServiceClient Class](transactionserviceclient-class-microsoft-dynamics-commerce-runtime-transactionservice.md)

[GetSalesInvoices Overload](transactionserviceclient-getsalesinvoices-method-microsoft-dynamics-commerce-runtime-transactionservice.md)

[Microsoft.Dynamics.Commerce.Runtime.TransactionService Namespace](microsoft-dynamics-commerce-runtime-transactionservice-namespace.md)

