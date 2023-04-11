---
title: GetLoyaltyCardRewardPointsStatusTransactionServiceRequest.IncludeNonRedeemablePoints Property  (Microsoft.Dynamics.Commerce.Runtime.Services.Messages)
TOCTitle: IncludeNonRedeemablePoints Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.Services.Messages.GetLoyaltyCardRewardPointsStatusTransactionServiceRequest.IncludeNonRedeemablePoints
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.services.messages.getloyaltycardrewardpointsstatustransactionservicerequest.includenonredeemablepoints(v=AX.60)
ms:contentKeyID: 65317236
author: tonyafehr
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.Services.Messages.GetLoyaltyCardRewardPointsStatusTransactionServiceRequest.IncludeNonRedeemablePoints
dev_langs:
- CSharp
- C++
- VB
---

# IncludeNonRedeemablePoints Property


[!INCLUDE[archive-banner](includes/archive-banner.md)]

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.Services.Messages](microsoft-dynamics-commerce-runtime-services-messages-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Services.Messages (in Microsoft.Dynamics.Commerce.Runtime.Services.Messages.dll)

## Syntax

``` vb
'Declaration
<DataMemberAttribute> _
Public Property IncludeNonRedeemablePoints As Boolean
    Get
    Private Set
'Usage
Dim instance As GetLoyaltyCardRewardPointsStatusTransactionServiceRequest
Dim value As Boolean

value = instance.IncludeNonRedeemablePoints
```

``` csharp
[DataMemberAttribute]
public bool IncludeNonRedeemablePoints { get; private set; }
```

``` c++
[DataMemberAttribute]
public:
property bool IncludeNonRedeemablePoints {
    bool get ();
    private: void set (bool value);
}
```

#### Property Value

Type: [System.Boolean](https://technet.microsoft.com/library/a28wyd50\(v=ax.60\))  

## See Also

#### Reference

[GetLoyaltyCardRewardPointsStatusTransactionServiceRequest Class](getloyaltycardrewardpointsstatustransactionservicerequest-class-microsoft-dynamics-commerce-runtime-services-messages.md)

[Microsoft.Dynamics.Commerce.Runtime.Services.Messages Namespace](microsoft-dynamics-commerce-runtime-services-messages-namespace.md)

