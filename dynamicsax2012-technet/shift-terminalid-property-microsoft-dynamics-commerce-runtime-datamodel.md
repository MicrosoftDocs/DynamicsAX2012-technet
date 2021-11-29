---
title: Shift.TerminalId Property  (Microsoft.Dynamics.Commerce.Runtime.DataModel)
TOCTitle: TerminalId Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.DataModel.Shift.TerminalId
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.datamodel.shift.terminalid(v=AX.60)
ms:contentKeyID: 62207729
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataModel.Shift.TerminalId
dev_langs:
- CSharp
- C++
- VB
---

# TerminalId Property


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Gets or sets terminal identifier that creates this Shift.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataModel](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Entities (in Microsoft.Dynamics.Commerce.Runtime.Entities.dll)

## Syntax

``` vb
'Declaration
<KeyAttribute> _
<DataMemberAttribute> _
<ColumnAttribute("TERMINALID")> _
Public Property TerminalId As String
    Get
    Set
'Usage
Dim instance As Shift
Dim value As String

value = instance.TerminalId

instance.TerminalId = value
```

``` csharp
[KeyAttribute]
[DataMemberAttribute]
[ColumnAttribute("TERMINALID")]
public string TerminalId { get; set; }
```

``` c++
[KeyAttribute]
[DataMemberAttribute]
[ColumnAttribute(L"TERMINALID")]
public:
property String^ TerminalId {
    String^ get ();
    void set (String^ value);
}
```

#### Property Value

Type: [System.String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\))  
Returns [String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\)).  

## Remarks

TerminalId is the identifier of the original terminal that creates the shift.

## See Also

#### Reference

[Shift Class](shift-class-microsoft-dynamics-commerce-runtime-datamodel.md)

[Microsoft.Dynamics.Commerce.Runtime.DataModel Namespace](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)

