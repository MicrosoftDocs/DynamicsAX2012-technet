---
title: IPricingDataManagerV2.ReadRetailDiscounts Method  (Microsoft.Dynamics.Commerce.Runtime.Data)
TOCTitle: ReadRetailDiscounts Method
ms:assetid: M:Microsoft.Dynamics.Commerce.Runtime.Data.IPricingDataManagerV2.ReadRetailDiscounts(System.Collections.Generic.IEnumerable{Microsoft.Dynamics.Commerce.Runtime.DataModel.ItemUnit},System.Collections.Generic.ISet{System.String},System.DateTimeOffset,System.DateTimeOffset,System.String,System.Collections.ObjectModel.ReadOnlyCollection{Microsoft.Dynamics.Commerce.Runtime.DataModel.ValidationPeriod}@)
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.data.ipricingdatamanagerv2.readretaildiscounts(v=AX.60)
ms:contentKeyID: 62206161
author: tonyafehr
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.Data.IPricingDataManagerV2.ReadRetailDiscounts
dev_langs:
- CSharp
- C++
- VB
---

# ReadRetailDiscounts Method


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Fetch all retail discounts for the given items, striped by item Id and dimension Id.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.Data](microsoft-dynamics-commerce-runtime-data-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.DataManagers (in Microsoft.Dynamics.Commerce.Runtime.DataManagers.dll)

## Syntax

``` vb
'Declaration
Function ReadRetailDiscounts ( _
    items As IEnumerable(Of ItemUnit), _
    priceGroups As ISet(Of String), _
    minActiveDate As DateTimeOffset, _
    maxActiveDate As DateTimeOffset, _
    currencyCode As String, _
    <OutAttribute> ByRef validationPeriods As ReadOnlyCollection(Of ValidationPeriod) _
) As ReadOnlyCollection(Of PeriodicDiscount)
'Usage
Dim instance As IPricingDataManagerV2
Dim items As IEnumerable(Of ItemUnit)
Dim priceGroups As ISet(Of String)
Dim minActiveDate As DateTimeOffset
Dim maxActiveDate As DateTimeOffset
Dim currencyCode As String
Dim validationPeriods As ReadOnlyCollection(Of ValidationPeriod)
Dim returnValue As ReadOnlyCollection(Of PeriodicDiscount)

returnValue = instance.ReadRetailDiscounts(items, _
    priceGroups, minActiveDate, maxActiveDate, _
    currencyCode, validationPeriods)
```

``` csharp
ReadOnlyCollection<PeriodicDiscount> ReadRetailDiscounts(
    IEnumerable<ItemUnit> items,
    ISet<string> priceGroups,
    DateTimeOffset minActiveDate,
    DateTimeOffset maxActiveDate,
    string currencyCode,
    out ReadOnlyCollection<ValidationPeriod> validationPeriods
)
```

``` c++
ReadOnlyCollection<PeriodicDiscount^>^ ReadRetailDiscounts(
    IEnumerable<ItemUnit^>^ items, 
    ISet<String^>^ priceGroups, 
    DateTimeOffset minActiveDate, 
    DateTimeOffset maxActiveDate, 
    String^ currencyCode, 
    [OutAttribute] ReadOnlyCollection<ValidationPeriod^>^% validationPeriods
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

  - currencyCode  
    Type: [System.String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\))  

<!-- end list -->

  - validationPeriods  
    Type: [System.Collections.ObjectModel.ReadOnlyCollection](https://technet.microsoft.com/library/ms132474\(v=ax.60\))\<[ValidationPeriod](validationperiod-class-microsoft-dynamics-commerce-runtime-datamodel.md)\>  

#### Return Value

Type: [System.Collections.ObjectModel.ReadOnlyCollection](https://technet.microsoft.com/library/ms132474\(v=ax.60\))\<[PeriodicDiscount](periodicdiscount-class-microsoft-dynamics-commerce-runtime-datamodel.md)\>  
Collection of price adjustments striped by item Id and variant dimension Id (if any).  

## See Also

#### Reference

[IPricingDataManagerV2 Interface](ipricingdatamanagerv2-interface-microsoft-dynamics-commerce-runtime-data.md)

[Microsoft.Dynamics.Commerce.Runtime.Data Namespace](microsoft-dynamics-commerce-runtime-data-namespace.md)

