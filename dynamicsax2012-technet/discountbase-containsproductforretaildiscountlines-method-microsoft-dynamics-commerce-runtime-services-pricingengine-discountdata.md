---
title: DiscountBase.ContainsProductForRetailDiscountLines Method  (Microsoft.Dynamics.Commerce.Runtime.Services.PricingEngine.DiscountData)
TOCTitle: ContainsProductForRetailDiscountLines Method
ms:assetid: M:Microsoft.Dynamics.Commerce.Runtime.Services.PricingEngine.DiscountData.DiscountBase.ContainsProductForRetailDiscountLines(System.Int64,System.Int64,System.String)
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.services.pricingengine.discountdata.discountbase.containsproductforretaildiscountlines(v=AX.60)
ms:contentKeyID: 62213513
author: tonyafehr
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.Services.PricingEngine.DiscountData.DiscountBase.ContainsProductForRetailDiscountLines
dev_langs:
- CSharp
- C++
- VB
---

# ContainsProductForRetailDiscountLines Method


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Determines if the trigger products contain the product or the variant Id.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.Services.PricingEngine.DiscountData](microsoft-dynamics-commerce-runtime-services-pricingengine-discountdata-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Services.PricingEngine (in Microsoft.Dynamics.Commerce.Runtime.Services.PricingEngine.dll)

## Syntax

``` vb
'Declaration
Protected Function ContainsProductForRetailDiscountLines ( _
    productOrVariantId As Long, _
    masterProductId As Long, _
    unitOfMeasure As String _
) As Boolean
'Usage
Dim productOrVariantId As Long
Dim masterProductId As Long
Dim unitOfMeasure As String
Dim returnValue As Boolean

returnValue = Me.ContainsProductForRetailDiscountLines(productOrVariantId, _
    masterProductId, unitOfMeasure)
```

``` csharp
protected bool ContainsProductForRetailDiscountLines(
    long productOrVariantId,
    long masterProductId,
    string unitOfMeasure
)
```

``` c++
protected:
bool ContainsProductForRetailDiscountLines(
    long long productOrVariantId, 
    long long masterProductId, 
    String^ unitOfMeasure
)
```

#### Parameters

  - productOrVariantId  
    Type: [System.Int64](https://technet.microsoft.com/library/6yy583ek\(v=ax.60\))  

<!-- end list -->

  - masterProductId  
    Type: [System.Int64](https://technet.microsoft.com/library/6yy583ek\(v=ax.60\))  

<!-- end list -->

  - unitOfMeasure  
    Type: [System.String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\))  

#### Return Value

Type: [System.Boolean](https://technet.microsoft.com/library/a28wyd50\(v=ax.60\))  
True if found.  

## See Also

#### Reference

[DiscountBase Class](discountbase-class-microsoft-dynamics-commerce-runtime-services-pricingengine-discountdata.md)

[Microsoft.Dynamics.Commerce.Runtime.Services.PricingEngine.DiscountData Namespace](microsoft-dynamics-commerce-runtime-services-pricingengine-discountdata-namespace.md)

