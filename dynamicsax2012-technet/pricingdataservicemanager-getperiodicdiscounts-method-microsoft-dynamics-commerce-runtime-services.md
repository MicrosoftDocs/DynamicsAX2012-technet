---
title: PricingDataServiceManager.GetPeriodicDiscounts Method  (Microsoft.Dynamics.Commerce.Runtime.Services)
TOCTitle: GetPeriodicDiscounts Method
ms:assetid: M:Microsoft.Dynamics.Commerce.Runtime.Services.PricingDataServiceManager.GetPeriodicDiscounts(System.Int64,System.Int64,System.Collections.Generic.IEnumerable{System.Int64},System.String,System.DateTimeOffset)
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.services.pricingdataservicemanager.getperiodicdiscounts(v=AX.60)
ms:contentKeyID: 65322404
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.Services.PricingDataServiceManager.GetPeriodicDiscounts
dev_langs:
- CSharp
- C++
- VB
---

# GetPeriodicDiscounts Method

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.Services](microsoft-dynamics-commerce-runtime-services-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Services (in Microsoft.Dynamics.Commerce.Runtime.Services.dll)

## Syntax

``` vb
'Declaration
Public Function GetPeriodicDiscounts ( _
    productId As Long, _
    variantId As Long, _
    priceGroupIds As IEnumerable(Of Long), _
    currencyCode As String, _
    activeDate As DateTimeOffset _
) As ReadOnlyCollection(Of PeriodicDiscount)
'Usage
Dim instance As PricingDataServiceManager
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
public ReadOnlyCollection<PeriodicDiscount> GetPeriodicDiscounts(
    long productId,
    long variantId,
    IEnumerable<long> priceGroupIds,
    string currencyCode,
    DateTimeOffset activeDate
)
```

``` c++
public:
virtual ReadOnlyCollection<PeriodicDiscount^>^ GetPeriodicDiscounts(
    long long productId, 
    long long variantId, 
    IEnumerable<long long>^ priceGroupIds, 
    String^ currencyCode, 
    DateTimeOffset activeDate
) sealed
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

#### Implements

[IPricingDataManager.GetPeriodicDiscounts(Int64, Int64, IEnumerable\<Int64\>, String, DateTimeOffset)](ipricingdatamanager-getperiodicdiscounts-method-microsoft-dynamics-commerce-runtime-data.md)  

## See Also

#### Reference

[PricingDataServiceManager Class](pricingdataservicemanager-class-microsoft-dynamics-commerce-runtime-services.md)

[Microsoft.Dynamics.Commerce.Runtime.Services Namespace](microsoft-dynamics-commerce-runtime-services-namespace.md)

