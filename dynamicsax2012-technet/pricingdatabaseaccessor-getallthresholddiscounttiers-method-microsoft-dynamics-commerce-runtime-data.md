---
title: PricingDatabaseAccessor.GetAllThresholdDiscountTiers Method  (Microsoft.Dynamics.Commerce.Runtime.Data)
TOCTitle: GetAllThresholdDiscountTiers Method
ms:assetid: M:Microsoft.Dynamics.Commerce.Runtime.Data.PricingDatabaseAccessor.GetAllThresholdDiscountTiers
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.data.pricingdatabaseaccessor.getallthresholddiscounttiers(v=AX.60)
ms:contentKeyID: 62209882
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.Data.PricingDatabaseAccessor.GetAllThresholdDiscountTiers
dev_langs:
- CSharp
- C++
- VB
---

# GetAllThresholdDiscountTiers Method


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Get all of the threshold discount tiers for all threshold discounts.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.Data](microsoft-dynamics-commerce-runtime-data-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.DataManagers (in Microsoft.Dynamics.Commerce.Runtime.DataManagers.dll)

## Syntax

``` vb
'Declaration
Public Function GetAllThresholdDiscountTiers As ReadOnlyCollection(Of ThresholdDiscountTier)
'Usage
Dim instance As PricingDatabaseAccessor
Dim returnValue As ReadOnlyCollection(Of ThresholdDiscountTier)

returnValue = instance.GetAllThresholdDiscountTiers()
```

``` csharp
public ReadOnlyCollection<ThresholdDiscountTier> GetAllThresholdDiscountTiers()
```

``` c++
public:
ReadOnlyCollection<ThresholdDiscountTier^>^ GetAllThresholdDiscountTiers()
```

#### Return Value

Type: [System.Collections.ObjectModel.ReadOnlyCollection](https://technet.microsoft.com/library/ms132474\(v=ax.60\))\<[ThresholdDiscountTier](thresholddiscounttier-class-microsoft-dynamics-commerce-runtime-datamodel.md)\>  
The collection of tiers.  

## See Also

#### Reference

[PricingDatabaseAccessor Class](pricingdatabaseaccessor-class-microsoft-dynamics-commerce-runtime-data.md)

[Microsoft.Dynamics.Commerce.Runtime.Data Namespace](microsoft-dynamics-commerce-runtime-data-namespace.md)

