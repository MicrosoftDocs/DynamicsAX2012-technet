---
title: HardwareProfile.PinPadDeviceDescription Property  (Microsoft.Dynamics.Commerce.Runtime.DataModel)
TOCTitle: PinPadDeviceDescription Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.DataModel.HardwareProfile.PinPadDeviceDescription
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.datamodel.hardwareprofile.pinpaddevicedescription(v=AX.60)
ms:contentKeyID: 62214019
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataModel.HardwareProfile.PinPadDeviceDescription
dev_langs:
- CSharp
- C++
- VB
---

# PinPadDeviceDescription Property

Gets or sets the pinpad device description.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataModel](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Entities (in Microsoft.Dynamics.Commerce.Runtime.Entities.dll)

## Syntax

``` vb
'Declaration
<DataMemberAttribute> _
<ColumnAttribute("PINPADDESCRIPTION")> _
Public Property PinPadDeviceDescription As String
    Get
    Set
'Usage
Dim instance As HardwareProfile
Dim value As String

value = instance.PinPadDeviceDescription

instance.PinPadDeviceDescription = value
```

``` csharp
[DataMemberAttribute]
[ColumnAttribute("PINPADDESCRIPTION")]
public string PinPadDeviceDescription { get; set; }
```

``` c++
[DataMemberAttribute]
[ColumnAttribute(L"PINPADDESCRIPTION")]
public:
property String^ PinPadDeviceDescription {
    String^ get ();
    void set (String^ value);
}
```

#### Property Value

Type: [System.String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\))  
The description string.  

## See Also

#### Reference

[HardwareProfile Class](hardwareprofile-class-microsoft-dynamics-commerce-runtime-datamodel.md)

[Microsoft.Dynamics.Commerce.Runtime.DataModel Namespace](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)

