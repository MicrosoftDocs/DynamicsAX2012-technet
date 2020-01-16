---
title: DeviceConfiguration.ReconnectToOnlineInterval Property  (Microsoft.Dynamics.Commerce.Runtime.DataModel)
TOCTitle: ReconnectToOnlineInterval Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.DataModel.DeviceConfiguration.ReconnectToOnlineInterval
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.datamodel.deviceconfiguration.reconnecttoonlineinterval(v=AX.60)
ms:contentKeyID: 65322467
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataModel.DeviceConfiguration.ReconnectToOnlineInterval
dev_langs:
- CSharp
- C++
- VB
---

# ReconnectToOnlineInterval Property

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataModel](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Entities (in Microsoft.Dynamics.Commerce.Runtime.Entities.dll)

## Syntax

``` vb
'Declaration
<ColumnAttribute("RECONNECTINTERVAL")> _
<DataMemberAttribute> _
Public Property ReconnectToOnlineInterval As Integer
    Get
    Set
'Usage
Dim instance As DeviceConfiguration
Dim value As Integer

value = instance.ReconnectToOnlineInterval

instance.ReconnectToOnlineInterval = value
```

``` csharp
[ColumnAttribute("RECONNECTINTERVAL")]
[DataMemberAttribute]
public int ReconnectToOnlineInterval { get; set; }
```

``` c++
[ColumnAttribute(L"RECONNECTINTERVAL")]
[DataMemberAttribute]
public:
property int ReconnectToOnlineInterval {
    int get ();
    void set (int value);
}
```

#### Property Value

Type: [System.Int32](https://technet.microsoft.com/library/td2s409d\(v=ax.60\))  

## See Also

#### Reference

[DeviceConfiguration Class](deviceconfiguration-class-microsoft-dynamics-commerce-runtime-datamodel.md)

[Microsoft.Dynamics.Commerce.Runtime.DataModel Namespace](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)

