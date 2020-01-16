---
title: TransactionServiceClient.SaveCustomerOrder Method  (Microsoft.Dynamics.Commerce.Runtime.TransactionService)
TOCTitle: SaveCustomerOrder Method
ms:assetid: M:Microsoft.Dynamics.Commerce.Runtime.TransactionService.TransactionServiceClient.SaveCustomerOrder(System.String,Microsoft.Dynamics.Commerce.Runtime.DataModel.CustomerOrderType,Microsoft.Dynamics.Commerce.Runtime.DataModel.CustomerOrderMode,System.String)
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.transactionservice.transactionserviceclient.savecustomerorder(v=AX.60)
ms:contentKeyID: 62211678
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.TransactionService.TransactionServiceClient.SaveCustomerOrder
dev_langs:
- CSharp
- C++
- VB
---

# SaveCustomerOrder Method

Saves customer order into AX.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.TransactionService](microsoft-dynamics-commerce-runtime-transactionservice-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.TransactionService (in Microsoft.Dynamics.Commerce.Runtime.TransactionService.dll)

## Syntax

``` vb
'Declaration
Public Function SaveCustomerOrder ( _
    salesId As String, _
    type As CustomerOrderType, _
    mode As CustomerOrderMode, _
    requestXml As String _
) As ReadOnlyCollection(Of Object)
'Usage
Dim instance As TransactionServiceClient
Dim salesId As String
Dim type As CustomerOrderType
Dim mode As CustomerOrderMode
Dim requestXml As String
Dim returnValue As ReadOnlyCollection(Of Object)

returnValue = instance.SaveCustomerOrder(salesId, _
    type, mode, requestXml)
```

``` csharp
public ReadOnlyCollection<Object> SaveCustomerOrder(
    string salesId,
    CustomerOrderType type,
    CustomerOrderMode mode,
    string requestXml
)
```

``` c++
public:
ReadOnlyCollection<Object^>^ SaveCustomerOrder(
    String^ salesId, 
    CustomerOrderType type, 
    CustomerOrderMode mode, 
    String^ requestXml
)
```

#### Parameters

  - salesId  
    Type: [System.String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\))  

<!-- end list -->

  - type  
    Type: [Microsoft.Dynamics.Commerce.Runtime.DataModel.CustomerOrderType](customerordertype-enumeration-microsoft-dynamics-commerce-runtime-datamodel.md)  

<!-- end list -->

  - mode  
    Type: [Microsoft.Dynamics.Commerce.Runtime.DataModel.CustomerOrderMode](customerordermode-enumeration-microsoft-dynamics-commerce-runtime-datamodel.md)  

<!-- end list -->

  - requestXml  
    Type: [System.String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\))  

#### Return Value

Type: [System.Collections.ObjectModel.ReadOnlyCollection](https://technet.microsoft.com/library/ms132474\(v=ax.60\))\<[Object](https://technet.microsoft.com/library/e5kfa45b\(v=ax.60\))\>  
The collection results from the transaction service call.  

## See Also

#### Reference

[TransactionServiceClient Class](transactionserviceclient-class-microsoft-dynamics-commerce-runtime-transactionservice.md)

[Microsoft.Dynamics.Commerce.Runtime.TransactionService Namespace](microsoft-dynamics-commerce-runtime-transactionservice-namespace.md)

