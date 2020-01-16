---
title: Terminal.HardwareProfile Property  (Microsoft.Dynamics.Commerce.Runtime.DataModel)
TOCTitle: HardwareProfile Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.DataModel.Terminal.HardwareProfile
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.datamodel.terminal.hardwareprofile(v=AX.60)
ms:contentKeyID: 62208401
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataModel.Terminal.HardwareProfile
dev_langs:
- CSharp
- C++
- VB
---

# HardwareProfile Property

Gets or sets the hardware profile.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataModel](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Entities (in Microsoft.Dynamics.Commerce.Runtime.Entities.dll)

## Syntax

``` vb
'Declaration
<DataMemberAttribute> _
<ColumnAttribute("HARDWAREPROFILE")> _
Public Property HardwareProfile As String
    Get
    Set
'Usage
Dim instance As Terminal
Dim value As String

value = instance.HardwareProfile

instance.HardwareProfile = value
```

``` csharp
[DataMemberAttribute]
[ColumnAttribute("HARDWAREPROFILE")]
public string HardwareProfile { get; set; }
```

``` c++
[DataMemberAttribute]
[ColumnAttribute(L"HARDWAREPROFILE")]
public:
property String^ HardwareProfile {
    String^ get ();
    void set (String^ value);
}
```

#### Property Value

Type: [System.String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\))  
Returns [String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\)).  

## See Also

#### Reference

[Terminal Class](terminal-class-microsoft-dynamics-commerce-runtime-datamodel.md)

[Microsoft.Dynamics.Commerce.Runtime.DataModel Namespace](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)

