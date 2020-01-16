---
title: DeviceActivationResult.Device Property  (Microsoft.Dynamics.Commerce.Runtime.DataModel)
TOCTitle: Device Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.DataModel.DeviceActivationResult.Device
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.datamodel.deviceactivationresult.device(v=AX.60)
ms:contentKeyID: 65319572
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataModel.DeviceActivationResult.Device
dev_langs:
- CSharp
- C++
- VB
---

# Device Property

Gets or sets the device.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataModel](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Entities (in Microsoft.Dynamics.Commerce.Runtime.Entities.dll)

## Syntax

``` vb
'Declaration
<DataMemberAttribute> _
Public Property Device As Device
    Get
    Set
'Usage
Dim instance As DeviceActivationResult
Dim value As Device

value = instance.Device

instance.Device = value
```

``` csharp
[DataMemberAttribute]
public Device Device { get; set; }
```

``` c++
[DataMemberAttribute]
public:
property Device^ Device {
    Device^ get ();
    void set (Device^ value);
}
```

#### Property Value

Type: [Microsoft.Dynamics.Commerce.Runtime.DataModel.Device](device-class-microsoft-dynamics-commerce-runtime-datamodel.md)  
The device object.  

## See Also

#### Reference

[DeviceActivationResult Class](deviceactivationresult-class-microsoft-dynamics-commerce-runtime-datamodel.md)

[Microsoft.Dynamics.Commerce.Runtime.DataModel Namespace](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)

