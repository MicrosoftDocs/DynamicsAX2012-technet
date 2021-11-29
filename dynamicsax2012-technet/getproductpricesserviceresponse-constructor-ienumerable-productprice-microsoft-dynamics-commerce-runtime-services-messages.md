---
title: GetProductPricesServiceResponse Constructor (IEnumerable(ProductPrice)) (Microsoft.Dynamics.Commerce.Runtime.Services.Messages)
TOCTitle: GetProductPricesServiceResponse Constructor (IEnumerable(ProductPrice))
ms:assetid: M:Microsoft.Dynamics.Commerce.Runtime.Services.Messages.GetProductPricesServiceResponse.#ctor(System.Collections.Generic.IEnumerable{Microsoft.Dynamics.Commerce.Runtime.DataModel.ProductPrice})
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.services.messages.getproductpricesserviceresponse.getproductpricesserviceresponse(v=AX.60)
ms:contentKeyID: 62211300
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
dev_langs:
- vb
- csharp
- c++
---

# GetProductPricesServiceResponse Constructor (IEnumerable(ProductPrice))


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Initializes a new instance of the [GetProductPricesServiceResponse](getproductpricesserviceresponse-class-microsoft-dynamics-commerce-runtime-services-messages.md) class.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.Services.Messages](microsoft-dynamics-commerce-runtime-services-messages-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Services.Messages (in Microsoft.Dynamics.Commerce.Runtime.Services.Messages.dll)

## Syntax

``` vb
'Declaration
Public Sub New ( _
    productPrices As IEnumerable(Of ProductPrice) _
)
'Usage
Dim productPrices As IEnumerable(Of ProductPrice)

Dim instance As New GetProductPricesServiceResponse(productPrices)
```

``` csharp
public GetProductPricesServiceResponse(
    IEnumerable<ProductPrice> productPrices
)
```

``` c++
public:
GetProductPricesServiceResponse(
    IEnumerable<ProductPrice^>^ productPrices
)
```

#### Parameters

  - productPrices  
    Type: [System.Collections.Generic.IEnumerable](https://technet.microsoft.com/library/9eekhta0\(v=ax.60\))\<[ProductPrice](productprice-class-microsoft-dynamics-commerce-runtime-datamodel.md)\>  

## See Also

#### Reference

[GetProductPricesServiceResponse Class](getproductpricesserviceresponse-class-microsoft-dynamics-commerce-runtime-services-messages.md)

[GetProductPricesServiceResponse Overload](getproductpricesserviceresponse-constructor-microsoft-dynamics-commerce-runtime-services-messages.md)

[Microsoft.Dynamics.Commerce.Runtime.Services.Messages Namespace](microsoft-dynamics-commerce-runtime-services-messages-namespace.md)

