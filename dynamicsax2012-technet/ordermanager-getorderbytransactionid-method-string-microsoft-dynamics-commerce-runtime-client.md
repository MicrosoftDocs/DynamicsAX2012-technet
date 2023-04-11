---
title: OrderManager.GetOrderByTransactionId Method (String) (Microsoft.Dynamics.Commerce.Runtime.Client)
TOCTitle: GetOrderByTransactionId Method (String)
ms:assetid: M:Microsoft.Dynamics.Commerce.Runtime.Client.OrderManager.GetOrderByTransactionId(System.String)
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.client.ordermanager.getorderbytransactionid(v=AX.60)
ms:contentKeyID: 62202717
author: tonyafehr
ms.date: 05/18/2015
mtps_version: v=AX.60
dev_langs:
- vb
- csharp
- c++
---

# GetOrderByTransactionId Method (String)


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Get the pending sales order matching the transaction identifier.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.Client](microsoft-dynamics-commerce-runtime-client-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Client (in Microsoft.Dynamics.Commerce.Runtime.Client.dll)

## Syntax

``` vb
'Declaration
Public Function GetOrderByTransactionId ( _
    transactionId As String _
) As SalesOrder
'Usage
Dim instance As OrderManager
Dim transactionId As String
Dim returnValue As SalesOrder

returnValue = instance.GetOrderByTransactionId(transactionId)
```

``` csharp
public SalesOrder GetOrderByTransactionId(
    string transactionId
)
```

``` c++
public:
SalesOrder^ GetOrderByTransactionId(
    String^ transactionId
)
```

#### Parameters

  - transactionId  
    Type: [System.String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\))  

#### Return Value

Type: [Microsoft.Dynamics.Commerce.Runtime.DataModel.SalesOrder](salesorder-class-microsoft-dynamics-commerce-runtime-datamodel.md)  
Pending sales order matching the transaction identifier, if found; otherwise null.  

## See Also

#### Reference

[OrderManager Class](ordermanager-class-microsoft-dynamics-commerce-runtime-client.md)

[GetOrderByTransactionId Overload](ordermanager-getorderbytransactionid-method-microsoft-dynamics-commerce-runtime-client.md)

[Microsoft.Dynamics.Commerce.Runtime.Client Namespace](microsoft-dynamics-commerce-runtime-client-namespace.md)

