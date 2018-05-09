---
title: Product.IndexedProductProperties Property  (Microsoft.Dynamics.Commerce.Runtime.DataModel)
TOCTitle: IndexedProductProperties Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.DataModel.Product.IndexedProductProperties
ms:mtpsurl: https://technet.microsoft.com/en-us/library/microsoft.dynamics.commerce.runtime.datamodel.product.indexedproductproperties(v=AX.60)
ms:contentKeyID: 62208108
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataModel.Product.IndexedProductProperties
dev_langs:
- CSharp
- C++
- VB
---

# IndexedProductProperties Property

Gets the properties associated with this product.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataModel](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Entities (in Microsoft.Dynamics.Commerce.Runtime.Entities.dll)

## Syntax

``` vb
'Declaration
<IgnoreDataMemberAttribute> _
Public Property IndexedProductProperties As ProductPropertyTranslationDictionary
    Get
    Friend Set
'Usage
Dim instance As Product
Dim value As ProductPropertyTranslationDictionary

value = instance.IndexedProductProperties
```

``` csharp
[IgnoreDataMemberAttribute]
public ProductPropertyTranslationDictionary IndexedProductProperties { get; internal set; }
```

``` c++
[IgnoreDataMemberAttribute]
public:
property ProductPropertyTranslationDictionary^ IndexedProductProperties {
    ProductPropertyTranslationDictionary^ get ();
    internal: void set (ProductPropertyTranslationDictionary^ value);
}
```

#### Property Value

Type: [Microsoft.Dynamics.Commerce.Runtime.DataModel.ProductPropertyTranslationDictionary](productpropertytranslationdictionary-class-microsoft-dynamics-commerce-runtime-datamodel.md)  
Returns [ProductPropertyTranslationDictionary](productpropertytranslationdictionary-class-microsoft-dynamics-commerce-runtime-datamodel.md).  

## See Also

#### Reference

[Product Class](product-class-microsoft-dynamics-commerce-runtime-datamodel.md)

[Microsoft.Dynamics.Commerce.Runtime.DataModel Namespace](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)

