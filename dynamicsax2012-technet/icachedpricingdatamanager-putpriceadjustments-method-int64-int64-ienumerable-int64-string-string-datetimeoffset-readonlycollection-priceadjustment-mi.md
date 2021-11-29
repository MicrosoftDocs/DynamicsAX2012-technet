---
title: ICachedPricingDataManager.PutPriceAdjustments Method (Int64, Int64, IEnumerable(Int64), String, String, DateTimeOffset, ReadOnlyCollection(PriceAdjustment)) (Microsoft.Dynamics.Commerce.Runtime.Data)
TOCTitle: PutPriceAdjustments Method (Int64, Int64, IEnumerable(Int64), String, String, DateTimeOffset, ReadOnlyCollection(PriceAdjustment))
ms:assetid: M:Microsoft.Dynamics.Commerce.Runtime.Data.ICachedPricingDataManager.PutPriceAdjustments(System.Int64,System.Int64,System.Collections.Generic.IEnumerable{System.Int64},System.String,System.String,System.DateTimeOffset,System.Collections.ObjectModel.ReadOnlyCollection{Microsoft.Dynamics.Commerce.Runtime.DataModel.PriceAdjustment})
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.data.icachedpricingdatamanager.putpriceadjustments(v=AX.60)
ms:contentKeyID: 62208477
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
dev_langs:
- vb
- csharp
- c++
---

# PutPriceAdjustments Method (Int64, Int64, IEnumerable(Int64), String, String, DateTimeOffset, ReadOnlyCollection(PriceAdjustment))


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Get all retail price adjustments matching the given product, channel price groups, currency, unit of measure, and date.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.Data](microsoft-dynamics-commerce-runtime-data-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.DataManagers (in Microsoft.Dynamics.Commerce.Runtime.DataManagers.dll)

## Syntax

``` vb
'Declaration
Sub PutPriceAdjustments ( _
    productId As Long, _
    distinctProductVariantId As Long, _
    priceGroupIds As IEnumerable(Of Long), _
    currencyCode As String, _
    unitOfMeasure As String, _
    dateToCheck As DateTimeOffset, _
    result As ReadOnlyCollection(Of PriceAdjustment) _
)
'Usage
Dim instance As ICachedPricingDataManager
Dim productId As Long
Dim distinctProductVariantId As Long
Dim priceGroupIds As IEnumerable(Of Long)
Dim currencyCode As String
Dim unitOfMeasure As String
Dim dateToCheck As DateTimeOffset
Dim result As ReadOnlyCollection(Of PriceAdjustment)

instance.PutPriceAdjustments(productId, _
    distinctProductVariantId, priceGroupIds, _
    currencyCode, unitOfMeasure, dateToCheck, _
    result)
```

``` csharp
void PutPriceAdjustments(
    long productId,
    long distinctProductVariantId,
    IEnumerable<long> priceGroupIds,
    string currencyCode,
    string unitOfMeasure,
    DateTimeOffset dateToCheck,
    ReadOnlyCollection<PriceAdjustment> result
)
```

``` c++
void PutPriceAdjustments(
    long long productId, 
    long long distinctProductVariantId, 
    IEnumerable<long long>^ priceGroupIds, 
    String^ currencyCode, 
    String^ unitOfMeasure, 
    DateTimeOffset dateToCheck, 
    ReadOnlyCollection<PriceAdjustment^>^ result
)
```

#### Parameters

  - productId  
    Type: [System.Int64](https://technet.microsoft.com/library/6yy583ek\(v=ax.60\))  

<!-- end list -->

  - distinctProductVariantId  
    Type: [System.Int64](https://technet.microsoft.com/library/6yy583ek\(v=ax.60\))  

<!-- end list -->

  - priceGroupIds  
    Type: [System.Collections.Generic.IEnumerable](https://technet.microsoft.com/library/9eekhta0\(v=ax.60\))\<[Int64](https://technet.microsoft.com/library/6yy583ek\(v=ax.60\))\>  

<!-- end list -->

  - currencyCode  
    Type: [System.String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\))  

<!-- end list -->

  - unitOfMeasure  
    Type: [System.String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\))  

<!-- end list -->

  - dateToCheck  
    Type: [System.DateTimeOffset](https://technet.microsoft.com/library/bb341783\(v=ax.60\))  

<!-- end list -->

  - result  
    Type: [System.Collections.ObjectModel.ReadOnlyCollection](https://technet.microsoft.com/library/ms132474\(v=ax.60\))\<[PriceAdjustment](priceadjustment-class-microsoft-dynamics-commerce-runtime-datamodel.md)\>  

## See Also

#### Reference

[ICachedPricingDataManager Interface](icachedpricingdatamanager-interface-microsoft-dynamics-commerce-runtime-data.md)

[PutPriceAdjustments Overload](icachedpricingdatamanager-putpriceadjustments-method-microsoft-dynamics-commerce-runtime-data.md)

[Microsoft.Dynamics.Commerce.Runtime.Data Namespace](microsoft-dynamics-commerce-runtime-data-namespace.md)

