---
title: DeviceConfiguration.Theme Property  (Microsoft.Dynamics.Commerce.Runtime.DataModel)
TOCTitle: Theme Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.DataModel.DeviceConfiguration.Theme
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.datamodel.deviceconfiguration.theme(v=AX.60)
ms:contentKeyID: 62213203
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataModel.DeviceConfiguration.Theme
dev_langs:
- CSharp
- C++
- VB
---

# Theme Property


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Gets or sets the value of theme.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataModel](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Entities (in Microsoft.Dynamics.Commerce.Runtime.Entities.dll)

## Syntax

``` vb
'Declaration
<ColumnAttribute("POSSKINNAME")> _
<DataMemberAttribute> _
Public Property Theme As String
    Get
    Set
'Usage
Dim instance As DeviceConfiguration
Dim value As String

value = instance.Theme

instance.Theme = value
```

``` csharp
[ColumnAttribute("POSSKINNAME")]
[DataMemberAttribute]
public string Theme { get; set; }
```

``` c++
[ColumnAttribute(L"POSSKINNAME")]
[DataMemberAttribute]
public:
property String^ Theme {
    String^ get ();
    void set (String^ value);
}
```

#### Property Value

Type: [System.String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\))  
Returns [String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\)).  

## See Also

#### Reference

[DeviceConfiguration Class](deviceconfiguration-class-microsoft-dynamics-commerce-runtime-datamodel.md)

[Microsoft.Dynamics.Commerce.Runtime.DataModel Namespace](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)

