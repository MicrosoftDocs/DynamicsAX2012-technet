---
title: ReasonCode.LanguageId Property  (Microsoft.Dynamics.Commerce.Runtime.DataModel)
TOCTitle: LanguageId Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.DataModel.ReasonCode.LanguageId
ms:mtpsurl: https://technet.microsoft.com/en-us/library/microsoft.dynamics.commerce.runtime.datamodel.reasoncode.languageid(v=AX.60)
ms:contentKeyID: 62204356
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataModel.ReasonCode.LanguageId
dev_langs:
- CSharp
- C++
- VB
---

# LanguageId Property

Gets the language identifier of reason code.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataModel](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Entities (in Microsoft.Dynamics.Commerce.Runtime.Entities.dll)

## Syntax

``` vb
'Declaration
<IgnoreDataMemberAttribute> _
<ColumnAttribute("LANGUAGEID")> _
Public ReadOnly Property LanguageId As String
    Get
'Usage
Dim instance As ReasonCode
Dim value As String

value = instance.LanguageId
```

``` csharp
[IgnoreDataMemberAttribute]
[ColumnAttribute("LANGUAGEID")]
public string LanguageId { get; }
```

``` c++
[IgnoreDataMemberAttribute]
[ColumnAttribute(L"LANGUAGEID")]
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

[ReasonCode Class](reasoncode-class-microsoft-dynamics-commerce-runtime-datamodel.md)

[Microsoft.Dynamics.Commerce.Runtime.DataModel Namespace](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)

