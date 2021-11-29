---
title: HardwareProfile.PinPadDeviceType Property  (Microsoft.Dynamics.Commerce.Runtime.DataModel)
TOCTitle: PinPadDeviceType Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.DataModel.HardwareProfile.PinPadDeviceType
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.datamodel.hardwareprofile.pinpaddevicetype(v=AX.60)
ms:contentKeyID: 62209733
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataModel.HardwareProfile.PinPadDeviceType
dev_langs:
- CSharp
- C++
- VB
---

# PinPadDeviceType Property


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Gets or sets the pinpad device type value.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataModel](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Entities (in Microsoft.Dynamics.Commerce.Runtime.Entities.dll)

## Syntax

``` vb
'Declaration
<ColumnAttribute("PINPAD")> _
<IgnoreDataMemberAttribute> _
Public Property PinPadDeviceType As DeviceType
    Get
    Set
'Usage
Dim instance As HardwareProfile
Dim value As DeviceType

value = instance.PinPadDeviceType

instance.PinPadDeviceType = value
```

``` csharp
[ColumnAttribute("PINPAD")]
[IgnoreDataMemberAttribute]
public DeviceType PinPadDeviceType { get; set; }
```

``` c++
[ColumnAttribute(L"PINPAD")]
[IgnoreDataMemberAttribute]
public:
property DeviceType PinPadDeviceType {
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

