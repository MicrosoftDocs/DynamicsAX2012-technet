---
title: TransactionServiceClient.GetCustomerOrder Method  (Microsoft.Dynamics.Commerce.Runtime.TransactionService)
TOCTitle: GetCustomerOrder Method
ms:assetid: M:Microsoft.Dynamics.Commerce.Runtime.TransactionService.TransactionServiceClient.GetCustomerOrder(System.String,System.Boolean)
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.transactionservice.transactionserviceclient.getcustomerorder(v=AX.60)
ms:contentKeyID: 62215101
author: tonyafehr
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


[!INCLUDE[archive-banner](includes/archive-banner.md)]

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
    Type: [System.String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\))  

<!-- end list -->

  - includeOnlineOrders  
    Type: [System.Boolean](https://technet.microsoft.com/library/a28wyd50\(v=ax.60\))  

#### Return Value

Type: [System.Collections.ObjectModel.ReadOnlyCollection](https://technet.microsoft.com/library/ms132474\(v=ax.60\))\<[Object](https://technet.microsoft.com/library/e5kfa45b\(v=ax.60\))\>  
The collection results from the transaction service call.  

## See Also

#### Reference

[TransactionServiceClient Class](transactionserviceclient-class-microsoft-dynamics-commerce-runtime-transactionservice.md)

[Microsoft.Dynamics.Commerce.Runtime.TransactionService Namespace](microsoft-dynamics-commerce-runtime-transactionservice-namespace.md)

