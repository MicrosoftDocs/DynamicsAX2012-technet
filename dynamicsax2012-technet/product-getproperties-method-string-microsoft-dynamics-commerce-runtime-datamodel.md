---
title: Product.GetProperties Method (String) (Microsoft.Dynamics.Commerce.Runtime.DataModel)
TOCTitle: GetProperties Method (String)
ms:assetid: M:Microsoft.Dynamics.Commerce.Runtime.DataModel.Product.GetProperties(System.String)
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.datamodel.product.getproperties(v=AX.60)
ms:contentKeyID: 62207946
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
dev_langs:
- vb
- csharp
- c++
---

# GetProperties Method (String)


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Enumerates the product's attributes, together with their translations for the specified language.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataModel](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Entities (in Microsoft.Dynamics.Commerce.Runtime.Entities.dll)

## Syntax

``` vb
'Declaration
Public Function GetProperties ( _
    languageKey As String _
) As ReadOnlyCollection(Of ProductProperty)
'Usage
Dim instance As Product
Dim languageKey As String
Dim returnValue As ReadOnlyCollection(Of ProductProperty)

returnValue = instance.GetProperties(languageKey)
```

``` csharp
public ReadOnlyCollection<ProductProperty> GetProperties(
    string languageKey
)
```

``` c++
public:
ReadOnlyCollection<ProductProperty^>^ GetProperties(
    String^ languageKey
)
```

#### Parameters

  - languageKey  
    Type: [System.String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\))  

#### Return Value

Type: [System.Collections.ObjectModel.ReadOnlyCollection](https://technet.microsoft.com/library/ms132474\(v=ax.60\))\<[ProductProperty](productproperty-class-microsoft-dynamics-commerce-runtime-datamodel.md)\>  
A list of product properties.  

## Remarks

Please see the remarks of the EnumerateProperties(long, string) function below for more details.

## See Also

#### Reference

[Product Class](product-class-microsoft-dynamics-commerce-runtime-datamodel.md)

[GetProperties Overload](product-getproperties-method-microsoft-dynamics-commerce-runtime-datamodel.md)

[Microsoft.Dynamics.Commerce.Runtime.DataModel Namespace](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)

