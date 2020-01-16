---
title: ICachedPricingDataManager.PutAllRetailDiscounts Method  (Microsoft.Dynamics.Commerce.Runtime.Data)
TOCTitle: PutAllRetailDiscounts Method
ms:assetid: M:Microsoft.Dynamics.Commerce.Runtime.Data.ICachedPricingDataManager.PutAllRetailDiscounts(System.Collections.ObjectModel.ReadOnlyCollection{Microsoft.Dynamics.Commerce.Runtime.DataModel.RetailDiscount})
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.data.icachedpricingdatamanager.putallretaildiscounts(v=AX.60)
ms:contentKeyID: 62208269
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.Data.ICachedPricingDataManager.PutAllRetailDiscounts
dev_langs:
- CSharp
- C++
- VB
---

# PutAllRetailDiscounts Method

Stores the result of a call to retrieve all retail discounts.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.Data](microsoft-dynamics-commerce-runtime-data-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.DataManagers (in Microsoft.Dynamics.Commerce.Runtime.DataManagers.dll)

## Syntax

``` vb
'Declaration
Sub PutAllRetailDiscounts ( _
    result As ReadOnlyCollection(Of RetailDiscount) _
)
'Usage
Dim instance As ICachedPricingDataManager
Dim result As ReadOnlyCollection(Of RetailDiscount)

instance.PutAllRetailDiscounts(result)
```

``` csharp
void PutAllRetailDiscounts(
    ReadOnlyCollection<RetailDiscount> result
)
```

``` c++
void PutAllRetailDiscounts(
    ReadOnlyCollection<RetailDiscount^>^ result
)
```

#### Parameters

  - result  
    Type: [System.Collections.ObjectModel.ReadOnlyCollection](https://technet.microsoft.com/library/ms132474\(v=ax.60\))\<[RetailDiscount](retaildiscount-class-microsoft-dynamics-commerce-runtime-datamodel.md)\>  

## See Also

#### Reference

[ICachedPricingDataManager Interface](icachedpricingdatamanager-interface-microsoft-dynamics-commerce-runtime-data.md)

[Microsoft.Dynamics.Commerce.Runtime.Data Namespace](microsoft-dynamics-commerce-runtime-data-namespace.md)

