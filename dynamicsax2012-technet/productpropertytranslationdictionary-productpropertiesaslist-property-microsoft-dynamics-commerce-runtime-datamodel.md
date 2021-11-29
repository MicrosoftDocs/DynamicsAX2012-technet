---
title: ProductPropertyTranslationDictionary.ProductPropertiesAsList Property  (Microsoft.Dynamics.Commerce.Runtime.DataModel)
TOCTitle: ProductPropertiesAsList Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.DataModel.ProductPropertyTranslationDictionary.ProductPropertiesAsList
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.datamodel.productpropertytranslationdictionary.productpropertiesaslist(v=AX.60)
ms:contentKeyID: 62210039
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataModel.ProductPropertyTranslationDictionary.ProductPropertiesAsList
dev_langs:
- CSharp
- C++
- VB
---

# ProductPropertiesAsList Property


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Gets the product properties as a flat list of properties, qualified by their respective translation languages.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataModel](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Entities (in Microsoft.Dynamics.Commerce.Runtime.Entities.dll)

## Syntax

``` vb
'Declaration
Public ReadOnly Property ProductPropertiesAsList As ICollection(Of ProductPropertyTranslation)
    Get
'Usage
Dim instance As ProductPropertyTranslationDictionary
Dim value As ICollection(Of ProductPropertyTranslation)

value = instance.ProductPropertiesAsList
```

``` csharp
public ICollection<ProductPropertyTranslation> ProductPropertiesAsList { get; }
```

``` c++
public:
property ICollection<ProductPropertyTranslation^>^ ProductPropertiesAsList {
    ICollection<ProductPropertyTranslation^>^ get ();
}
```

#### Property Value

Type: [System.Collections.Generic.ICollection](https://technet.microsoft.com/library/92t2ye13\(v=ax.60\))\<[ProductPropertyTranslation](productpropertytranslation-class-microsoft-dynamics-commerce-runtime-datamodel.md)\>  
Returns [ICollection\<T\>](https://technet.microsoft.com/library/92t2ye13\(v=ax.60\)).  

## See Also

#### Reference

[ProductPropertyTranslationDictionary Class](productpropertytranslationdictionary-class-microsoft-dynamics-commerce-runtime-datamodel.md)

[Microsoft.Dynamics.Commerce.Runtime.DataModel Namespace](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)

