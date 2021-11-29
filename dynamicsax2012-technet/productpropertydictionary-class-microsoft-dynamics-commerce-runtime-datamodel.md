---
title: ProductPropertyDictionary Class (Microsoft.Dynamics.Commerce.Runtime.DataModel)
TOCTitle: ProductPropertyDictionary Class
ms:assetid: T:Microsoft.Dynamics.Commerce.Runtime.DataModel.ProductPropertyDictionary
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.datamodel.productpropertydictionary(v=AX.60)
ms:contentKeyID: 62208267
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataModel.ProductPropertyDictionary
dev_langs:
- CSharp
- C++
- VB
---

# ProductPropertyDictionary Class


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Represents the properties of a product, keyed by their unique property names.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataModel](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Entities (in Microsoft.Dynamics.Commerce.Runtime.Entities.dll)

## Syntax

``` vb
'Declaration
<CollectionDataContractAttribute(Name := "ProductPropertyDictionary", ItemName := "Entry",  _
    KeyName := "PropertyName", ValueName := "ProductProperty")> _
Public NotInheritable Class ProductPropertyDictionary _
    Inherits Dictionary(Of String, ProductProperty)
'Usage
Dim instance As ProductPropertyDictionary
```

``` csharp
[CollectionDataContractAttribute(Name = "ProductPropertyDictionary", ItemName = "Entry", 
    KeyName = "PropertyName", ValueName = "ProductProperty")]
public sealed class ProductPropertyDictionary : Dictionary<string, ProductProperty>
```

``` c++
[CollectionDataContractAttribute(Name = L"ProductPropertyDictionary", ItemName = L"Entry", 
    KeyName = L"PropertyName", ValueName = L"ProductProperty")]
public ref class ProductPropertyDictionary sealed : public Dictionary<String^, ProductProperty^>
```

## Inheritance Hierarchy

[System.Object](https://technet.microsoft.com/library/e5kfa45b\(v=ax.60\))  
  [System.Collections.Generic.Dictionary](https://technet.microsoft.com/library/xfhwa508\(v=ax.60\))\<[String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\)), [ProductProperty](productproperty-class-microsoft-dynamics-commerce-runtime-datamodel.md)\>  
    Microsoft.Dynamics.Commerce.Runtime.DataModel.ProductPropertyDictionary  

## Thread Safety

Any public static (Shared in Visual Basic) members of this type are thread safe. Any instance members are not guaranteed to be thread safe.

## See Also

#### Reference

[Microsoft.Dynamics.Commerce.Runtime.DataModel Namespace](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)

