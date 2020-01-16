---
title: DiscountBase.DateValidationType Property  (Microsoft.Dynamics.Commerce.Runtime.Services.PricingEngine.DiscountData)
TOCTitle: DateValidationType Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.Services.PricingEngine.DiscountData.DiscountBase.DateValidationType
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.services.pricingengine.discountdata.discountbase.datevalidationtype(v=AX.60)
ms:contentKeyID: 62208757
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.Services.PricingEngine.DiscountData.DiscountBase.DateValidationType
dev_langs:
- CSharp
- C++
- VB
---

# DateValidationType Property

Gets or sets the validation type to use for date validation for this offer.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.Services.PricingEngine.DiscountData](microsoft-dynamics-commerce-runtime-services-pricingengine-discountdata-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Services.PricingEngine (in Microsoft.Dynamics.Commerce.Runtime.Services.PricingEngine.dll)

## Syntax

``` vb
'Declaration
Public Property DateValidationType As DateValidationType
    Get
    Set
'Usage
Dim instance As DiscountBase
Dim value As DateValidationType

value = instance.DateValidationType

instance.DateValidationType = value
```

``` csharp
public DateValidationType DateValidationType { get; set; }
```

``` c++
public:
property DateValidationType DateValidationType {
    DateValidationType get ();
    void set (DateValidationType value);
}
```

#### Property Value

Type: [Microsoft.Dynamics.Commerce.Runtime.DataModel.DateValidationType](datevalidationtype-enumeration-microsoft-dynamics-commerce-runtime-datamodel.md)  
Returns [DateValidationType](datevalidationtype-enumeration-microsoft-dynamics-commerce-runtime-datamodel.md).  

## See Also

#### Reference

[DiscountBase Class](discountbase-class-microsoft-dynamics-commerce-runtime-services-pricingengine-discountdata.md)

[Microsoft.Dynamics.Commerce.Runtime.Services.PricingEngine.DiscountData Namespace](microsoft-dynamics-commerce-runtime-services-pricingengine-discountdata-namespace.md)

