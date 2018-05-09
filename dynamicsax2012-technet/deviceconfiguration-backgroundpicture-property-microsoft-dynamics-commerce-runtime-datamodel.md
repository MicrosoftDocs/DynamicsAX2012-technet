---
title: DeviceConfiguration.BackgroundPicture Property  (Microsoft.Dynamics.Commerce.Runtime.DataModel)
TOCTitle: BackgroundPicture Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.DataModel.DeviceConfiguration.BackgroundPicture
ms:mtpsurl: https://technet.microsoft.com/en-us/library/microsoft.dynamics.commerce.runtime.datamodel.deviceconfiguration.backgroundpicture(v=AX.60)
ms:contentKeyID: 65322071
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataModel.DeviceConfiguration.BackgroundPicture
dev_langs:
- CSharp
- C++
- VB
---

# BackgroundPicture Property

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataModel](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Entities (in Microsoft.Dynamics.Commerce.Runtime.Entities.dll)

## Syntax

``` vb
'Declaration
<IgnoreDataMemberAttribute> _
<ColumnAttribute("BACKGROUNDPICTURE")> _
Public Property BackgroundPicture As Byte()
    Get
    Set
'Usage
Dim instance As DeviceConfiguration
Dim value As Byte()

value = instance.BackgroundPicture

instance.BackgroundPicture = value
```

``` csharp
[IgnoreDataMemberAttribute]
[ColumnAttribute("BACKGROUNDPICTURE")]
public byte[] BackgroundPicture { get; set; }
```

``` c++
[IgnoreDataMemberAttribute]
[ColumnAttribute(L"BACKGROUNDPICTURE")]
public:
property array<unsigned char>^ BackgroundPicture {
    array<unsigned char>^ get ();
    void set (array<unsigned char>^ value);
}
```

#### Property Value

Type: [System.Byte](https://technet.microsoft.com/en-us/library/yyb1w04y\(v=ax.60\))\[\]  

## See Also

#### Reference

[DeviceConfiguration Class](deviceconfiguration-class-microsoft-dynamics-commerce-runtime-datamodel.md)

[Microsoft.Dynamics.Commerce.Runtime.DataModel Namespace](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)

