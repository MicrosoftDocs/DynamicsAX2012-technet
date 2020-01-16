---
title: HardwareProfile.RFIDDeviceDescription Property  (Microsoft.Dynamics.Commerce.Runtime.DataModel)
TOCTitle: RFIDDeviceDescription Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.DataModel.HardwareProfile.RFIDDeviceDescription
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.datamodel.hardwareprofile.rfiddevicedescription(v=AX.60)
ms:contentKeyID: 62210292
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataModel.HardwareProfile.RFIDDeviceDescription
dev_langs:
- CSharp
- C++
- VB
---

# RFIDDeviceDescription Property

Gets or sets the RFID device description.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataModel](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Entities (in Microsoft.Dynamics.Commerce.Runtime.Entities.dll)

## Syntax

``` vb
'Declaration
<DataMemberAttribute> _
<ColumnAttribute("RFIDDESCRIPTION")> _
Public Property RFIDDeviceDescription As String
    Get
    Set
'Usage
Dim instance As HardwareProfile
Dim value As String

value = instance.RFIDDeviceDescription

instance.RFIDDeviceDescription = value
```

``` csharp
[DataMemberAttribute]
[ColumnAttribute("RFIDDESCRIPTION")]
public string RFIDDeviceDescription { get; set; }
```

``` c++
[DataMemberAttribute]
[ColumnAttribute(L"RFIDDESCRIPTION")]
public:
property String^ RFIDDeviceDescription {
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

