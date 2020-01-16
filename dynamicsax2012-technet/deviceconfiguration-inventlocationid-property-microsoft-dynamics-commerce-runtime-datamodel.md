---
title: DeviceConfiguration.InventLocationId Property  (Microsoft.Dynamics.Commerce.Runtime.DataModel)
TOCTitle: InventLocationId Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.DataModel.DeviceConfiguration.InventLocationId
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.datamodel.deviceconfiguration.inventlocationid(v=AX.60)
ms:contentKeyID: 62201816
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataModel.DeviceConfiguration.InventLocationId
dev_langs:
- CSharp
- C++
- VB
---

# InventLocationId Property

Gets or sets the inventory location id.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataModel](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Entities (in Microsoft.Dynamics.Commerce.Runtime.Entities.dll)

## Syntax

``` vb
'Declaration
<DataMemberAttribute> _
<ColumnAttribute("INVENTLOCATION")> _
Public Property InventLocationId As String
    Get
    Set
'Usage
Dim instance As DeviceConfiguration
Dim value As String

value = instance.InventLocationId

instance.InventLocationId = value
```

``` csharp
[DataMemberAttribute]
[ColumnAttribute("INVENTLOCATION")]
public string InventLocationId { get; set; }
```

``` c++
[DataMemberAttribute]
[ColumnAttribute(L"INVENTLOCATION")]
public:
property String^ InventLocationId {
    String^ get ();
    void set (String^ value);
}
```

#### Property Value

Type: [System.String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\))  
The string containing the inventory location id.  

## See Also

#### Reference

[DeviceConfiguration Class](deviceconfiguration-class-microsoft-dynamics-commerce-runtime-datamodel.md)

[Microsoft.Dynamics.Commerce.Runtime.DataModel Namespace](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)

