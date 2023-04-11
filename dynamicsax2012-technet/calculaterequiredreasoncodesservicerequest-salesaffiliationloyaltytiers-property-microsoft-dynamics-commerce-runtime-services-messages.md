---
title: CalculateRequiredReasonCodesServiceRequest.SalesAffiliationLoyaltyTiers Property  (Microsoft.Dynamics.Commerce.Runtime.Services.Messages)
TOCTitle: SalesAffiliationLoyaltyTiers Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.Services.Messages.CalculateRequiredReasonCodesServiceRequest.SalesAffiliationLoyaltyTiers
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.services.messages.calculaterequiredreasoncodesservicerequest.salesaffiliationloyaltytiers(v=AX.60)
ms:contentKeyID: 62206384
author: tonyafehr
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.Services.Messages.CalculateRequiredReasonCodesServiceRequest.SalesAffiliationLoyaltyTiers
dev_langs:
- CSharp
- C++
- VB
---

# SalesAffiliationLoyaltyTiers Property


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Gets the sales affiliation lines to calculate on.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.Services.Messages](microsoft-dynamics-commerce-runtime-services-messages-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Services.Messages (in Microsoft.Dynamics.Commerce.Runtime.Services.Messages.dll)

## Syntax

``` vb
'Declaration
<DataMemberAttribute> _
Public Property SalesAffiliationLoyaltyTiers As IEnumerable(Of SalesAffiliationLoyaltyTier)
    Get
    Private Set
'Usage
Dim instance As CalculateRequiredReasonCodesServiceRequest
Dim value As IEnumerable(Of SalesAffiliationLoyaltyTier)

value = instance.SalesAffiliationLoyaltyTiers
```

``` csharp
[DataMemberAttribute]
public IEnumerable<SalesAffiliationLoyaltyTier> SalesAffiliationLoyaltyTiers { get; private set; }
```

``` c++
[DataMemberAttribute]
public:
property IEnumerable<SalesAffiliationLoyaltyTier^>^ SalesAffiliationLoyaltyTiers {
    IEnumerable<SalesAffiliationLoyaltyTier^>^ get ();
    private: void set (IEnumerable<SalesAffiliationLoyaltyTier^>^ value);
}
```

#### Property Value

Type: [System.Collections.Generic.IEnumerable](https://technet.microsoft.com/library/9eekhta0\(v=ax.60\))\<[SalesAffiliationLoyaltyTier](salesaffiliationloyaltytier-class-microsoft-dynamics-commerce-runtime-datamodel.md)\>  
Returns [IEnumerable\<T\>](https://technet.microsoft.com/library/9eekhta0\(v=ax.60\)).  

## See Also

#### Reference

[CalculateRequiredReasonCodesServiceRequest Class](calculaterequiredreasoncodesservicerequest-class-microsoft-dynamics-commerce-runtime-services-messages.md)

[Microsoft.Dynamics.Commerce.Runtime.Services.Messages Namespace](microsoft-dynamics-commerce-runtime-services-messages-namespace.md)

