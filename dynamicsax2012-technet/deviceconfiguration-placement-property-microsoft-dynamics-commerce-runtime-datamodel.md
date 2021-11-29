---
title: DeviceConfiguration.Placement Property  (Microsoft.Dynamics.Commerce.Runtime.DataModel)
TOCTitle: Placement Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.DataModel.DeviceConfiguration.Placement
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.datamodel.deviceconfiguration.placement(v=AX.60)
ms:contentKeyID: 62209322
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataModel.DeviceConfiguration.Placement
dev_langs:
- CSharp
- C++
- VB
---

# Placement Property


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Gets or sets the terminal placement.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataModel](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Entities (in Microsoft.Dynamics.Commerce.Runtime.Entities.dll)

## Syntax

``` vb
'Declaration
<ColumnAttribute("LOCATION")> _
<DataMemberAttribute> _
Public Property Placement As String
    Get
    Set
'Usage
Dim instance As DeviceConfiguration
Dim value As String

value = instance.Placement

instance.Placement = value
```

``` csharp
[ColumnAttribute("LOCATION")]
[DataMemberAttribute]
public string Placement { get; set; }
```

``` c++
[ColumnAttribute(L"LOCATION")]
[DataMemberAttribute]
public:
property String^ Placement {
    String^ get ();
    void set (String^ value);
}
```

#### Property Value

Type: [System.String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\))  
The string containing the terminal placement.  

## See Also

#### Reference

[DeviceConfiguration Class](deviceconfiguration-class-microsoft-dynamics-commerce-runtime-datamodel.md)

[Microsoft.Dynamics.Commerce.Runtime.DataModel Namespace](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)

