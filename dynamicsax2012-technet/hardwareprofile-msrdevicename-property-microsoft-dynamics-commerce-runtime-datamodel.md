---
title: HardwareProfile.MsrDeviceName Property  (Microsoft.Dynamics.Commerce.Runtime.DataModel)
TOCTitle: MsrDeviceName Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.DataModel.HardwareProfile.MSRDeviceName
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.datamodel.hardwareprofile.msrdevicename(v=AX.60)
ms:contentKeyID: 62213258
author: tonyafehr
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataModel.HardwareProfile.MsrDeviceName
dev_langs:
- CSharp
- C++
- VB
---

# MsrDeviceName Property


[!INCLUDE[archive-banner](includes/archive-banner.md)]

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataModel](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Entities (in Microsoft.Dynamics.Commerce.Runtime.Entities.dll)

## Syntax

``` vb
'Declaration
<DataMemberAttribute> _
<ColumnAttribute("MSRDEVICENAME")> _
Public Property MsrDeviceName As String
    Get
    Set
'Usage
Dim instance As HardwareProfile
Dim value As String

value = instance.MsrDeviceName

instance.MsrDeviceName = value
```

``` csharp
[DataMemberAttribute]
[ColumnAttribute("MSRDEVICENAME")]
public string MsrDeviceName { get; set; }
```

``` c++
[DataMemberAttribute]
[ColumnAttribute(L"MSRDEVICENAME")]
public:
property String^ MsrDeviceName {
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

