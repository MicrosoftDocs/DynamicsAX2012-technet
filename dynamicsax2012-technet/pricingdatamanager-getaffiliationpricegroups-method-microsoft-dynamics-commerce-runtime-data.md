---
title: PricingDataManager.GetAffiliationPriceGroups Method  (Microsoft.Dynamics.Commerce.Runtime.Data)
TOCTitle: GetAffiliationPriceGroups Method
ms:assetid: M:Microsoft.Dynamics.Commerce.Runtime.Data.PricingDataManager.GetAffiliationPriceGroups(System.Collections.Generic.IEnumerable{Microsoft.Dynamics.Commerce.Runtime.DataModel.AffiliationLoyaltyTier})
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.data.pricingdatamanager.getaffiliationpricegroups(v=AX.60)
ms:contentKeyID: 62210652
author: tonyafehr
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.Data.PricingDataManager.GetAffiliationPriceGroups
dev_langs:
- CSharp
- C++
- VB
---

# GetAffiliationPriceGroups Method


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Gets the affiliation price groups.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.Data](microsoft-dynamics-commerce-runtime-data-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.DataManagers (in Microsoft.Dynamics.Commerce.Runtime.DataManagers.dll)

## Syntax

``` vb
'Declaration
Public Function GetAffiliationPriceGroups ( _
    affiliationLoyaltyTiers As IEnumerable(Of AffiliationLoyaltyTier) _
) As ReadOnlyCollection(Of PriceGroup)
'Usage
Dim instance As PricingDataManager
Dim affiliationLoyaltyTiers As IEnumerable(Of AffiliationLoyaltyTier)
Dim returnValue As ReadOnlyCollection(Of PriceGroup)

returnValue = instance.GetAffiliationPriceGroups(affiliationLoyaltyTiers)
```

``` csharp
public ReadOnlyCollection<PriceGroup> GetAffiliationPriceGroups(
    IEnumerable<AffiliationLoyaltyTier> affiliationLoyaltyTiers
)
```

``` c++
public:
virtual ReadOnlyCollection<PriceGroup^>^ GetAffiliationPriceGroups(
    IEnumerable<AffiliationLoyaltyTier^>^ affiliationLoyaltyTiers
) sealed
```

#### Parameters

  - affiliationLoyaltyTiers  
    Type: [System.Collections.Generic.IEnumerable](https://technet.microsoft.com/library/9eekhta0\(v=ax.60\))\<[AffiliationLoyaltyTier](affiliationloyaltytier-class-microsoft-dynamics-commerce-runtime-datamodel.md)\>  

#### Return Value

Type: [System.Collections.ObjectModel.ReadOnlyCollection](https://technet.microsoft.com/library/ms132474\(v=ax.60\))\<[PriceGroup](pricegroup-class-microsoft-dynamics-commerce-runtime-datamodel.md)\>  
A collection of affiliation price groups.  

#### Implements

[IPricingDataManagerV2.GetAffiliationPriceGroups(IEnumerable\<AffiliationLoyaltyTier\>)](ipricingdatamanagerv2-getaffiliationpricegroups-method-microsoft-dynamics-commerce-runtime-data.md)  

## See Also

#### Reference

[PricingDataManager Class](pricingdatamanager-class-microsoft-dynamics-commerce-runtime-data.md)

[Microsoft.Dynamics.Commerce.Runtime.Data Namespace](microsoft-dynamics-commerce-runtime-data-namespace.md)

