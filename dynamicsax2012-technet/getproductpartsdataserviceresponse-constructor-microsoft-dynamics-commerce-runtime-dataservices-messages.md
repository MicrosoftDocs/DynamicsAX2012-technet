---
title: GetProductPartsDataServiceResponse Constructor  (Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages)
TOCTitle: GetProductPartsDataServiceResponse Constructor
ms:assetid: M:Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages.GetProductPartsDataServiceResponse.#ctor(System.Collections.ObjectModel.ReadOnlyCollection{Microsoft.Dynamics.Commerce.Runtime.DataModel.ProductIdentity},System.Collections.ObjectModel.ReadOnlyCollection{Microsoft.Dynamics.Commerce.Runtime.DataModel.ProductVariant},System.Collections.ObjectModel.ReadOnlyCollection{Microsoft.Dynamics.Commerce.Runtime.DataModel.ProductProperty},System.Collections.ObjectModel.ReadOnlyCollection{Microsoft.Dynamics.Commerce.Runtime.DataModel.ProductAttributeSchemaEntry},System.Collections.ObjectModel.ReadOnlyCollection{Microsoft.Dynamics.Commerce.Runtime.DataModel.ProductRules},System.Collections.ObjectModel.ReadOnlyCollection{Microsoft.Dynamics.Commerce.Runtime.DataModel.ProductCatalog},System.Collections.ObjectModel.ReadOnlyCollection{Microsoft.Dynamics.Commerce.Runtime.DataModel.ProductCategoryAssociation},System.Collections.ObjectModel.ReadOnlyCollection{Microsoft.Dynamics.Commerce.Runtime.DataModel.RelatedProduct},System.Collections.ObjectModel.ReadOnlyCollection{Microsoft.Dynamics.Commerce.Runtime.DataModel.LinkedProduct})
ms:mtpsurl: https://technet.microsoft.com/library/Dn989434(v=AX.60)
ms:contentKeyID: 65319387
author: tonyafehr
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages.GetProductPartsDataServiceResponse.#ctor
dev_langs:
- CSharp
- C++
- VB
---

# GetProductPartsDataServiceResponse Constructor


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Initializes a new instance of the [GetProductPartsDataServiceResponse](getproductpartsdataserviceresponse-class-microsoft-dynamics-commerce-runtime-dataservices-messages.md) class.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages](microsoft-dynamics-commerce-runtime-dataservices-messages-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages (in Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages.dll)

## Syntax

``` vb
'Declaration
Public Sub New ( _
    productIdentities As ReadOnlyCollection(Of ProductIdentity), _
    productVariants As ReadOnlyCollection(Of ProductVariant), _
    productProperties As ReadOnlyCollection(Of ProductProperty), _
    productAttributeSchemaEntries As ReadOnlyCollection(Of ProductAttributeSchemaEntry), _
    productRules As ReadOnlyCollection(Of ProductRules), _
    productCatalogs As ReadOnlyCollection(Of ProductCatalog), _
    categoryAssociations As ReadOnlyCollection(Of ProductCategoryAssociation), _
    relatedProducts As ReadOnlyCollection(Of RelatedProduct), _
    linkedProducts As ReadOnlyCollection(Of LinkedProduct) _
)
'Usage
Dim productIdentities As ReadOnlyCollection(Of ProductIdentity)
Dim productVariants As ReadOnlyCollection(Of ProductVariant)
Dim productProperties As ReadOnlyCollection(Of ProductProperty)
Dim productAttributeSchemaEntries As ReadOnlyCollection(Of ProductAttributeSchemaEntry)
Dim productRules As ReadOnlyCollection(Of ProductRules)
Dim productCatalogs As ReadOnlyCollection(Of ProductCatalog)
Dim categoryAssociations As ReadOnlyCollection(Of ProductCategoryAssociation)
Dim relatedProducts As ReadOnlyCollection(Of RelatedProduct)
Dim linkedProducts As ReadOnlyCollection(Of LinkedProduct)

Dim instance As New GetProductPartsDataServiceResponse(productIdentities, _
    productVariants, productProperties, _
    productAttributeSchemaEntries, _
    productRules, productCatalogs, categoryAssociations, _
    relatedProducts, linkedProducts)
```

``` csharp
public GetProductPartsDataServiceResponse(
    ReadOnlyCollection<ProductIdentity> productIdentities,
    ReadOnlyCollection<ProductVariant> productVariants,
    ReadOnlyCollection<ProductProperty> productProperties,
    ReadOnlyCollection<ProductAttributeSchemaEntry> productAttributeSchemaEntries,
    ReadOnlyCollection<ProductRules> productRules,
    ReadOnlyCollection<ProductCatalog> productCatalogs,
    ReadOnlyCollection<ProductCategoryAssociation> categoryAssociations,
    ReadOnlyCollection<RelatedProduct> relatedProducts,
    ReadOnlyCollection<LinkedProduct> linkedProducts
)
```

``` c++
public:
GetProductPartsDataServiceResponse(
    ReadOnlyCollection<ProductIdentity^>^ productIdentities, 
    ReadOnlyCollection<ProductVariant^>^ productVariants, 
    ReadOnlyCollection<ProductProperty^>^ productProperties, 
    ReadOnlyCollection<ProductAttributeSchemaEntry^>^ productAttributeSchemaEntries, 
    ReadOnlyCollection<ProductRules^>^ productRules, 
    ReadOnlyCollection<ProductCatalog^>^ productCatalogs, 
    ReadOnlyCollection<ProductCategoryAssociation^>^ categoryAssociations, 
    ReadOnlyCollection<RelatedProduct^>^ relatedProducts, 
    ReadOnlyCollection<LinkedProduct^>^ linkedProducts
)
```

#### Parameters

  - productIdentities  
    Type: [System.Collections.ObjectModel.ReadOnlyCollection](https://technet.microsoft.com/library/ms132474\(v=ax.60\))\<[ProductIdentity](productidentity-class-microsoft-dynamics-commerce-runtime-datamodel.md)\>  

<!-- end list -->

  - productVariants  
    Type: [System.Collections.ObjectModel.ReadOnlyCollection](https://technet.microsoft.com/library/ms132474\(v=ax.60\))\<[ProductVariant](productvariant-class-microsoft-dynamics-commerce-runtime-datamodel.md)\>  

<!-- end list -->

  - productProperties  
    Type: [System.Collections.ObjectModel.ReadOnlyCollection](https://technet.microsoft.com/library/ms132474\(v=ax.60\))\<[ProductProperty](productproperty-class-microsoft-dynamics-commerce-runtime-datamodel.md)\>  

<!-- end list -->

  - productAttributeSchemaEntries  
    Type: [System.Collections.ObjectModel.ReadOnlyCollection](https://technet.microsoft.com/library/ms132474\(v=ax.60\))\<[ProductAttributeSchemaEntry](productattributeschemaentry-class-microsoft-dynamics-commerce-runtime-datamodel.md)\>  

<!-- end list -->

  - productRules  
    Type: [System.Collections.ObjectModel.ReadOnlyCollection](https://technet.microsoft.com/library/ms132474\(v=ax.60\))\<[ProductRules](productrules-class-microsoft-dynamics-commerce-runtime-datamodel.md)\>  

<!-- end list -->

  - productCatalogs  
    Type: [System.Collections.ObjectModel.ReadOnlyCollection](https://technet.microsoft.com/library/ms132474\(v=ax.60\))\<[ProductCatalog](productcatalog-class-microsoft-dynamics-commerce-runtime-datamodel.md)\>  

<!-- end list -->

  - categoryAssociations  
    Type: [System.Collections.ObjectModel.ReadOnlyCollection](https://technet.microsoft.com/library/ms132474\(v=ax.60\))\<[ProductCategoryAssociation](productcategoryassociation-class-microsoft-dynamics-commerce-runtime-datamodel.md)\>  

<!-- end list -->

  - relatedProducts  
    Type: [System.Collections.ObjectModel.ReadOnlyCollection](https://technet.microsoft.com/library/ms132474\(v=ax.60\))\<[RelatedProduct](relatedproduct-class-microsoft-dynamics-commerce-runtime-datamodel.md)\>  

<!-- end list -->

  - linkedProducts  
    Type: [System.Collections.ObjectModel.ReadOnlyCollection](https://technet.microsoft.com/library/ms132474\(v=ax.60\))\<[LinkedProduct](linkedproduct-class-microsoft-dynamics-commerce-runtime-datamodel.md)\>  

## See Also

#### Reference

[GetProductPartsDataServiceResponse Class](getproductpartsdataserviceresponse-class-microsoft-dynamics-commerce-runtime-dataservices-messages.md)

[Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages Namespace](microsoft-dynamics-commerce-runtime-dataservices-messages-namespace.md)

