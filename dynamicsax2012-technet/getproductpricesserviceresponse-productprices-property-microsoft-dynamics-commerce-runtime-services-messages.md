---
title: GetProductPricesServiceResponse.ProductPrices Property  (Microsoft.Dynamics.Commerce.Runtime.Services.Messages)
TOCTitle: ProductPrices Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.Services.Messages.GetProductPricesServiceResponse.ProductPrices
ms:mtpsurl: https://technet.microsoft.com/en-us/library/microsoft.dynamics.commerce.runtime.services.messages.getproductpricesserviceresponse.productprices(v=AX.60)
ms:contentKeyID: 62208832
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.Services.Messages.GetProductPricesServiceResponse.ProductPrices
dev_langs:
- CSharp
- C++
- VB
---

# ProductPrices Property

Gets the collection of listing pricess which have been retrieved and calculated.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.Services.Messages](microsoft-dynamics-commerce-runtime-services-messages-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Services.Messages (in Microsoft.Dynamics.Commerce.Runtime.Services.Messages.dll)

## Syntax

``` vb
'Declaration
<DataMemberAttribute> _
Public Property ProductPrices As ReadOnlyCollection(Of ProductPrice)
    Get
    Private Set
'Usage
Dim instance As GetProductPricesServiceResponse
Dim value As ReadOnlyCollection(Of ProductPrice)

value = instance.ProductPrices
```

``` csharp
[DataMemberAttribute]
public ReadOnlyCollection<ProductPrice> ProductPrices { get; private set; }
```

``` c++
[DataMemberAttribute]
public:
property ReadOnlyCollection<ProductPrice^>^ ProductPrices {
    ReadOnlyCollection<ProductPrice^>^ get ();
    private: void set (ReadOnlyCollection<ProductPrice^>^ value);
}
```

#### Property Value

Type: [System.Collections.ObjectModel.ReadOnlyCollection](https://technet.microsoft.com/en-us/library/ms132474\(v=ax.60\))\<[ProductPrice](productprice-class-microsoft-dynamics-commerce-runtime-datamodel.md)\>  
Returns [ReadOnlyCollection\<T\>](https://technet.microsoft.com/en-us/library/ms132474\(v=ax.60\)).  

## See Also

#### Reference

[GetProductPricesServiceResponse Class](getproductpricesserviceresponse-class-microsoft-dynamics-commerce-runtime-services-messages.md)

[Microsoft.Dynamics.Commerce.Runtime.Services.Messages Namespace](microsoft-dynamics-commerce-runtime-services-messages-namespace.md)

