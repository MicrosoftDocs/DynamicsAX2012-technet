---
title: ReasonSubCode.LanguageId Property  (Microsoft.Dynamics.Commerce.Runtime.DataModel)
TOCTitle: LanguageId Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.DataModel.ReasonSubCode.LanguageId
ms:mtpsurl: https://technet.microsoft.com/en-us/library/microsoft.dynamics.commerce.runtime.datamodel.reasonsubcode.languageid(v=AX.60)
ms:contentKeyID: 62211118
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataModel.ReasonSubCode.LanguageId
dev_langs:
- CSharp
- C++
- VB
---

# LanguageId Property

Gets the language identifier of reason sub code.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataModel](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Entities (in Microsoft.Dynamics.Commerce.Runtime.Entities.dll)

## Syntax

``` vb
'Declaration
<ColumnAttribute("LANGUAGEID")> _
<IgnoreDataMemberAttribute> _
Public ReadOnly Property LanguageId As String
    Get
'Usage
Dim instance As ReasonSubCode
Dim value As String

value = instance.LanguageId
```

``` csharp
[ColumnAttribute("LANGUAGEID")]
[IgnoreDataMemberAttribute]
public string LanguageId { get; }
```

``` c++
[ColumnAttribute(L"LANGUAGEID")]
[IgnoreDataMemberAttribute]
public:
property String^ LanguageId {
    String^ get ();
}
```

#### Property Value

Type: [System.String](https://technet.microsoft.com/en-us/library/s1wwdcbf\(v=ax.60\))  
The language id.  

## See Also

#### Reference

[ReasonSubCode Class](reasonsubcode-class-microsoft-dynamics-commerce-runtime-datamodel.md)

[Microsoft.Dynamics.Commerce.Runtime.DataModel Namespace](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)

