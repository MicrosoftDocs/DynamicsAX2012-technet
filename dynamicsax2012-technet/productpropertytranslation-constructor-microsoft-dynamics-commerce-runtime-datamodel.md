---
title: ProductPropertyTranslation Constructor  (Microsoft.Dynamics.Commerce.Runtime.DataModel)
TOCTitle: ProductPropertyTranslation Constructor
ms:assetid: M:Microsoft.Dynamics.Commerce.Runtime.DataModel.ProductPropertyTranslation.#ctor(System.String,Microsoft.Dynamics.Commerce.Runtime.DataModel.ProductPropertyDictionary)
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.datamodel.productpropertytranslation.productpropertytranslation(v=AX.60)
ms:contentKeyID: 62211526
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataModel.ProductPropertyTranslation.#ctor
dev_langs:
- CSharp
- C++
- VB
---

# ProductPropertyTranslation Constructor


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Initializes a new instance of the [ProductPropertyTranslation](productpropertytranslation-class-microsoft-dynamics-commerce-runtime-datamodel.md) class.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataModel](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Entities (in Microsoft.Dynamics.Commerce.Runtime.Entities.dll)

## Syntax

``` vb
'Declaration
Public Sub New ( _
    languageKey As String, _
    properties As ProductPropertyDictionary _
)
'Usage
Dim languageKey As String
Dim properties As ProductPropertyDictionary

Dim instance As New ProductPropertyTranslation(languageKey, _
    properties)
```

``` csharp
public ProductPropertyTranslation(
    string languageKey,
    ProductPropertyDictionary properties
)
```

``` c++
public:
ProductPropertyTranslation(
    String^ languageKey, 
    ProductPropertyDictionary^ properties
)
```

#### Parameters

  - languageKey  
    Type: [System.String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\))  

<!-- end list -->

  - properties  
    Type: [Microsoft.Dynamics.Commerce.Runtime.DataModel.ProductPropertyDictionary](productpropertydictionary-class-microsoft-dynamics-commerce-runtime-datamodel.md)  

## See Also

#### Reference

[ProductPropertyTranslation Class](productpropertytranslation-class-microsoft-dynamics-commerce-runtime-datamodel.md)

[Microsoft.Dynamics.Commerce.Runtime.DataModel Namespace](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)

