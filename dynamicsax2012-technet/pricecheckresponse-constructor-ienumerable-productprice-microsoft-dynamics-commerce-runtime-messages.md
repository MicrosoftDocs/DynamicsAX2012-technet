---
title: PriceCheckResponse Constructor (IEnumerable(ProductPrice)) (Microsoft.Dynamics.Commerce.Runtime.Messages)
TOCTitle: PriceCheckResponse Constructor (IEnumerable(ProductPrice))
ms:assetid: M:Microsoft.Dynamics.Commerce.Runtime.Messages.PriceCheckResponse.#ctor(System.Collections.Generic.IEnumerable{Microsoft.Dynamics.Commerce.Runtime.DataModel.ProductPrice})
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.messages.pricecheckresponse.pricecheckresponse(v=AX.60)
ms:contentKeyID: 62204930
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
dev_langs:
- vb
- csharp
- c++
---

# PriceCheckResponse Constructor (IEnumerable(ProductPrice))


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Initializes a new instance of the [PriceCheckResponse](pricecheckresponse-class-microsoft-dynamics-commerce-runtime-messages.md) class.

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

Dim instance As New PriceCheckResponse(productPrices)
```

``` csharp
public PriceCheckResponse(
    IEnumerable<ProductPrice> productPrices
)
```

``` c++
public:
PriceCheckResponse(
    IEnumerable<ProductPrice^>^ productPrices
)
```

#### Parameters

  - productPrices  
    Type: [System.Collections.Generic.IEnumerable](https://technet.microsoft.com/library/9eekhta0\(v=ax.60\))\<[ProductPrice](productprice-class-microsoft-dynamics-commerce-runtime-datamodel.md)\>  

## See Also

#### Reference

[PriceCheckResponse Class](pricecheckresponse-class-microsoft-dynamics-commerce-runtime-messages.md)

[PriceCheckResponse Overload](pricecheckresponse-constructor-microsoft-dynamics-commerce-runtime-messages.md)

[Microsoft.Dynamics.Commerce.Runtime.Messages Namespace](microsoft-dynamics-commerce-runtime-messages-namespace.md)

