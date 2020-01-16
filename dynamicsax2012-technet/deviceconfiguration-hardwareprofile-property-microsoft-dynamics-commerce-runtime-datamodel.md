---
title: DeviceConfiguration.HardwareProfile Property  (Microsoft.Dynamics.Commerce.Runtime.DataModel)
TOCTitle: HardwareProfile Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.DataModel.DeviceConfiguration.HardwareProfile
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.datamodel.deviceconfiguration.hardwareprofile(v=AX.60)
ms:contentKeyID: 62212859
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataModel.DeviceConfiguration.HardwareProfile
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
<ColumnAttribute("HARDWAREPROFILE")> _
<DataMemberAttribute> _
Public Property HardwareProfile As String
    Get
    Set
'Usage
Dim instance As DeviceConfiguration
Dim value As String

value = instance.HardwareProfile

instance.HardwareProfile = value
```

``` csharp
[ColumnAttribute("HARDWAREPROFILE")]
[DataMemberAttribute]
public string HardwareProfile { get; set; }
```

``` c++
[ColumnAttribute(L"HARDWAREPROFILE")]
[DataMemberAttribute]
public:
property String^ HardwareProfile {
    String^ get ();
    void set (String^ value);
}
```

#### Property Value

Type: [System.String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\))  
The string containing the hardware profile.  

## See Also

#### Reference

[DeviceConfiguration Class](deviceconfiguration-class-microsoft-dynamics-commerce-runtime-datamodel.md)

[Microsoft.Dynamics.Commerce.Runtime.DataModel Namespace](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)

