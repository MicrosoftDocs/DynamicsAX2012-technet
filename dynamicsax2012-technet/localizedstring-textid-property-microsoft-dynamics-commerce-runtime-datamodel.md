---
title: LocalizedString.TextId Property  (Microsoft.Dynamics.Commerce.Runtime.DataModel)
TOCTitle: TextId Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.DataModel.LocalizedString.TextId
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.datamodel.localizedstring.textid(v=AX.60)
ms:contentKeyID: 62208596
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataModel.LocalizedString.TextId
dev_langs:
- CSharp
- C++
- VB
---

# TextId Property

Gets or sets the text identifier.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataModel](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Entities (in Microsoft.Dynamics.Commerce.Runtime.Entities.dll)

## Syntax

``` vb
'Declaration
<DataMemberAttribute> _
<ColumnAttribute("TEXTID")> _
Public Property TextId As Integer
    Get
    Set
'Usage
Dim instance As LocalizedString
Dim value As Integer

value = instance.TextId

instance.TextId = value
```

``` csharp
[DataMemberAttribute]
[ColumnAttribute("TEXTID")]
public int TextId { get; set; }
```

``` c++
[DataMemberAttribute]
[ColumnAttribute(L"TEXTID")]
public:
property int TextId {
    int get ();
    void set (int value);
}
```

#### Property Value

Type: [System.Int32](https://technet.microsoft.com/library/td2s409d\(v=ax.60\))  
Returns [Int32](https://technet.microsoft.com/library/td2s409d\(v=ax.60\)).  

## See Also

#### Reference

[LocalizedString Class](localizedstring-class-microsoft-dynamics-commerce-runtime-datamodel.md)

[Microsoft.Dynamics.Commerce.Runtime.DataModel Namespace](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)

