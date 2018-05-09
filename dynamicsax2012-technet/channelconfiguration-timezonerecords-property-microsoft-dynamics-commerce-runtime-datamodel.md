---
title: ChannelConfiguration.TimeZoneRecords Property  (Microsoft.Dynamics.Commerce.Runtime.DataModel)
TOCTitle: TimeZoneRecords Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.DataModel.ChannelConfiguration.TimeZoneRecords
ms:mtpsurl: https://technet.microsoft.com/en-us/library/microsoft.dynamics.commerce.runtime.datamodel.channelconfiguration.timezonerecords(v=AX.60)
ms:contentKeyID: 65321543
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataModel.ChannelConfiguration.TimeZoneRecords
dev_langs:
- CSharp
- C++
- VB
---

# TimeZoneRecords Property

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataModel](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Entities (in Microsoft.Dynamics.Commerce.Runtime.Entities.dll)

## Syntax

``` vb
'Declaration
<IgnoreDataMemberAttribute> _
Public Property TimeZoneRecords As List(Of TimeZoneInterval)
    Get
    Set
'Usage
Dim instance As ChannelConfiguration
Dim value As List(Of TimeZoneInterval)

value = instance.TimeZoneRecords

instance.TimeZoneRecords = value
```

``` csharp
[IgnoreDataMemberAttribute]
public List<TimeZoneInterval> TimeZoneRecords { get; set; }
```

``` c++
[IgnoreDataMemberAttribute]
public:
property List<TimeZoneInterval^>^ TimeZoneRecords {
    List<TimeZoneInterval^>^ get ();
    void set (List<TimeZoneInterval^>^ value);
}
```

#### Property Value

Type: [System.Collections.Generic.List](https://technet.microsoft.com/en-us/library/6sh2ey19\(v=ax.60\))\<[TimeZoneInterval](timezoneinterval-class-microsoft-dynamics-commerce-runtime-datamodel.md)\>  

## See Also

#### Reference

[ChannelConfiguration Class](channelconfiguration-class-microsoft-dynamics-commerce-runtime-datamodel.md)

[Microsoft.Dynamics.Commerce.Runtime.DataModel Namespace](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)

