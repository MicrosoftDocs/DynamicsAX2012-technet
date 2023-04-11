---
title: TextValueTranslation.Text Property  (Microsoft.Dynamics.Commerce.Runtime.DataModel)
TOCTitle: Text Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.DataModel.TextValueTranslation.Text
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.datamodel.textvaluetranslation.text(v=AX.60)
ms:contentKeyID: 49823988
author: tonyafehr
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataModel.TextValueTranslation.Text
dev_langs:
- CSharp
- C++
- VB
---

# Text Property


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Gets or sets translated text.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataModel](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Entities (in Microsoft.Dynamics.Commerce.Runtime.Entities.dll)

## Syntax

``` vb
'Declaration
<DataMemberAttribute> _
<ColumnAttribute("TEXTVALUE")> _
Public Property Text As String
    Get
    Set
'Usage
Dim instance As TextValueTranslation
Dim value As String

value = instance.Text

instance.Text = value
```

``` csharp
[DataMemberAttribute]
[ColumnAttribute("TEXTVALUE")]
public string Text { get; set; }
```

``` c++
[DataMemberAttribute]
[ColumnAttribute(L"TEXTVALUE")]
public:
property String^ Text {
    String^ get ();
    void set (String^ value);
}
```

#### Property Value

Type: [System.String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\))  
The translated text.  

## See Also

#### Reference

[TextValueTranslation Class](textvaluetranslation-class-microsoft-dynamics-commerce-runtime-datamodel.md)

[Microsoft.Dynamics.Commerce.Runtime.DataModel Namespace](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)

