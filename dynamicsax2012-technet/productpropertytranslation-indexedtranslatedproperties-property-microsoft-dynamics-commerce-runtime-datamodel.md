---
title: ProductPropertyTranslation.IndexedTranslatedProperties Property  (Microsoft.Dynamics.Commerce.Runtime.DataModel)
TOCTitle: IndexedTranslatedProperties Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.DataModel.ProductPropertyTranslation.IndexedTranslatedProperties
ms:mtpsurl: https://technet.microsoft.com/en-us/library/microsoft.dynamics.commerce.runtime.datamodel.productpropertytranslation.indexedtranslatedproperties(v=AX.60)
ms:contentKeyID: 62213081
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataModel.ProductPropertyTranslation.IndexedTranslatedProperties
dev_langs:
- CSharp
- C++
- VB
---

# IndexedTranslatedProperties Property

Gets the translated properties.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataModel](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Entities (in Microsoft.Dynamics.Commerce.Runtime.Entities.dll)

## Syntax

``` vb
'Declaration
<IgnoreDataMemberAttribute> _
Public Property IndexedTranslatedProperties As ProductPropertyDictionary
    Get
    Set
'Usage
Dim instance As ProductPropertyTranslation
Dim value As ProductPropertyDictionary

value = instance.IndexedTranslatedProperties

instance.IndexedTranslatedProperties = value
```

``` csharp
[IgnoreDataMemberAttribute]
public ProductPropertyDictionary IndexedTranslatedProperties { get; set; }
```

``` c++
[IgnoreDataMemberAttribute]
public:
property ProductPropertyDictionary^ IndexedTranslatedProperties {
    ProductPropertyDictionary^ get ();
    void set (ProductPropertyDictionary^ value);
}
```

#### Property Value

Type: [Microsoft.Dynamics.Commerce.Runtime.DataModel.ProductPropertyDictionary](productpropertydictionary-class-microsoft-dynamics-commerce-runtime-datamodel.md)  
Returns [ProductPropertyDictionary](productpropertydictionary-class-microsoft-dynamics-commerce-runtime-datamodel.md).  

## See Also

#### Reference

[ProductPropertyTranslation Class](productpropertytranslation-class-microsoft-dynamics-commerce-runtime-datamodel.md)

[Microsoft.Dynamics.Commerce.Runtime.DataModel Namespace](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)

