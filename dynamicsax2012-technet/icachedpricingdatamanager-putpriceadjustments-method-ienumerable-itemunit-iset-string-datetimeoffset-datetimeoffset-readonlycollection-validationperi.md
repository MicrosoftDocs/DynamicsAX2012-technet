---
title: ICachedPricingDataManager.PutPriceAdjustments Method (IEnumerable(ItemUnit), ISet(String), DateTimeOffset, DateTimeOffset, ReadOnlyCollection(ValidationPeriod), ReadOnlyCollection(PriceAdjustment)) (Microsoft.Dynamics.Commerce.Runtime.Data)
TOCTitle: PutPriceAdjustments Method (IEnumerable(ItemUnit), ISet(String), DateTimeOffset, DateTimeOffset, ReadOnlyCollection(ValidationPeriod), ReadOnlyCollection(PriceAdjustment))
ms:assetid: M:Microsoft.Dynamics.Commerce.Runtime.Data.ICachedPricingDataManager.PutPriceAdjustments(System.Collections.Generic.IEnumerable{Microsoft.Dynamics.Commerce.Runtime.DataModel.ItemUnit},System.Collections.Generic.ISet{System.String},System.DateTimeOffset,System.DateTimeOffset,System.Collections.ObjectModel.ReadOnlyCollection{Microsoft.Dynamics.Commerce.Runtime.DataModel.ValidationPeriod},System.Collections.ObjectModel.ReadOnlyCollection{Microsoft.Dynamics.Commerce.Runtime.DataModel.PriceAdjustment})
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.data.icachedpricingdatamanager.putpriceadjustments(v=AX.60)
ms:contentKeyID: 62208965
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
dev_langs:
- vb
- csharp
- c++
---

# PutPriceAdjustments Method (IEnumerable(ItemUnit), ISet(String), DateTimeOffset, DateTimeOffset, ReadOnlyCollection(ValidationPeriod), ReadOnlyCollection(PriceAdjustment))


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Fetch all price adjustments for the given items, striped by item Id and dimension Id.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.Data](microsoft-dynamics-commerce-runtime-data-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.DataManagers (in Microsoft.Dynamics.Commerce.Runtime.DataManagers.dll)

## Syntax

``` vb
'Declaration
Sub PutPriceAdjustments ( _
    items As IEnumerable(Of ItemUnit), _
    priceGroups As ISet(Of String), _
    minActiveDate As DateTimeOffset, _
    maxActiveDate As DateTimeOffset, _
    validationPeriods As ReadOnlyCollection(Of ValidationPeriod), _
    result As ReadOnlyCollection(Of PriceAdjustment) _
)
'Usage
Dim instance As ICachedPricingDataManager
Dim items As IEnumerable(Of ItemUnit)
Dim priceGroups As ISet(Of String)
Dim minActiveDate As DateTimeOffset
Dim maxActiveDate As DateTimeOffset
Dim validationPeriods As ReadOnlyCollection(Of ValidationPeriod)
Dim result As ReadOnlyCollection(Of PriceAdjustment)

instance.PutPriceAdjustments(items, priceGroups, _
    minActiveDate, maxActiveDate, validationPeriods, _
    result)
```

``` csharp
void PutPriceAdjustments(
    IEnumerable<ItemUnit> items,
    ISet<string> priceGroups,
    DateTimeOffset minActiveDate,
    DateTimeOffset maxActiveDate,
    ReadOnlyCollection<ValidationPeriod> validationPeriods,
    ReadOnlyCollection<PriceAdjustment> result
)
```

``` c++
void PutPriceAdjustments(
    IEnumerable<ItemUnit^>^ items, 
    ISet<String^>^ priceGroups, 
    DateTimeOffset minActiveDate, 
    DateTimeOffset maxActiveDate, 
    ReadOnlyCollection<ValidationPeriod^>^ validationPeriods, 
    ReadOnlyCollection<PriceAdjustment^>^ result
)
```

#### Parameters

  - items  
    Type: [System.Collections.Generic.IEnumerable](https://technet.microsoft.com/library/9eekhta0\(v=ax.60\))\<[ItemUnit](itemunit-class-microsoft-dynamics-commerce-runtime-datamodel.md)\>  

<!-- end list -->

  - priceGroups  
    Type: [System.Collections.Generic.ISet](https://technet.microsoft.com/library/dd412081\(v=ax.60\))\<[String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\))\>  

<!-- end list -->

  - minActiveDate  
    Type: [System.DateTimeOffset](https://technet.microsoft.com/library/bb341783\(v=ax.60\))  

<!-- end list -->

  - maxActiveDate  
    Type: [System.DateTimeOffset](https://technet.microsoft.com/library/bb341783\(v=ax.60\))  

<!-- end list -->

  - validationPeriods  
    Type: [System.Collections.ObjectModel.ReadOnlyCollection](https://technet.microsoft.com/library/ms132474\(v=ax.60\))\<[ValidationPeriod](validationperiod-class-microsoft-dynamics-commerce-runtime-datamodel.md)\>  

<!-- end list -->

  - result  
    Type: [System.Collections.ObjectModel.ReadOnlyCollection](https://technet.microsoft.com/library/ms132474\(v=ax.60\))\<[PriceAdjustment](priceadjustment-class-microsoft-dynamics-commerce-runtime-datamodel.md)\>  

## See Also

#### Reference

[ICachedPricingDataManager Interface](icachedpricingdatamanager-interface-microsoft-dynamics-commerce-runtime-data.md)

[PutPriceAdjustments Overload](icachedpricingdatamanager-putpriceadjustments-method-microsoft-dynamics-commerce-runtime-data.md)

[Microsoft.Dynamics.Commerce.Runtime.Data Namespace](microsoft-dynamics-commerce-runtime-data-namespace.md)

