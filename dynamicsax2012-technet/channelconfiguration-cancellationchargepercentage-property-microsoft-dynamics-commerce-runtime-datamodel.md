---
title: ChannelConfiguration.CancellationChargePercentage Property  (Microsoft.Dynamics.Commerce.Runtime.DataModel)
TOCTitle: CancellationChargePercentage Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.DataModel.ChannelConfiguration.CancellationChargePercentage
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.datamodel.channelconfiguration.cancellationchargepercentage(v=AX.60)
ms:contentKeyID: 62205378
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataModel.ChannelConfiguration.CancellationChargePercentage
dev_langs:
- CSharp
- C++
- VB
---

# CancellationChargePercentage Property

Gets the default cancellation charge percentage for a Customer Order.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataModel](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Entities (in Microsoft.Dynamics.Commerce.Runtime.Entities.dll)

## Syntax

``` vb
'Declaration
<ColumnAttribute("CANCELLATIONCHARGE")> _
<DataMemberAttribute> _
Public Property CancellationChargePercentage As Decimal
    Get
    Friend Set
'Usage
Dim instance As ChannelConfiguration
Dim value As Decimal

value = instance.CancellationChargePercentage
```

``` csharp
[ColumnAttribute("CANCELLATIONCHARGE")]
[DataMemberAttribute]
public decimal CancellationChargePercentage { get; internal set; }
```

``` c++
[ColumnAttribute(L"CANCELLATIONCHARGE")]
[DataMemberAttribute]
public:
property Decimal CancellationChargePercentage {
    Decimal get ();
    internal: void set (Decimal value);
}
```

#### Property Value

Type: [System.Decimal](https://technet.microsoft.com/library/1k2e8atx\(v=ax.60\))  
Returns [Decimal](https://technet.microsoft.com/library/1k2e8atx\(v=ax.60\)).  

## See Also

#### Reference

[ChannelConfiguration Class](channelconfiguration-class-microsoft-dynamics-commerce-runtime-datamodel.md)

[Microsoft.Dynamics.Commerce.Runtime.DataModel Namespace](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)

