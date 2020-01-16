---
title: HardwareProfileCashDrawerPoolDevice.DeviceName Property  (Microsoft.Dynamics.Commerce.Runtime.DataModel)
TOCTitle: DeviceName Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.DataModel.HardwareProfileCashDrawerPoolDevice.DeviceName
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.datamodel.hardwareprofilecashdrawerpooldevice.devicename(v=AX.60)
ms:contentKeyID: 65317676
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataModel.HardwareProfileCashDrawerPoolDevice.DeviceName
dev_langs:
- CSharp
- C++
- VB
---

# DeviceName Property

Gets or sets the cash drawer device name.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataModel](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Entities (in Microsoft.Dynamics.Commerce.Runtime.Entities.dll)

## Syntax

``` vb
'Declaration
<DataMemberAttribute> _
<ColumnAttribute("DEVICENAME")> _
Public Property DeviceName As String
    Get
    Set
'Usage
Dim instance As HardwareProfileCashDrawerPoolDevice
Dim value As String

value = instance.DeviceName

instance.DeviceName = value
```

``` csharp
[DataMemberAttribute]
[ColumnAttribute("DEVICENAME")]
public string DeviceName { get; set; }
```

``` c++
[DataMemberAttribute]
[ColumnAttribute(L"DEVICENAME")]
public:
property String^ DeviceName {
    String^ get ();
    void set (String^ value);
}
```

#### Property Value

Type: [System.String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\))  
The name string.  

## See Also

#### Reference

[HardwareProfileCashDrawerPoolDevice Class](hardwareprofilecashdrawerpooldevice-class-microsoft-dynamics-commerce-runtime-datamodel.md)

[Microsoft.Dynamics.Commerce.Runtime.DataModel Namespace](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)

