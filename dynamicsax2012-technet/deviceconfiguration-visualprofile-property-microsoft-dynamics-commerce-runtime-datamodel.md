---
title: DeviceConfiguration.VisualProfile Property  (Microsoft.Dynamics.Commerce.Runtime.DataModel)
TOCTitle: VisualProfile Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.DataModel.DeviceConfiguration.VisualProfile
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.datamodel.deviceconfiguration.visualprofile(v=AX.60)
ms:contentKeyID: 62210824
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataModel.DeviceConfiguration.VisualProfile
dev_langs:
- CSharp
- C++
- VB
---

# VisualProfile Property


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Gets or sets the visual profile.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataModel](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Entities (in Microsoft.Dynamics.Commerce.Runtime.Entities.dll)

## Syntax

``` vb
'Declaration
<DataMemberAttribute> _
<ColumnAttribute("VISUALPROFILE")> _
Public Property VisualProfile As String
    Get
    Set
'Usage
Dim instance As DeviceConfiguration
Dim value As String

value = instance.VisualProfile

instance.VisualProfile = value
```

``` csharp
[DataMemberAttribute]
[ColumnAttribute("VISUALPROFILE")]
public string VisualProfile { get; set; }
```

``` c++
[DataMemberAttribute]
[ColumnAttribute(L"VISUALPROFILE")]
public:
property String^ VisualProfile {
    String^ get ();
    void set (String^ value);
}
```

#### Property Value

Type: [System.String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\))  
The string containing the visual profile.  

## See Also

#### Reference

[DeviceConfiguration Class](deviceconfiguration-class-microsoft-dynamics-commerce-runtime-datamodel.md)

[Microsoft.Dynamics.Commerce.Runtime.DataModel Namespace](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)

