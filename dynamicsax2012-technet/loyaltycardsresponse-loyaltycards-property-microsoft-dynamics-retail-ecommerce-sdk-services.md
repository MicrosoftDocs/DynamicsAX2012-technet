---
title: LoyaltyCardsResponse.LoyaltyCards Property  (Microsoft.Dynamics.Retail.Ecommerce.Sdk.Services)
TOCTitle: LoyaltyCards Property
ms:assetid: P:Microsoft.Dynamics.Retail.Ecommerce.Sdk.Services.LoyaltyCardsResponse.LoyaltyCards
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.retail.ecommerce.sdk.services.loyaltycardsresponse.loyaltycards(v=AX.60)
ms:contentKeyID: 65318378
author: tonyafehr
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Retail.Ecommerce.Sdk.Services.LoyaltyCardsResponse.LoyaltyCards
dev_langs:
- CSharp
- C++
- VB
---

# LoyaltyCards Property


[!INCLUDE[archive-banner](includes/archive-banner.md)]

**Namespace:**  [Microsoft.Dynamics.Retail.Ecommerce.Sdk.Services](microsoft-dynamics-retail-ecommerce-sdk-services-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Retail.Ecommerce.Sdk.Services (in Microsoft.Dynamics.Retail.Ecommerce.Sdk.Services.dll)

## Syntax

``` vb
'Declaration
<DataMemberAttribute> _
Public Property LoyaltyCards As IEnumerable(Of LoyaltyCard)
    Get
    Friend Set
'Usage
Dim instance As LoyaltyCardsResponse
Dim value As IEnumerable(Of LoyaltyCard)

value = instance.LoyaltyCards
```

``` csharp
[DataMemberAttribute]
public IEnumerable<LoyaltyCard> LoyaltyCards { get; internal set; }
```

``` c++
[DataMemberAttribute]
public:
property IEnumerable<LoyaltyCard^>^ LoyaltyCards {
    IEnumerable<LoyaltyCard^>^ get ();
    internal: void set (IEnumerable<LoyaltyCard^>^ value);
}
```

#### Property Value

Type: [System.Collections.Generic.IEnumerable](https://technet.microsoft.com/library/9eekhta0\(v=ax.60\))\<[LoyaltyCard](loyaltycard-class-microsoft-dynamics-retail-ecommerce-sdk-core-models.md)\>  

## See Also

#### Reference

[LoyaltyCardsResponse Class](loyaltycardsresponse-class-microsoft-dynamics-retail-ecommerce-sdk-services.md)

[Microsoft.Dynamics.Retail.Ecommerce.Sdk.Services Namespace](microsoft-dynamics-retail-ecommerce-sdk-services-namespace.md)

