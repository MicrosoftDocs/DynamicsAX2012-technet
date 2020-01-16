---
title: ProductManager.GetActiveProductPrice Method (IEnumerable(Int64), DateTime, String) (Microsoft.Dynamics.Commerce.Runtime.Client)
TOCTitle: GetActiveProductPrice Method (IEnumerable(Int64), DateTime, String)
ms:assetid: M:Microsoft.Dynamics.Commerce.Runtime.Client.ProductManager.GetActiveProductPrice(System.Collections.Generic.IEnumerable{System.Int64},System.DateTime,System.String)
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.client.productmanager.getactiveproductprice(v=AX.60)
ms:contentKeyID: 62211682
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
dev_langs:
- vb
- csharp
- c++
---

# GetActiveProductPrice Method (IEnumerable(Int64), DateTime, String)

Gets the active product price of an item.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.Client](microsoft-dynamics-commerce-runtime-client-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Client (in Microsoft.Dynamics.Commerce.Runtime.Client.dll)

## Syntax

``` vb
'Declaration
Public Function GetActiveProductPrice ( _
    productIds As IEnumerable(Of Long), _
    activeDate As DateTime, _
    customerAccountNumber As String _
) As ReadOnlyCollection(Of ProductPrice)
'Usage
Dim instance As ProductManager
Dim productIds As IEnumerable(Of Long)
Dim activeDate As DateTime
Dim customerAccountNumber As String
Dim returnValue As ReadOnlyCollection(Of ProductPrice)

returnValue = instance.GetActiveProductPrice(productIds, _
    activeDate, customerAccountNumber)
```

``` csharp
public ReadOnlyCollection<ProductPrice> GetActiveProductPrice(
    IEnumerable<long> productIds,
    DateTime activeDate,
    string customerAccountNumber
)
```

``` c++
public:
ReadOnlyCollection<ProductPrice^>^ GetActiveProductPrice(
    IEnumerable<long long>^ productIds, 
    DateTime activeDate, 
    String^ customerAccountNumber
)
```

#### Parameters

  - productIds  
    Type: [System.Collections.Generic.IEnumerable](https://technet.microsoft.com/library/9eekhta0\(v=ax.60\))\<[Int64](https://technet.microsoft.com/library/6yy583ek\(v=ax.60\))\>  

<!-- end list -->

  - activeDate  
    Type: [System.DateTime](https://technet.microsoft.com/library/03ybds8y\(v=ax.60\))  

<!-- end list -->

  - customerAccountNumber  
    Type: [System.String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\))  

#### Return Value

Type: [System.Collections.ObjectModel.ReadOnlyCollection](https://technet.microsoft.com/library/ms132474\(v=ax.60\))\<[ProductPrice](productprice-class-microsoft-dynamics-commerce-runtime-datamodel.md)\>  
Price of item.  

## See Also

#### Reference

[ProductManager Class](productmanager-class-microsoft-dynamics-commerce-runtime-client.md)

[GetActiveProductPrice Overload](productmanager-getactiveproductprice-method-microsoft-dynamics-commerce-runtime-client.md)

[Microsoft.Dynamics.Commerce.Runtime.Client Namespace](microsoft-dynamics-commerce-runtime-client-namespace.md)

