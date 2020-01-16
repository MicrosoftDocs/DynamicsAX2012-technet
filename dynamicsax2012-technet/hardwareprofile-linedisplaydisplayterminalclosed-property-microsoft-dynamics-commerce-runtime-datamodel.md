---
title: HardwareProfile.LineDisplayDisplayTerminalClosed Property  (Microsoft.Dynamics.Commerce.Runtime.DataModel)
TOCTitle: LineDisplayDisplayTerminalClosed Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.DataModel.HardwareProfile.LineDisplayDisplayTerminalClosed
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.datamodel.hardwareprofile.linedisplaydisplayterminalclosed(v=AX.60)
ms:contentKeyID: 62205770
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataModel.HardwareProfile.LineDisplayDisplayTerminalClosed
dev_langs:
- CSharp
- C++
- VB
---

# LineDisplayDisplayTerminalClosed Property

Gets or sets a value indicating whether display terminal closed value is set.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataModel](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Entities (in Microsoft.Dynamics.Commerce.Runtime.Entities.dll)

## Syntax

``` vb
'Declaration
<DataMemberAttribute> _
<ColumnAttribute("DISPLAYTERMINALCLOSED")> _
Public Property LineDisplayDisplayTerminalClosed As Boolean
    Get
    Set
'Usage
Dim instance As HardwareProfile
Dim value As Boolean

value = instance.LineDisplayDisplayTerminalClosed

instance.LineDisplayDisplayTerminalClosed = value
```

``` csharp
[DataMemberAttribute]
[ColumnAttribute("DISPLAYTERMINALCLOSED")]
public bool LineDisplayDisplayTerminalClosed { get; set; }
```

``` c++
[DataMemberAttribute]
[ColumnAttribute(L"DISPLAYTERMINALCLOSED")]
public:
property bool LineDisplayDisplayTerminalClosed {
    bool get ();
    void set (bool value);
}
```

#### Property Value

Type: [System.Boolean](https://technet.microsoft.com/library/a28wyd50\(v=ax.60\))  
True if display terminal closed is set; otherwise, false.  

## See Also

#### Reference

[HardwareProfile Class](hardwareprofile-class-microsoft-dynamics-commerce-runtime-datamodel.md)

[Microsoft.Dynamics.Commerce.Runtime.DataModel Namespace](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)

