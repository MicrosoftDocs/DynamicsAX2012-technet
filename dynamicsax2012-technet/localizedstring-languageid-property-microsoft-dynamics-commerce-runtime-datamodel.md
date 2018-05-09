---
title: LocalizedString.LanguageId Property  (Microsoft.Dynamics.Commerce.Runtime.DataModel)
TOCTitle: LanguageId Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.DataModel.LocalizedString.LanguageId
ms:mtpsurl: https://technet.microsoft.com/en-us/library/microsoft.dynamics.commerce.runtime.datamodel.localizedstring.languageid(v=AX.60)
ms:contentKeyID: 62211070
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataModel.LocalizedString.LanguageId
dev_langs:
- CSharp
- C++
- VB
---

# LanguageId Property

Gets or sets the language/culture identifier.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataModel](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Entities (in Microsoft.Dynamics.Commerce.Runtime.Entities.dll)

## Syntax

``` vb
'Declaration
<ColumnAttribute("LANGUAGEID")> _
<DataMemberAttribute> _
Public Property LanguageId As String
    Get
    Set
'Usage
Dim instance As LocalizedString
Dim value As String

value = instance.LanguageId

instance.LanguageId = value
```

``` csharp
[ColumnAttribute("LANGUAGEID")]
[DataMemberAttribute]
public string LanguageId { get; set; }
```

``` c++
[ColumnAttribute(L"LANGUAGEID")]
[DataMemberAttribute]
public:
property String^ LanguageId {
    String^ get ();
    void set (String^ value);
}
```

#### Property Value

Type: [System.String](https://technet.microsoft.com/en-us/library/s1wwdcbf\(v=ax.60\))  
Returns [String](https://technet.microsoft.com/en-us/library/s1wwdcbf\(v=ax.60\)).  

## See Also

#### Reference

[LocalizedString Class](localizedstring-class-microsoft-dynamics-commerce-runtime-datamodel.md)

[Microsoft.Dynamics.Commerce.Runtime.DataModel Namespace](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)

