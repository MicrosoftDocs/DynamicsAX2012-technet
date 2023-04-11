---
title: GetLoyaltyCardRewardPointsStatusTransactionServiceResponse.LoyaltyCards Property  (Microsoft.Dynamics.Commerce.Runtime.Services.Messages)
TOCTitle: LoyaltyCards Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.Services.Messages.GetLoyaltyCardRewardPointsStatusTransactionServiceResponse.LoyaltyCards
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.services.messages.getloyaltycardrewardpointsstatustransactionserviceresponse.loyaltycards(v=AX.60)
ms:contentKeyID: 65318980
author: tonyafehr
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.Services.Messages.GetLoyaltyCardRewardPointsStatusTransactionServiceResponse.LoyaltyCards
dev_langs:
- CSharp
- C++
- VB
---

# LoyaltyCards Property


[!INCLUDE[archive-banner](includes/archive-banner.md)]

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.Services.Messages](microsoft-dynamics-commerce-runtime-services-messages-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Services.Messages (in Microsoft.Dynamics.Commerce.Runtime.Services.Messages.dll)

## Syntax

``` vb
'Declaration
<DataMemberAttribute> _
Public Property LoyaltyCards As ReadOnlyCollection(Of LoyaltyCard)
    Get
    Private Set
'Usage
Dim instance As GetLoyaltyCardRewardPointsStatusTransactionServiceResponse
Dim value As ReadOnlyCollection(Of LoyaltyCard)

value = instance.LoyaltyCards
```

``` csharp
[DataMemberAttribute]
public ReadOnlyCollection<LoyaltyCard> LoyaltyCards { get; private set; }
```

``` c++
[DataMemberAttribute]
public:
property ReadOnlyCollection<LoyaltyCard^>^ LoyaltyCards {
    ReadOnlyCollection<LoyaltyCard^>^ get ();
    private: void set (ReadOnlyCollection<LoyaltyCard^>^ value);
}
```

#### Property Value

Type: [System.Collections.ObjectModel.ReadOnlyCollection](https://technet.microsoft.com/library/ms132474\(v=ax.60\))\<[LoyaltyCard](loyaltycard-class-microsoft-dynamics-commerce-runtime-datamodel.md)\>  

## See Also

#### Reference

[GetLoyaltyCardRewardPointsStatusTransactionServiceResponse Class](getloyaltycardrewardpointsstatustransactionserviceresponse-class-microsoft-dynamics-commerce-runtime-services-messages.md)

[Microsoft.Dynamics.Commerce.Runtime.Services.Messages Namespace](microsoft-dynamics-commerce-runtime-services-messages-namespace.md)

