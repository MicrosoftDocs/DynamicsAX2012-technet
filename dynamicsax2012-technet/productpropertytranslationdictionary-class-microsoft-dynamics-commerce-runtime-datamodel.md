---
title: ProductPropertyTranslationDictionary Class (Microsoft.Dynamics.Commerce.Runtime.DataModel)
TOCTitle: ProductPropertyTranslationDictionary Class
ms:assetid: T:Microsoft.Dynamics.Commerce.Runtime.DataModel.ProductPropertyTranslationDictionary
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.datamodel.productpropertytranslationdictionary(v=AX.60)
ms:contentKeyID: 62209445
author: tonyafehr
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataModel.ProductPropertyTranslationDictionary
dev_langs:
- CSharp
- C++
- VB
---

# ProductPropertyTranslationDictionary Class


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Represents the translations of a product's properties, keyed by the languages identifier.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataModel](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Entities (in Microsoft.Dynamics.Commerce.Runtime.Entities.dll)

## Syntax

``` vb
'Declaration
<CollectionDataContractAttribute(Name := "ProductPropertyTranslationDictionary", ItemName := "Entry",  _
    KeyName := "Language", ValueName := "ProductPropertySet")> _
Public NotInheritable Class ProductPropertyTranslationDictionary _
    Inherits Dictionary(Of String, ProductPropertyDictionary)
'Usage
Dim instance As ProductPropertyTranslationDictionary
```

``` csharp
[CollectionDataContractAttribute(Name = "ProductPropertyTranslationDictionary", ItemName = "Entry", 
    KeyName = "Language", ValueName = "ProductPropertySet")]
public sealed class ProductPropertyTranslationDictionary : Dictionary<string, ProductPropertyDictionary>
```

``` c++
[CollectionDataContractAttribute(Name = L"ProductPropertyTranslationDictionary", ItemName = L"Entry", 
    KeyName = L"Language", ValueName = L"ProductPropertySet")]
public ref class ProductPropertyTranslationDictionary sealed : public Dictionary<String^, ProductPropertyDictionary^>
```

## Inheritance Hierarchy

[System.Object](https://technet.microsoft.com/library/e5kfa45b\(v=ax.60\))  
  [System.Collections.Generic.Dictionary](https://technet.microsoft.com/library/xfhwa508\(v=ax.60\))\<[String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\)), [ProductPropertyDictionary](productpropertydictionary-class-microsoft-dynamics-commerce-runtime-datamodel.md)\>  
    Microsoft.Dynamics.Commerce.Runtime.DataModel.ProductPropertyTranslationDictionary  

## Thread Safety

Any public static (Shared in Visual Basic) members of this type are thread safe. Any instance members are not guaranteed to be thread safe.

## See Also

#### Reference

[Microsoft.Dynamics.Commerce.Runtime.DataModel Namespace](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)

