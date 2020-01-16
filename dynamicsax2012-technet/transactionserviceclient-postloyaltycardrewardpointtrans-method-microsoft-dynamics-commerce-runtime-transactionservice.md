---
title: TransactionServiceClient.PostLoyaltyCardRewardPointTrans Method  (Microsoft.Dynamics.Commerce.Runtime.TransactionService)
TOCTitle: PostLoyaltyCardRewardPointTrans Method
ms:assetid: M:Microsoft.Dynamics.Commerce.Runtime.TransactionService.TransactionServiceClient.PostLoyaltyCardRewardPointTrans(Microsoft.Dynamics.Commerce.Runtime.DataModel.SalesTransaction,Microsoft.Dynamics.Commerce.Runtime.DataModel.LoyaltyRewardPointEntryType,Microsoft.Dynamics.Commerce.Runtime.DataModel.ChannelConfiguration)
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.transactionservice.transactionserviceclient.postloyaltycardrewardpointtrans(v=AX.60)
ms:contentKeyID: 62214937
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.TransactionService.TransactionServiceClient.PostLoyaltyCardRewardPointTrans
dev_langs:
- CSharp
- C++
- VB
---

# PostLoyaltyCardRewardPointTrans Method

Posts the loyalty card reward points to AX HQ.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.TransactionService](microsoft-dynamics-commerce-runtime-transactionservice-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.TransactionService (in Microsoft.Dynamics.Commerce.Runtime.TransactionService.dll)

## Syntax

``` vb
'Declaration
Public Sub PostLoyaltyCardRewardPointTrans ( _
    transaction As SalesTransaction, _
    entryType As LoyaltyRewardPointEntryType, _
    channelConfiguration As ChannelConfiguration _
)
'Usage
Dim instance As TransactionServiceClient
Dim transaction As SalesTransaction
Dim entryType As LoyaltyRewardPointEntryType
Dim channelConfiguration As ChannelConfiguration

instance.PostLoyaltyCardRewardPointTrans(transaction, _
    entryType, channelConfiguration)
```

``` csharp
public void PostLoyaltyCardRewardPointTrans(
    SalesTransaction transaction,
    LoyaltyRewardPointEntryType entryType,
    ChannelConfiguration channelConfiguration
)
```

``` c++
public:
void PostLoyaltyCardRewardPointTrans(
    SalesTransaction^ transaction, 
    LoyaltyRewardPointEntryType entryType, 
    ChannelConfiguration^ channelConfiguration
)
```

#### Parameters

  - transaction  
    Type: [Microsoft.Dynamics.Commerce.Runtime.DataModel.SalesTransaction](salestransaction-class-microsoft-dynamics-commerce-runtime-datamodel.md)  

<!-- end list -->

  - entryType  
    Type: [Microsoft.Dynamics.Commerce.Runtime.DataModel.LoyaltyRewardPointEntryType](loyaltyrewardpointentrytype-enumeration-microsoft-dynamics-commerce-runtime-datamodel.md)  

<!-- end list -->

  - channelConfiguration  
    Type: [Microsoft.Dynamics.Commerce.Runtime.DataModel.ChannelConfiguration](channelconfiguration-class-microsoft-dynamics-commerce-runtime-datamodel.md)  

## See Also

#### Reference

[TransactionServiceClient Class](transactionserviceclient-class-microsoft-dynamics-commerce-runtime-transactionservice.md)

[Microsoft.Dynamics.Commerce.Runtime.TransactionService Namespace](microsoft-dynamics-commerce-runtime-transactionservice-namespace.md)

