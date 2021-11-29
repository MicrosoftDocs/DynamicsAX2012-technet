---
title: GetLoyaltyCardRewardPointsStatusTransactionServiceRequest.LoyaltyCardNumber Property  (Microsoft.Dynamics.Commerce.Runtime.Services.Messages)
TOCTitle: LoyaltyCardNumber Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.Services.Messages.GetLoyaltyCardRewardPointsStatusTransactionServiceRequest.LoyaltyCardNumber
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.services.messages.getloyaltycardrewardpointsstatustransactionservicerequest.loyaltycardnumber(v=AX.60)
ms:contentKeyID: 65321485
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.Services.Messages.GetLoyaltyCardRewardPointsStatusTransactionServiceRequest.LoyaltyCardNumber
dev_langs:
- CSharp
- C++
- VB
---

# LoyaltyCardNumber Property


[!INCLUDE[archive-banner](includes/archive-banner.md)]

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.Services.Messages](microsoft-dynamics-commerce-runtime-services-messages-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Services.Messages (in Microsoft.Dynamics.Commerce.Runtime.Services.Messages.dll)

## Syntax

``` vb
'Declaration
<DataMemberAttribute> _
Public Property LoyaltyCardNumber As String
    Get
    Private Set
'Usage
Dim instance As GetLoyaltyCardRewardPointsStatusTransactionServiceRequest
Dim value As String

value = instance.LoyaltyCardNumber
```

``` csharp
[DataMemberAttribute]
public string LoyaltyCardNumber { get; private set; }
```

``` c++
[DataMemberAttribute]
public:
property String^ LoyaltyCardNumber {
    String^ get ();
    private: void set (String^ value);
}
```

#### Property Value

Type: [System.String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\))  

## See Also

#### Reference

[GetLoyaltyCardRewardPointsStatusTransactionServiceRequest Class](getloyaltycardrewardpointsstatustransactionservicerequest-class-microsoft-dynamics-commerce-runtime-services-messages.md)

[Microsoft.Dynamics.Commerce.Runtime.Services.Messages Namespace](microsoft-dynamics-commerce-runtime-services-messages-namespace.md)

