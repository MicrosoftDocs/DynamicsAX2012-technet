---
title: HardwareProfilePrinter.DeviceType Property  (Microsoft.Dynamics.Commerce.Runtime.DataModel)
TOCTitle: DeviceType Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.DataModel.HardwareProfilePrinter.DeviceType
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.datamodel.hardwareprofileprinter.devicetype(v=AX.60)
ms:contentKeyID: 62212584
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataModel.HardwareProfilePrinter.DeviceType
dev_langs:
- CSharp
- C++
- VB
---

# DeviceType Property

Gets or sets the printer device type value.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataModel](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Entities (in Microsoft.Dynamics.Commerce.Runtime.Entities.dll)

## Syntax

``` vb
'Declaration
<ColumnAttribute("PRINTERTYPE")> _
<IgnoreDataMemberAttribute> _
Public Property DeviceType As DeviceType
    Get
    Set
'Usage
Dim instance As HardwareProfilePrinter
Dim value As DeviceType

value = instance.DeviceType

instance.DeviceType = value
```

``` csharp
[ColumnAttribute("PRINTERTYPE")]
[IgnoreDataMemberAttribute]
public DeviceType DeviceType { get; set; }
```

``` c++
[ColumnAttribute(L"PRINTERTYPE")]
[IgnoreDataMemberAttribute]
public:
property DeviceType DeviceType {
    DeviceType get ();
    void set (DeviceType value);
}
```

#### Property Value

Type: [Microsoft.Dynamics.Commerce.Runtime.DataModel.DeviceType](devicetype-enumeration-microsoft-dynamics-commerce-runtime-datamodel.md)  
The DeviceType value.  

## See Also

#### Reference

[HardwareProfilePrinter Class](hardwareprofileprinter-class-microsoft-dynamics-commerce-runtime-datamodel.md)

[Microsoft.Dynamics.Commerce.Runtime.DataModel Namespace](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)

