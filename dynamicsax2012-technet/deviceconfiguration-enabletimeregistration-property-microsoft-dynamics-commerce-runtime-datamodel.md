---
title: DeviceConfiguration.EnableTimeRegistration Property  (Microsoft.Dynamics.Commerce.Runtime.DataModel)
TOCTitle: EnableTimeRegistration Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.DataModel.DeviceConfiguration.EnableTimeRegistration
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.datamodel.deviceconfiguration.enabletimeregistration(v=AX.60)
ms:contentKeyID: 62213458
author: tonyafehr
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataModel.DeviceConfiguration.EnableTimeRegistration
dev_langs:
- CSharp
- C++
- VB
---

# EnableTimeRegistration Property


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Gets or sets a value indicating whether time registration is enabled.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataModel](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Entities (in Microsoft.Dynamics.Commerce.Runtime.Entities.dll)

## Syntax

``` vb
'Declaration
<DataMemberAttribute> _
<ColumnAttribute("TAENABLEREGISTRATION")> _
Public Property EnableTimeRegistration As Boolean
    Get
    Set
'Usage
Dim instance As DeviceConfiguration
Dim value As Boolean

value = instance.EnableTimeRegistration

instance.EnableTimeRegistration = value
```

``` csharp
[DataMemberAttribute]
[ColumnAttribute("TAENABLEREGISTRATION")]
public bool EnableTimeRegistration { get; set; }
```

``` c++
[DataMemberAttribute]
[ColumnAttribute(L"TAENABLEREGISTRATION")]
public:
property bool EnableTimeRegistration {
    bool get ();
    void set (bool value);
}
```

#### Property Value

Type: [System.Boolean](https://technet.microsoft.com/library/a28wyd50\(v=ax.60\))  
The value true if time registration is enabled; otherwise, false.  

## See Also

#### Reference

[DeviceConfiguration Class](deviceconfiguration-class-microsoft-dynamics-commerce-runtime-datamodel.md)

[Microsoft.Dynamics.Commerce.Runtime.DataModel Namespace](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)

