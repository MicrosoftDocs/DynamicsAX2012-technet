---
title: Device.DeviceNumber Property  (Microsoft.Dynamics.Commerce.Runtime.DataModel)
TOCTitle: DeviceNumber Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.DataModel.Device.DeviceNumber
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.datamodel.device.devicenumber(v=AX.60)
ms:contentKeyID: 62214956
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataModel.Device.DeviceNumber
dev_langs:
- CSharp
- C++
- VB
---

# DeviceNumber Property

Gets or sets the device identifier.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataModel](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Entities (in Microsoft.Dynamics.Commerce.Runtime.Entities.dll)

## Syntax

``` vb
'Declaration
<DataMemberAttribute> _
<ColumnAttribute("DEVICEID")> _
Public Property DeviceNumber As String
    Get
    Set
'Usage
Dim instance As Device
Dim value As String

value = instance.DeviceNumber

instance.DeviceNumber = value
```

``` csharp
[DataMemberAttribute]
[ColumnAttribute("DEVICEID")]
public string DeviceNumber { get; set; }
```

``` c++
[DataMemberAttribute]
[ColumnAttribute(L"DEVICEID")]
public:
property String^ DeviceNumber {
    String^ get ();
    void set (String^ value);
}
```

#### Property Value

Type: [System.String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\))  
The device identifier.  

## See Also

#### Reference

[Device Class](device-class-microsoft-dynamics-commerce-runtime-datamodel.md)

[Microsoft.Dynamics.Commerce.Runtime.DataModel Namespace](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)

