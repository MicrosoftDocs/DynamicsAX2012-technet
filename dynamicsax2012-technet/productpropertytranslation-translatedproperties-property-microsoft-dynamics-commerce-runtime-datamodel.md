---
title: ProductPropertyTranslation.TranslatedProperties Property  (Microsoft.Dynamics.Commerce.Runtime.DataModel)
TOCTitle: TranslatedProperties Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.DataModel.ProductPropertyTranslation.TranslatedProperties
ms:mtpsurl: https://technet.microsoft.com/en-us/library/microsoft.dynamics.commerce.runtime.datamodel.productpropertytranslation.translatedproperties(v=AX.60)
ms:contentKeyID: 62214667
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataModel.ProductPropertyTranslation.TranslatedProperties
dev_langs:
- CSharp
- C++
- VB
---

# TranslatedProperties Property

Gets the translated properties.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataModel](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Entities (in Microsoft.Dynamics.Commerce.Runtime.Entities.dll)

## Syntax

``` vb
'Declaration
<DataMemberAttribute> _
Public ReadOnly Property TranslatedProperties As ICollection(Of ProductProperty)
    Get
'Usage
Dim instance As ProductPropertyTranslation
Dim value As ICollection(Of ProductProperty)

value = instance.TranslatedProperties
```

``` csharp
[DataMemberAttribute]
public ICollection<ProductProperty> TranslatedProperties { get; }
```

``` c++
[DataMemberAttribute]
public:
property ICollection<ProductProperty^>^ TranslatedProperties {
    ICollection<ProductProperty^>^ get ();
}
```

#### Property Value

Type: [System.Collections.Generic.ICollection](https://technet.microsoft.com/en-us/library/92t2ye13\(v=ax.60\))\<[ProductProperty](productproperty-class-microsoft-dynamics-commerce-runtime-datamodel.md)\>  
Returns [ICollection\<T\>](https://technet.microsoft.com/en-us/library/92t2ye13\(v=ax.60\)).  

## See Also

#### Reference

[ProductPropertyTranslation Class](productpropertytranslation-class-microsoft-dynamics-commerce-runtime-datamodel.md)

[Microsoft.Dynamics.Commerce.Runtime.DataModel Namespace](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)

