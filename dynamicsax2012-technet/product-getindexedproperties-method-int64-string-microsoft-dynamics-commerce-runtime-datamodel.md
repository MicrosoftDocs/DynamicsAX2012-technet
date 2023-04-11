---
title: Product.GetIndexedProperties Method (Int64, String) (Microsoft.Dynamics.Commerce.Runtime.DataModel)
TOCTitle: GetIndexedProperties Method (Int64, String)
ms:assetid: M:Microsoft.Dynamics.Commerce.Runtime.DataModel.Product.GetIndexedProperties(System.Int64,System.String)
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.datamodel.product.getindexedproperties(v=AX.60)
ms:contentKeyID: 62209357
author: tonyafehr
ms.date: 05/18/2015
mtps_version: v=AX.60
dev_langs:
- vb
- csharp
- c++
---

# GetIndexedProperties Method (Int64, String)


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Enumerates a product's properties for the specified variant id and language key.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataModel](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Entities (in Microsoft.Dynamics.Commerce.Runtime.Entities.dll)

## Syntax

``` vb
'Declaration
Public Function GetIndexedProperties ( _
    variantId As Long, _
    languageKey As String _
) As ProductPropertyDictionary
'Usage
Dim instance As Product
Dim variantId As Long
Dim languageKey As String
Dim returnValue As ProductPropertyDictionary

returnValue = instance.GetIndexedProperties(variantId, _
    languageKey)
```

``` csharp
public ProductPropertyDictionary GetIndexedProperties(
    long variantId,
    string languageKey
)
```

``` c++
public:
ProductPropertyDictionary^ GetIndexedProperties(
    long long variantId, 
    String^ languageKey
)
```

#### Parameters

  - variantId  
    Type: [System.Int64](https://technet.microsoft.com/library/6yy583ek\(v=ax.60\))  

<!-- end list -->

  - languageKey  
    Type: [System.String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\))  

#### Return Value

Type: [Microsoft.Dynamics.Commerce.Runtime.DataModel.ProductPropertyDictionary](productpropertydictionary-class-microsoft-dynamics-commerce-runtime-datamodel.md)  
A list of product properties.  

## Remarks

For the master product, all the product's attributes are returned. For variants, the function will return the variant's override of a master attribute, or the master's attribute where an override does not exist.

Similarly, if the language key matches the default channel language, all of the product's attributes will be returned from the default language "translation". Otherwise, the matching translation will be returned, where one exists, and the default translation for attributes which aren't translated in the specified language.

Essentially, the function will always return the same attribute schema, regardless of the values of the input parameters.

Note it is illegal to have non-default language translations for attributes which don't have a default language value, and also for variants to have an attribute which the master does not. Dimensions are not considered as regular attributes.

## See Also

#### Reference

[Product Class](product-class-microsoft-dynamics-commerce-runtime-datamodel.md)

[GetIndexedProperties Overload](product-getindexedproperties-method-microsoft-dynamics-commerce-runtime-datamodel.md)

[Microsoft.Dynamics.Commerce.Runtime.DataModel Namespace](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)

