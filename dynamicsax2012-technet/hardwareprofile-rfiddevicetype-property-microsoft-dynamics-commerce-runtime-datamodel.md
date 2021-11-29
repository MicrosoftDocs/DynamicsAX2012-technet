---
title: HardwareProfile.RFIDDeviceType Property  (Microsoft.Dynamics.Commerce.Runtime.DataModel)
TOCTitle: RFIDDeviceType Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.DataModel.HardwareProfile.RFIDDeviceType
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.datamodel.hardwareprofile.rfiddevicetype(v=AX.60)
ms:contentKeyID: 62204921
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataModel.HardwareProfile.RFIDDeviceType
dev_langs:
- CSharp
- C++
- VB
---

# RFIDDeviceType Property


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Gets or sets the RFID device type value.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataModel](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Entities (in Microsoft.Dynamics.Commerce.Runtime.Entities.dll)

## Syntax

``` vb
'Declaration
<IgnoreDataMemberAttribute> _
<ColumnAttribute("RFIDSCANNERTYPE")> _
Public Property RFIDDeviceType As DeviceType
    Get
    Set
'Usage
Dim instance As HardwareProfile
Dim value As DeviceType

value = instance.RFIDDeviceType

instance.RFIDDeviceType = value
```

``` csharp
[IgnoreDataMemberAttribute]
[ColumnAttribute("RFIDSCANNERTYPE")]
public DeviceType RFIDDeviceType { get; set; }
```

``` c++
[IgnoreDataMemberAttribute]
[ColumnAttribute(L"RFIDSCANNERTYPE")]
public:
property DeviceType RFIDDeviceType {
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

