---
title: GetProductPartsDataServiceResponse.RelatedProducts Property  (Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages)
TOCTitle: RelatedProducts Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages.GetProductPartsDataServiceResponse.RelatedProducts
ms:mtpsurl: https://technet.microsoft.com/en-us/library/microsoft.dynamics.commerce.runtime.dataservices.messages.getproductpartsdataserviceresponse.relatedproducts(v=AX.60)
ms:contentKeyID: 65320121
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages.GetProductPartsDataServiceResponse.RelatedProducts
dev_langs:
- CSharp
- C++
- VB
---

# RelatedProducts Property

Gets the related products.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages](microsoft-dynamics-commerce-runtime-dataservices-messages-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages (in Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages.dll)

## Syntax

``` vb
'Declaration
Public Property RelatedProducts As ReadOnlyCollection(Of RelatedProduct)
    Get
    Private Set
'Usage
Dim instance As GetProductPartsDataServiceResponse
Dim value As ReadOnlyCollection(Of RelatedProduct)

value = instance.RelatedProducts
```

``` csharp
public ReadOnlyCollection<RelatedProduct> RelatedProducts { get; private set; }
```

``` c++
public:
property ReadOnlyCollection<RelatedProduct^>^ RelatedProducts {
    ReadOnlyCollection<RelatedProduct^>^ get ();
    private: void set (ReadOnlyCollection<RelatedProduct^>^ value);
}
```

#### Property Value

Type: [System.Collections.ObjectModel.ReadOnlyCollection](https://technet.microsoft.com/en-us/library/ms132474\(v=ax.60\))\<[RelatedProduct](relatedproduct-class-microsoft-dynamics-commerce-runtime-datamodel.md)\>  
Returns [ReadOnlyCollection\<T\>](https://technet.microsoft.com/en-us/library/ms132474\(v=ax.60\)).  

## See Also

#### Reference

[GetProductPartsDataServiceResponse Class](getproductpartsdataserviceresponse-class-microsoft-dynamics-commerce-runtime-dataservices-messages.md)

[Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages Namespace](microsoft-dynamics-commerce-runtime-dataservices-messages-namespace.md)

