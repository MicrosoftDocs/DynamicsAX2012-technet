---
title: HardwareProfile.MsrDeviceDescription Property  (Microsoft.Dynamics.Commerce.Runtime.DataModel)
TOCTitle: MsrDeviceDescription Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.DataModel.HardwareProfile.MSRDeviceDescription
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.datamodel.hardwareprofile.msrdevicedescription(v=AX.60)
ms:contentKeyID: 62211947
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataModel.HardwareProfile.MsrDeviceDescription
dev_langs:
- CSharp
- C++
- VB
---

# MsrDeviceDescription Property


[!INCLUDE[archive-banner](includes/archive-banner.md)]

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataModel](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Entities (in Microsoft.Dynamics.Commerce.Runtime.Entities.dll)

## Syntax

``` vb
'Declaration
<DataMemberAttribute> _
<ColumnAttribute("MSRDESCRIPTION")> _
Public Property MsrDeviceDescription As String
    Get
    Set
'Usage
Dim instance As HardwareProfile
Dim value As String

value = instance.MsrDeviceDescription

instance.MsrDeviceDescription = value
```

``` csharp
[DataMemberAttribute]
[ColumnAttribute("MSRDESCRIPTION")]
public string MsrDeviceDescription { get; set; }
```

``` c++
[DataMemberAttribute]
[ColumnAttribute(L"MSRDESCRIPTION")]
public:
property String^ MsrDeviceDescription {
    String^ get ();
    void set (String^ value);
}
```

#### Property Value

Type: [System.String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\))  

## See Also

#### Reference

[HardwareProfile Class](hardwareprofile-class-microsoft-dynamics-commerce-runtime-datamodel.md)

[Microsoft.Dynamics.Commerce.Runtime.DataModel Namespace](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)

