---
title: PricingDataServiceManager.FindPriceAdjustments Method  (Microsoft.Dynamics.Commerce.Runtime.Services)
TOCTitle: FindPriceAdjustments Method
ms:assetid: M:Microsoft.Dynamics.Commerce.Runtime.Services.PricingDataServiceManager.FindPriceAdjustments(System.Int64,System.Int64,System.Collections.Generic.IEnumerable{System.Int64},System.String,System.String,System.DateTimeOffset)
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.services.pricingdataservicemanager.findpriceadjustments(v=AX.60)
ms:contentKeyID: 65321653
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.Services.PricingDataServiceManager.FindPriceAdjustments
dev_langs:
- CSharp
- C++
- VB
---

# FindPriceAdjustments Method

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.Services](microsoft-dynamics-commerce-runtime-services-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Services (in Microsoft.Dynamics.Commerce.Runtime.Services.dll)

## Syntax

``` vb
'Declaration
Public Function FindPriceAdjustments ( _
    productId As Long, _
    distinctProductVariantId As Long, _
    priceGroupIds As IEnumerable(Of Long), _
    currencyCode As String, _
    unitOfMeasure As String, _
    dateToCheck As DateTimeOffset _
) As ReadOnlyCollection(Of PriceAdjustment)
'Usage
Dim instance As PricingDataServiceManager
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
public ReadOnlyCollection<PriceAdjustment> FindPriceAdjustments(
    long productId,
    long distinctProductVariantId,
    IEnumerable<long> priceGroupIds,
    string currencyCode,
    string unitOfMeasure,
    DateTimeOffset dateToCheck
)
```

``` c++
public:
virtual ReadOnlyCollection<PriceAdjustment^>^ FindPriceAdjustments(
    long long productId, 
    long long distinctProductVariantId, 
    IEnumerable<long long>^ priceGroupIds, 
    String^ currencyCode, 
    String^ unitOfMeasure, 
    DateTimeOffset dateToCheck
) sealed
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

#### Return Value

Type: [System.Collections.ObjectModel.ReadOnlyCollection](https://technet.microsoft.com/library/ms132474\(v=ax.60\))\<[PriceAdjustment](priceadjustment-class-microsoft-dynamics-commerce-runtime-datamodel.md)\>  

#### Implements

[IPricingDataManager.FindPriceAdjustments(Int64, Int64, IEnumerable\<Int64\>, String, String, DateTimeOffset)](ipricingdatamanager-findpriceadjustments-method-microsoft-dynamics-commerce-runtime-data.md)  

## See Also

#### Reference

[PricingDataServiceManager Class](pricingdataservicemanager-class-microsoft-dynamics-commerce-runtime-services.md)

[Microsoft.Dynamics.Commerce.Runtime.Services Namespace](microsoft-dynamics-commerce-runtime-services-namespace.md)

