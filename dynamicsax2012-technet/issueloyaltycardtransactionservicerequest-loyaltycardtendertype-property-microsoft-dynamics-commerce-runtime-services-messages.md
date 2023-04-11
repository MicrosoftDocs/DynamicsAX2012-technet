---
title: IssueLoyaltyCardTransactionServiceRequest.LoyaltyCardTenderType Property  (Microsoft.Dynamics.Commerce.Runtime.Services.Messages)
TOCTitle: LoyaltyCardTenderType Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.Services.Messages.IssueLoyaltyCardTransactionServiceRequest.LoyaltyCardTenderType
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.services.messages.issueloyaltycardtransactionservicerequest.loyaltycardtendertype(v=AX.60)
ms:contentKeyID: 65317040
author: tonyafehr
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.Services.Messages.IssueLoyaltyCardTransactionServiceRequest.LoyaltyCardTenderType
dev_langs:
- CSharp
- C++
- VB
---

# LoyaltyCardTenderType Property


[!INCLUDE[archive-banner](includes/archive-banner.md)]

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.Services.Messages](microsoft-dynamics-commerce-runtime-services-messages-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Services.Messages (in Microsoft.Dynamics.Commerce.Runtime.Services.Messages.dll)

## Syntax

``` vb
'Declaration
<DataMemberAttribute> _
Public Property LoyaltyCardTenderType As LoyaltyCardTenderType
    Get
    Private Set
'Usage
Dim instance As IssueLoyaltyCardTransactionServiceRequest
Dim value As LoyaltyCardTenderType

value = instance.LoyaltyCardTenderType
```

``` csharp
[DataMemberAttribute]
public LoyaltyCardTenderType LoyaltyCardTenderType { get; private set; }
```

``` c++
[DataMemberAttribute]
public:
property LoyaltyCardTenderType LoyaltyCardTenderType {
    LoyaltyCardTenderType get ();
    private: void set (LoyaltyCardTenderType value);
}
```

#### Property Value

Type: [Microsoft.Dynamics.Commerce.Runtime.DataModel.LoyaltyCardTenderType](loyaltycardtendertype-enumeration-microsoft-dynamics-commerce-runtime-datamodel.md)  

## See Also

#### Reference

[IssueLoyaltyCardTransactionServiceRequest Class](issueloyaltycardtransactionservicerequest-class-microsoft-dynamics-commerce-runtime-services-messages.md)

[Microsoft.Dynamics.Commerce.Runtime.Services.Messages Namespace](microsoft-dynamics-commerce-runtime-services-messages-namespace.md)

