---
title: HardwareProfile.LineDisplayDeviceName Property  (Microsoft.Dynamics.Commerce.Runtime.DataModel)
TOCTitle: LineDisplayDeviceName Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.DataModel.HardwareProfile.LineDisplayDeviceName
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.datamodel.hardwareprofile.linedisplaydevicename(v=AX.60)
ms:contentKeyID: 62213288
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataModel.HardwareProfile.LineDisplayDeviceName
dev_langs:
- CSharp
- C++
- VB
---

# LineDisplayDeviceName Property

Gets or sets the line display device name value.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataModel](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Entities (in Microsoft.Dynamics.Commerce.Runtime.Entities.dll)

## Syntax

``` vb
'Declaration
<ColumnAttribute("DISPLAYDEVICENAME")> _
<DataMemberAttribute> _
Public Property LineDisplayDeviceName As String
    Get
    Set
'Usage
Dim instance As HardwareProfile
Dim value As String

value = instance.LineDisplayDeviceName

instance.LineDisplayDeviceName = value
```

``` csharp
[ColumnAttribute("DISPLAYDEVICENAME")]
[DataMemberAttribute]
public string LineDisplayDeviceName { get; set; }
```

``` c++
[ColumnAttribute(L"DISPLAYDEVICENAME")]
[DataMemberAttribute]
public:
property String^ LineDisplayDeviceName {
    String^ get ();
    void set (String^ value);
}
```

#### Property Value

Type: [System.String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\))  
The display name.  

## See Also

#### Reference

[HardwareProfile Class](hardwareprofile-class-microsoft-dynamics-commerce-runtime-datamodel.md)

[Microsoft.Dynamics.Commerce.Runtime.DataModel Namespace](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)

