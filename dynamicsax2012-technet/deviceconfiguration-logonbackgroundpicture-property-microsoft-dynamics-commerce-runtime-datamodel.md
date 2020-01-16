---
title: DeviceConfiguration.LogOnBackgroundPicture Property  (Microsoft.Dynamics.Commerce.Runtime.DataModel)
TOCTitle: LogOnBackgroundPicture Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.DataModel.DeviceConfiguration.LogOnBackgroundPicture
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.datamodel.deviceconfiguration.logonbackgroundpicture(v=AX.60)
ms:contentKeyID: 65318268
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataModel.DeviceConfiguration.LogOnBackgroundPicture
dev_langs:
- CSharp
- C++
- VB
---

# LogOnBackgroundPicture Property

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataModel](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Entities (in Microsoft.Dynamics.Commerce.Runtime.Entities.dll)

## Syntax

``` vb
'Declaration
<IgnoreDataMemberAttribute> _
<ColumnAttribute("LOGONBACKGROUNDPICTURE")> _
Public Property LogOnBackgroundPicture As Byte()
    Get
    Set
'Usage
Dim instance As DeviceConfiguration
Dim value As Byte()

value = instance.LogOnBackgroundPicture

instance.LogOnBackgroundPicture = value
```

``` csharp
[IgnoreDataMemberAttribute]
[ColumnAttribute("LOGONBACKGROUNDPICTURE")]
public byte[] LogOnBackgroundPicture { get; set; }
```

``` c++
[IgnoreDataMemberAttribute]
[ColumnAttribute(L"LOGONBACKGROUNDPICTURE")]
public:
property array<unsigned char>^ LogOnBackgroundPicture {
    array<unsigned char>^ get ();
    void set (array<unsigned char>^ value);
}
```

#### Property Value

Type: [System.Byte](https://technet.microsoft.com/library/yyb1w04y\(v=ax.60\))\[\]  

## See Also

#### Reference

[DeviceConfiguration Class](deviceconfiguration-class-microsoft-dynamics-commerce-runtime-datamodel.md)

[Microsoft.Dynamics.Commerce.Runtime.DataModel Namespace](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)

