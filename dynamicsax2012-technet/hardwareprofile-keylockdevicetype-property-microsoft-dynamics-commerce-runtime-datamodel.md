---
title: HardwareProfile.KeyLockDeviceType Property  (Microsoft.Dynamics.Commerce.Runtime.DataModel)
TOCTitle: KeyLockDeviceType Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.DataModel.HardwareProfile.KeyLockDeviceType
ms:mtpsurl: https://technet.microsoft.com/en-us/library/microsoft.dynamics.commerce.runtime.datamodel.hardwareprofile.keylockdevicetype(v=AX.60)
ms:contentKeyID: 62207092
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataModel.HardwareProfile.KeyLockDeviceType
dev_langs:
- CSharp
- C++
- VB
---

# KeyLockDeviceType Property

Gets or sets the keylock device type value.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataModel](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Entities (in Microsoft.Dynamics.Commerce.Runtime.Entities.dll)

## Syntax

``` vb
'Declaration
<ColumnAttribute("KEYLOCK")> _
<IgnoreDataMemberAttribute> _
Public Property KeyLockDeviceType As DeviceType
    Get
    Set
'Usage
Dim instance As HardwareProfile
Dim value As DeviceType

value = instance.KeyLockDeviceType

instance.KeyLockDeviceType = value
```

``` csharp
[ColumnAttribute("KEYLOCK")]
[IgnoreDataMemberAttribute]
public DeviceType KeyLockDeviceType { get; set; }
```

``` c++
[ColumnAttribute(L"KEYLOCK")]
[IgnoreDataMemberAttribute]
public:
property DeviceType KeyLockDeviceType {
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

