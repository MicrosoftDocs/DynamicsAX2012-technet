---
title: ChannelConfiguration.ChannelCountryRegionISOCode Property  (Microsoft.Dynamics.Commerce.Runtime.DataModel)
TOCTitle: ChannelCountryRegionISOCode Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.DataModel.ChannelConfiguration.ChannelCountryRegionISOCode
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.datamodel.channelconfiguration.channelcountryregionisocode(v=AX.60)
ms:contentKeyID: 62207245
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataModel.ChannelConfiguration.ChannelCountryRegionISOCode
dev_langs:
- CSharp
- C++
- VB
---

# ChannelCountryRegionISOCode Property

Gets the country/region ISO code of the current channel.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataModel](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Entities (in Microsoft.Dynamics.Commerce.Runtime.Entities.dll)

## Syntax

``` vb
'Declaration
<ColumnAttribute("COUNTRYREGIONISOCODE")> _
<DataMemberAttribute> _
Public Property ChannelCountryRegionISOCode As String
    Get
    Friend Set
'Usage
Dim instance As ChannelConfiguration
Dim value As String

value = instance.ChannelCountryRegionISOCode
```

``` csharp
[ColumnAttribute("COUNTRYREGIONISOCODE")]
[DataMemberAttribute]
public string ChannelCountryRegionISOCode { get; internal set; }
```

``` c++
[ColumnAttribute(L"COUNTRYREGIONISOCODE")]
[DataMemberAttribute]
public:
property String^ ChannelCountryRegionISOCode {
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

