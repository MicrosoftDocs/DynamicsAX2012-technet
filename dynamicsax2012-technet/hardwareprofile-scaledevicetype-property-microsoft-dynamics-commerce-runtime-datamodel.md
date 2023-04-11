---
title: HardwareProfile.ScaleDeviceType Property  (Microsoft.Dynamics.Commerce.Runtime.DataModel)
TOCTitle: ScaleDeviceType Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.DataModel.HardwareProfile.ScaleDeviceType
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.datamodel.hardwareprofile.scaledevicetype(v=AX.60)
ms:contentKeyID: 62204253
author: tonyafehr
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataModel.HardwareProfile.ScaleDeviceType
dev_langs:
- CSharp
- C++
- VB
---

# ScaleDeviceType Property


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Gets or sets the scale device type value.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataModel](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Entities (in Microsoft.Dynamics.Commerce.Runtime.Entities.dll)

## Syntax

``` vb
'Declaration
<IgnoreDataMemberAttribute> _
<ColumnAttribute("SCALE")> _
Public Property ScaleDeviceType As DeviceType
    Get
    Set
'Usage
Dim instance As HardwareProfile
Dim value As DeviceType

value = instance.ScaleDeviceType

instance.ScaleDeviceType = value
```

``` csharp
[IgnoreDataMemberAttribute]
[ColumnAttribute("SCALE")]
public DeviceType ScaleDeviceType { get; set; }
```

``` c++
[IgnoreDataMemberAttribute]
[ColumnAttribute(L"SCALE")]
public:
property DeviceType ScaleDeviceType {
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

