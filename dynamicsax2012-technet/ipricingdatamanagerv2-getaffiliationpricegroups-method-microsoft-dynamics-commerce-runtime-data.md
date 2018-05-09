---
title: IPricingDataManagerV2.GetAffiliationPriceGroups Method  (Microsoft.Dynamics.Commerce.Runtime.Data)
TOCTitle: GetAffiliationPriceGroups Method
ms:assetid: M:Microsoft.Dynamics.Commerce.Runtime.Data.IPricingDataManagerV2.GetAffiliationPriceGroups(System.Collections.Generic.IEnumerable{Microsoft.Dynamics.Commerce.Runtime.DataModel.AffiliationLoyaltyTier})
ms:mtpsurl: https://technet.microsoft.com/en-us/library/microsoft.dynamics.commerce.runtime.data.ipricingdatamanagerv2.getaffiliationpricegroups(v=AX.60)
ms:contentKeyID: 62211669
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.Data.IPricingDataManagerV2.GetAffiliationPriceGroups
dev_langs:
- CSharp
- C++
- VB
---

# GetAffiliationPriceGroups Method

Gets the affiliation price groups.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.Data](microsoft-dynamics-commerce-runtime-data-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.DataManagers (in Microsoft.Dynamics.Commerce.Runtime.DataManagers.dll)

## Syntax

``` vb
'Declaration
Function GetAffiliationPriceGroups ( _
    affiliationLoyaltyTiers As IEnumerable(Of AffiliationLoyaltyTier) _
) As ReadOnlyCollection(Of PriceGroup)
'Usage
Dim instance As IPricingDataManagerV2
Dim affiliationLoyaltyTiers As IEnumerable(Of AffiliationLoyaltyTier)
Dim returnValue As ReadOnlyCollection(Of PriceGroup)

returnValue = instance.GetAffiliationPriceGroups(affiliationLoyaltyTiers)
```

``` csharp
ReadOnlyCollection<PriceGroup> GetAffiliationPriceGroups(
    IEnumerable<AffiliationLoyaltyTier> affiliationLoyaltyTiers
)
```

``` c++
ReadOnlyCollection<PriceGroup^>^ GetAffiliationPriceGroups(
    IEnumerable<AffiliationLoyaltyTier^>^ affiliationLoyaltyTiers
)
```

#### Parameters

  - affiliationLoyaltyTiers  
    Type: [System.Collections.Generic.IEnumerable](https://technet.microsoft.com/en-us/library/9eekhta0\(v=ax.60\))\<[AffiliationLoyaltyTier](affiliationloyaltytier-class-microsoft-dynamics-commerce-runtime-datamodel.md)\>  

#### Return Value

Type: [System.Collections.ObjectModel.ReadOnlyCollection](https://technet.microsoft.com/en-us/library/ms132474\(v=ax.60\))\<[PriceGroup](pricegroup-class-microsoft-dynamics-commerce-runtime-datamodel.md)\>  
A collection of affiliation price groups.  

## See Also

#### Reference

[IPricingDataManagerV2 Interface](ipricingdatamanagerv2-interface-microsoft-dynamics-commerce-runtime-data.md)

[Microsoft.Dynamics.Commerce.Runtime.Data Namespace](microsoft-dynamics-commerce-runtime-data-namespace.md)

