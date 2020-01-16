---
title: ProductBuilder.AssembleProductsFromDataSets Method  (Microsoft.Dynamics.Commerce.Runtime.Data)
TOCTitle: AssembleProductsFromDataSets Method
ms:assetid: M:Microsoft.Dynamics.Commerce.Runtime.Data.ProductBuilder.AssembleProductsFromDataSets(Microsoft.Dynamics.Commerce.Runtime.DataModel.ProjectionDomain,Microsoft.Dynamics.Commerce.Runtime.DataModel.CommerceEntityDataLevel,System.Tuple{System.Collections.ObjectModel.ReadOnlyCollection{Microsoft.Dynamics.Commerce.Runtime.DataModel.ProductIdentity},System.Collections.ObjectModel.ReadOnlyCollection{Microsoft.Dynamics.Commerce.Runtime.DataModel.ProductVariant},System.Collections.ObjectModel.ReadOnlyCollection{Microsoft.Dynamics.Commerce.Runtime.DataModel.ProductRules},System.Collections.ObjectModel.ReadOnlyCollection{Microsoft.Dynamics.Commerce.Runtime.DataModel.ProductAttributeSchemaEntry},System.Collections.ObjectModel.ReadOnlyCollection{Microsoft.Dynamics.Commerce.Runtime.DataModel.ProductProperty},System.Collections.ObjectModel.ReadOnlyCollection{Microsoft.Dynamics.Commerce.Runtime.DataModel.ProductCatalog},System.Collections.ObjectModel.ReadOnlyCollection{Microsoft.Dynamics.Commerce.Runtime.DataModel.ProductCategoryAssociation},System.Tuple{System.Collections.ObjectModel.ReadOnlyCollection{Microsoft.Dynamics.Commerce.Runtime.DataModel.RelatedProduct}}},System.Collections.ObjectModel.ReadOnlyCollection{Microsoft.Dynamics.Commerce.Runtime.DataModel.LinkedProduct},System.Collections.Generic.IList{Microsoft.Dynamics.Commerce.Runtime.DataModel.KitDefinition},System.Collections.ObjectModel.ReadOnlyCollection{Microsoft.Dynamics.Commerce.Runtime.DataModel.KitComponent},System.Collections.ObjectModel.ReadOnlyCollection{Microsoft.Dynamics.Commerce.Runtime.DataModel.KitConfigToComponentAssociation},System.Collections.ObjectModel.ReadOnlyCollection{Microsoft.Dynamics.Commerce.Runtime.DataModel.KitComponent},System.Collections.ObjectModel.ReadOnlyCollection{Microsoft.Dynamics.Commerce.Runtime.DataModel.UnitOfMeasureConversion},System.String,Microsoft.Dynamics.Commerce.Runtime.DataModel.ProductSearchResult)
ms:mtpsurl: https://technet.microsoft.com/library/Dn989953(v=AX.60)
ms:contentKeyID: 65320409
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.Data.ProductBuilder.AssembleProductsFromDataSets
dev_langs:
- CSharp
- C++
- VB
---

# AssembleProductsFromDataSets Method

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.Data](microsoft-dynamics-commerce-runtime-data-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.DataManagers (in Microsoft.Dynamics.Commerce.Runtime.DataManagers.dll)

## Syntax

``` vb
'Declaration
Public Shared Sub AssembleProductsFromDataSets ( _
    context As ProjectionDomain, _
    dataLevel As CommerceEntityDataLevel, _
    dataSets As Tuple(Of ReadOnlyCollection(Of ProductIdentity), ReadOnlyCollection(Of ProductVariant), ReadOnlyCollection(Of ProductRules), ReadOnlyCollection(Of ProductAttributeSchemaEntry), ReadOnlyCollection(Of ProductProperty), ReadOnlyCollection(Of ProductCatalog), ReadOnlyCollection(Of ProductCategoryAssociation), Tuple(Of ReadOnlyCollection(Of RelatedProduct))), _
    linkedProductDataSet As ReadOnlyCollection(Of LinkedProduct), _
    kitDefinitions As IList(Of KitDefinition), _
    componentAndSubstituteList As ReadOnlyCollection(Of KitComponent), _
    configToComponentAssociations As ReadOnlyCollection(Of KitConfigToComponentAssociation), _
    parentKitsComponentInfo As ReadOnlyCollection(Of KitComponent), _
    unitOfMeasureOptionsDataSet As ReadOnlyCollection(Of UnitOfMeasureConversion), _
    defaultLanguageId As String, _
    result As ProductSearchResult _
)
'Usage
Dim context As ProjectionDomain
Dim dataLevel As CommerceEntityDataLevel
Dim dataSets As Tuple(Of ReadOnlyCollection(Of ProductIdentity), ReadOnlyCollection(Of ProductVariant), ReadOnlyCollection(Of ProductRules), ReadOnlyCollection(Of ProductAttributeSchemaEntry), ReadOnlyCollection(Of ProductProperty), ReadOnlyCollection(Of ProductCatalog), ReadOnlyCollection(Of ProductCategoryAssociation), Tuple(Of ReadOnlyCollection(Of RelatedProduct)))
Dim linkedProductDataSet As ReadOnlyCollection(Of LinkedProduct)
Dim kitDefinitions As IList(Of KitDefinition)
Dim componentAndSubstituteList As ReadOnlyCollection(Of KitComponent)
Dim configToComponentAssociations As ReadOnlyCollection(Of KitConfigToComponentAssociation)
Dim parentKitsComponentInfo As ReadOnlyCollection(Of KitComponent)
Dim unitOfMeasureOptionsDataSet As ReadOnlyCollection(Of UnitOfMeasureConversion)
Dim defaultLanguageId As String
Dim result As ProductSearchResult

ProductBuilder.AssembleProductsFromDataSets(context, _
    dataLevel, dataSets, linkedProductDataSet, _
    kitDefinitions, componentAndSubstituteList, _
    configToComponentAssociations, _
    parentKitsComponentInfo, unitOfMeasureOptionsDataSet, _
    defaultLanguageId, result)
```

``` csharp
public static void AssembleProductsFromDataSets(
    ProjectionDomain context,
    CommerceEntityDataLevel dataLevel,
    Tuple<ReadOnlyCollection<ProductIdentity>, ReadOnlyCollection<ProductVariant>, ReadOnlyCollection<ProductRules>, ReadOnlyCollection<ProductAttributeSchemaEntry>, ReadOnlyCollection<ProductProperty>, ReadOnlyCollection<ProductCatalog>, ReadOnlyCollection<ProductCategoryAssociation>, Tuple<ReadOnlyCollection<RelatedProduct>>> dataSets,
    ReadOnlyCollection<LinkedProduct> linkedProductDataSet,
    IList<KitDefinition> kitDefinitions,
    ReadOnlyCollection<KitComponent> componentAndSubstituteList,
    ReadOnlyCollection<KitConfigToComponentAssociation> configToComponentAssociations,
    ReadOnlyCollection<KitComponent> parentKitsComponentInfo,
    ReadOnlyCollection<UnitOfMeasureConversion> unitOfMeasureOptionsDataSet,
    string defaultLanguageId,
    ProductSearchResult result
)
```

``` c++
public:
static void AssembleProductsFromDataSets(
    ProjectionDomain^ context, 
    CommerceEntityDataLevel dataLevel, 
    Tuple<ReadOnlyCollection<ProductIdentity^>^, ReadOnlyCollection<ProductVariant^>^, ReadOnlyCollection<ProductRules^>^, ReadOnlyCollection<ProductAttributeSchemaEntry^>^, ReadOnlyCollection<ProductProperty^>^, ReadOnlyCollection<ProductCatalog^>^, ReadOnlyCollection<ProductCategoryAssociation^>^, Tuple<ReadOnlyCollection<RelatedProduct^>^>^>^ dataSets, 
    ReadOnlyCollection<LinkedProduct^>^ linkedProductDataSet, 
    IList<KitDefinition^>^ kitDefinitions, 
    ReadOnlyCollection<KitComponent^>^ componentAndSubstituteList, 
    ReadOnlyCollection<KitConfigToComponentAssociation^>^ configToComponentAssociations, 
    ReadOnlyCollection<KitComponent^>^ parentKitsComponentInfo, 
    ReadOnlyCollection<UnitOfMeasureConversion^>^ unitOfMeasureOptionsDataSet, 
    String^ defaultLanguageId, 
    ProductSearchResult^ result
)
```

#### Parameters

  - context  
    Type: [Microsoft.Dynamics.Commerce.Runtime.DataModel.ProjectionDomain](projectiondomain-class-microsoft-dynamics-commerce-runtime-datamodel.md)  

<!-- end list -->

  - dataLevel  
    Type: [Microsoft.Dynamics.Commerce.Runtime.DataModel.CommerceEntityDataLevel](commerceentitydatalevel-enumeration-microsoft-dynamics-commerce-runtime-datamodel.md)  

<!-- end list -->

  - dataSets  
    Type: Tuple\<[ReadOnlyCollection](https://technet.microsoft.com/library/ms132474\(v=ax.60\))\<[ProductIdentity](productidentity-class-microsoft-dynamics-commerce-runtime-datamodel.md)\>, [ReadOnlyCollection](https://technet.microsoft.com/library/ms132474\(v=ax.60\))\<[ProductVariant](productvariant-class-microsoft-dynamics-commerce-runtime-datamodel.md)\>, [ReadOnlyCollection](https://technet.microsoft.com/library/ms132474\(v=ax.60\))\<[ProductRules](productrules-class-microsoft-dynamics-commerce-runtime-datamodel.md)\>, [ReadOnlyCollection](https://technet.microsoft.com/library/ms132474\(v=ax.60\))\<[ProductAttributeSchemaEntry](productattributeschemaentry-class-microsoft-dynamics-commerce-runtime-datamodel.md)\>, [ReadOnlyCollection](https://technet.microsoft.com/library/ms132474\(v=ax.60\))\<[ProductProperty](productproperty-class-microsoft-dynamics-commerce-runtime-datamodel.md)\>, [ReadOnlyCollection](https://technet.microsoft.com/library/ms132474\(v=ax.60\))\<[ProductCatalog](productcatalog-class-microsoft-dynamics-commerce-runtime-datamodel.md)\>, [ReadOnlyCollection](https://technet.microsoft.com/library/ms132474\(v=ax.60\))\<[ProductCategoryAssociation](productcategoryassociation-class-microsoft-dynamics-commerce-runtime-datamodel.md)\>, Tuple\<[ReadOnlyCollection](https://technet.microsoft.com/library/ms132474\(v=ax.60\))\<[RelatedProduct](relatedproduct-class-microsoft-dynamics-commerce-runtime-datamodel.md)\>\>\>  

<!-- end list -->

  - linkedProductDataSet  
    Type: [System.Collections.ObjectModel.ReadOnlyCollection](https://technet.microsoft.com/library/ms132474\(v=ax.60\))\<[LinkedProduct](linkedproduct-class-microsoft-dynamics-commerce-runtime-datamodel.md)\>  

<!-- end list -->

  - kitDefinitions  
    Type: [System.Collections.Generic.IList](https://technet.microsoft.com/library/5y536ey6\(v=ax.60\))\<[KitDefinition](kitdefinition-class-microsoft-dynamics-commerce-runtime-datamodel.md)\>  

<!-- end list -->

  - componentAndSubstituteList  
    Type: [System.Collections.ObjectModel.ReadOnlyCollection](https://technet.microsoft.com/library/ms132474\(v=ax.60\))\<[KitComponent](kitcomponent-class-microsoft-dynamics-commerce-runtime-datamodel.md)\>  

<!-- end list -->

  - configToComponentAssociations  
    Type: [System.Collections.ObjectModel.ReadOnlyCollection](https://technet.microsoft.com/library/ms132474\(v=ax.60\))\<[KitConfigToComponentAssociation](kitconfigtocomponentassociation-class-microsoft-dynamics-commerce-runtime-datamodel.md)\>  

<!-- end list -->

  - parentKitsComponentInfo  
    Type: [System.Collections.ObjectModel.ReadOnlyCollection](https://technet.microsoft.com/library/ms132474\(v=ax.60\))\<[KitComponent](kitcomponent-class-microsoft-dynamics-commerce-runtime-datamodel.md)\>  

<!-- end list -->

  - unitOfMeasureOptionsDataSet  
    Type: [System.Collections.ObjectModel.ReadOnlyCollection](https://technet.microsoft.com/library/ms132474\(v=ax.60\))\<[UnitOfMeasureConversion](unitofmeasureconversion-class-microsoft-dynamics-commerce-runtime-datamodel.md)\>  

<!-- end list -->

  - defaultLanguageId  
    Type: [System.String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\))  

<!-- end list -->

  - result  
    Type: [Microsoft.Dynamics.Commerce.Runtime.DataModel.ProductSearchResult](productsearchresult-class-microsoft-dynamics-commerce-runtime-datamodel.md)  

## See Also

#### Reference

[ProductBuilder Class](productbuilder-class-microsoft-dynamics-commerce-runtime-data.md)

[Microsoft.Dynamics.Commerce.Runtime.Data Namespace](microsoft-dynamics-commerce-runtime-data-namespace.md)

