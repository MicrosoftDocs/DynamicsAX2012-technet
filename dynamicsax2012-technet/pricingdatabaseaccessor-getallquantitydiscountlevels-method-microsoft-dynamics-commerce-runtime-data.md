---
title: PricingDatabaseAccessor.GetAllQuantityDiscountLevels Method  (Microsoft.Dynamics.Commerce.Runtime.Data)
TOCTitle: GetAllQuantityDiscountLevels Method
ms:assetid: M:Microsoft.Dynamics.Commerce.Runtime.Data.PricingDatabaseAccessor.GetAllQuantityDiscountLevels
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.data.pricingdatabaseaccessor.getallquantitydiscountlevels(v=AX.60)
ms:contentKeyID: 62205931
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.Data.PricingDatabaseAccessor.GetAllQuantityDiscountLevels
dev_langs:
- CSharp
- C++
- VB
---

# GetAllQuantityDiscountLevels Method


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Get the quantity (multi-buy) discount threshold levels for all quantity discounts configured in the system.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.Data](microsoft-dynamics-commerce-runtime-data-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.DataManagers (in Microsoft.Dynamics.Commerce.Runtime.DataManagers.dll)

## Syntax

``` vb
'Declaration
Public Function GetAllQuantityDiscountLevels As ReadOnlyCollection(Of QuantityDiscountLevel)
'Usage
Dim instance As PricingDatabaseAccessor
Dim returnValue As ReadOnlyCollection(Of QuantityDiscountLevel)

returnValue = instance.GetAllQuantityDiscountLevels()
```

``` csharp
public ReadOnlyCollection<QuantityDiscountLevel> GetAllQuantityDiscountLevels()
```

``` c++
public:
ReadOnlyCollection<QuantityDiscountLevel^>^ GetAllQuantityDiscountLevels()
```

#### Return Value

Type: [System.Collections.ObjectModel.ReadOnlyCollection](https://technet.microsoft.com/library/ms132474\(v=ax.60\))\<[QuantityDiscountLevel](quantitydiscountlevel-class-microsoft-dynamics-commerce-runtime-datamodel.md)\>  
The collection of quantity discount levels.  

## See Also

#### Reference

[PricingDatabaseAccessor Class](pricingdatabaseaccessor-class-microsoft-dynamics-commerce-runtime-data.md)

[Microsoft.Dynamics.Commerce.Runtime.Data Namespace](microsoft-dynamics-commerce-runtime-data-namespace.md)

