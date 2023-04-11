---
title: GetLoyaltyCardStatusServiceResponse.LoyaltyCard Property  (Microsoft.Dynamics.Commerce.Runtime.Services.Messages)
TOCTitle: LoyaltyCard Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.Services.Messages.GetLoyaltyCardStatusServiceResponse.LoyaltyCard
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.services.messages.getloyaltycardstatusserviceresponse.loyaltycard(v=AX.60)
ms:contentKeyID: 62212835
author: tonyafehr
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.Services.Messages.GetLoyaltyCardStatusServiceResponse.LoyaltyCard
dev_langs:
- CSharp
- C++
- VB
---

# LoyaltyCard Property


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Gets the loyalty card.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.Services.Messages](microsoft-dynamics-commerce-runtime-services-messages-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Services.Messages (in Microsoft.Dynamics.Commerce.Runtime.Services.Messages.dll)

## Syntax

``` vb
'Declaration
<DataMemberAttribute> _
Public Property LoyaltyCard As LoyaltyCard
    Get
    Private Set
'Usage
Dim instance As GetLoyaltyCardStatusServiceResponse
Dim value As LoyaltyCard

value = instance.LoyaltyCard
```

``` csharp
[DataMemberAttribute]
public LoyaltyCard LoyaltyCard { get; private set; }
```

``` c++
[DataMemberAttribute]
public:
property LoyaltyCard^ LoyaltyCard {
    LoyaltyCard^ get ();
    private: void set (LoyaltyCard^ value);
}
```

#### Property Value

Type: [Microsoft.Dynamics.Commerce.Runtime.DataModel.LoyaltyCard](loyaltycard-class-microsoft-dynamics-commerce-runtime-datamodel.md)  
Returns [LoyaltyCard](loyaltycard-class-microsoft-dynamics-commerce-runtime-datamodel.md).  

## See Also

#### Reference

[GetLoyaltyCardStatusServiceResponse Class](getloyaltycardstatusserviceresponse-class-microsoft-dynamics-commerce-runtime-services-messages.md)

[Microsoft.Dynamics.Commerce.Runtime.Services.Messages Namespace](microsoft-dynamics-commerce-runtime-services-messages-namespace.md)

