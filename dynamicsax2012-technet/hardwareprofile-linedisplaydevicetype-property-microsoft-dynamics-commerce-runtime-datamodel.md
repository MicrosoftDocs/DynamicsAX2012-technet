---
title: HardwareProfile.LineDisplayDeviceType Property  (Microsoft.Dynamics.Commerce.Runtime.DataModel)
TOCTitle: LineDisplayDeviceType Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.DataModel.HardwareProfile.LineDisplayDeviceType
ms:mtpsurl: https://technet.microsoft.com/en-us/library/microsoft.dynamics.commerce.runtime.datamodel.hardwareprofile.linedisplaydevicetype(v=AX.60)
ms:contentKeyID: 62214813
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataModel.HardwareProfile.LineDisplayDeviceType
dev_langs:
- CSharp
- C++
- VB
---

# LineDisplayDeviceType Property

Gets or sets the line display device type value.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataModel](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Entities (in Microsoft.Dynamics.Commerce.Runtime.Entities.dll)

## Syntax

``` vb
'Declaration
<ColumnAttribute("DISPLAYDEVICE")> _
<IgnoreDataMemberAttribute> _
Public Property LineDisplayDeviceType As DeviceType
    Get
    Set
'Usage
Dim instance As HardwareProfile
Dim value As DeviceType

value = instance.LineDisplayDeviceType

instance.LineDisplayDeviceType = value
```

``` csharp
[ColumnAttribute("DISPLAYDEVICE")]
[IgnoreDataMemberAttribute]
public DeviceType LineDisplayDeviceType { get; set; }
```

``` c++
[ColumnAttribute(L"DISPLAYDEVICE")]
[IgnoreDataMemberAttribute]
public:
property DeviceType LineDisplayDeviceType {
    DeviceType get ();
    void set (DeviceType value);
}
```

#### Property Value

Type: [Microsoft.Dynamics.Commerce.Runtime.DataModel.DeviceType](devicetype-enumeration-microsoft-dynamics-commerce-runtime-datamodel.md)  
The DeviceType value.  

## See Also

#### Reference

[HardwareProfile Class](hardwareprofile-class-microsoft-dynamics-commerce-runtime-datamodel.md)

[Microsoft.Dynamics.Commerce.Runtime.DataModel Namespace](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)

