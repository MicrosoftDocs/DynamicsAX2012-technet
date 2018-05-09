---
title: HardwareProfile.SignatureCaptureDeviceType Property  (Microsoft.Dynamics.Commerce.Runtime.DataModel)
TOCTitle: SignatureCaptureDeviceType Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.DataModel.HardwareProfile.SignatureCaptureDeviceType
ms:mtpsurl: https://technet.microsoft.com/en-us/library/microsoft.dynamics.commerce.runtime.datamodel.hardwareprofile.signaturecapturedevicetype(v=AX.60)
ms:contentKeyID: 62212567
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataModel.HardwareProfile.SignatureCaptureDeviceType
dev_langs:
- CSharp
- C++
- VB
---

# SignatureCaptureDeviceType Property

Gets or sets the signature capture device type value.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataModel](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Entities (in Microsoft.Dynamics.Commerce.Runtime.Entities.dll)

## Syntax

``` vb
'Declaration
<ColumnAttribute("SIGCAP")> _
<IgnoreDataMemberAttribute> _
Public Property SignatureCaptureDeviceType As DeviceType
    Get
    Set
'Usage
Dim instance As HardwareProfile
Dim value As DeviceType

value = instance.SignatureCaptureDeviceType

instance.SignatureCaptureDeviceType = value
```

``` csharp
[ColumnAttribute("SIGCAP")]
[IgnoreDataMemberAttribute]
public DeviceType SignatureCaptureDeviceType { get; set; }
```

``` c++
[ColumnAttribute(L"SIGCAP")]
[IgnoreDataMemberAttribute]
public:
property DeviceType SignatureCaptureDeviceType {
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

