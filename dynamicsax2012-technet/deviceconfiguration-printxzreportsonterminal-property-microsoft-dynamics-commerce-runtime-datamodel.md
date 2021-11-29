---
title: DeviceConfiguration.PrintXZReportsOnTerminal Property  (Microsoft.Dynamics.Commerce.Runtime.DataModel)
TOCTitle: PrintXZReportsOnTerminal Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.DataModel.DeviceConfiguration.PrintXZReportsOnTerminal
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.datamodel.deviceconfiguration.printxzreportsonterminal(v=AX.60)
ms:contentKeyID: 62209003
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataModel.DeviceConfiguration.PrintXZReportsOnTerminal
dev_langs:
- CSharp
- C++
- VB
---

# PrintXZReportsOnTerminal Property


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Gets or sets a value indicating whether print xz reports on terminal is allowed.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataModel](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Entities (in Microsoft.Dynamics.Commerce.Runtime.Entities.dll)

## Syntax

``` vb
'Declaration
<DataMemberAttribute> _
<ColumnAttribute("PRINTXREPORTONTERMINAL")> _
Public Property PrintXZReportsOnTerminal As Boolean
    Get
    Set
'Usage
Dim instance As DeviceConfiguration
Dim value As Boolean

value = instance.PrintXZReportsOnTerminal

instance.PrintXZReportsOnTerminal = value
```

``` csharp
[DataMemberAttribute]
[ColumnAttribute("PRINTXREPORTONTERMINAL")]
public bool PrintXZReportsOnTerminal { get; set; }
```

``` c++
[DataMemberAttribute]
[ColumnAttribute(L"PRINTXREPORTONTERMINAL")]
public:
property bool PrintXZReportsOnTerminal {
    bool get ();
    void set (bool value);
}
```

#### Property Value

Type: [System.Boolean](https://technet.microsoft.com/library/a28wyd50\(v=ax.60\))  
The value true if print xz reports on terminal is set; otherwise, false.  

## See Also

#### Reference

[DeviceConfiguration Class](deviceconfiguration-class-microsoft-dynamics-commerce-runtime-datamodel.md)

[Microsoft.Dynamics.Commerce.Runtime.DataModel Namespace](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)

