---
title: GetProductPartsDataServiceResponse.ProductCatalogs Property  (Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages)
TOCTitle: ProductCatalogs Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages.GetProductPartsDataServiceResponse.ProductCatalogs
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.dataservices.messages.getproductpartsdataserviceresponse.productcatalogs(v=AX.60)
ms:contentKeyID: 65317805
author: tonyafehr
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages.GetProductPartsDataServiceResponse.ProductCatalogs
dev_langs:
- CSharp
- C++
- VB
---

# ProductCatalogs Property


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Gets the product catalogs.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages](microsoft-dynamics-commerce-runtime-dataservices-messages-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages (in Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages.dll)

## Syntax

``` vb
'Declaration
Public Property ProductCatalogs As ReadOnlyCollection(Of ProductCatalog)
    Get
    Private Set
'Usage
Dim instance As GetProductPartsDataServiceResponse
Dim value As ReadOnlyCollection(Of ProductCatalog)

value = instance.ProductCatalogs
```

``` csharp
public ReadOnlyCollection<ProductCatalog> ProductCatalogs { get; private set; }
```

``` c++
public:
property ReadOnlyCollection<ProductCatalog^>^ ProductCatalogs {
    ReadOnlyCollection<ProductCatalog^>^ get ();
    private: void set (ReadOnlyCollection<ProductCatalog^>^ value);
}
```

#### Property Value

Type: [System.Collections.ObjectModel.ReadOnlyCollection](https://technet.microsoft.com/library/ms132474\(v=ax.60\))\<[ProductCatalog](productcatalog-class-microsoft-dynamics-commerce-runtime-datamodel.md)\>  
Returns [ReadOnlyCollection\<T\>](https://technet.microsoft.com/library/ms132474\(v=ax.60\)).  

## See Also

#### Reference

[GetProductPartsDataServiceResponse Class](getproductpartsdataserviceresponse-class-microsoft-dynamics-commerce-runtime-dataservices-messages.md)

[Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages Namespace](microsoft-dynamics-commerce-runtime-dataservices-messages-namespace.md)

