---
title: DeviceConfiguration.OpenDrawerAtLogOnLogOff Property  (Microsoft.Dynamics.Commerce.Runtime.DataModel)
TOCTitle: OpenDrawerAtLogOnLogOff Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.DataModel.DeviceConfiguration.OpenDrawerAtLogOnLogOff
ms:mtpsurl: https://technet.microsoft.com/en-us/library/microsoft.dynamics.commerce.runtime.datamodel.deviceconfiguration.opendraweratlogonlogoff(v=AX.60)
ms:contentKeyID: 62210975
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataModel.DeviceConfiguration.OpenDrawerAtLogOnLogOff
dev_langs:
- CSharp
- C++
- VB
---

# OpenDrawerAtLogOnLogOff Property

Gets or sets a value indicating whether open drawer at login logout is enabled.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataModel](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Entities (in Microsoft.Dynamics.Commerce.Runtime.Entities.dll)

## Syntax

``` vb
'Declaration
<DataMemberAttribute> _
<ColumnAttribute("OPENDRAWERATLILO")> _
Public Property OpenDrawerAtLogOnLogOff As Boolean
    Get
    Set
'Usage
Dim instance As DeviceConfiguration
Dim value As Boolean

value = instance.OpenDrawerAtLogOnLogOff

instance.OpenDrawerAtLogOnLogOff = value
```

``` csharp
[DataMemberAttribute]
[ColumnAttribute("OPENDRAWERATLILO")]
public bool OpenDrawerAtLogOnLogOff { get; set; }
```

``` c++
[DataMemberAttribute]
[ColumnAttribute(L"OPENDRAWERATLILO")]
public:
property bool OpenDrawerAtLogOnLogOff {
    bool get ();
    void set (bool value);
}
```

#### Property Value

Type: [System.Boolean](https://technet.microsoft.com/en-us/library/a28wyd50\(v=ax.60\))  
The value true if open drawer at login logout is enabled; otherwise, false.  

## See Also

#### Reference

[DeviceConfiguration Class](deviceconfiguration-class-microsoft-dynamics-commerce-runtime-datamodel.md)

[Microsoft.Dynamics.Commerce.Runtime.DataModel Namespace](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)

