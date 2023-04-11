---
title: PricingSqliteDatabaseAccessor.ReadRetailDiscounts Method  (Microsoft.Dynamics.Commerce.Runtime.DataServices.Sqlite)
TOCTitle: ReadRetailDiscounts Method
ms:assetid: M:Microsoft.Dynamics.Commerce.Runtime.DataServices.Sqlite.PricingSqliteDatabaseAccessor.ReadRetailDiscounts(System.Collections.Generic.IEnumerable{Microsoft.Dynamics.Commerce.Runtime.DataModel.ItemUnit},System.Collections.Generic.IEnumerable{System.String},System.DateTimeOffset,System.DateTimeOffset,System.String,System.Collections.ObjectModel.ReadOnlyCollection{Microsoft.Dynamics.Commerce.Runtime.DataModel.ValidationPeriod}@)
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.dataservices.sqlite.pricingsqlitedatabaseaccessor.readretaildiscounts(v=AX.60)
ms:contentKeyID: 65320310
author: tonyafehr
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataServices.Sqlite.PricingSqliteDatabaseAccessor.ReadRetailDiscounts
dev_langs:
- CSharp
- C++
- VB
---

# ReadRetailDiscounts Method


[!INCLUDE[archive-banner](includes/archive-banner.md)]

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataServices.Sqlite](microsoft-dynamics-commerce-runtime-dataservices-sqlite-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.DataServices.Sqlite (in Microsoft.Dynamics.Commerce.Runtime.DataServices.Sqlite.dll)

## Syntax

``` vb
'Declaration
Public Function ReadRetailDiscounts ( _
    items As IEnumerable(Of ItemUnit), _
    priceGroups As IEnumerable(Of String), _
    minActiveDate As DateTimeOffset, _
    maxActiveDate As DateTimeOffset, _
    currencyCode As String, _
    <OutAttribute> ByRef validationPeriods As ReadOnlyCollection(Of ValidationPeriod) _
) As ReadOnlyCollection(Of PeriodicDiscount)
'Usage
Dim instance As PricingSqliteDatabaseAccessor
Dim items As IEnumerable(Of ItemUnit)
Dim priceGroups As IEnumerable(Of String)
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
public ReadOnlyCollection<PeriodicDiscount> ReadRetailDiscounts(
    IEnumerable<ItemUnit> items,
    IEnumerable<string> priceGroups,
    DateTimeOffset minActiveDate,
    DateTimeOffset maxActiveDate,
    string currencyCode,
    out ReadOnlyCollection<ValidationPeriod> validationPeriods
)
```

``` c++
public:
ReadOnlyCollection<PeriodicDiscount^>^ ReadRetailDiscounts(
    IEnumerable<ItemUnit^>^ items, 
    IEnumerable<String^>^ priceGroups, 
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
    Type: [System.Collections.Generic.IEnumerable](https://technet.microsoft.com/library/9eekhta0\(v=ax.60\))\<[String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\))\>  

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

## See Also

#### Reference

[PricingSqliteDatabaseAccessor Class](pricingsqlitedatabaseaccessor-class-microsoft-dynamics-commerce-runtime-dataservices-sqlite.md)

[Microsoft.Dynamics.Commerce.Runtime.DataServices.Sqlite Namespace](microsoft-dynamics-commerce-runtime-dataservices-sqlite-namespace.md)

