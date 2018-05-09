---
title: TextValueTranslation.Language Property  (Microsoft.Dynamics.Commerce.Runtime.DataModel)
TOCTitle: Language Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.DataModel.TextValueTranslation.Language
ms:mtpsurl: https://technet.microsoft.com/en-us/library/microsoft.dynamics.commerce.runtime.datamodel.textvaluetranslation.language(v=AX.60)
ms:contentKeyID: 49821749
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataModel.TextValueTranslation.Language
dev_langs:
- CSharp
- C++
- VB
---

# Language Property

Gets or sets the language to which the translation applies.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataModel](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Entities (in Microsoft.Dynamics.Commerce.Runtime.Entities.dll)

## Syntax

``` vb
'Declaration
<DataMemberAttribute> _
<ColumnAttribute("LANGUAGE")> _
Public Property Language As String
    Get
    Set
'Usage
Dim instance As TextValueTranslation
Dim value As String

value = instance.Language

instance.Language = value
```

``` csharp
[DataMemberAttribute]
[ColumnAttribute("LANGUAGE")]
public string Language { get; set; }
```

``` c++
[DataMemberAttribute]
[ColumnAttribute(L"LANGUAGE")]
public:
property String^ Language {
    String^ get ();
    void set (String^ value);
}
```

#### Property Value

Type: [System.String](https://technet.microsoft.com/en-us/library/s1wwdcbf\(v=ax.60\))  
The language Id e.g. en-us.  

## See Also

#### Reference

[TextValueTranslation Class](textvaluetranslation-class-microsoft-dynamics-commerce-runtime-datamodel.md)

[Microsoft.Dynamics.Commerce.Runtime.DataModel Namespace](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)

