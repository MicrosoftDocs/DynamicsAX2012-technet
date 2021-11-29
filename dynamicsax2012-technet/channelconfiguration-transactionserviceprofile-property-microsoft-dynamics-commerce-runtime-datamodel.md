---
title: ChannelConfiguration.TransactionServiceProfile Property  (Microsoft.Dynamics.Commerce.Runtime.DataModel)
TOCTitle: TransactionServiceProfile Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.DataModel.ChannelConfiguration.TransactionServiceProfile
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.datamodel.channelconfiguration.transactionserviceprofile(v=AX.60)
ms:contentKeyID: 62210438
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataModel.ChannelConfiguration.TransactionServiceProfile
dev_langs:
- CSharp
- C++
- VB
---

# TransactionServiceProfile Property


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Gets the transaction service profile.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataModel](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Entities (in Microsoft.Dynamics.Commerce.Runtime.Entities.dll)

## Syntax

``` vb
'Declaration
<IgnoreDataMemberAttribute> _
Public Property TransactionServiceProfile As TransactionServiceProfile
    Get
    Set
'Usage
Dim instance As ChannelConfiguration
Dim value As TransactionServiceProfile

value = instance.TransactionServiceProfile

instance.TransactionServiceProfile = value
```

``` csharp
[IgnoreDataMemberAttribute]
public TransactionServiceProfile TransactionServiceProfile { get; set; }
```

``` c++
[IgnoreDataMemberAttribute]
public:
property TransactionServiceProfile^ TransactionServiceProfile {
    TransactionServiceProfile^ get ();
    void set (TransactionServiceProfile^ value);
}
```

#### Property Value

Type: [Microsoft.Dynamics.Commerce.Runtime.DataModel.TransactionServiceProfile](transactionserviceprofile-class-microsoft-dynamics-commerce-runtime-datamodel.md)  
Returns [TransactionServiceProfile](transactionserviceprofile-class-microsoft-dynamics-commerce-runtime-datamodel.md).  

## See Also

#### Reference

[ChannelConfiguration Class](channelconfiguration-class-microsoft-dynamics-commerce-runtime-datamodel.md)

[Microsoft.Dynamics.Commerce.Runtime.DataModel Namespace](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)

