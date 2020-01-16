---
title: SalesLine.ReturnTerminalId Property  (Microsoft.Dynamics.Commerce.Runtime.DataModel)
TOCTitle: ReturnTerminalId Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.DataModel.SalesLine.ReturnTerminalId
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.datamodel.salesline.returnterminalid(v=AX.60)
ms:contentKeyID: 62206481
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataModel.SalesLine.ReturnTerminalId
dev_langs:
- CSharp
- C++
- VB
---

# ReturnTerminalId Property

Gets or sets the return terminal identifier.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataModel](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Entities (in Microsoft.Dynamics.Commerce.Runtime.Entities.dll)

## Syntax

``` vb
'Declaration
<ColumnAttribute("RETURNTERMINALID")> _
<DataMemberAttribute> _
Public Property ReturnTerminalId As String
    Get
    Set
'Usage
Dim instance As SalesLine
Dim value As String

value = instance.ReturnTerminalId

instance.ReturnTerminalId = value
```

``` csharp
[ColumnAttribute("RETURNTERMINALID")]
[DataMemberAttribute]
public string ReturnTerminalId { get; set; }
```

``` c++
[ColumnAttribute(L"RETURNTERMINALID")]
[DataMemberAttribute]
public:
property String^ ReturnTerminalId {
    String^ get ();
    void set (String^ value);
}
```

#### Property Value

Type: [System.String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\))  
The terminal identifier.  

## See Also

#### Reference

[SalesLine Class](salesline-class-microsoft-dynamics-commerce-runtime-datamodel.md)

[Microsoft.Dynamics.Commerce.Runtime.DataModel Namespace](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)

