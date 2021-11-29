---
title: HardwareProfileCashDrawerPoolDevice.DeviceDescription Property  (Microsoft.Dynamics.Commerce.Runtime.DataModel)
TOCTitle: DeviceDescription Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.DataModel.HardwareProfileCashDrawerPoolDevice.DeviceDescription
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.datamodel.hardwareprofilecashdrawerpooldevice.devicedescription(v=AX.60)
ms:contentKeyID: 65318215
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataModel.HardwareProfileCashDrawerPoolDevice.DeviceDescription
dev_langs:
- CSharp
- C++
- VB
---

# DeviceDescription Property


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Gets or sets the cash drawer device description.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataModel](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Entities (in Microsoft.Dynamics.Commerce.Runtime.Entities.dll)

## Syntax

``` vb
'Declaration
<ColumnAttribute("DEVICEDESCRIPTION")> _
<DataMemberAttribute> _
Public Property DeviceDescription As String
    Get
    Set
'Usage
Dim instance As HardwareProfileCashDrawerPoolDevice
Dim value As String

value = instance.DeviceDescription

instance.DeviceDescription = value
```

``` csharp
[ColumnAttribute("DEVICEDESCRIPTION")]
[DataMemberAttribute]
public string DeviceDescription { get; set; }
```

``` c++
[ColumnAttribute(L"DEVICEDESCRIPTION")]
[DataMemberAttribute]
public:
property String^ DeviceDescription {
    String^ get ();
    void set (String^ value);
}
```

#### Property Value

Type: [System.String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\))  
The description string.  

## See Also

#### Reference

[HardwareProfileCashDrawerPoolDevice Class](hardwareprofilecashdrawerpooldevice-class-microsoft-dynamics-commerce-runtime-datamodel.md)

[Microsoft.Dynamics.Commerce.Runtime.DataModel Namespace](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)

