---
title: PricingSqliteDatabaseAccessor.GetAffiliationPriceGroups Method  (Microsoft.Dynamics.Commerce.Runtime.DataServices.Sqlite)
TOCTitle: GetAffiliationPriceGroups Method
ms:assetid: M:Microsoft.Dynamics.Commerce.Runtime.DataServices.Sqlite.PricingSqliteDatabaseAccessor.GetAffiliationPriceGroups(System.Collections.Generic.IEnumerable{Microsoft.Dynamics.Commerce.Runtime.DataModel.AffiliationLoyaltyTier})
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.dataservices.sqlite.pricingsqlitedatabaseaccessor.getaffiliationpricegroups(v=AX.60)
ms:contentKeyID: 65317492
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataServices.Sqlite.PricingSqliteDatabaseAccessor.GetAffiliationPriceGroups
dev_langs:
- CSharp
- C++
- VB
---

# GetAffiliationPriceGroups Method

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataServices.Sqlite](microsoft-dynamics-commerce-runtime-dataservices-sqlite-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.DataServices.Sqlite (in Microsoft.Dynamics.Commerce.Runtime.DataServices.Sqlite.dll)

## Syntax

``` vb
'Declaration
Public Function GetAffiliationPriceGroups ( _
    affiliationLoyaltyTiers As IEnumerable(Of AffiliationLoyaltyTier) _
) As ReadOnlyCollection(Of PriceGroup)
'Usage
Dim instance As PricingSqliteDatabaseAccessor
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
ReadOnlyCollection<PriceGroup^>^ GetAffiliationPriceGroups(
    IEnumerable<AffiliationLoyaltyTier^>^ affiliationLoyaltyTiers
)
```

#### Parameters

  - affiliationLoyaltyTiers  
    Type: [System.Collections.Generic.IEnumerable](https://technet.microsoft.com/library/9eekhta0\(v=ax.60\))\<[AffiliationLoyaltyTier](affiliationloyaltytier-class-microsoft-dynamics-commerce-runtime-datamodel.md)\>  

#### Return Value

Type: [System.Collections.ObjectModel.ReadOnlyCollection](https://technet.microsoft.com/library/ms132474\(v=ax.60\))\<[PriceGroup](pricegroup-class-microsoft-dynamics-commerce-runtime-datamodel.md)\>  

## See Also

#### Reference

[PricingSqliteDatabaseAccessor Class](pricingsqlitedatabaseaccessor-class-microsoft-dynamics-commerce-runtime-dataservices-sqlite.md)

[Microsoft.Dynamics.Commerce.Runtime.DataServices.Sqlite Namespace](microsoft-dynamics-commerce-runtime-dataservices-sqlite-namespace.md)

