---
title: OrderManager.GetOrderByTransactionId Method (IEnumerable(String)) (Microsoft.Dynamics.Commerce.Runtime.Client)
TOCTitle: GetOrderByTransactionId Method (IEnumerable(String))
ms:assetid: M:Microsoft.Dynamics.Commerce.Runtime.Client.OrderManager.GetOrderByTransactionId(System.Collections.Generic.IEnumerable{System.String})
ms:mtpsurl: https://technet.microsoft.com/en-us/library/microsoft.dynamics.commerce.runtime.client.ordermanager.getorderbytransactionid(v=AX.60)
ms:contentKeyID: 62212936
ms.date: 05/18/2015
mtps_version: v=AX.60
dev_langs:
- vb
- csharp
- c++
---

# GetOrderByTransactionId Method (IEnumerable(String))

Get the pending sales orders matching any transaction identifier in the collection.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.Client](microsoft-dynamics-commerce-runtime-client-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Client (in Microsoft.Dynamics.Commerce.Runtime.Client.dll)

## Syntax

``` vb
'Declaration
Public Function GetOrderByTransactionId ( _
    transactionIdCollection As IEnumerable(Of String) _
) As ReadOnlyCollection(Of SalesOrder)
'Usage
Dim instance As OrderManager
Dim transactionIdCollection As IEnumerable(Of String)
Dim returnValue As ReadOnlyCollection(Of SalesOrder)

returnValue = instance.GetOrderByTransactionId(transactionIdCollection)
```

``` csharp
public ReadOnlyCollection<SalesOrder> GetOrderByTransactionId(
    IEnumerable<string> transactionIdCollection
)
```

``` c++
public:
ReadOnlyCollection<SalesOrder^>^ GetOrderByTransactionId(
    IEnumerable<String^>^ transactionIdCollection
)
```

#### Parameters

  - transactionIdCollection  
    Type: [System.Collections.Generic.IEnumerable](https://technet.microsoft.com/en-us/library/9eekhta0\(v=ax.60\))\<[String](https://technet.microsoft.com/en-us/library/s1wwdcbf\(v=ax.60\))\>  

#### Return Value

Type: [System.Collections.ObjectModel.ReadOnlyCollection](https://technet.microsoft.com/en-us/library/ms132474\(v=ax.60\))\<[SalesOrder](salesorder-class-microsoft-dynamics-commerce-runtime-datamodel.md)\>  
Pending sales order matching the cart identifier, if found; otherwise null.  

## See Also

#### Reference

[OrderManager Class](ordermanager-class-microsoft-dynamics-commerce-runtime-client.md)

[GetOrderByTransactionId Overload](ordermanager-getorderbytransactionid-method-microsoft-dynamics-commerce-runtime-client.md)

[Microsoft.Dynamics.Commerce.Runtime.Client Namespace](microsoft-dynamics-commerce-runtime-client-namespace.md)

