---
title: HardwareProfile.MsrDeviceType Property  (Microsoft.Dynamics.Commerce.Runtime.DataModel)
TOCTitle: MsrDeviceType Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.DataModel.HardwareProfile.MSRDeviceType
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.datamodel.hardwareprofile.msrdevicetype(v=AX.60)
ms:contentKeyID: 62206133
author: tonyafehr
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataModel.HardwareProfile.MsrDeviceType
dev_langs:
- CSharp
- C++
- VB
---

# MsrDeviceType Property


[!INCLUDE[archive-banner](includes/archive-banner.md)]

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataModel](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Entities (in Microsoft.Dynamics.Commerce.Runtime.Entities.dll)

## Syntax

``` vb
'Declaration
<IgnoreDataMemberAttribute> _
<ColumnAttribute("MSR")> _
Public Property MsrDeviceType As DeviceType
    Get
    Set
'Usage
Dim instance As HardwareProfile
Dim value As DeviceType

value = instance.MsrDeviceType

instance.MsrDeviceType = value
```

``` csharp
[IgnoreDataMemberAttribute]
[ColumnAttribute("MSR")]
public DeviceType MsrDeviceType { get; set; }
```

``` c++
[IgnoreDataMemberAttribute]
[ColumnAttribute(L"MSR")]
public:
property DeviceType MsrDeviceType {
    DeviceType get ();
    void set (DeviceType value);
}
```

#### Property Value

Type: [Microsoft.Dynamics.Commerce.Runtime.DataModel.DeviceType](devicetype-enumeration-microsoft-dynamics-commerce-runtime-datamodel.md)  

## See Also

#### Reference

[HardwareProfile Class](hardwareprofile-class-microsoft-dynamics-commerce-runtime-datamodel.md)

[Microsoft.Dynamics.Commerce.Runtime.DataModel Namespace](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)

