---
title: ChannelConfiguration.MinimumDepositPercentage Property  (Microsoft.Dynamics.Commerce.Runtime.DataModel)
TOCTitle: MinimumDepositPercentage Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.DataModel.ChannelConfiguration.MinimumDepositPercentage
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.datamodel.channelconfiguration.minimumdepositpercentage(v=AX.60)
ms:contentKeyID: 62208530
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataModel.ChannelConfiguration.MinimumDepositPercentage
dev_langs:
- CSharp
- C++
- VB
---

# MinimumDepositPercentage Property


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Gets the minimum deposit percentage required for a Customer Orders.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataModel](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Entities (in Microsoft.Dynamics.Commerce.Runtime.Entities.dll)

## Syntax

``` vb
'Declaration
<DataMemberAttribute> _
<ColumnAttribute("MINIMUMDEPOSITFORSALESORDER")> _
Public Property MinimumDepositPercentage As Decimal
    Get
    Friend Set
'Usage
Dim instance As ChannelConfiguration
Dim value As Decimal

value = instance.MinimumDepositPercentage
```

``` csharp
[DataMemberAttribute]
[ColumnAttribute("MINIMUMDEPOSITFORSALESORDER")]
public decimal MinimumDepositPercentage { get; internal set; }
```

``` c++
[DataMemberAttribute]
[ColumnAttribute(L"MINIMUMDEPOSITFORSALESORDER")]
public:
property Decimal MinimumDepositPercentage {
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

