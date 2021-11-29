---
title: Product.GetIndexedProperties Method (String) (Microsoft.Dynamics.Commerce.Runtime.DataModel)
TOCTitle: GetIndexedProperties Method (String)
ms:assetid: M:Microsoft.Dynamics.Commerce.Runtime.DataModel.Product.GetIndexedProperties(System.String)
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.datamodel.product.getindexedproperties(v=AX.60)
ms:contentKeyID: 62206880
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
dev_langs:
- vb
- csharp
- c++
---

# GetIndexedProperties Method (String)


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Enumerates the product's attributes, together with their translations for the specified language.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataModel](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Entities (in Microsoft.Dynamics.Commerce.Runtime.Entities.dll)

## Syntax

``` vb
'Declaration
Public Function GetIndexedProperties ( _
    languageKey As String _
) As ProductPropertyDictionary
'Usage
Dim instance As Product
Dim languageKey As String
Dim returnValue As ProductPropertyDictionary

returnValue = instance.GetIndexedProperties(languageKey)
```

``` csharp
public ProductPropertyDictionary GetIndexedProperties(
    string languageKey
)
```

``` c++
public:
ProductPropertyDictionary^ GetIndexedProperties(
    String^ languageKey
)
```

#### Parameters

  - languageKey  
    Type: [System.String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\))  

#### Return Value

Type: [Microsoft.Dynamics.Commerce.Runtime.DataModel.ProductPropertyDictionary](productpropertydictionary-class-microsoft-dynamics-commerce-runtime-datamodel.md)  
A collection of product properties, indexed on the property key name.  

## Remarks

Please see the remarks of the EnumerateProperties(long, string) function below for more details.

## See Also

#### Reference

[Product Class](product-class-microsoft-dynamics-commerce-runtime-datamodel.md)

[GetIndexedProperties Overload](product-getindexedproperties-method-microsoft-dynamics-commerce-runtime-datamodel.md)

[Microsoft.Dynamics.Commerce.Runtime.DataModel Namespace](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)

