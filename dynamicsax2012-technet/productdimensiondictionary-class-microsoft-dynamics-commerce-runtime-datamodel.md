---
title: ProductDimensionDictionary Class (Microsoft.Dynamics.Commerce.Runtime.DataModel)
TOCTitle: ProductDimensionDictionary Class
ms:assetid: T:Microsoft.Dynamics.Commerce.Runtime.DataModel.ProductDimensionDictionary
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.datamodel.productdimensiondictionary(v=AX.60)
ms:contentKeyID: 62202106
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataModel.ProductDimensionDictionary
dev_langs:
- CSharp
- C++
- VB
---

# ProductDimensionDictionary Class

Represents the dimensions of a product, keyed by their unique property names.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataModel](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Entities (in Microsoft.Dynamics.Commerce.Runtime.Entities.dll)

## Syntax

``` vb
'Declaration
<CollectionDataContractAttribute(Name := "ProductDimensionDictionary", ItemName := "Entry",  _
    KeyName := "KeyName", ValueName := "ProductDimensionValueDictionary")> _
Public NotInheritable Class ProductDimensionDictionary _
    Inherits Dictionary(Of String, ProductDimensionValueDictionary)
'Usage
Dim instance As ProductDimensionDictionary
```

``` csharp
[CollectionDataContractAttribute(Name = "ProductDimensionDictionary", ItemName = "Entry", 
    KeyName = "KeyName", ValueName = "ProductDimensionValueDictionary")]
public sealed class ProductDimensionDictionary : Dictionary<string, ProductDimensionValueDictionary>
```

``` c++
[CollectionDataContractAttribute(Name = L"ProductDimensionDictionary", ItemName = L"Entry", 
    KeyName = L"KeyName", ValueName = L"ProductDimensionValueDictionary")]
public ref class ProductDimensionDictionary sealed : public Dictionary<String^, ProductDimensionValueDictionary^>
```

## Inheritance Hierarchy

[System.Object](https://technet.microsoft.com/library/e5kfa45b\(v=ax.60\))  
  [System.Collections.Generic.Dictionary](https://technet.microsoft.com/library/xfhwa508\(v=ax.60\))\<[String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\)), [ProductDimensionValueDictionary](productdimensionvaluedictionary-class-microsoft-dynamics-commerce-runtime-datamodel.md)\>  
    Microsoft.Dynamics.Commerce.Runtime.DataModel.ProductDimensionDictionary  

## Thread Safety

Any public static (Shared in Visual Basic) members of this type are thread safe. Any instance members are not guaranteed to be thread safe.

## See Also

#### Reference

[Microsoft.Dynamics.Commerce.Runtime.DataModel Namespace](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)

