---
title: TransactionServiceClient.GetProductData Method (IEnumerable(Int64)) (Microsoft.Dynamics.Commerce.Runtime.TransactionService)
TOCTitle: GetProductData Method (IEnumerable(Int64))
ms:assetid: M:Microsoft.Dynamics.Commerce.Runtime.TransactionService.TransactionServiceClient.GetProductData(System.Collections.Generic.IEnumerable{System.Int64})
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.transactionservice.transactionserviceclient.getproductdata(v=AX.60)
ms:contentKeyID: 62212352
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
dev_langs:
- vb
- csharp
- c++
---

# GetProductData Method (IEnumerable(Int64))

Gets the product data (as an XML document) for the specified product identifiers.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.TransactionService](microsoft-dynamics-commerce-runtime-transactionservice-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.TransactionService (in Microsoft.Dynamics.Commerce.Runtime.TransactionService.dll)

## Syntax

``` vb
'Declaration
Public Function GetProductData ( _
    productIds As IEnumerable(Of Long) _
) As XDocument
'Usage
Dim instance As TransactionServiceClient
Dim productIds As IEnumerable(Of Long)
Dim returnValue As XDocument

returnValue = instance.GetProductData(productIds)
```

``` csharp
public XDocument GetProductData(
    IEnumerable<long> productIds
)
```

``` c++
public:
XDocument^ GetProductData(
    IEnumerable<long long>^ productIds
)
```

#### Parameters

  - productIds  
    Type: [System.Collections.Generic.IEnumerable](https://technet.microsoft.com/library/9eekhta0\(v=ax.60\))\<[Int64](https://technet.microsoft.com/library/6yy583ek\(v=ax.60\))\>  

#### Return Value

Type: [System.Xml.Linq.XDocument](https://technet.microsoft.com/library/bb345449\(v=ax.60\))  
An XML document containing all of the relevant product data.  

## See Also

#### Reference

[TransactionServiceClient Class](transactionserviceclient-class-microsoft-dynamics-commerce-runtime-transactionservice.md)

[GetProductData Overload](transactionserviceclient-getproductdata-method-microsoft-dynamics-commerce-runtime-transactionservice.md)

[Microsoft.Dynamics.Commerce.Runtime.TransactionService Namespace](microsoft-dynamics-commerce-runtime-transactionservice-namespace.md)

