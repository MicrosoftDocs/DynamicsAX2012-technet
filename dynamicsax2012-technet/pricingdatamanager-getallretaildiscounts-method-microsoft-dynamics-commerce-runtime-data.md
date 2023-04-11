---
title: PricingDataManager.GetAllRetailDiscounts Method  (Microsoft.Dynamics.Commerce.Runtime.Data)
TOCTitle: GetAllRetailDiscounts Method
ms:assetid: M:Microsoft.Dynamics.Commerce.Runtime.Data.PricingDataManager.GetAllRetailDiscounts
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.data.pricingdatamanager.getallretaildiscounts(v=AX.60)
ms:contentKeyID: 62209917
author: tonyafehr
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.Data.PricingDataManager.GetAllRetailDiscounts
dev_langs:
- CSharp
- C++
- VB
---

# GetAllRetailDiscounts Method


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Get all of the discounts configured in the system.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.Data](microsoft-dynamics-commerce-runtime-data-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.DataManagers (in Microsoft.Dynamics.Commerce.Runtime.DataManagers.dll)

## Syntax

``` vb
'Declaration
Public Function GetAllRetailDiscounts As ReadOnlyCollection(Of RetailDiscount)
'Usage
Dim instance As PricingDataManager
Dim returnValue As ReadOnlyCollection(Of RetailDiscount)

returnValue = instance.GetAllRetailDiscounts()
```

``` csharp
public ReadOnlyCollection<RetailDiscount> GetAllRetailDiscounts()
```

``` c++
public:
virtual ReadOnlyCollection<RetailDiscount^>^ GetAllRetailDiscounts() sealed
```

#### Return Value

Type: [System.Collections.ObjectModel.ReadOnlyCollection](https://technet.microsoft.com/library/ms132474\(v=ax.60\))\<[RetailDiscount](retaildiscount-class-microsoft-dynamics-commerce-runtime-datamodel.md)\>  
The collection of discounts.  

#### Implements

[IPricingDataManagerV2.GetAllRetailDiscounts()](ipricingdatamanagerv2-getallretaildiscounts-method-microsoft-dynamics-commerce-runtime-data.md)  

## See Also

#### Reference

[PricingDataManager Class](pricingdatamanager-class-microsoft-dynamics-commerce-runtime-data.md)

[Microsoft.Dynamics.Commerce.Runtime.Data Namespace](microsoft-dynamics-commerce-runtime-data-namespace.md)

