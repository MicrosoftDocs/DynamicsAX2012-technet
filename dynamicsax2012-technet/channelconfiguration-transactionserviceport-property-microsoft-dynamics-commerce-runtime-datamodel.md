---
title: ChannelConfiguration.TransactionServicePort Property  (Microsoft.Dynamics.Commerce.Runtime.DataModel)
TOCTitle: TransactionServicePort Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.DataModel.ChannelConfiguration.TransactionServicePort
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.datamodel.channelconfiguration.transactionserviceport(v=AX.60)
ms:contentKeyID: 49832036
author: tonyafehr
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataModel.ChannelConfiguration.TransactionServicePort
dev_langs:
- CSharp
- C++
- VB
---

# TransactionServicePort Property


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Gets the transaction service port.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataModel](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Entities (in Microsoft.Dynamics.Commerce.Runtime.Entities.dll)

## Syntax

``` vb
'Declaration
<IgnoreDataMemberAttribute> _
Public ReadOnly Property TransactionServicePort As Integer
    Get
'Usage
Dim instance As ChannelConfiguration
Dim value As Integer

value = instance.TransactionServicePort
```

``` csharp
[IgnoreDataMemberAttribute]
public int TransactionServicePort { get; }
```

``` c++
[IgnoreDataMemberAttribute]
public:
property int TransactionServicePort {
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

