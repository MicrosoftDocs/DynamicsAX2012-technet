---
title: DiscountBase.NumberOfLeastExpensiveLines Property  (Microsoft.Dynamics.Commerce.Runtime.Services.PricingEngine.DiscountData)
TOCTitle: NumberOfLeastExpensiveLines Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.Services.PricingEngine.DiscountData.DiscountBase.NumberOfLeastExpensiveLines
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.services.pricingengine.discountdata.discountbase.numberofleastexpensivelines(v=AX.60)
ms:contentKeyID: 62212433
author: tonyafehr
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.Services.PricingEngine.DiscountData.DiscountBase.NumberOfLeastExpensiveLines
dev_langs:
- CSharp
- C++
- VB
---

# NumberOfLeastExpensiveLines Property


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Gets or sets the number of least-expensive lines to use in triggering this offer.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.Services.PricingEngine.DiscountData](microsoft-dynamics-commerce-runtime-services-pricingengine-discountdata-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Services.PricingEngine (in Microsoft.Dynamics.Commerce.Runtime.Services.PricingEngine.dll)

## Syntax

``` vb
'Declaration
Public Property NumberOfLeastExpensiveLines As Integer
    Get
    Set
'Usage
Dim instance As DiscountBase
Dim value As Integer

value = instance.NumberOfLeastExpensiveLines

instance.NumberOfLeastExpensiveLines = value
```

``` csharp
public int NumberOfLeastExpensiveLines { get; set; }
```

``` c++
public:
property int NumberOfLeastExpensiveLines {
    int get ();
    void set (int value);
}
```

#### Property Value

Type: [System.Int32](https://technet.microsoft.com/library/td2s409d\(v=ax.60\))  
Returns [Int32](https://technet.microsoft.com/library/td2s409d\(v=ax.60\)).  

## See Also

#### Reference

[DiscountBase Class](discountbase-class-microsoft-dynamics-commerce-runtime-services-pricingengine-discountdata.md)

[Microsoft.Dynamics.Commerce.Runtime.Services.PricingEngine.DiscountData Namespace](microsoft-dynamics-commerce-runtime-services-pricingengine-discountdata-namespace.md)

