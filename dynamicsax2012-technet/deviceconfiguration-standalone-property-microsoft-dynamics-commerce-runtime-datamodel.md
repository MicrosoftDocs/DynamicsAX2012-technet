---
title: DeviceConfiguration.StandAlone Property  (Microsoft.Dynamics.Commerce.Runtime.DataModel)
TOCTitle: StandAlone Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.DataModel.DeviceConfiguration.StandAlone
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.datamodel.deviceconfiguration.standalone(v=AX.60)
ms:contentKeyID: 62213146
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataModel.DeviceConfiguration.StandAlone
dev_langs:
- CSharp
- C++
- VB
---

# StandAlone Property


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Gets or sets a value indicating whether stand alone is enabled.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataModel](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Entities (in Microsoft.Dynamics.Commerce.Runtime.Entities.dll)

## Syntax

``` vb
'Declaration
<ColumnAttribute("STANDALONE")> _
<DataMemberAttribute> _
Public Property StandAlone As Boolean
    Get
    Set
'Usage
Dim instance As DeviceConfiguration
Dim value As Boolean

value = instance.StandAlone

instance.StandAlone = value
```

``` csharp
[ColumnAttribute("STANDALONE")]
[DataMemberAttribute]
public bool StandAlone { get; set; }
```

``` c++
[ColumnAttribute(L"STANDALONE")]
[DataMemberAttribute]
public:
property bool StandAlone {
    bool get ();
    void set (bool value);
}
```

#### Property Value

Type: [System.Boolean](https://technet.microsoft.com/library/a28wyd50\(v=ax.60\))  
The value true if stand alone is enabled; otherwise, false.  

## See Also

#### Reference

[DeviceConfiguration Class](deviceconfiguration-class-microsoft-dynamics-commerce-runtime-datamodel.md)

[Microsoft.Dynamics.Commerce.Runtime.DataModel Namespace](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)

