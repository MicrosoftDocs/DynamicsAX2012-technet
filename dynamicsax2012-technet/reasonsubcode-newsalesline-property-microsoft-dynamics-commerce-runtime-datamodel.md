---
title: ReasonSubCode.NewSalesLine Property  (Microsoft.Dynamics.Commerce.Runtime.DataModel)
TOCTitle: NewSalesLine Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.DataModel.ReasonSubCode.NewSalesLine
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.datamodel.reasonsubcode.newsalesline(v=AX.60)
ms:contentKeyID: 62207868
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataModel.ReasonSubCode.NewSalesLine
dev_langs:
- CSharp
- C++
- VB
---

# NewSalesLine Property

Gets a value indicating whether new sales line.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataModel](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Entities (in Microsoft.Dynamics.Commerce.Runtime.Entities.dll)

## Syntax

``` vb
'Declaration
<ColumnAttribute("NEWSALESLINE")> _
<DataMemberAttribute> _
Public Property NewSalesLine As Boolean
    Get
    Friend Set
'Usage
Dim instance As ReasonSubCode
Dim value As Boolean

value = instance.NewSalesLine
```

``` csharp
[ColumnAttribute("NEWSALESLINE")]
[DataMemberAttribute]
public bool NewSalesLine { get; internal set; }
```

``` c++
[ColumnAttribute(L"NEWSALESLINE")]
[DataMemberAttribute]
public:
property bool NewSalesLine {
    bool get ();
    internal: void set (bool value);
}
```

#### Property Value

Type: [System.Boolean](https://technet.microsoft.com/library/a28wyd50\(v=ax.60\))  
The value true if new sales line; otherwise, false.  

## See Also

#### Reference

[ReasonSubCode Class](reasonsubcode-class-microsoft-dynamics-commerce-runtime-datamodel.md)

[Microsoft.Dynamics.Commerce.Runtime.DataModel Namespace](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)

