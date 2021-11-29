---
title: Device.DeviceType Property  (Microsoft.Dynamics.Commerce.Runtime.DataModel)
TOCTitle: DeviceType Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.DataModel.Device.DeviceType
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.datamodel.device.devicetype(v=AX.60)
ms:contentKeyID: 62213398
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataModel.Device.DeviceType
dev_langs:
- CSharp
- C++
- VB
---

# DeviceType Property


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Gets or sets the device type.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataModel](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Entities (in Microsoft.Dynamics.Commerce.Runtime.Entities.dll)

## Syntax

``` vb
'Declaration
<ColumnAttribute("TYPE")> _
<DataMemberAttribute> _
Public Property DeviceType As String
    Get
    Set
'Usage
Dim instance As Device
Dim value As String

value = instance.DeviceType

instance.DeviceType = value
```

``` csharp
[ColumnAttribute("TYPE")]
[DataMemberAttribute]
public string DeviceType { get; set; }
```

``` c++
[ColumnAttribute(L"TYPE")]
[DataMemberAttribute]
public:
property String^ DeviceType {
    String^ get ();
    void set (String^ value);
}
```

#### Property Value

Type: [System.String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\))  
The device type.  

## See Also

#### Reference

[Device Class](device-class-microsoft-dynamics-commerce-runtime-datamodel.md)

[Microsoft.Dynamics.Commerce.Runtime.DataModel Namespace](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)

