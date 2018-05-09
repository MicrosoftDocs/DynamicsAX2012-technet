---
title: DeviceConfiguration.SelectHardwareStationOnTendering Property  (Microsoft.Dynamics.Commerce.Runtime.DataModel)
TOCTitle: SelectHardwareStationOnTendering Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.DataModel.DeviceConfiguration.SelectHardwareStationOnTendering
ms:mtpsurl: https://technet.microsoft.com/en-us/library/microsoft.dynamics.commerce.runtime.datamodel.deviceconfiguration.selecthardwarestationontendering(v=AX.60)
ms:contentKeyID: 65317388
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataModel.DeviceConfiguration.SelectHardwareStationOnTendering
dev_langs:
- CSharp
- C++
- VB
---

# SelectHardwareStationOnTendering Property

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataModel](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Entities (in Microsoft.Dynamics.Commerce.Runtime.Entities.dll)

## Syntax

``` vb
'Declaration
<ColumnAttribute("SELECTHARDWARESTATIONONTENDERING")> _
<DataMemberAttribute> _
Public Property SelectHardwareStationOnTendering As Boolean
    Get
    Set
'Usage
Dim instance As DeviceConfiguration
Dim value As Boolean

value = instance.SelectHardwareStationOnTendering

instance.SelectHardwareStationOnTendering = value
```

``` csharp
[ColumnAttribute("SELECTHARDWARESTATIONONTENDERING")]
[DataMemberAttribute]
public bool SelectHardwareStationOnTendering { get; set; }
```

``` c++
[ColumnAttribute(L"SELECTHARDWARESTATIONONTENDERING")]
[DataMemberAttribute]
public:
property bool SelectHardwareStationOnTendering {
    bool get ();
    void set (bool value);
}
```

#### Property Value

Type: [System.Boolean](https://technet.microsoft.com/en-us/library/a28wyd50\(v=ax.60\))  

## See Also

#### Reference

[DeviceConfiguration Class](deviceconfiguration-class-microsoft-dynamics-commerce-runtime-datamodel.md)

[Microsoft.Dynamics.Commerce.Runtime.DataModel Namespace](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)

