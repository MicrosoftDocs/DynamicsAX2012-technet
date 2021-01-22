---
title: CatalogSearchCriteria.Language Property  (Microsoft.Dynamics.Commerce.Runtime.DataModel)
TOCTitle: Language Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.DataModel.CatalogSearchCriteria.Language
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.datamodel.catalogsearchcriteria.language(v=AX.60)
ms:contentKeyID: 62207255
author: Khairunj
ms.author: daxcpft
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataModel.CatalogSearchCriteria.Language
dev_langs:
- CSharp
- C++
- VB
---

# Language Property

Gets or sets the language key for the product search.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataModel](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Entities (in Microsoft.Dynamics.Commerce.Runtime.Entities.dll)

## Syntax

``` vb
'Declaration
<DataMemberAttribute> _
Public Property Language As String
    Get
    Set
'Usage
Dim instance As CatalogSearchCriteria
Dim value As String

value = instance.Language

instance.Language = value
```

``` csharp
[DataMemberAttribute]
public string Language { get; set; }
```

``` c++
[DataMemberAttribute]
public:
property String^ Language {
    String^ get ();
    void set (String^ value);
}
```

#### Property Value

Type: [System.String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\))  
Returns [String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\)).  

## Remarks

Observations: - This criteria will be ignored for searches with a specified data level less than Standard.

\- If set, the query will return only translations for this language.

\- If invalid/unknown, the query will return the default language translations.

\- If not set, the query will return all existing translations.

## See Also

#### Reference

[CatalogSearchCriteria Class](catalogsearchcriteria-class-microsoft-dynamics-commerce-runtime-datamodel.md)

[Microsoft.Dynamics.Commerce.Runtime.DataModel Namespace](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)

