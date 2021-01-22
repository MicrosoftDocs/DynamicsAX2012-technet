---
title: ChannelConfiguration.TransactionServiceStaffLogOnConfiguration Property  (Microsoft.Dynamics.Commerce.Runtime.DataModel)
TOCTitle: TransactionServiceStaffLogOnConfiguration Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.DataModel.ChannelConfiguration.TransactionServiceStaffLogOnConfiguration
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.datamodel.channelconfiguration.transactionservicestafflogonconfiguration(v=AX.60)
ms:contentKeyID: 62208338
author: Khairunj
ms.author: daxcpft
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataModel.ChannelConfiguration.TransactionServiceStaffLogOnConfiguration
dev_langs:
- CSharp
- C++
- VB
---

# TransactionServiceStaffLogOnConfiguration Property

Gets the transaction service staff login configuration.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataModel](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Entities (in Microsoft.Dynamics.Commerce.Runtime.Entities.dll)

## Syntax

``` vb
'Declaration
<IgnoreDataMemberAttribute> _
Public Property TransactionServiceStaffLogOnConfiguration As LogOnConfiguration
    Get
    Friend Set
'Usage
Dim instance As ChannelConfiguration
Dim value As LogOnConfiguration

value = instance.TransactionServiceStaffLogOnConfiguration
```

``` csharp
[IgnoreDataMemberAttribute]
public LogOnConfiguration TransactionServiceStaffLogOnConfiguration { get; internal set; }
```

``` c++
[IgnoreDataMemberAttribute]
public:
property LogOnConfiguration TransactionServiceStaffLogOnConfiguration {
    LogOnConfiguration get ();
    internal: void set (LogOnConfiguration value);
}
```

#### Property Value

Type: [Microsoft.Dynamics.Commerce.Runtime.DataModel.LogOnConfiguration](logonconfiguration-enumeration-microsoft-dynamics-commerce-runtime-datamodel.md)  
Returns [LogOnConfiguration](logonconfiguration-enumeration-microsoft-dynamics-commerce-runtime-datamodel.md).  

## See Also

#### Reference

[ChannelConfiguration Class](channelconfiguration-class-microsoft-dynamics-commerce-runtime-datamodel.md)

[Microsoft.Dynamics.Commerce.Runtime.DataModel Namespace](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)

