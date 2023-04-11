---
title: GetProductPartsDataServiceResponse.ProductVariants Property  (Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages)
TOCTitle: ProductVariants Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages.GetProductPartsDataServiceResponse.ProductVariants
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.dataservices.messages.getproductpartsdataserviceresponse.productvariants(v=AX.60)
ms:contentKeyID: 65322688
author: tonyafehr
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages.GetProductPartsDataServiceResponse.ProductVariants
dev_langs:
- CSharp
- C++
- VB
---

# ProductVariants Property


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Gets the product variants.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages](microsoft-dynamics-commerce-runtime-dataservices-messages-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages (in Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages.dll)

## Syntax

``` vb
'Declaration
Public Property ProductVariants As ReadOnlyCollection(Of ProductVariant)
    Get
    Private Set
'Usage
Dim instance As GetProductPartsDataServiceResponse
Dim value As ReadOnlyCollection(Of ProductVariant)

value = instance.ProductVariants
```

``` csharp
public ReadOnlyCollection<ProductVariant> ProductVariants { get; private set; }
```

``` c++
public:
property ReadOnlyCollection<ProductVariant^>^ ProductVariants {
    ReadOnlyCollection<ProductVariant^>^ get ();
    private: void set (ReadOnlyCollection<ProductVariant^>^ value);
}
```

#### Property Value

Type: [System.Collections.ObjectModel.ReadOnlyCollection](https://technet.microsoft.com/library/ms132474\(v=ax.60\))\<[ProductVariant](productvariant-class-microsoft-dynamics-commerce-runtime-datamodel.md)\>  
Returns [ReadOnlyCollection\<T\>](https://technet.microsoft.com/library/ms132474\(v=ax.60\)).  

## See Also

#### Reference

[GetProductPartsDataServiceResponse Class](getproductpartsdataserviceresponse-class-microsoft-dynamics-commerce-runtime-dataservices-messages.md)

[Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages Namespace](microsoft-dynamics-commerce-runtime-dataservices-messages-namespace.md)

