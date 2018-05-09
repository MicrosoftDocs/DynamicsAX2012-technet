---
title: DiscountBase.NumberOfTimesApplicable Property  (Microsoft.Dynamics.Commerce.Runtime.Services.PricingEngine.DiscountData)
TOCTitle: NumberOfTimesApplicable Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.Services.PricingEngine.DiscountData.DiscountBase.NumberOfTimesApplicable
ms:mtpsurl: https://technet.microsoft.com/en-us/library/microsoft.dynamics.commerce.runtime.services.pricingengine.discountdata.discountbase.numberoftimesapplicable(v=AX.60)
ms:contentKeyID: 62209949
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.Services.PricingEngine.DiscountData.DiscountBase.NumberOfTimesApplicable
dev_langs:
- CSharp
- C++
- VB
---

# NumberOfTimesApplicable Property

Gets or sets the number of times this offer can be applied to a transaction.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.Services.PricingEngine.DiscountData](microsoft-dynamics-commerce-runtime-services-pricingengine-discountdata-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Services.PricingEngine (in Microsoft.Dynamics.Commerce.Runtime.Services.PricingEngine.dll)

## Syntax

``` vb
'Declaration
Public Property NumberOfTimesApplicable As Integer
    Get
    Set
'Usage
Dim instance As DiscountBase
Dim value As Integer

value = instance.NumberOfTimesApplicable

instance.NumberOfTimesApplicable = value
```

``` csharp
public int NumberOfTimesApplicable { get; set; }
```

``` c++
public:
property int NumberOfTimesApplicable {
    int get ();
    void set (int value);
}
```

#### Property Value

Type: [System.Int32](https://technet.microsoft.com/en-us/library/td2s409d\(v=ax.60\))  
Returns [Int32](https://technet.microsoft.com/en-us/library/td2s409d\(v=ax.60\)).  

## See Also

#### Reference

[DiscountBase Class](discountbase-class-microsoft-dynamics-commerce-runtime-services-pricingengine-discountdata.md)

[Microsoft.Dynamics.Commerce.Runtime.Services.PricingEngine.DiscountData Namespace](microsoft-dynamics-commerce-runtime-services-pricingengine-discountdata-namespace.md)

