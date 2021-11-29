---
title: DeviceConfiguration.TerminalStatement Property  (Microsoft.Dynamics.Commerce.Runtime.DataModel)
TOCTitle: TerminalStatement Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.DataModel.DeviceConfiguration.TerminalStatement
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.datamodel.deviceconfiguration.terminalstatement(v=AX.60)
ms:contentKeyID: 62207286
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataModel.DeviceConfiguration.TerminalStatement
dev_langs:
- CSharp
- C++
- VB
---

# TerminalStatement Property


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Gets or sets a value indicating whether terminal statement is enabled.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataModel](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Entities (in Microsoft.Dynamics.Commerce.Runtime.Entities.dll)

## Syntax

``` vb
'Declaration
<DataMemberAttribute> _
<ColumnAttribute("TERMINALSTATEMENT")> _
Public Property TerminalStatement As Boolean
    Get
    Set
'Usage
Dim instance As DeviceConfiguration
Dim value As Boolean

value = instance.TerminalStatement

instance.TerminalStatement = value
```

``` csharp
[DataMemberAttribute]
[ColumnAttribute("TERMINALSTATEMENT")]
public bool TerminalStatement { get; set; }
```

``` c++
[DataMemberAttribute]
[ColumnAttribute(L"TERMINALSTATEMENT")]
public:
property bool TerminalStatement {
    bool get ();
    void set (bool value);
}
```

#### Property Value

Type: [System.Boolean](https://technet.microsoft.com/library/a28wyd50\(v=ax.60\))  
The value true if terminal statement is enabled; otherwise, false.  

## See Also

#### Reference

[DeviceConfiguration Class](deviceconfiguration-class-microsoft-dynamics-commerce-runtime-datamodel.md)

[Microsoft.Dynamics.Commerce.Runtime.DataModel Namespace](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)

