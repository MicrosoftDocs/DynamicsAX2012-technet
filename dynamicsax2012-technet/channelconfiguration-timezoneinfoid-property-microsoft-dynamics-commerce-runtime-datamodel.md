---
title: ChannelConfiguration.TimeZoneInfoId Property  (Microsoft.Dynamics.Commerce.Runtime.DataModel)
TOCTitle: TimeZoneInfoId Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.DataModel.ChannelConfiguration.TimeZoneInfoId
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.datamodel.channelconfiguration.timezoneinfoid(v=AX.60)
ms:contentKeyID: 62208192
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataModel.ChannelConfiguration.TimeZoneInfoId
dev_langs:
- CSharp
- C++
- VB
---

# TimeZoneInfoId Property


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Gets the time zone identifier.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataModel](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Entities (in Microsoft.Dynamics.Commerce.Runtime.Entities.dll)

## Syntax

``` vb
'Declaration
<ColumnAttribute("TIMEZONEINFOID")> _
<DataMemberAttribute> _
Public Property TimeZoneInfoId As String
    Get
    Friend Set
'Usage
Dim instance As ChannelConfiguration
Dim value As String

value = instance.TimeZoneInfoId
```

``` csharp
[ColumnAttribute("TIMEZONEINFOID")]
[DataMemberAttribute]
public string TimeZoneInfoId { get; internal set; }
```

``` c++
[ColumnAttribute(L"TIMEZONEINFOID")]
[DataMemberAttribute]
public:
property String^ TimeZoneInfoId {
    String^ get ();
    internal: void set (String^ value);
}
```

#### Property Value

Type: [System.String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\))  
Returns [String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\)).  

## See Also

#### Reference

[ChannelConfiguration Class](channelconfiguration-class-microsoft-dynamics-commerce-runtime-datamodel.md)

[Microsoft.Dynamics.Commerce.Runtime.DataModel Namespace](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)

