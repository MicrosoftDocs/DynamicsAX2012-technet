---
title: AttributeNameTranslation.Language Property  (Microsoft.Dynamics.Commerce.Runtime.DataModel)
TOCTitle: Language Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.DataModel.AttributeNameTranslation.Language
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.datamodel.attributenametranslation.language(v=AX.60)
ms:contentKeyID: 49829706
author: tfehr
ms.author: daxcpft
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataModel.AttributeNameTranslation.Language
dev_langs:
- CSharp
- C++
- VB
---

# Language Property


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Gets or sets the translation language (e.g. en-US).

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataModel](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Entities (in Microsoft.Dynamics.Commerce.Runtime.Entities.dll)

## Syntax

``` vb
'Declaration
<ColumnAttribute("LANGUAGE")> _
<DataMemberAttribute> _
Public Property Language As String
    Get
    Set
'Usage
Dim instance As AttributeNameTranslation
Dim value As String

value = instance.Language

instance.Language = value
```

``` csharp
[ColumnAttribute("LANGUAGE")]
[DataMemberAttribute]
public string Language { get; set; }
```

``` c++
[ColumnAttribute(L"LANGUAGE")]
[DataMemberAttribute]
public:
property String^ Language {
    String^ get ();
    void set (String^ value);
}
```

#### Property Value

Type: [System.String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\))  
The language.  

## See Also

#### Reference

[AttributeNameTranslation Class](attributenametranslation-class-microsoft-dynamics-commerce-runtime-datamodel.md)

[Microsoft.Dynamics.Commerce.Runtime.DataModel Namespace](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)

