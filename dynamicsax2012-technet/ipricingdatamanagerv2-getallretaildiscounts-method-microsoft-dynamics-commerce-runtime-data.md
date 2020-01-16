---
title: IPricingDataManagerV2.GetAllRetailDiscounts Method  (Microsoft.Dynamics.Commerce.Runtime.Data)
TOCTitle: GetAllRetailDiscounts Method
ms:assetid: M:Microsoft.Dynamics.Commerce.Runtime.Data.IPricingDataManagerV2.GetAllRetailDiscounts
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.data.ipricingdatamanagerv2.getallretaildiscounts(v=AX.60)
ms:contentKeyID: 62211769
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.Data.IPricingDataManagerV2.GetAllRetailDiscounts
dev_langs:
- CSharp
- C++
- VB
---

# GetAllRetailDiscounts Method

Get all of the discounts configured in the system.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.Data](microsoft-dynamics-commerce-runtime-data-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.DataManagers (in Microsoft.Dynamics.Commerce.Runtime.DataManagers.dll)

## Syntax

``` vb
'Declaration
Function GetAllRetailDiscounts As ReadOnlyCollection(Of RetailDiscount)
'Usage
Dim instance As IPricingDataManagerV2
Dim returnValue As ReadOnlyCollection(Of RetailDiscount)

returnValue = instance.GetAllRetailDiscounts()
```

``` csharp
ReadOnlyCollection<RetailDiscount> GetAllRetailDiscounts()
```

``` c++
ReadOnlyCollection<RetailDiscount^>^ GetAllRetailDiscounts()
```

#### Return Value

Type: [System.Collections.ObjectModel.ReadOnlyCollection](https://technet.microsoft.com/library/ms132474\(v=ax.60\))\<[RetailDiscount](retaildiscount-class-microsoft-dynamics-commerce-runtime-datamodel.md)\>  
The collection of discounts.  

## See Also

#### Reference

[IPricingDataManagerV2 Interface](ipricingdatamanagerv2-interface-microsoft-dynamics-commerce-runtime-data.md)

[Microsoft.Dynamics.Commerce.Runtime.Data Namespace](microsoft-dynamics-commerce-runtime-data-namespace.md)

