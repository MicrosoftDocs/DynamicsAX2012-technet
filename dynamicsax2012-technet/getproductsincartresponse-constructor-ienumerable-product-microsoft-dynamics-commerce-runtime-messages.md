---
title: GetProductsInCartResponse Constructor (IEnumerable(Product)) (Microsoft.Dynamics.Commerce.Runtime.Messages)
TOCTitle: GetProductsInCartResponse Constructor (IEnumerable(Product))
ms:assetid: M:Microsoft.Dynamics.Commerce.Runtime.Messages.GetProductsInCartResponse.#ctor(System.Collections.Generic.IEnumerable{Microsoft.Dynamics.Commerce.Runtime.DataModel.Product})
ms:mtpsurl: https://technet.microsoft.com/en-us/library/microsoft.dynamics.commerce.runtime.messages.getproductsincartresponse.getproductsincartresponse(v=AX.60)
ms:contentKeyID: 62206885
ms.date: 05/18/2015
mtps_version: v=AX.60
dev_langs:
- vb
- csharp
- c++
---

# GetProductsInCartResponse Constructor (IEnumerable(Product))

Initializes a new instance of the [GetProductsInCartResponse](getproductsincartresponse-class-microsoft-dynamics-commerce-runtime-messages.md) class.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.Messages](microsoft-dynamics-commerce-runtime-messages-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Messages (in Microsoft.Dynamics.Commerce.Runtime.Messages.dll)

## Syntax

``` vb
'Declaration
Public Sub New ( _
    products As IEnumerable(Of Product) _
)
'Usage
Dim products As IEnumerable(Of Product)

Dim instance As New GetProductsInCartResponse(products)
```

``` csharp
public GetProductsInCartResponse(
    IEnumerable<Product> products
)
```

``` c++
public:
GetProductsInCartResponse(
    IEnumerable<Product^>^ products
)
```

#### Parameters

  - products  
    Type: [System.Collections.Generic.IEnumerable](https://technet.microsoft.com/en-us/library/9eekhta0\(v=ax.60\))\<[Product](product-class-microsoft-dynamics-commerce-runtime-datamodel.md)\>  

## See Also

#### Reference

[GetProductsInCartResponse Class](getproductsincartresponse-class-microsoft-dynamics-commerce-runtime-messages.md)

[GetProductsInCartResponse Overload](getproductsincartresponse-constructor-microsoft-dynamics-commerce-runtime-messages.md)

[Microsoft.Dynamics.Commerce.Runtime.Messages Namespace](microsoft-dynamics-commerce-runtime-messages-namespace.md)

