---
title: DeviceConfiguration.SwitchToOfflineTimeout Property  (Microsoft.Dynamics.Commerce.Runtime.DataModel)
TOCTitle: SwitchToOfflineTimeout Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.DataModel.DeviceConfiguration.SwitchToOfflineTimeout
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.datamodel.deviceconfiguration.switchtoofflinetimeout(v=AX.60)
ms:contentKeyID: 65320531
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataModel.DeviceConfiguration.SwitchToOfflineTimeout
dev_langs:
- CSharp
- C++
- VB
---

# SwitchToOfflineTimeout Property

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataModel](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Entities (in Microsoft.Dynamics.Commerce.Runtime.Entities.dll)

## Syntax

``` vb
'Declaration
<DataMemberAttribute> _
<ColumnAttribute("OFFLINETIMEOUT")> _
Public Property SwitchToOfflineTimeout As Integer
    Get
    Set
'Usage
Dim instance As DeviceConfiguration
Dim value As Integer

value = instance.SwitchToOfflineTimeout

instance.SwitchToOfflineTimeout = value
```

``` csharp
[DataMemberAttribute]
[ColumnAttribute("OFFLINETIMEOUT")]
public int SwitchToOfflineTimeout { get; set; }
```

``` c++
[DataMemberAttribute]
[ColumnAttribute(L"OFFLINETIMEOUT")]
public:
property int SwitchToOfflineTimeout {
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

