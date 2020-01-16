---
title: PricingDataManager.ReadPriceAdjustments Method  (Microsoft.Dynamics.Commerce.Runtime.Data)
TOCTitle: ReadPriceAdjustments Method
ms:assetid: M:Microsoft.Dynamics.Commerce.Runtime.Data.PricingDataManager.ReadPriceAdjustments(System.Collections.Generic.IEnumerable{Microsoft.Dynamics.Commerce.Runtime.DataModel.ItemUnit},System.Collections.Generic.ISet{System.String},System.DateTimeOffset,System.DateTimeOffset,System.Collections.ObjectModel.ReadOnlyCollection{Microsoft.Dynamics.Commerce.Runtime.DataModel.ValidationPeriod}@)
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.data.pricingdatamanager.readpriceadjustments(v=AX.60)
ms:contentKeyID: 62207594
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.Data.PricingDataManager.ReadPriceAdjustments
dev_langs:
- CSharp
- C++
- VB
---

# ReadPriceAdjustments Method

Fetch all price adjustments for the given items, striped by item Id and dimension Id.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.Data](microsoft-dynamics-commerce-runtime-data-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.DataManagers (in Microsoft.Dynamics.Commerce.Runtime.DataManagers.dll)

## Syntax

``` vb
'Declaration
Public Function ReadPriceAdjustments ( _
    items As IEnumerable(Of ItemUnit), _
    priceGroups As ISet(Of String), _
    minActiveDate As DateTimeOffset, _
    maxActiveDate As DateTimeOffset, _
    <OutAttribute> ByRef validationPeriods As ReadOnlyCollection(Of ValidationPeriod) _
) As ReadOnlyCollection(Of PriceAdjustment)
'Usage
Dim instance As PricingDataManager
Dim items As IEnumerable(Of ItemUnit)
Dim priceGroups As ISet(Of String)
Dim minActiveDate As DateTimeOffset
Dim maxActiveDate As DateTimeOffset
Dim validationPeriods As ReadOnlyCollection(Of ValidationPeriod)
Dim returnValue As ReadOnlyCollection(Of PriceAdjustment)

returnValue = instance.ReadPriceAdjustments(items, _
    priceGroups, minActiveDate, maxActiveDate, _
    validationPeriods)
```

``` csharp
public ReadOnlyCollection<PriceAdjustment> ReadPriceAdjustments(
    IEnumerable<ItemUnit> items,
    ISet<string> priceGroups,
    DateTimeOffset minActiveDate,
    DateTimeOffset maxActiveDate,
    out ReadOnlyCollection<ValidationPeriod> validationPeriods
)
```

``` c++
public:
virtual ReadOnlyCollection<PriceAdjustment^>^ ReadPriceAdjustments(
    IEnumerable<ItemUnit^>^ items, 
    ISet<String^>^ priceGroups, 
    DateTimeOffset minActiveDate, 
    DateTimeOffset maxActiveDate, 
    [OutAttribute] ReadOnlyCollection<ValidationPeriod^>^% validationPeriods
) sealed
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

#### Return Value

Type: [System.Collections.ObjectModel.ReadOnlyCollection](https://technet.microsoft.com/library/ms132474\(v=ax.60\))\<[PriceAdjustment](priceadjustment-class-microsoft-dynamics-commerce-runtime-datamodel.md)\>  
Collection of price adjustments striped by item Id and variant dimension Id (if any).  

#### Implements

[IPricingDataManagerV2.ReadPriceAdjustments(IEnumerable\<ItemUnit\>, ISet\<String\>, DateTimeOffset, DateTimeOffset, ReadOnlyCollection\<ValidationPeriod\>)](ipricingdatamanagerv2-readpriceadjustments-method-microsoft-dynamics-commerce-runtime-data.md)  

## Remarks

This method may be called in a publishing context, when it may deal with thousands of items. Caching is suspended for these scenarios.

## See Also

#### Reference

[PricingDataManager Class](pricingdatamanager-class-microsoft-dynamics-commerce-runtime-data.md)

[Microsoft.Dynamics.Commerce.Runtime.Data Namespace](microsoft-dynamics-commerce-runtime-data-namespace.md)

