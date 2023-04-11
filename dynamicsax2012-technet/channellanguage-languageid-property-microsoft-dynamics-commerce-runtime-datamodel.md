---
title: ChannelLanguage.LanguageId Property  (Microsoft.Dynamics.Commerce.Runtime.DataModel)
TOCTitle: LanguageId Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.DataModel.ChannelLanguage.LanguageId
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.datamodel.channellanguage.languageid(v=AX.60)
ms:contentKeyID: 49852386
author: tonyafehr
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataModel.ChannelLanguage.LanguageId
dev_langs:
- CSharp
- C++
- VB
---

# LanguageId Property


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Gets the language identifier.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataModel](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Entities (in Microsoft.Dynamics.Commerce.Runtime.Entities.dll)

## Syntax

``` vb
'Declaration
<DataMemberAttribute> _
<ColumnAttribute("LANGUAGEID")> _
Public Property LanguageId As String
    Get
    Friend Set
'Usage
Dim instance As ChannelLanguage
Dim value As String

value = instance.LanguageId
```

``` csharp
[DataMemberAttribute]
[ColumnAttribute("LANGUAGEID")]
public string LanguageId { get; internal set; }
```

``` c++
[DataMemberAttribute]
[ColumnAttribute(L"LANGUAGEID")]
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

[ChannelLanguage Class](channellanguage-class-microsoft-dynamics-commerce-runtime-datamodel.md)

[Microsoft.Dynamics.Commerce.Runtime.DataModel Namespace](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)

