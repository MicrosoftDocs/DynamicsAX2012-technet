---
title: DeviceConfiguration.AccentColor Property  (Microsoft.Dynamics.Commerce.Runtime.DataModel)
TOCTitle: AccentColor Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.DataModel.DeviceConfiguration.AccentColor
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.datamodel.deviceconfiguration.accentcolor(v=AX.60)
ms:contentKeyID: 62209298
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataModel.DeviceConfiguration.AccentColor
dev_langs:
- CSharp
- C++
- VB
---

# AccentColor Property


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Gets or sets the value of accent color.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataModel](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Entities (in Microsoft.Dynamics.Commerce.Runtime.Entities.dll)

## Syntax

``` vb
'Declaration
<DataMemberAttribute> _
<ColumnAttribute("COLOR")> _
Public Property AccentColor As Integer
    Get
    Set
'Usage
Dim instance As DeviceConfiguration
Dim value As Integer

value = instance.AccentColor

instance.AccentColor = value
```

``` csharp
[DataMemberAttribute]
[ColumnAttribute("COLOR")]
public int AccentColor { get; set; }
```

``` c++
[DataMemberAttribute]
[ColumnAttribute(L"COLOR")]
public:
property int AccentColor {
    int get ();
    void set (int value);
}
```

#### Property Value

Type: [System.Int32](https://technet.microsoft.com/library/td2s409d\(v=ax.60\))  
Returns [Int32](https://technet.microsoft.com/library/td2s409d\(v=ax.60\)).  

## See Also

#### Reference

[DeviceConfiguration Class](deviceconfiguration-class-microsoft-dynamics-commerce-runtime-datamodel.md)

[Microsoft.Dynamics.Commerce.Runtime.DataModel Namespace](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)

