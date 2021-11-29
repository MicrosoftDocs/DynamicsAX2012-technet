---
title: ProductVariant.IndexedProperties Property  (Microsoft.Dynamics.Commerce.Runtime.DataModel)
TOCTitle: IndexedProperties Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.DataModel.ProductVariant.IndexedProperties
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.datamodel.productvariant.indexedproperties(v=AX.60)
ms:contentKeyID: 62208315
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataModel.ProductVariant.IndexedProperties
dev_langs:
- CSharp
- C++
- VB
---

# IndexedProperties Property


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Gets the properties of a variant indexed by the translation language id.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataModel](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Entities (in Microsoft.Dynamics.Commerce.Runtime.Entities.dll)

## Syntax

``` vb
'Declaration
<IgnoreDataMemberAttribute> _
Public Property IndexedProperties As ProductPropertyTranslationDictionary
    Get
    Set
'Usage
Dim instance As ProductVariant
Dim value As ProductPropertyTranslationDictionary

value = instance.IndexedProperties

instance.IndexedProperties = value
```

``` csharp
[IgnoreDataMemberAttribute]
public ProductPropertyTranslationDictionary IndexedProperties { get; set; }
```

``` c++
[IgnoreDataMemberAttribute]
public:
property ProductPropertyTranslationDictionary^ IndexedProperties {
    ProductPropertyTranslationDictionary^ get ();
    void set (ProductPropertyTranslationDictionary^ value);
}
```

#### Property Value

Type: [Microsoft.Dynamics.Commerce.Runtime.DataModel.ProductPropertyTranslationDictionary](productpropertytranslationdictionary-class-microsoft-dynamics-commerce-runtime-datamodel.md)  
Returns [ProductPropertyTranslationDictionary](productpropertytranslationdictionary-class-microsoft-dynamics-commerce-runtime-datamodel.md).  

## See Also

#### Reference

[ProductVariant Class](productvariant-class-microsoft-dynamics-commerce-runtime-datamodel.md)

[Microsoft.Dynamics.Commerce.Runtime.DataModel Namespace](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)

