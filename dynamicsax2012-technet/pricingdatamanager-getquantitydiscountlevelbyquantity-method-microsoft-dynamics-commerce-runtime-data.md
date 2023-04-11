---
title: PricingDataManager.GetQuantityDiscountLevelByQuantity Method  (Microsoft.Dynamics.Commerce.Runtime.Data)
TOCTitle: GetQuantityDiscountLevelByQuantity Method
ms:assetid: M:Microsoft.Dynamics.Commerce.Runtime.Data.PricingDataManager.GetQuantityDiscountLevelByQuantity(System.String,System.Decimal)
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.data.pricingdatamanager.getquantitydiscountlevelbyquantity(v=AX.60)
ms:contentKeyID: 49847863
author: tonyafehr
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.Data.PricingDataManager.GetQuantityDiscountLevelByQuantity
dev_langs:
- CSharp
- C++
- VB
---

# GetQuantityDiscountLevelByQuantity Method


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Get the quantity discount threshold level which the given quantity qualifies for on the given offer.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.Data](microsoft-dynamics-commerce-runtime-data-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.DataManagers (in Microsoft.Dynamics.Commerce.Runtime.DataManagers.dll)

## Syntax

``` vb
'Declaration
Public Function GetQuantityDiscountLevelByQuantity ( _
    offerId As String, _
    quantity As Decimal _
) As QuantityDiscountLevel
'Usage
Dim instance As PricingDataManager
Dim offerId As String
Dim quantity As Decimal
Dim returnValue As QuantityDiscountLevel

returnValue = instance.GetQuantityDiscountLevelByQuantity(offerId, _
    quantity)
```

``` csharp
public QuantityDiscountLevel GetQuantityDiscountLevelByQuantity(
    string offerId,
    decimal quantity
)
```

``` c++
public:
virtual QuantityDiscountLevel^ GetQuantityDiscountLevelByQuantity(
    String^ offerId, 
    Decimal quantity
) sealed
```

#### Parameters

  - offerId  
    Type: [System.String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\))  

<!-- end list -->

  - quantity  
    Type: [System.Decimal](https://technet.microsoft.com/library/1k2e8atx\(v=ax.60\))  

#### Return Value

Type: [Microsoft.Dynamics.Commerce.Runtime.DataModel.QuantityDiscountLevel](quantitydiscountlevel-class-microsoft-dynamics-commerce-runtime-datamodel.md)  
Threshold configuration with amount for the given quantity and discount.  

#### Implements

[IPricingDataManager.GetQuantityDiscountLevelByQuantity(String, Decimal)](ipricingdatamanager-getquantitydiscountlevelbyquantity-method-microsoft-dynamics-commerce-runtime-data.md)  

## See Also

#### Reference

[PricingDataManager Class](pricingdatamanager-class-microsoft-dynamics-commerce-runtime-data.md)

[Microsoft.Dynamics.Commerce.Runtime.Data Namespace](microsoft-dynamics-commerce-runtime-data-namespace.md)

