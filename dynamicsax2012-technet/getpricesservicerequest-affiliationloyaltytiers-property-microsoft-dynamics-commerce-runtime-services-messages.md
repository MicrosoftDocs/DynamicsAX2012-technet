---
title: GetPricesServiceRequest.AffiliationLoyaltyTiers Property  (Microsoft.Dynamics.Commerce.Runtime.Services.Messages)
TOCTitle: AffiliationLoyaltyTiers Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.Services.Messages.GetPricesServiceRequest.AffiliationLoyaltyTiers
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.services.messages.getpricesservicerequest.affiliationloyaltytiers(v=AX.60)
ms:contentKeyID: 65315549
author: tonyafehr
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.Services.Messages.GetPricesServiceRequest.AffiliationLoyaltyTiers
dev_langs:
- CSharp
- C++
- VB
---

# AffiliationLoyaltyTiers Property


[!INCLUDE[archive-banner](includes/archive-banner.md)]

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.Services.Messages](microsoft-dynamics-commerce-runtime-services-messages-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Services.Messages (in Microsoft.Dynamics.Commerce.Runtime.Services.Messages.dll)

## Syntax

``` vb
'Declaration
<DataMemberAttribute> _
Public Property AffiliationLoyaltyTiers As IEnumerable(Of AffiliationLoyaltyTier)
    Get
    Private Set
'Usage
Dim instance As GetPricesServiceRequest
Dim value As IEnumerable(Of AffiliationLoyaltyTier)

value = instance.AffiliationLoyaltyTiers
```

``` csharp
[DataMemberAttribute]
public IEnumerable<AffiliationLoyaltyTier> AffiliationLoyaltyTiers { get; private set; }
```

``` c++
[DataMemberAttribute]
public:
property IEnumerable<AffiliationLoyaltyTier^>^ AffiliationLoyaltyTiers {
    IEnumerable<AffiliationLoyaltyTier^>^ get ();
    private: void set (IEnumerable<AffiliationLoyaltyTier^>^ value);
}
```

#### Property Value

Type: [System.Collections.Generic.IEnumerable](https://technet.microsoft.com/library/9eekhta0\(v=ax.60\))\<[AffiliationLoyaltyTier](affiliationloyaltytier-class-microsoft-dynamics-commerce-runtime-datamodel.md)\>  

## See Also

#### Reference

[GetPricesServiceRequest Class](getpricesservicerequest-class-microsoft-dynamics-commerce-runtime-services-messages.md)

[Microsoft.Dynamics.Commerce.Runtime.Services.Messages Namespace](microsoft-dynamics-commerce-runtime-services-messages-namespace.md)

