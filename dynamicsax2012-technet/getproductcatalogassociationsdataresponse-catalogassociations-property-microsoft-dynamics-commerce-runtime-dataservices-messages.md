---
title: GetProductCatalogAssociationsDataResponse.CatalogAssociations Property  (Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages)
TOCTitle: CatalogAssociations Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages.GetProductCatalogAssociationsDataResponse.CatalogAssociations
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.dataservices.messages.getproductcatalogassociationsdataresponse.catalogassociations(v=AX.60)
ms:contentKeyID: 65320215
author: tonyafehr
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages.GetProductCatalogAssociationsDataResponse.CatalogAssociations
dev_langs:
- CSharp
- C++
- VB
---

# CatalogAssociations Property


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Gets the collection of product catalog associations.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages](microsoft-dynamics-commerce-runtime-dataservices-messages-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages (in Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages.dll)

## Syntax

``` vb
'Declaration
<DataMemberAttribute> _
Public Property CatalogAssociations As ReadOnlyCollection(Of ProductCatalogAssociation)
    Get
    Private Set
'Usage
Dim instance As GetProductCatalogAssociationsDataResponse
Dim value As ReadOnlyCollection(Of ProductCatalogAssociation)

value = instance.CatalogAssociations
```

``` csharp
[DataMemberAttribute]
public ReadOnlyCollection<ProductCatalogAssociation> CatalogAssociations { get; private set; }
```

``` c++
[DataMemberAttribute]
public:
property ReadOnlyCollection<ProductCatalogAssociation^>^ CatalogAssociations {
    ReadOnlyCollection<ProductCatalogAssociation^>^ get ();
    private: void set (ReadOnlyCollection<ProductCatalogAssociation^>^ value);
}
```

#### Property Value

Type: [System.Collections.ObjectModel.ReadOnlyCollection](https://technet.microsoft.com/library/ms132474\(v=ax.60\))\<[ProductCatalogAssociation](productcatalogassociation-class-microsoft-dynamics-commerce-runtime-datamodel.md)\>  
Returns [ReadOnlyCollection\<T\>](https://technet.microsoft.com/library/ms132474\(v=ax.60\)).  

## See Also

#### Reference

[GetProductCatalogAssociationsDataResponse Class](getproductcatalogassociationsdataresponse-class-microsoft-dynamics-commerce-runtime-dataservices-messages.md)

[Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages Namespace](microsoft-dynamics-commerce-runtime-dataservices-messages-namespace.md)

