---
title: ChannelConfiguration.TransactionServiceProtocol Property  (Microsoft.Dynamics.Commerce.Runtime.DataModel)
TOCTitle: TransactionServiceProtocol Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.DataModel.ChannelConfiguration.TransactionServiceProtocol
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.datamodel.channelconfiguration.transactionserviceprotocol(v=AX.60)
ms:contentKeyID: 49844903
author: tonyafehr
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataModel.ChannelConfiguration.TransactionServiceProtocol
dev_langs:
- CSharp
- C++
- VB
---

# TransactionServiceProtocol Property


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Gets the transaction service protocol.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataModel](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Entities (in Microsoft.Dynamics.Commerce.Runtime.Entities.dll)

## Syntax

``` vb
'Declaration
<IgnoreDataMemberAttribute> _
Public ReadOnly Property TransactionServiceProtocol As Integer
    Get
'Usage
Dim instance As ChannelConfiguration
Dim value As Integer

value = instance.TransactionServiceProtocol
```

``` csharp
[IgnoreDataMemberAttribute]
public int TransactionServiceProtocol { get; }
```

``` c++
[IgnoreDataMemberAttribute]
public:
property int TransactionServiceProtocol {
    int get ();
}
```

#### Property Value

Type: [System.Int32](https://technet.microsoft.com/library/td2s409d\(v=ax.60\))  
Returns [Int32](https://technet.microsoft.com/library/td2s409d\(v=ax.60\)).  

## See Also

#### Reference

[ChannelConfiguration Class](channelconfiguration-class-microsoft-dynamics-commerce-runtime-datamodel.md)

[Microsoft.Dynamics.Commerce.Runtime.DataModel Namespace](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)

