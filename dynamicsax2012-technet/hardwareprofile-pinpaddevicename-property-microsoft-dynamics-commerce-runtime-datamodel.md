---
title: HardwareProfile.PinPadDeviceName Property  (Microsoft.Dynamics.Commerce.Runtime.DataModel)
TOCTitle: PinPadDeviceName Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.DataModel.HardwareProfile.PinPadDeviceName
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.datamodel.hardwareprofile.pinpaddevicename(v=AX.60)
ms:contentKeyID: 62210785
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataModel.HardwareProfile.PinPadDeviceName
dev_langs:
- CSharp
- C++
- VB
---

# PinPadDeviceName Property

Gets or sets the pinpad device name.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataModel](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Entities (in Microsoft.Dynamics.Commerce.Runtime.Entities.dll)

## Syntax

``` vb
'Declaration
<DataMemberAttribute> _
<ColumnAttribute("PINPADDEVICENAME")> _
Public Property PinPadDeviceName As String
    Get
    Set
'Usage
Dim instance As HardwareProfile
Dim value As String

value = instance.PinPadDeviceName

instance.PinPadDeviceName = value
```

``` csharp
[DataMemberAttribute]
[ColumnAttribute("PINPADDEVICENAME")]
public string PinPadDeviceName { get; set; }
```

``` c++
[DataMemberAttribute]
[ColumnAttribute(L"PINPADDEVICENAME")]
public:
property String^ PinPadDeviceName {
    String^ get ();
    void set (String^ value);
}
```

#### Property Value

Type: [System.String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\))  
The name string.  

## See Also

#### Reference

[HardwareProfile Class](hardwareprofile-class-microsoft-dynamics-commerce-runtime-datamodel.md)

[Microsoft.Dynamics.Commerce.Runtime.DataModel Namespace](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)

