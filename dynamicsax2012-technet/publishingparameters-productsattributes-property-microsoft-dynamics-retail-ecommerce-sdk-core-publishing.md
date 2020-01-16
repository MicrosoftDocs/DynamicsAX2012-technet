---
title: PublishingParameters.ProductsAttributes Property  (Microsoft.Dynamics.Retail.Ecommerce.Sdk.Core.Publishing)
TOCTitle: ProductsAttributes Property
ms:assetid: P:Microsoft.Dynamics.Retail.Ecommerce.Sdk.Core.Publishing.PublishingParameters.ProductsAttributes
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.retail.ecommerce.sdk.core.publishing.publishingparameters.productsattributes(v=AX.60)
ms:contentKeyID: 65317117
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Retail.Ecommerce.Sdk.Core.Publishing.PublishingParameters.ProductsAttributes
dev_langs:
- CSharp
- C++
- VB
---

# ProductsAttributes Property

**Namespace:**  [Microsoft.Dynamics.Retail.Ecommerce.Sdk.Core.Publishing](microsoft-dynamics-retail-ecommerce-sdk-core-publishing-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Retail.Ecommerce.Sdk.Core (in Microsoft.Dynamics.Retail.Ecommerce.Sdk.Core.dll)

## Syntax

``` vb
'Declaration
Public Property ProductsAttributes As IEnumerable(Of AttributeProduct)
    Get
    Friend Set
'Usage
Dim instance As PublishingParameters
Dim value As IEnumerable(Of AttributeProduct)

value = instance.ProductsAttributes
```

``` csharp
public IEnumerable<AttributeProduct> ProductsAttributes { get; internal set; }
```

``` c++
public:
property IEnumerable<AttributeProduct^>^ ProductsAttributes {
    IEnumerable<AttributeProduct^>^ get ();
    internal: void set (IEnumerable<AttributeProduct^>^ value);
}
```

#### Property Value

Type: [System.Collections.Generic.IEnumerable](https://technet.microsoft.com/library/9eekhta0\(v=ax.60\))\<AttributeProduct\>  

## See Also

#### Reference

[PublishingParameters Class](publishingparameters-class-microsoft-dynamics-retail-ecommerce-sdk-core-publishing.md)

[Microsoft.Dynamics.Retail.Ecommerce.Sdk.Core.Publishing Namespace](microsoft-dynamics-retail-ecommerce-sdk-core-publishing-namespace.md)

