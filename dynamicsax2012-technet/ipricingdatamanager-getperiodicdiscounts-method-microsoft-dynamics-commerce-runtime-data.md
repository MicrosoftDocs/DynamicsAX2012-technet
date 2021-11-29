---
title: IPricingDataManager.GetPeriodicDiscounts Method  (Microsoft.Dynamics.Commerce.Runtime.Data)
TOCTitle: GetPeriodicDiscounts Method
ms:assetid: M:Microsoft.Dynamics.Commerce.Runtime.Data.IPricingDataManager.GetPeriodicDiscounts(System.Int64,System.Int64,System.Collections.Generic.IEnumerable{System.Int64},System.String,System.DateTimeOffset)
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.data.ipricingdatamanager.getperiodicdiscounts(v=AX.60)
ms:contentKeyID: 62204217
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.Data.IPricingDataManager.GetPeriodicDiscounts
dev_langs:
- CSharp
- C++
- VB
---

# GetPeriodicDiscounts Method


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Get all retail periodic discounts (offer, quantity discounts, and mix and match discount) configurations which match the given product and context.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.Data](microsoft-dynamics-commerce-runtime-data-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.DataManagers (in Microsoft.Dynamics.Commerce.Runtime.DataManagers.dll)

## Syntax

``` vb
'Declaration
Function GetPeriodicDiscounts ( _
    productId As Long, _
    variantId As Long, _
    priceGroupIds As IEnumerable(Of Long), _
    currencyCode As String, _
    activeDate As DateTimeOffset _
) As ReadOnlyCollection(Of PeriodicDiscount)
'Usage
Dim instance As IPricingDataManager
Dim productId As Long
Dim variantId As Long
Dim priceGroupIds As IEnumerable(Of Long)
Dim currencyCode As String
Dim activeDate As DateTimeOffset
Dim returnValue As ReadOnlyCollection(Of PeriodicDiscount)

returnValue = instance.GetPeriodicDiscounts(productId, _
    variantId, priceGroupIds, currencyCode, _
    activeDate)
```

``` csharp
ReadOnlyCollection<PeriodicDiscount> GetPeriodicDiscounts(
    long productId,
    long variantId,
    IEnumerable<long> priceGroupIds,
    string currencyCode,
    DateTimeOffset activeDate
)
```

``` c++
ReadOnlyCollection<PeriodicDiscount^>^ GetPeriodicDiscounts(
    long long productId, 
    long long variantId, 
    IEnumerable<long long>^ priceGroupIds, 
    String^ currencyCode, 
    DateTimeOffset activeDate
)
```

#### Parameters

  - productId  
    Type: [System.Int64](https://technet.microsoft.com/library/6yy583ek\(v=ax.60\))  

<!-- end list -->

  - variantId  
    Type: [System.Int64](https://technet.microsoft.com/library/6yy583ek\(v=ax.60\))  

<!-- end list -->

  - priceGroupIds  
    Type: [System.Collections.Generic.IEnumerable](https://technet.microsoft.com/library/9eekhta0\(v=ax.60\))\<[Int64](https://technet.microsoft.com/library/6yy583ek\(v=ax.60\))\>  

<!-- end list -->

  - currencyCode  
    Type: [System.String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\))  

<!-- end list -->

  - activeDate  
    Type: [System.DateTimeOffset](https://technet.microsoft.com/library/bb341783\(v=ax.60\))  

#### Return Value

Type: [System.Collections.ObjectModel.ReadOnlyCollection](https://technet.microsoft.com/library/ms132474\(v=ax.60\))\<[PeriodicDiscount](periodicdiscount-class-microsoft-dynamics-commerce-runtime-datamodel.md)\>  
All periodic discount rules which may apply to the item and context given.  

## See Also

#### Reference

[IPricingDataManager Interface](ipricingdatamanager-interface-microsoft-dynamics-commerce-runtime-data.md)

[Microsoft.Dynamics.Commerce.Runtime.Data Namespace](microsoft-dynamics-commerce-runtime-data-namespace.md)

