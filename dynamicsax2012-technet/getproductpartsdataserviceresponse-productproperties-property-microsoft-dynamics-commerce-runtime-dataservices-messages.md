---
title: GetProductPartsDataServiceResponse.ProductProperties Property  (Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages)
TOCTitle: ProductProperties Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages.GetProductPartsDataServiceResponse.ProductProperties
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.dataservices.messages.getproductpartsdataserviceresponse.productproperties(v=AX.60)
ms:contentKeyID: 65319822
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages.GetProductPartsDataServiceResponse.ProductProperties
dev_langs:
- CSharp
- C++
- VB
---

# ProductProperties Property

Gets the product properties.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages](microsoft-dynamics-commerce-runtime-dataservices-messages-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages (in Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages.dll)

## Syntax

``` vb
'Declaration
Public Property ProductProperties As ReadOnlyCollection(Of ProductProperty)
    Get
    Private Set
'Usage
Dim instance As GetProductPartsDataServiceResponse
Dim value As ReadOnlyCollection(Of ProductProperty)

value = instance.ProductProperties
```

``` csharp
public ReadOnlyCollection<ProductProperty> ProductProperties { get; private set; }
```

``` c++
public:
property ReadOnlyCollection<ProductProperty^>^ ProductProperties {
    ReadOnlyCollection<ProductProperty^>^ get ();
    private: void set (ReadOnlyCollection<ProductProperty^>^ value);
}
```

#### Property Value

Type: [System.Collections.ObjectModel.ReadOnlyCollection](https://technet.microsoft.com/library/ms132474\(v=ax.60\))\<[ProductProperty](productproperty-class-microsoft-dynamics-commerce-runtime-datamodel.md)\>  
Returns [ReadOnlyCollection\<T\>](https://technet.microsoft.com/library/ms132474\(v=ax.60\)).  

## See Also

#### Reference

[GetProductPartsDataServiceResponse Class](getproductpartsdataserviceresponse-class-microsoft-dynamics-commerce-runtime-dataservices-messages.md)

[Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages Namespace](microsoft-dynamics-commerce-runtime-dataservices-messages-namespace.md)

