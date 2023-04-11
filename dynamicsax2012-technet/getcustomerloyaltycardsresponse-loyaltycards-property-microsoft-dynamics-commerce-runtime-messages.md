---
title: GetCustomerLoyaltyCardsResponse.LoyaltyCards Property  (Microsoft.Dynamics.Commerce.Runtime.Messages)
TOCTitle: LoyaltyCards Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.Messages.GetCustomerLoyaltyCardsResponse.LoyaltyCards
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.messages.getcustomerloyaltycardsresponse.loyaltycards(v=AX.60)
ms:contentKeyID: 62214081
author: tonyafehr
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.Messages.GetCustomerLoyaltyCardsResponse.LoyaltyCards
dev_langs:
- CSharp
- C++
- VB
---

# LoyaltyCards Property


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Gets the collection of loyalty cards.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.Messages](microsoft-dynamics-commerce-runtime-messages-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Messages (in Microsoft.Dynamics.Commerce.Runtime.Messages.dll)

## Syntax

``` vb
'Declaration
<DataMemberAttribute> _
Public Property LoyaltyCards As ReadOnlyCollection(Of LoyaltyCard)
    Get
    Private Set
'Usage
Dim instance As GetCustomerLoyaltyCardsResponse
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
Returns [ReadOnlyCollection\<T\>](https://technet.microsoft.com/library/ms132474\(v=ax.60\)).  

## See Also

#### Reference

[GetCustomerLoyaltyCardsResponse Class](getcustomerloyaltycardsresponse-class-microsoft-dynamics-commerce-runtime-messages.md)

[Microsoft.Dynamics.Commerce.Runtime.Messages Namespace](microsoft-dynamics-commerce-runtime-messages-namespace.md)

