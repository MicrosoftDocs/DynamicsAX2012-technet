---
title: GetProductCatalogAssociationsDataResponse Constructor  (Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages)
TOCTitle: GetProductCatalogAssociationsDataResponse Constructor
ms:assetid: M:Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages.GetProductCatalogAssociationsDataResponse.#ctor(System.Collections.ObjectModel.ReadOnlyCollection{Microsoft.Dynamics.Commerce.Runtime.DataModel.ProductCatalogAssociation})
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.dataservices.messages.getproductcatalogassociationsdataresponse.getproductcatalogassociationsdataresponse(v=AX.60)
ms:contentKeyID: 65320560
author: tonyafehr
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages.GetProductCatalogAssociationsDataResponse.#ctor
dev_langs:
- CSharp
- C++
- VB
---

# GetProductCatalogAssociationsDataResponse Constructor


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Initializes a new instance of the [GetProductCatalogAssociationsDataResponse](getproductcatalogassociationsdataresponse-class-microsoft-dynamics-commerce-runtime-dataservices-messages.md) class.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages](microsoft-dynamics-commerce-runtime-dataservices-messages-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages (in Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages.dll)

## Syntax

``` vb
'Declaration
Public Sub New ( _
    catalogAssociations As ReadOnlyCollection(Of ProductCatalogAssociation) _
)
'Usage
Dim catalogAssociations As ReadOnlyCollection(Of ProductCatalogAssociation)

Dim instance As New GetProductCatalogAssociationsDataResponse(catalogAssociations)
```

``` csharp
public GetProductCatalogAssociationsDataResponse(
    ReadOnlyCollection<ProductCatalogAssociation> catalogAssociations
)
```

``` c++
public:
GetProductCatalogAssociationsDataResponse(
    ReadOnlyCollection<ProductCatalogAssociation^>^ catalogAssociations
)
```

#### Parameters

  - catalogAssociations  
    Type: [System.Collections.ObjectModel.ReadOnlyCollection](https://technet.microsoft.com/library/ms132474\(v=ax.60\))\<[ProductCatalogAssociation](productcatalogassociation-class-microsoft-dynamics-commerce-runtime-datamodel.md)\>  

## See Also

#### Reference

[GetProductCatalogAssociationsDataResponse Class](getproductcatalogassociationsdataresponse-class-microsoft-dynamics-commerce-runtime-dataservices-messages.md)

[Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages Namespace](microsoft-dynamics-commerce-runtime-dataservices-messages-namespace.md)

