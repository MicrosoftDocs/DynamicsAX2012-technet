---
title: GetChangedPricesServiceResponse Constructor (IEnumerable(Product)) (Microsoft.Dynamics.Commerce.Runtime.Services.Messages)
TOCTitle: GetChangedPricesServiceResponse Constructor (IEnumerable(Product))
ms:assetid: M:Microsoft.Dynamics.Commerce.Runtime.Services.Messages.GetChangedPricesServiceResponse.#ctor(System.Collections.Generic.IEnumerable{Microsoft.Dynamics.Commerce.Runtime.DataModel.Product})
ms:mtpsurl: https://technet.microsoft.com/en-us/library/microsoft.dynamics.commerce.runtime.services.messages.getchangedpricesserviceresponse.getchangedpricesserviceresponse(v=AX.60)
ms:contentKeyID: 62210608
ms.date: 05/18/2015
mtps_version: v=AX.60
dev_langs:
- vb
- csharp
- c++
---

# GetChangedPricesServiceResponse Constructor (IEnumerable(Product))

Initializes a new instance of the [GetChangedPricesServiceResponse](getchangedpricesserviceresponse-class-microsoft-dynamics-commerce-runtime-services-messages.md) class.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.Services.Messages](microsoft-dynamics-commerce-runtime-services-messages-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Services.Messages (in Microsoft.Dynamics.Commerce.Runtime.Services.Messages.dll)

## Syntax

``` vb
'Declaration
Public Sub New ( _
    products As IEnumerable(Of Product) _
)
'Usage
Dim products As IEnumerable(Of Product)

Dim instance As New GetChangedPricesServiceResponse(products)
```

``` csharp
public GetChangedPricesServiceResponse(
    IEnumerable<Product> products
)
```

``` c++
public:
GetChangedPricesServiceResponse(
    IEnumerable<Product^>^ products
)
```

#### Parameters

  - products  
    Type: [System.Collections.Generic.IEnumerable](https://technet.microsoft.com/en-us/library/9eekhta0\(v=ax.60\))\<[Product](product-class-microsoft-dynamics-commerce-runtime-datamodel.md)\>  

## See Also

#### Reference

[GetChangedPricesServiceResponse Class](getchangedpricesserviceresponse-class-microsoft-dynamics-commerce-runtime-services-messages.md)

[GetChangedPricesServiceResponse Overload](getchangedpricesserviceresponse-constructor-microsoft-dynamics-commerce-runtime-services-messages.md)

[Microsoft.Dynamics.Commerce.Runtime.Services.Messages Namespace](microsoft-dynamics-commerce-runtime-services-messages-namespace.md)

