---
title: ChannelConfiguration.EarnLoyaltyOffline Property  (Microsoft.Dynamics.Commerce.Runtime.DataModel)
TOCTitle: EarnLoyaltyOffline Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.DataModel.ChannelConfiguration.EarnLoyaltyOffline
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.datamodel.channelconfiguration.earnloyaltyoffline(v=AX.60)
ms:contentKeyID: 62209162
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataModel.ChannelConfiguration.EarnLoyaltyOffline
dev_langs:
- CSharp
- C++
- VB
---

# EarnLoyaltyOffline Property

Gets a value indicating whether the loyalty points are earned offline.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataModel](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Entities (in Microsoft.Dynamics.Commerce.Runtime.Entities.dll)

## Syntax

``` vb
'Declaration
<DataMemberAttribute> _
<ColumnAttribute("EARNLOYALTYOFFLINE")> _
Public Property EarnLoyaltyOffline As Boolean
    Get
    Friend Set
'Usage
Dim instance As ChannelConfiguration
Dim value As Boolean

value = instance.EarnLoyaltyOffline
```

``` csharp
[DataMemberAttribute]
[ColumnAttribute("EARNLOYALTYOFFLINE")]
public bool EarnLoyaltyOffline { get; internal set; }
```

``` c++
[DataMemberAttribute]
[ColumnAttribute(L"EARNLOYALTYOFFLINE")]
public:
property bool EarnLoyaltyOffline {
    bool get ();
    internal: void set (bool value);
}
```

#### Property Value

Type: [System.Boolean](https://technet.microsoft.com/library/a28wyd50\(v=ax.60\))  
Returns [Boolean](https://technet.microsoft.com/library/a28wyd50\(v=ax.60\)).  

## See Also

#### Reference

[ChannelConfiguration Class](channelconfiguration-class-microsoft-dynamics-commerce-runtime-datamodel.md)

[Microsoft.Dynamics.Commerce.Runtime.DataModel Namespace](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)

