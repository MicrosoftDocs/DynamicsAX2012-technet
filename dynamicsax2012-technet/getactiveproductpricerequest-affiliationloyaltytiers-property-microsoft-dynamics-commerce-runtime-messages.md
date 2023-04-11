---
title: GetActiveProductPriceRequest.AffiliationLoyaltyTiers Property  (Microsoft.Dynamics.Commerce.Runtime.Messages)
TOCTitle: AffiliationLoyaltyTiers Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.Messages.GetActiveProductPriceRequest.AffiliationLoyaltyTiers
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.messages.getactiveproductpricerequest.affiliationloyaltytiers(v=AX.60)
ms:contentKeyID: 65320683
author: tonyafehr
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.Messages.GetActiveProductPriceRequest.AffiliationLoyaltyTiers
dev_langs:
- CSharp
- C++
- VB
---

# AffiliationLoyaltyTiers Property


[!INCLUDE[archive-banner](includes/archive-banner.md)]

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.Messages](microsoft-dynamics-commerce-runtime-messages-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Messages (in Microsoft.Dynamics.Commerce.Runtime.Messages.dll)

## Syntax

``` vb
'Declaration
<DataMemberAttribute> _
Public Property AffiliationLoyaltyTiers As IEnumerable(Of AffiliationLoyaltyTier)
    Get
    Set
'Usage
Dim instance As GetActiveProductPriceRequest
Dim value As IEnumerable(Of AffiliationLoyaltyTier)

value = instance.AffiliationLoyaltyTiers

instance.AffiliationLoyaltyTiers = value
```

``` csharp
[DataMemberAttribute]
public IEnumerable<AffiliationLoyaltyTier> AffiliationLoyaltyTiers { get; set; }
```

``` c++
[DataMemberAttribute]
public:
property IEnumerable<AffiliationLoyaltyTier^>^ AffiliationLoyaltyTiers {
    IEnumerable<AffiliationLoyaltyTier^>^ get ();
    void set (IEnumerable<AffiliationLoyaltyTier^>^ value);
}
```

#### Property Value

Type: [System.Collections.Generic.IEnumerable](https://technet.microsoft.com/library/9eekhta0\(v=ax.60\))\<[AffiliationLoyaltyTier](affiliationloyaltytier-class-microsoft-dynamics-commerce-runtime-datamodel.md)\>  

## See Also

#### Reference

[GetActiveProductPriceRequest Class](getactiveproductpricerequest-class-microsoft-dynamics-commerce-runtime-messages.md)

[Microsoft.Dynamics.Commerce.Runtime.Messages Namespace](microsoft-dynamics-commerce-runtime-messages-namespace.md)

