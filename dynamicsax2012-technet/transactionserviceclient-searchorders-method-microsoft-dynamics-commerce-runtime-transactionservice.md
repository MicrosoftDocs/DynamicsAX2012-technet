---
title: TransactionServiceClient.SearchOrders Method  (Microsoft.Dynamics.Commerce.Runtime.TransactionService)
TOCTitle: SearchOrders Method
ms:assetid: M:Microsoft.Dynamics.Commerce.Runtime.TransactionService.TransactionServiceClient.SearchOrders(Microsoft.Dynamics.Commerce.Runtime.DataModel.SalesOrderSearchCriteria,System.Int32)
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.transactionservice.transactionserviceclient.searchorders(v=AX.60)
ms:contentKeyID: 62209290
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.TransactionService.TransactionServiceClient.SearchOrders
dev_langs:
- CSharp
- C++
- VB
---

# SearchOrders Method

Searches for orders that match the given criteria in AX.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.TransactionService](microsoft-dynamics-commerce-runtime-transactionservice-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.TransactionService (in Microsoft.Dynamics.Commerce.Runtime.TransactionService.dll)

## Syntax

``` vb
'Declaration
Public Function SearchOrders ( _
    criteria As SalesOrderSearchCriteria, _
    maxTransactionSearchResults As Integer _
) As IEnumerable(Of SalesOrder)
'Usage
Dim instance As TransactionServiceClient
Dim criteria As SalesOrderSearchCriteria
Dim maxTransactionSearchResults As Integer
Dim returnValue As IEnumerable(Of SalesOrder)

returnValue = instance.SearchOrders(criteria, _
    maxTransactionSearchResults)
```

``` csharp
public IEnumerable<SalesOrder> SearchOrders(
    SalesOrderSearchCriteria criteria,
    int maxTransactionSearchResults
)
```

``` c++
public:
IEnumerable<SalesOrder^>^ SearchOrders(
    SalesOrderSearchCriteria^ criteria, 
    int maxTransactionSearchResults
)
```

#### Parameters

  - criteria  
    Type: [Microsoft.Dynamics.Commerce.Runtime.DataModel.SalesOrderSearchCriteria](salesordersearchcriteria-class-microsoft-dynamics-commerce-runtime-datamodel.md)  

<!-- end list -->

  - maxTransactionSearchResults  
    Type: [System.Int32](https://technet.microsoft.com/library/td2s409d\(v=ax.60\))  

#### Return Value

Type: [System.Collections.Generic.IEnumerable](https://technet.microsoft.com/library/9eekhta0\(v=ax.60\))\<[SalesOrder](salesorder-class-microsoft-dynamics-commerce-runtime-datamodel.md)\>  
A sales transaction.  

## See Also

#### Reference

[TransactionServiceClient Class](transactionserviceclient-class-microsoft-dynamics-commerce-runtime-transactionservice.md)

[Microsoft.Dynamics.Commerce.Runtime.TransactionService Namespace](microsoft-dynamics-commerce-runtime-transactionservice-namespace.md)

