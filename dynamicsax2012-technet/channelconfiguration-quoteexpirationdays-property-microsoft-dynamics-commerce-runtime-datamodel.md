---
title: ChannelConfiguration.QuoteExpirationDays Property  (Microsoft.Dynamics.Commerce.Runtime.DataModel)
TOCTitle: QuoteExpirationDays Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.DataModel.ChannelConfiguration.QuoteExpirationDays
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.datamodel.channelconfiguration.quoteexpirationdays(v=AX.60)
ms:contentKeyID: 62214268
author: Khairunj
ms.author: daxcpft
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataModel.ChannelConfiguration.QuoteExpirationDays
dev_langs:
- CSharp
- C++
- VB
---

# QuoteExpirationDays Property

Gets the number of days a quote is valid after its creation.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataModel](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Entities (in Microsoft.Dynamics.Commerce.Runtime.Entities.dll)

## Syntax

``` vb
'Declaration
<DataMemberAttribute> _
<ColumnAttribute("QUOTEEXPIRATIONDAYS")> _
Public Property QuoteExpirationDays As Integer
    Get
    Friend Set
'Usage
Dim instance As ChannelConfiguration
Dim value As Integer

value = instance.QuoteExpirationDays
```

``` csharp
[DataMemberAttribute]
[ColumnAttribute("QUOTEEXPIRATIONDAYS")]
public int QuoteExpirationDays { get; internal set; }
```

``` c++
[DataMemberAttribute]
[ColumnAttribute(L"QUOTEEXPIRATIONDAYS")]
public:
property int QuoteExpirationDays {
    int get ();
    internal: void set (int value);
}
```

#### Property Value

Type: [System.Int32](https://technet.microsoft.com/library/td2s409d\(v=ax.60\))  
Returns [Int32](https://technet.microsoft.com/library/td2s409d\(v=ax.60\)).  

## See Also

#### Reference

[ChannelConfiguration Class](channelconfiguration-class-microsoft-dynamics-commerce-runtime-datamodel.md)

[Microsoft.Dynamics.Commerce.Runtime.DataModel Namespace](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)

