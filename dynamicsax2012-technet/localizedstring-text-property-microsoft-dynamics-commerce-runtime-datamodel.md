---
title: LocalizedString.Text Property  (Microsoft.Dynamics.Commerce.Runtime.DataModel)
TOCTitle: Text Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.DataModel.LocalizedString.Text
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.datamodel.localizedstring.text(v=AX.60)
ms:contentKeyID: 62208465
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataModel.LocalizedString.Text
dev_langs:
- CSharp
- C++
- VB
---

# Text Property


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Gets or sets the text value.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataModel](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Entities (in Microsoft.Dynamics.Commerce.Runtime.Entities.dll)

## Syntax

``` vb
'Declaration
<ColumnAttribute("TEXT")> _
<DataMemberAttribute> _
Public Property Text As String
    Get
    Set
'Usage
Dim instance As LocalizedString
Dim value As String

value = instance.Text

instance.Text = value
```

``` csharp
[ColumnAttribute("TEXT")]
[DataMemberAttribute]
public string Text { get; set; }
```

``` c++
[ColumnAttribute(L"TEXT")]
[DataMemberAttribute]
public:
property String^ Text {
    String^ get ();
    void set (String^ value);
}
```

#### Property Value

Type: [System.String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\))  
Returns [String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\)).  

## See Also

#### Reference

[LocalizedString Class](localizedstring-class-microsoft-dynamics-commerce-runtime-datamodel.md)

[Microsoft.Dynamics.Commerce.Runtime.DataModel Namespace](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)

