---
title: AccentColor.AccentId Property  (Microsoft.Dynamics.Commerce.Runtime.DataModel)
TOCTitle: AccentId Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.DataModel.AccentColor.AccentId
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.datamodel.accentcolor.accentid(v=AX.60)
ms:contentKeyID: 62213302
author: Khairunj
ms.author: daxcpft
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataModel.AccentColor.AccentId
dev_langs:
- CSharp
- C++
- VB
---

# AccentId Property

Gets or sets the value of accend identifier.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataModel](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Entities (in Microsoft.Dynamics.Commerce.Runtime.Entities.dll)

## Syntax

``` vb
'Declaration
<ColumnAttribute("ACCENTID")> _
<DataMemberAttribute> _
Public Property AccentId As String
    Get
    Set
'Usage
Dim instance As AccentColor
Dim value As String

value = instance.AccentId

instance.AccentId = value
```

``` csharp
[ColumnAttribute("ACCENTID")]
[DataMemberAttribute]
public string AccentId { get; set; }
```

``` c++
[ColumnAttribute(L"ACCENTID")]
[DataMemberAttribute]
public:
property String^ AccentId {
    String^ get ();
    void set (String^ value);
}
```

#### Property Value

Type: [System.String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\))  
Returns [String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\)).  

## See Also

#### Reference

[AccentColor Class](accentcolor-class-microsoft-dynamics-commerce-runtime-datamodel.md)

[Microsoft.Dynamics.Commerce.Runtime.DataModel Namespace](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)

