---
title: TransactionServiceClient.GetCustomerOrder Method  (Microsoft.Dynamics.Commerce.Runtime.TransactionService)
TOCTitle: GetCustomerOrder Method
ms:assetid: M:Microsoft.Dynamics.Commerce.Runtime.TransactionService.TransactionServiceClient.GetCustomerOrder(System.String,System.Boolean)
ms:mtpsurl: https://technet.microsoft.com/en-us/library/microsoft.dynamics.commerce.runtime.transactionservice.transactionserviceclient.getcustomerorder(v=AX.60)
ms:contentKeyID: 62215101
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.TransactionService.TransactionServiceClient.GetCustomerOrder
dev_langs:
- CSharp
- C++
- VB
---

# GetCustomerOrder Method

Gets the customer order by identifier.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.TransactionService](microsoft-dynamics-commerce-runtime-transactionservice-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.TransactionService (in Microsoft.Dynamics.Commerce.Runtime.TransactionService.dll)

## Syntax

``` vb
'Declaration
Public Function GetCustomerOrder ( _
    salesId As String, _
    includeOnlineOrders As Boolean _
) As ReadOnlyCollection(Of Object)
'Usage
Dim instance As TransactionServiceClient
Dim salesId As String
Dim includeOnlineOrders As Boolean
Dim returnValue As ReadOnlyCollection(Of Object)

returnValue = instance.GetCustomerOrder(salesId, _
    includeOnlineOrders)
```

``` csharp
public ReadOnlyCollection<Object> GetCustomerOrder(
    string salesId,
    bool includeOnlineOrders
)
```

``` c++
public:
ReadOnlyCollection<Object^>^ GetCustomerOrder(
    String^ salesId, 
    bool includeOnlineOrders
)
```

#### Parameters

  - salesId  
    Type: [System.String](https://technet.microsoft.com/en-us/library/s1wwdcbf\(v=ax.60\))  

<!-- end list -->

  - includeOnlineOrders  
    Type: [System.Boolean](https://technet.microsoft.com/en-us/library/a28wyd50\(v=ax.60\))  

#### Return Value

Type: [System.Collections.ObjectModel.ReadOnlyCollection](https://technet.microsoft.com/en-us/library/ms132474\(v=ax.60\))\<[Object](https://technet.microsoft.com/en-us/library/e5kfa45b\(v=ax.60\))\>  
The collection results from the transaction service call.  

## See Also

#### Reference

[TransactionServiceClient Class](transactionserviceclient-class-microsoft-dynamics-commerce-runtime-transactionservice.md)

[Microsoft.Dynamics.Commerce.Runtime.TransactionService Namespace](microsoft-dynamics-commerce-runtime-transactionservice-namespace.md)

