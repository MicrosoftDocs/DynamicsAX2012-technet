---
title: ChannelConfiguration.TransactionServiceSecurityOff Property  (Microsoft.Dynamics.Commerce.Runtime.DataModel)
TOCTitle: TransactionServiceSecurityOff Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.DataModel.ChannelConfiguration.TransactionServiceSecurityOff
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.datamodel.channelconfiguration.transactionservicesecurityoff(v=AX.60)
ms:contentKeyID: 49851029
author: tonyafehr
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataModel.ChannelConfiguration.TransactionServiceSecurityOff
dev_langs:
- CSharp
- C++
- VB
---

# TransactionServiceSecurityOff Property


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Gets a value indicating whether to have transaction service security off.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataModel](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Entities (in Microsoft.Dynamics.Commerce.Runtime.Entities.dll)

## Syntax

``` vb
'Declaration
<IgnoreDataMemberAttribute> _
Public ReadOnly Property TransactionServiceSecurityOff As Boolean
    Get
'Usage
Dim instance As ChannelConfiguration
Dim value As Boolean

value = instance.TransactionServiceSecurityOff
```

``` csharp
[IgnoreDataMemberAttribute]
public bool TransactionServiceSecurityOff { get; }
```

``` c++
[IgnoreDataMemberAttribute]
public:
property bool TransactionServiceSecurityOff {
    bool get ();
}
```

#### Property Value

Type: [System.Boolean](https://technet.microsoft.com/library/a28wyd50\(v=ax.60\))  
Returns [Boolean](https://technet.microsoft.com/library/a28wyd50\(v=ax.60\)).  

## See Also

#### Reference

[ChannelConfiguration Class](channelconfiguration-class-microsoft-dynamics-commerce-runtime-datamodel.md)

[Microsoft.Dynamics.Commerce.Runtime.DataModel Namespace](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)

