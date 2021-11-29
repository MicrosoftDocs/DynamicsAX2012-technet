---
title: ChannelConfiguration.CountryRegionId Property  (Microsoft.Dynamics.Commerce.Runtime.DataModel)
TOCTitle: CountryRegionId Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.DataModel.ChannelConfiguration.CountryRegionId
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.datamodel.channelconfiguration.countryregionid(v=AX.60)
ms:contentKeyID: 49833424
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataModel.ChannelConfiguration.CountryRegionId
dev_langs:
- CSharp
- C++
- VB
---

# CountryRegionId Property


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Gets the country/region identifier of the current channel.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataModel](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Entities (in Microsoft.Dynamics.Commerce.Runtime.Entities.dll)

## Syntax

``` vb
'Declaration
<DataMemberAttribute> _
<ColumnAttribute("COUNTRYREGIONID")> _
Public Property CountryRegionId As String
    Get
    Friend Set
'Usage
Dim instance As ChannelConfiguration
Dim value As String

value = instance.CountryRegionId
```

``` csharp
[DataMemberAttribute]
[ColumnAttribute("COUNTRYREGIONID")]
public string CountryRegionId { get; internal set; }
```

``` c++
[DataMemberAttribute]
[ColumnAttribute(L"COUNTRYREGIONID")]
public:
property String^ CountryRegionId {
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

