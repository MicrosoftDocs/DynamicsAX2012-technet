---
title: ChannelConfiguration.TimeZoneCode Property  (Microsoft.Dynamics.Commerce.Runtime.DataModel)
TOCTitle: TimeZoneCode Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.DataModel.ChannelConfiguration.TimeZoneCode
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.datamodel.channelconfiguration.timezonecode(v=AX.60)
ms:contentKeyID: 65322112
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataModel.ChannelConfiguration.TimeZoneCode
dev_langs:
- CSharp
- C++
- VB
---

# TimeZoneCode Property

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataModel](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Entities (in Microsoft.Dynamics.Commerce.Runtime.Entities.dll)

## Syntax

``` vb
'Declaration
<DataMemberAttribute> _
<ColumnAttribute("TIMEZONECODE")> _
Public Property TimeZoneCode As Integer
    Get
    Friend Set
'Usage
Dim instance As ChannelConfiguration
Dim value As Integer

value = instance.TimeZoneCode
```

``` csharp
[DataMemberAttribute]
[ColumnAttribute("TIMEZONECODE")]
public int TimeZoneCode { get; internal set; }
```

``` c++
[DataMemberAttribute]
[ColumnAttribute(L"TIMEZONECODE")]
public:
property int TimeZoneCode {
    int get ();
    internal: void set (int value);
}
```

#### Property Value

Type: [System.Int32](https://technet.microsoft.com/library/td2s409d\(v=ax.60\))  

## See Also

#### Reference

[ChannelConfiguration Class](channelconfiguration-class-microsoft-dynamics-commerce-runtime-datamodel.md)

[Microsoft.Dynamics.Commerce.Runtime.DataModel Namespace](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)

