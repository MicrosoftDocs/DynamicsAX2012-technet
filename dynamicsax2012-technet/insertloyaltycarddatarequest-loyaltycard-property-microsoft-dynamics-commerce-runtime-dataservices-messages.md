---
title: InsertLoyaltyCardDataRequest.LoyaltyCard Property  (Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages)
TOCTitle: LoyaltyCard Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages.InsertLoyaltyCardDataRequest.LoyaltyCard
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.dataservices.messages.insertloyaltycarddatarequest.loyaltycard(v=AX.60)
ms:contentKeyID: 65321508
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages.InsertLoyaltyCardDataRequest.LoyaltyCard
dev_langs:
- CSharp
- C++
- VB
---

# LoyaltyCard Property


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Gets the loyalty card with card tiers.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages](microsoft-dynamics-commerce-runtime-dataservices-messages-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages (in Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages.dll)

## Syntax

``` vb
'Declaration
<DataMemberAttribute> _
Public Property LoyaltyCard As LoyaltyCard
    Get
    Private Set
'Usage
Dim instance As InsertLoyaltyCardDataRequest
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

[InsertLoyaltyCardDataRequest Class](insertloyaltycarddatarequest-class-microsoft-dynamics-commerce-runtime-dataservices-messages.md)

[Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages Namespace](microsoft-dynamics-commerce-runtime-dataservices-messages-namespace.md)

