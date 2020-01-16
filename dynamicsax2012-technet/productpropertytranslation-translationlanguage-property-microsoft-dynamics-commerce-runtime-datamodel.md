---
title: ProductPropertyTranslation.TranslationLanguage Property  (Microsoft.Dynamics.Commerce.Runtime.DataModel)
TOCTitle: TranslationLanguage Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.DataModel.ProductPropertyTranslation.TranslationLanguage
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.datamodel.productpropertytranslation.translationlanguage(v=AX.60)
ms:contentKeyID: 62212165
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataModel.ProductPropertyTranslation.TranslationLanguage
dev_langs:
- CSharp
- C++
- VB
---

# TranslationLanguage Property

Gets or sets the translation language.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataModel](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Entities (in Microsoft.Dynamics.Commerce.Runtime.Entities.dll)

## Syntax

``` vb
'Declaration
<DataMemberAttribute> _
Public Property TranslationLanguage As String
    Get
    Set
'Usage
Dim instance As ProductPropertyTranslation
Dim value As String

value = instance.TranslationLanguage

instance.TranslationLanguage = value
```

``` csharp
[DataMemberAttribute]
public string TranslationLanguage { get; set; }
```

``` c++
[DataMemberAttribute]
public:
property String^ TranslationLanguage {
    String^ get ();
    void set (String^ value);
}
```

#### Property Value

Type: [System.String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\))  
Returns [String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\)).  

## See Also

#### Reference

[ProductPropertyTranslation Class](productpropertytranslation-class-microsoft-dynamics-commerce-runtime-datamodel.md)

[Microsoft.Dynamics.Commerce.Runtime.DataModel Namespace](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)

