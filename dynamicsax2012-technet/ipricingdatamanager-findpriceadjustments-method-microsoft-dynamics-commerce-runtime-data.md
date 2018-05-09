---
title: IPricingDataManager.FindPriceAdjustments Method  (Microsoft.Dynamics.Commerce.Runtime.Data)
TOCTitle: FindPriceAdjustments Method
ms:assetid: M:Microsoft.Dynamics.Commerce.Runtime.Data.IPricingDataManager.FindPriceAdjustments(System.Int64,System.Int64,System.Collections.Generic.IEnumerable{System.Int64},System.String,System.String,System.DateTimeOffset)
ms:mtpsurl: https://technet.microsoft.com/en-us/library/microsoft.dynamics.commerce.runtime.data.ipricingdatamanager.findpriceadjustments(v=AX.60)
ms:contentKeyID: 62211443
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.Data.IPricingDataManager.FindPriceAdjustments
dev_langs:
- CSharp
- C++
- VB
---

# FindPriceAdjustments Method

Get all retail price adjustments matching the given product, channel price groups, currency, unit of measure, and date.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.Data](microsoft-dynamics-commerce-runtime-data-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.DataManagers (in Microsoft.Dynamics.Commerce.Runtime.DataManagers.dll)

## Syntax

``` vb
'Declaration
Function FindPriceAdjustments ( _
    productId As Long, _
    distinctProductVariantId As Long, _
    priceGroupIds As IEnumerable(Of Long), _
    currencyCode As String, _
    unitOfMeasure As String, _
    dateToCheck As DateTimeOffset _
) As ReadOnlyCollection(Of PriceAdjustment)
'Usage
Dim instance As IPricingDataManager
Dim productId As Long
Dim distinctProductVariantId As Long
Dim priceGroupIds As IEnumerable(Of Long)
Dim currencyCode As String
Dim unitOfMeasure As String
Dim dateToCheck As DateTimeOffset
Dim returnValue As ReadOnlyCollection(Of PriceAdjustment)

returnValue = instance.FindPriceAdjustments(productId, _
    distinctProductVariantId, priceGroupIds, _
    currencyCode, unitOfMeasure, dateToCheck)
```

``` csharp
ReadOnlyCollection<PriceAdjustment> FindPriceAdjustments(
    long productId,
    long distinctProductVariantId,
    IEnumerable<long> priceGroupIds,
    string currencyCode,
    string unitOfMeasure,
    DateTimeOffset dateToCheck
)
```

``` c++
ReadOnlyCollection<PriceAdjustment^>^ FindPriceAdjustments(
    long long productId, 
    long long distinctProductVariantId, 
    IEnumerable<long long>^ priceGroupIds, 
    String^ currencyCode, 
    String^ unitOfMeasure, 
    DateTimeOffset dateToCheck
)
```

#### Parameters

  - productId  
    Type: [System.Int64](https://technet.microsoft.com/en-us/library/6yy583ek\(v=ax.60\))  

<!-- end list -->

  - distinctProductVariantId  
    Type: [System.Int64](https://technet.microsoft.com/en-us/library/6yy583ek\(v=ax.60\))  

<!-- end list -->

  - priceGroupIds  
    Type: [System.Collections.Generic.IEnumerable](https://technet.microsoft.com/en-us/library/9eekhta0\(v=ax.60\))\<[Int64](https://technet.microsoft.com/en-us/library/6yy583ek\(v=ax.60\))\>  

<!-- end list -->

  - currencyCode  
    Type: [System.String](https://technet.microsoft.com/en-us/library/s1wwdcbf\(v=ax.60\))  

<!-- end list -->

  - unitOfMeasure  
    Type: [System.String](https://technet.microsoft.com/en-us/library/s1wwdcbf\(v=ax.60\))  

<!-- end list -->

  - dateToCheck  
    Type: [System.DateTimeOffset](https://technet.microsoft.com/en-us/library/bb341783\(v=ax.60\))  

#### Return Value

Type: [System.Collections.ObjectModel.ReadOnlyCollection](https://technet.microsoft.com/en-us/library/ms132474\(v=ax.60\))\<[PriceAdjustment](priceadjustment-class-microsoft-dynamics-commerce-runtime-datamodel.md)\>  
All price adjustment rules which may apply to the item and context given.  

## See Also

#### Reference

[IPricingDataManager Interface](ipricingdatamanager-interface-microsoft-dynamics-commerce-runtime-data.md)

[Microsoft.Dynamics.Commerce.Runtime.Data Namespace](microsoft-dynamics-commerce-runtime-data-namespace.md)

