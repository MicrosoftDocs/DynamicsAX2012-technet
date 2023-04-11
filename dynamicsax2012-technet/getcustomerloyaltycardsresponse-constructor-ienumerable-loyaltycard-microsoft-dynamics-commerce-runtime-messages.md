---
title: GetCustomerLoyaltyCardsResponse Constructor (IEnumerable(LoyaltyCard)) (Microsoft.Dynamics.Commerce.Runtime.Messages)
TOCTitle: GetCustomerLoyaltyCardsResponse Constructor (IEnumerable(LoyaltyCard))
ms:assetid: M:Microsoft.Dynamics.Commerce.Runtime.Messages.GetCustomerLoyaltyCardsResponse.#ctor(System.Collections.Generic.IEnumerable{Microsoft.Dynamics.Commerce.Runtime.DataModel.LoyaltyCard})
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.messages.getcustomerloyaltycardsresponse.getcustomerloyaltycardsresponse(v=AX.60)
ms:contentKeyID: 62209096
author: tonyafehr
ms.date: 05/18/2015
mtps_version: v=AX.60
dev_langs:
- vb
- csharp
- c++
---

# GetCustomerLoyaltyCardsResponse Constructor (IEnumerable(LoyaltyCard))


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Initializes a new instance of the [GetCustomerLoyaltyCardsResponse](getcustomerloyaltycardsresponse-class-microsoft-dynamics-commerce-runtime-messages.md) class.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.Messages](microsoft-dynamics-commerce-runtime-messages-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Messages (in Microsoft.Dynamics.Commerce.Runtime.Messages.dll)

## Syntax

``` vb
'Declaration
Public Sub New ( _
    loyaltyCards As IEnumerable(Of LoyaltyCard) _
)
'Usage
Dim loyaltyCards As IEnumerable(Of LoyaltyCard)

Dim instance As New GetCustomerLoyaltyCardsResponse(loyaltyCards)
```

``` csharp
public GetCustomerLoyaltyCardsResponse(
    IEnumerable<LoyaltyCard> loyaltyCards
)
```

``` c++
public:
GetCustomerLoyaltyCardsResponse(
    IEnumerable<LoyaltyCard^>^ loyaltyCards
)
```

#### Parameters

  - loyaltyCards  
    Type: [System.Collections.Generic.IEnumerable](https://technet.microsoft.com/library/9eekhta0\(v=ax.60\))\<[LoyaltyCard](loyaltycard-class-microsoft-dynamics-commerce-runtime-datamodel.md)\>  

## See Also

#### Reference

[GetCustomerLoyaltyCardsResponse Class](getcustomerloyaltycardsresponse-class-microsoft-dynamics-commerce-runtime-messages.md)

[GetCustomerLoyaltyCardsResponse Overload](getcustomerloyaltycardsresponse-constructor-microsoft-dynamics-commerce-runtime-messages.md)

[Microsoft.Dynamics.Commerce.Runtime.Messages Namespace](microsoft-dynamics-commerce-runtime-messages-namespace.md)

