---
title: GetIndependentProductPriceDiscountResponse Constructor  (Microsoft.Dynamics.Commerce.Runtime.Messages)
TOCTitle: GetIndependentProductPriceDiscountResponse Constructor
ms:assetid: M:Microsoft.Dynamics.Commerce.Runtime.Messages.GetIndependentProductPriceDiscountResponse.#ctor(System.Collections.Generic.IEnumerable{Microsoft.Dynamics.Commerce.Runtime.DataModel.ProductPrice})
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.messages.getindependentproductpricediscountresponse.getindependentproductpricediscountresponse(v=AX.60)
ms:contentKeyID: 65316982
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.Messages.GetIndependentProductPriceDiscountResponse.#ctor
dev_langs:
- CSharp
- C++
- VB
---

# GetIndependentProductPriceDiscountResponse Constructor


[!INCLUDE[archive-banner](includes/archive-banner.md)]

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

Dim instance As New GetIndependentProductPriceDiscountResponse(productPrices)
```

``` csharp
public GetIndependentProductPriceDiscountResponse(
    IEnumerable<ProductPrice> productPrices
)
```

``` c++
public:
GetIndependentProductPriceDiscountResponse(
    IEnumerable<ProductPrice^>^ productPrices
)
```

#### Parameters

  - productPrices  
    Type: [System.Collections.Generic.IEnumerable](https://technet.microsoft.com/library/9eekhta0\(v=ax.60\))\<[ProductPrice](productprice-class-microsoft-dynamics-commerce-runtime-datamodel.md)\>  

## See Also

#### Reference

[GetIndependentProductPriceDiscountResponse Class](getindependentproductpricediscountresponse-class-microsoft-dynamics-commerce-runtime-messages.md)

[Microsoft.Dynamics.Commerce.Runtime.Messages Namespace](microsoft-dynamics-commerce-runtime-messages-namespace.md)

