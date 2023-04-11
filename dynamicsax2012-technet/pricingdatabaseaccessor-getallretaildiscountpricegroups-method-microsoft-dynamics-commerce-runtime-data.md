---
title: PricingDatabaseAccessor.GetAllRetailDiscountPriceGroups Method  (Microsoft.Dynamics.Commerce.Runtime.Data)
TOCTitle: GetAllRetailDiscountPriceGroups Method
ms:assetid: M:Microsoft.Dynamics.Commerce.Runtime.Data.PricingDatabaseAccessor.GetAllRetailDiscountPriceGroups
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.data.pricingdatabaseaccessor.getallretaildiscountpricegroups(v=AX.60)
ms:contentKeyID: 62215171
author: tonyafehr
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.Data.PricingDatabaseAccessor.GetAllRetailDiscountPriceGroups
dev_langs:
- CSharp
- C++
- VB
---

# GetAllRetailDiscountPriceGroups Method


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Get the price group relations for all discounts configured in the system.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.Data](microsoft-dynamics-commerce-runtime-data-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.DataManagers (in Microsoft.Dynamics.Commerce.Runtime.DataManagers.dll)

## Syntax

``` vb
'Declaration
Public Function GetAllRetailDiscountPriceGroups As ReadOnlyCollection(Of RetailDiscountPriceGroup)
'Usage
Dim instance As PricingDatabaseAccessor
Dim returnValue As ReadOnlyCollection(Of RetailDiscountPriceGroup)

returnValue = instance.GetAllRetailDiscountPriceGroups()
```

``` csharp
public ReadOnlyCollection<RetailDiscountPriceGroup> GetAllRetailDiscountPriceGroups()
```

``` c++
public:
ReadOnlyCollection<RetailDiscountPriceGroup^>^ GetAllRetailDiscountPriceGroups()
```

#### Return Value

Type: [System.Collections.ObjectModel.ReadOnlyCollection](https://technet.microsoft.com/library/ms132474\(v=ax.60\))\<[RetailDiscountPriceGroup](retaildiscountpricegroup-class-microsoft-dynamics-commerce-runtime-datamodel.md)\>  
The collection of price group to discount offer relationships.  

## See Also

#### Reference

[PricingDatabaseAccessor Class](pricingdatabaseaccessor-class-microsoft-dynamics-commerce-runtime-data.md)

[Microsoft.Dynamics.Commerce.Runtime.Data Namespace](microsoft-dynamics-commerce-runtime-data-namespace.md)

