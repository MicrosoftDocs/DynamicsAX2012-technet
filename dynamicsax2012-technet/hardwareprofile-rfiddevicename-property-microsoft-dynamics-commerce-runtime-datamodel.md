---
title: HardwareProfile.RFIDDeviceName Property  (Microsoft.Dynamics.Commerce.Runtime.DataModel)
TOCTitle: RFIDDeviceName Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.DataModel.HardwareProfile.RFIDDeviceName
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.datamodel.hardwareprofile.rfiddevicename(v=AX.60)
ms:contentKeyID: 62208254
author: tonyafehr
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataModel.HardwareProfile.RFIDDeviceName
dev_langs:
- CSharp
- C++
- VB
---

# RFIDDeviceName Property


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Gets or sets the RFID device name.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataModel](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Entities (in Microsoft.Dynamics.Commerce.Runtime.Entities.dll)

## Syntax

``` vb
'Declaration
<ColumnAttribute("RFIDDEVICENAME")> _
<DataMemberAttribute> _
Public Property RFIDDeviceName As String
    Get
    Set
'Usage
Dim instance As HardwareProfile
Dim value As String

value = instance.RFIDDeviceName

instance.RFIDDeviceName = value
```

``` csharp
[ColumnAttribute("RFIDDEVICENAME")]
[DataMemberAttribute]
public string RFIDDeviceName { get; set; }
```

``` c++
[ColumnAttribute(L"RFIDDEVICENAME")]
[DataMemberAttribute]
public:
property String^ RFIDDeviceName {
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

