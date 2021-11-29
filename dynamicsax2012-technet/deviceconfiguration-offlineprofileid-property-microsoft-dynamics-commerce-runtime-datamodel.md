---
title: DeviceConfiguration.OfflineProfileId Property  (Microsoft.Dynamics.Commerce.Runtime.DataModel)
TOCTitle: OfflineProfileId Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.DataModel.DeviceConfiguration.OfflineProfileId
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.datamodel.deviceconfiguration.offlineprofileid(v=AX.60)
ms:contentKeyID: 65319665
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataModel.DeviceConfiguration.OfflineProfileId
dev_langs:
- CSharp
- C++
- VB
---

# OfflineProfileId Property


[!INCLUDE[archive-banner](includes/archive-banner.md)]

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataModel](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Entities (in Microsoft.Dynamics.Commerce.Runtime.Entities.dll)

## Syntax

``` vb
'Declaration
<DataMemberAttribute> _
<ColumnAttribute("OFFLINEPROFILE")> _
Public Property OfflineProfileId As Long
    Get
    Set
'Usage
Dim instance As DeviceConfiguration
Dim value As Long

value = instance.OfflineProfileId

instance.OfflineProfileId = value
```

``` csharp
[DataMemberAttribute]
[ColumnAttribute("OFFLINEPROFILE")]
public long OfflineProfileId { get; set; }
```

``` c++
[DataMemberAttribute]
[ColumnAttribute(L"OFFLINEPROFILE")]
public:
property long long OfflineProfileId {
    long long get ();
    void set (long long value);
}
```

#### Property Value

Type: [System.Int64](https://technet.microsoft.com/library/6yy583ek\(v=ax.60\))  

## See Also

#### Reference

[DeviceConfiguration Class](deviceconfiguration-class-microsoft-dynamics-commerce-runtime-datamodel.md)

[Microsoft.Dynamics.Commerce.Runtime.DataModel Namespace](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)

