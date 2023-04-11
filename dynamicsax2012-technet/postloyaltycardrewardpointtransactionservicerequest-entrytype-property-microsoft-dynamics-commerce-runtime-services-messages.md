---
title: PostLoyaltyCardRewardPointTransactionServiceRequest.EntryType Property  (Microsoft.Dynamics.Commerce.Runtime.Services.Messages)
TOCTitle: EntryType Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.Services.Messages.PostLoyaltyCardRewardPointTransactionServiceRequest.EntryType
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.services.messages.postloyaltycardrewardpointtransactionservicerequest.entrytype(v=AX.60)
ms:contentKeyID: 65316926
author: tonyafehr
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.Services.Messages.PostLoyaltyCardRewardPointTransactionServiceRequest.EntryType
dev_langs:
- CSharp
- C++
- VB
---

# EntryType Property


[!INCLUDE[archive-banner](includes/archive-banner.md)]

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.Services.Messages](microsoft-dynamics-commerce-runtime-services-messages-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Services.Messages (in Microsoft.Dynamics.Commerce.Runtime.Services.Messages.dll)

## Syntax

``` vb
'Declaration
<DataMemberAttribute> _
Public Property EntryType As LoyaltyRewardPointEntryType
    Get
    Private Set
'Usage
Dim instance As PostLoyaltyCardRewardPointTransactionServiceRequest
Dim value As LoyaltyRewardPointEntryType

value = instance.EntryType
```

``` csharp
[DataMemberAttribute]
public LoyaltyRewardPointEntryType EntryType { get; private set; }
```

``` c++
[DataMemberAttribute]
public:
property LoyaltyRewardPointEntryType EntryType {
    LoyaltyRewardPointEntryType get ();
    private: void set (LoyaltyRewardPointEntryType value);
}
```

#### Property Value

Type: [Microsoft.Dynamics.Commerce.Runtime.DataModel.LoyaltyRewardPointEntryType](loyaltyrewardpointentrytype-enumeration-microsoft-dynamics-commerce-runtime-datamodel.md)  

## See Also

#### Reference

[PostLoyaltyCardRewardPointTransactionServiceRequest Class](postloyaltycardrewardpointtransactionservicerequest-class-microsoft-dynamics-commerce-runtime-services-messages.md)

[Microsoft.Dynamics.Commerce.Runtime.Services.Messages Namespace](microsoft-dynamics-commerce-runtime-services-messages-namespace.md)

