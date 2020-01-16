---
title: GetActiveProductPriceResponse Constructor (IEnumerable(ProductPrice)) (Microsoft.Dynamics.Commerce.Runtime.Messages)
TOCTitle: GetActiveProductPriceResponse Constructor (IEnumerable(ProductPrice))
ms:assetid: M:Microsoft.Dynamics.Commerce.Runtime.Messages.GetActiveProductPriceResponse.#ctor(System.Collections.Generic.IEnumerable{Microsoft.Dynamics.Commerce.Runtime.DataModel.ProductPrice})
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.messages.getactiveproductpriceresponse.getactiveproductpriceresponse(v=AX.60)
ms:contentKeyID: 62211582
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
dev_langs:
- vb
- csharp
- c++
---

# GetActiveProductPriceResponse Constructor (IEnumerable(ProductPrice))

Initializes a new instance of the [GetActiveProductPriceResponse](getactiveproductpriceresponse-class-microsoft-dynamics-commerce-runtime-messages.md) class.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.Messages](microsoft-dynamics-commerce-runtime-messages-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Messages (in Microsoft.Dynamics.Commerce.Runtime.Messages.dll)

## Syntax

``` vb
'Declaration
Public Sub New ( _
    productPrices As IEnumerable(Of ProductPrice) _
)
'Usage
Dim productPrices As IEnumerable(Of ProductPrice)

Dim instance As New GetActiveProductPriceResponse(productPrices)
```

``` csharp
public GetActiveProductPriceResponse(
    IEnumerable<ProductPrice> productPrices
)
```

``` c++
public:
GetActiveProductPriceResponse(
    IEnumerable<ProductPrice^>^ productPrices
)
```

#### Parameters

  - productPrices  
    Type: [System.Collections.Generic.IEnumerable](https://technet.microsoft.com/library/9eekhta0\(v=ax.60\))\<[ProductPrice](productprice-class-microsoft-dynamics-commerce-runtime-datamodel.md)\>  

## See Also

#### Reference

[GetActiveProductPriceResponse Class](getactiveproductpriceresponse-class-microsoft-dynamics-commerce-runtime-messages.md)

[GetActiveProductPriceResponse Overload](getactiveproductpriceresponse-constructor-microsoft-dynamics-commerce-runtime-messages.md)

[Microsoft.Dynamics.Commerce.Runtime.Messages Namespace](microsoft-dynamics-commerce-runtime-messages-namespace.md)

