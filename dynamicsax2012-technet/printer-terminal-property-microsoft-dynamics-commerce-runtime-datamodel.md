---
title: Printer.Terminal Property  (Microsoft.Dynamics.Commerce.Runtime.DataModel)
TOCTitle: Terminal Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.DataModel.Printer.Terminal
ms:mtpsurl: https://technet.microsoft.com/en-us/library/microsoft.dynamics.commerce.runtime.datamodel.printer.terminal(v=AX.60)
ms:contentKeyID: 62211615
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataModel.Printer.Terminal
dev_langs:
- CSharp
- C++
- VB
---

# Terminal Property

Gets or sets the terminal the printer is associated with.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataModel](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Entities (in Microsoft.Dynamics.Commerce.Runtime.Entities.dll)

## Syntax

``` vb
'Declaration
<DataMemberAttribute> _
<ColumnAttribute("TERMINALID")> _
Public Property Terminal As Long
    Get
    Set
'Usage
Dim instance As Printer
Dim value As Long

value = instance.Terminal

instance.Terminal = value
```

``` csharp
[DataMemberAttribute]
[ColumnAttribute("TERMINALID")]
public long Terminal { get; set; }
```

``` c++
[DataMemberAttribute]
[ColumnAttribute(L"TERMINALID")]
public:
property long long Terminal {
    long long get ();
    void set (long long value);
}
```

#### Property Value

Type: [System.Int64](https://technet.microsoft.com/en-us/library/6yy583ek\(v=ax.60\))  
Returns [Int64](https://technet.microsoft.com/en-us/library/6yy583ek\(v=ax.60\)).  

## See Also

#### Reference

[Printer Class](printer-class-microsoft-dynamics-commerce-runtime-datamodel.md)

[Microsoft.Dynamics.Commerce.Runtime.DataModel Namespace](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)

