---
title: TransactionServiceClient.GetProductData Method (IEnumerable(String)) (Microsoft.Dynamics.Commerce.Runtime.TransactionService)
TOCTitle: GetProductData Method (IEnumerable(String))
ms:assetid: M:Microsoft.Dynamics.Commerce.Runtime.TransactionService.TransactionServiceClient.GetProductData(System.Collections.Generic.IEnumerable{System.String})
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.transactionservice.transactionserviceclient.getproductdata(v=AX.60)
ms:contentKeyID: 62208687
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
dev_langs:
- vb
- csharp
- c++
---

# GetProductData Method (IEnumerable(String))

Gets the product data (as an XML document) for the specified item identifiers.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.TransactionService](microsoft-dynamics-commerce-runtime-transactionservice-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.TransactionService (in Microsoft.Dynamics.Commerce.Runtime.TransactionService.dll)

## Syntax

``` vb
'Declaration
Public Function GetProductData ( _
    itemIds As IEnumerable(Of String) _
) As XDocument
'Usage
Dim instance As TransactionServiceClient
Dim itemIds As IEnumerable(Of String)
Dim returnValue As XDocument

returnValue = instance.GetProductData(itemIds)
```

``` csharp
public XDocument GetProductData(
    IEnumerable<string> itemIds
)
```

``` c++
public:
XDocument^ GetProductData(
    IEnumerable<String^>^ itemIds
)
```

#### Parameters

  - itemIds  
    Type: [System.Collections.Generic.IEnumerable](https://technet.microsoft.com/library/9eekhta0\(v=ax.60\))\<[String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\))\>  

#### Return Value

Type: [System.Xml.Linq.XDocument](https://technet.microsoft.com/library/bb345449\(v=ax.60\))  
An XML document containing all of the relevant product data.  

## See Also

#### Reference

[TransactionServiceClient Class](transactionserviceclient-class-microsoft-dynamics-commerce-runtime-transactionservice.md)

[GetProductData Overload](transactionserviceclient-getproductdata-method-microsoft-dynamics-commerce-runtime-transactionservice.md)

[Microsoft.Dynamics.Commerce.Runtime.TransactionService Namespace](microsoft-dynamics-commerce-runtime-transactionservice-namespace.md)

