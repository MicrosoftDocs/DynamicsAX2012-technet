---
title: OfflineSyncStatsLine.Terminal Property  (Microsoft.Dynamics.Commerce.Runtime.DataModel)
TOCTitle: Terminal Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.DataModel.OfflineSyncStatsLine.Terminal
ms:mtpsurl: https://technet.microsoft.com/en-us/library/microsoft.dynamics.commerce.runtime.datamodel.offlinesyncstatsline.terminal(v=AX.60)
ms:contentKeyID: 65320322
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataModel.OfflineSyncStatsLine.Terminal
dev_langs:
- CSharp
- C++
- VB
---

# Terminal Property

Gets or sets the terminal name.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataModel](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Entities (in Microsoft.Dynamics.Commerce.Runtime.Entities.dll)

## Syntax

``` vb
'Declaration
<DataMemberAttribute> _
<ColumnAttribute("TERMINALID")> _
Public Property Terminal As String
    Get
    Set
'Usage
Dim instance As OfflineSyncStatsLine
Dim value As String

value = instance.Terminal

instance.Terminal = value
```

``` csharp
[DataMemberAttribute]
[ColumnAttribute("TERMINALID")]
public string Terminal { get; set; }
```

``` c++
[DataMemberAttribute]
[ColumnAttribute(L"TERMINALID")]
public:
property String^ Terminal {
    String^ get ();
    void set (String^ value);
}
```

#### Property Value

Type: [System.String](https://technet.microsoft.com/en-us/library/s1wwdcbf\(v=ax.60\))  
Returns [String](https://technet.microsoft.com/en-us/library/s1wwdcbf\(v=ax.60\)).  

## See Also

#### Reference

[OfflineSyncStatsLine Class](offlinesyncstatsline-class-microsoft-dynamics-commerce-runtime-datamodel.md)

[Microsoft.Dynamics.Commerce.Runtime.DataModel Namespace](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)

