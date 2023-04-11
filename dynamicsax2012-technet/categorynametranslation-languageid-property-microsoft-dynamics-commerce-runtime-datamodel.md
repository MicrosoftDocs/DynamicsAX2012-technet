---
title: CategoryNameTranslation.LanguageId Property  (Microsoft.Dynamics.Commerce.Runtime.DataModel)
TOCTitle: LanguageId Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.DataModel.CategoryNameTranslation.LanguageId
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.datamodel.categorynametranslation.languageid(v=AX.60)
ms:contentKeyID: 49834301
author: tonyafehr
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataModel.CategoryNameTranslation.LanguageId
dev_langs:
- CSharp
- C++
- VB
---

# LanguageId Property


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Gets the language identifier for this translation.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataModel](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Entities (in Microsoft.Dynamics.Commerce.Runtime.Entities.dll)

## Syntax

``` vb
'Declaration
<ColumnAttribute("LANGUAGEID")> _
<DataMemberAttribute> _
Public Property LanguageId As String
    Get
    Friend Set
'Usage
Dim instance As CategoryNameTranslation
Dim value As String

value = instance.LanguageId
```

``` csharp
[ColumnAttribute("LANGUAGEID")]
[DataMemberAttribute]
public string LanguageId { get; internal set; }
```

``` c++
[ColumnAttribute(L"LANGUAGEID")]
[DataMemberAttribute]
public:
property String^ LanguageId {
    String^ get ();
    internal: void set (String^ value);
}
```

#### Property Value

Type: [System.String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\))  
Returns [String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\)).  

## See Also

#### Reference

[CategoryNameTranslation Class](categorynametranslation-class-microsoft-dynamics-commerce-runtime-datamodel.md)

[Microsoft.Dynamics.Commerce.Runtime.DataModel Namespace](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)

