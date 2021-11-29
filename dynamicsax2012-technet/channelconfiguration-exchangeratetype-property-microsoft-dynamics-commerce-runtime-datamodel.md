---
title: ChannelConfiguration.ExchangeRateType Property  (Microsoft.Dynamics.Commerce.Runtime.DataModel)
TOCTitle: ExchangeRateType Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.DataModel.ChannelConfiguration.ExchangeRateType
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.datamodel.channelconfiguration.exchangeratetype(v=AX.60)
ms:contentKeyID: 49833842
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataModel.ChannelConfiguration.ExchangeRateType
dev_langs:
- CSharp
- C++
- VB
---

# ExchangeRateType Property


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Gets the exchange rate type.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataModel](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Entities (in Microsoft.Dynamics.Commerce.Runtime.Entities.dll)

## Syntax

``` vb
'Declaration
<DataMemberAttribute> _
<ColumnAttribute("EXCHANGERATETYPE")> _
Public Property ExchangeRateType As Long
    Get
    Friend Set
'Usage
Dim instance As ChannelConfiguration
Dim value As Long

value = instance.ExchangeRateType
```

``` csharp
[DataMemberAttribute]
[ColumnAttribute("EXCHANGERATETYPE")]
public long ExchangeRateType { get; internal set; }
```

``` c++
[DataMemberAttribute]
[ColumnAttribute(L"EXCHANGERATETYPE")]
public:
property long long ExchangeRateType {
    long long get ();
    internal: void set (long long value);
}
```

#### Property Value

Type: [System.Int64](https://technet.microsoft.com/library/6yy583ek\(v=ax.60\))  
Returns [Int64](https://technet.microsoft.com/library/6yy583ek\(v=ax.60\)).  

## See Also

#### Reference

[ChannelConfiguration Class](channelconfiguration-class-microsoft-dynamics-commerce-runtime-datamodel.md)

[Microsoft.Dynamics.Commerce.Runtime.DataModel Namespace](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)

