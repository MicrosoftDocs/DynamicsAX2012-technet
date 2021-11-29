---
title: HardwareProfile.ScaleDeviceName Property  (Microsoft.Dynamics.Commerce.Runtime.DataModel)
TOCTitle: ScaleDeviceName Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.DataModel.HardwareProfile.ScaleDeviceName
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.datamodel.hardwareprofile.scaledevicename(v=AX.60)
ms:contentKeyID: 62213167
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataModel.HardwareProfile.ScaleDeviceName
dev_langs:
- CSharp
- C++
- VB
---

# ScaleDeviceName Property


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Gets or sets the scale device name.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataModel](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Entities (in Microsoft.Dynamics.Commerce.Runtime.Entities.dll)

## Syntax

``` vb
'Declaration
<DataMemberAttribute> _
<ColumnAttribute("SCALEDEVICENAME")> _
Public Property ScaleDeviceName As String
    Get
    Set
'Usage
Dim instance As HardwareProfile
Dim value As String

value = instance.ScaleDeviceName

instance.ScaleDeviceName = value
```

``` csharp
[DataMemberAttribute]
[ColumnAttribute("SCALEDEVICENAME")]
public string ScaleDeviceName { get; set; }
```

``` c++
[DataMemberAttribute]
[ColumnAttribute(L"SCALEDEVICENAME")]
public:
property String^ ScaleDeviceName {
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

