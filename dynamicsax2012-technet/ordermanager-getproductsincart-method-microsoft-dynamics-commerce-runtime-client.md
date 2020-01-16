---
title: OrderManager.GetProductsInCart Method  (Microsoft.Dynamics.Commerce.Runtime.Client)
TOCTitle: GetProductsInCart Method
ms:assetid: M:Microsoft.Dynamics.Commerce.Runtime.Client.OrderManager.GetProductsInCart(System.String)
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.client.ordermanager.getproductsincart(v=AX.60)
ms:contentKeyID: 62209182
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.Client.OrderManager.GetProductsInCart
dev_langs:
- CSharp
- C++
- VB
---

# GetProductsInCart Method

Get all products invloved in the cart specified by cartId.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.Client](microsoft-dynamics-commerce-runtime-client-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Client (in Microsoft.Dynamics.Commerce.Runtime.Client.dll)

## Syntax

``` vb
'Declaration
Public Function GetProductsInCart ( _
    cartId As String _
) As ReadOnlyCollection(Of Product)
'Usage
Dim instance As OrderManager
Dim cartId As String
Dim returnValue As ReadOnlyCollection(Of Product)

returnValue = instance.GetProductsInCart(cartId)
```

``` csharp
public ReadOnlyCollection<Product> GetProductsInCart(
    string cartId
)
```

``` c++
public:
ReadOnlyCollection<Product^>^ GetProductsInCart(
    String^ cartId
)
```

#### Parameters

  - cartId  
    Type: [System.String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\))  

#### Return Value

Type: [System.Collections.ObjectModel.ReadOnlyCollection](https://technet.microsoft.com/library/ms132474\(v=ax.60\))\<[Product](product-class-microsoft-dynamics-commerce-runtime-datamodel.md)\>  
A collection of [Cart](cart-class-microsoft-dynamics-commerce-runtime-datamodel.md).  

## See Also

#### Reference

[OrderManager Class](ordermanager-class-microsoft-dynamics-commerce-runtime-client.md)

[Microsoft.Dynamics.Commerce.Runtime.Client Namespace](microsoft-dynamics-commerce-runtime-client-namespace.md)

