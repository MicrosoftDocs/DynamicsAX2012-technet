---
title: ProductDatabaseAccessor.RetrieveProductParts Method  (Microsoft.Dynamics.Commerce.Runtime.Data)
TOCTitle: RetrieveProductParts Method
ms:assetid: M:Microsoft.Dynamics.Commerce.Runtime.Data.ProductDatabaseAccessor.RetrieveProductParts(Microsoft.Dynamics.Commerce.Runtime.DataModel.ProductSearchCriteria,System.Boolean,Microsoft.Dynamics.Commerce.Runtime.DataModel.QueryResultSettings,System.Boolean)
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.data.productdatabaseaccessor.retrieveproductparts(v=AX.60)
ms:contentKeyID: 65318572
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.Data.ProductDatabaseAccessor.RetrieveProductParts
dev_langs:
- CSharp
- C++
- VB
---

# RetrieveProductParts Method


[!INCLUDE[archive-banner](includes/archive-banner.md)]

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.Data](microsoft-dynamics-commerce-runtime-data-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.DataManagers (in Microsoft.Dynamics.Commerce.Runtime.DataManagers.dll)

## Syntax

``` vb
'Declaration
Public Function RetrieveProductParts ( _
    queryCriteria As ProductSearchCriteria, _
    isForwardLooking As Boolean, _
    settings As QueryResultSettings, _
    isOnline As Boolean _
) As Tuple(Of ReadOnlyCollection(Of ProductIdentity), ReadOnlyCollection(Of ProductVariant), ReadOnlyCollection(Of ProductRules), ReadOnlyCollection(Of ProductAttributeSchemaEntry), ReadOnlyCollection(Of ProductProperty), ReadOnlyCollection(Of ProductCatalog), ReadOnlyCollection(Of ProductCategoryAssociation), Tuple(Of ReadOnlyCollection(Of RelatedProduct)))
'Usage
Dim instance As ProductDatabaseAccessor
Dim queryCriteria As ProductSearchCriteria
Dim isForwardLooking As Boolean
Dim settings As QueryResultSettings
Dim isOnline As Boolean
Dim returnValue As Tuple(Of ReadOnlyCollection(Of ProductIdentity), ReadOnlyCollection(Of ProductVariant), ReadOnlyCollection(Of ProductRules), ReadOnlyCollection(Of ProductAttributeSchemaEntry), ReadOnlyCollection(Of ProductProperty), ReadOnlyCollection(Of ProductCatalog), ReadOnlyCollection(Of ProductCategoryAssociation), Tuple(Of ReadOnlyCollection(Of RelatedProduct)))

returnValue = instance.RetrieveProductParts(queryCriteria, _
    isForwardLooking, settings, isOnline)
```

``` csharp
public Tuple<ReadOnlyCollection<ProductIdentity>, ReadOnlyCollection<ProductVariant>, ReadOnlyCollection<ProductRules>, ReadOnlyCollection<ProductAttributeSchemaEntry>, ReadOnlyCollection<ProductProperty>, ReadOnlyCollection<ProductCatalog>, ReadOnlyCollection<ProductCategoryAssociation>, Tuple<ReadOnlyCollection<RelatedProduct>>> RetrieveProductParts(
    ProductSearchCriteria queryCriteria,
    bool isForwardLooking,
    QueryResultSettings settings,
    bool isOnline
)
```

``` c++
public:
Tuple<ReadOnlyCollection<ProductIdentity^>^, ReadOnlyCollection<ProductVariant^>^, ReadOnlyCollection<ProductRules^>^, ReadOnlyCollection<ProductAttributeSchemaEntry^>^, ReadOnlyCollection<ProductProperty^>^, ReadOnlyCollection<ProductCatalog^>^, ReadOnlyCollection<ProductCategoryAssociation^>^, Tuple<ReadOnlyCollection<RelatedProduct^>^>^>^ RetrieveProductParts(
    ProductSearchCriteria^ queryCriteria, 
    bool isForwardLooking, 
    QueryResultSettings^ settings, 
    bool isOnline
)
```

#### Parameters

  - queryCriteria  
    Type: [Microsoft.Dynamics.Commerce.Runtime.DataModel.ProductSearchCriteria](productsearchcriteria-class-microsoft-dynamics-commerce-runtime-datamodel.md)  

<!-- end list -->

  - isForwardLooking  
    Type: [System.Boolean](https://technet.microsoft.com/library/a28wyd50\(v=ax.60\))  

<!-- end list -->

  - settings  
    Type: [Microsoft.Dynamics.Commerce.Runtime.DataModel.QueryResultSettings](queryresultsettings-class-microsoft-dynamics-commerce-runtime-datamodel.md)  

<!-- end list -->

  - isOnline  
    Type: [System.Boolean](https://technet.microsoft.com/library/a28wyd50\(v=ax.60\))  

#### Return Value

Type: Tuple\<[ReadOnlyCollection](https://technet.microsoft.com/library/ms132474\(v=ax.60\))\<[ProductIdentity](productidentity-class-microsoft-dynamics-commerce-runtime-datamodel.md)\>, [ReadOnlyCollection](https://technet.microsoft.com/library/ms132474\(v=ax.60\))\<[ProductVariant](productvariant-class-microsoft-dynamics-commerce-runtime-datamodel.md)\>, [ReadOnlyCollection](https://technet.microsoft.com/library/ms132474\(v=ax.60\))\<[ProductRules](productrules-class-microsoft-dynamics-commerce-runtime-datamodel.md)\>, [ReadOnlyCollection](https://technet.microsoft.com/library/ms132474\(v=ax.60\))\<[ProductAttributeSchemaEntry](productattributeschemaentry-class-microsoft-dynamics-commerce-runtime-datamodel.md)\>, [ReadOnlyCollection](https://technet.microsoft.com/library/ms132474\(v=ax.60\))\<[ProductProperty](productproperty-class-microsoft-dynamics-commerce-runtime-datamodel.md)\>, [ReadOnlyCollection](https://technet.microsoft.com/library/ms132474\(v=ax.60\))\<[ProductCatalog](productcatalog-class-microsoft-dynamics-commerce-runtime-datamodel.md)\>, [ReadOnlyCollection](https://technet.microsoft.com/library/ms132474\(v=ax.60\))\<[ProductCategoryAssociation](productcategoryassociation-class-microsoft-dynamics-commerce-runtime-datamodel.md)\>, Tuple\<[ReadOnlyCollection](https://technet.microsoft.com/library/ms132474\(v=ax.60\))\<[RelatedProduct](relatedproduct-class-microsoft-dynamics-commerce-runtime-datamodel.md)\>\>\>  

## See Also

#### Reference

[ProductDatabaseAccessor Class](productdatabaseaccessor-class-microsoft-dynamics-commerce-runtime-data.md)

[Microsoft.Dynamics.Commerce.Runtime.Data Namespace](microsoft-dynamics-commerce-runtime-data-namespace.md)

