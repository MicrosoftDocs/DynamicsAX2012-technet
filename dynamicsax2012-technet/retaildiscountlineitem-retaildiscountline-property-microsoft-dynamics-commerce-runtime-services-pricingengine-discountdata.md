---
title: RetailDiscountLineItem.RetailDiscountLine Property  (Microsoft.Dynamics.Commerce.Runtime.Services.PricingEngine.DiscountData)
TOCTitle: RetailDiscountLine Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.Services.PricingEngine.DiscountData.RetailDiscountLineItem.RetailDiscountLine
ms:mtpsurl: https://technet.microsoft.com/en-us/library/microsoft.dynamics.commerce.runtime.services.pricingengine.discountdata.retaildiscountlineitem.retaildiscountline(v=AX.60)
ms:contentKeyID: 62211524
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.Services.PricingEngine.DiscountData.RetailDiscountLineItem.RetailDiscountLine
dev_langs:
- CSharp
- C++
- VB
---

# RetailDiscountLine Property

Gets or sets the discount line that the item belongs to for this application.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.Services.PricingEngine.DiscountData](microsoft-dynamics-commerce-runtime-services-pricingengine-discountdata-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Services.PricingEngine (in Microsoft.Dynamics.Commerce.Runtime.Services.PricingEngine.dll)

## Syntax

``` vb
'Declaration
Public Property RetailDiscountLine As RetailDiscountLine
    Get
    Set
'Usage
Dim instance As RetailDiscountLineItem
Dim value As RetailDiscountLine

value = instance.RetailDiscountLine

instance.RetailDiscountLine = value
```

``` csharp
public RetailDiscountLine RetailDiscountLine { get; set; }
```

``` c++
public:
property RetailDiscountLine^ RetailDiscountLine {
    RetailDiscountLine^ get ();
    void set (RetailDiscountLine^ value);
}
```

#### Property Value

Type: [Microsoft.Dynamics.Commerce.Runtime.DataModel.RetailDiscountLine](retaildiscountline-class-microsoft-dynamics-commerce-runtime-datamodel.md)  
Returns [RetailDiscountLine](retaildiscountline-class-microsoft-dynamics-commerce-runtime-datamodel.md).  

## See Also

#### Reference

[RetailDiscountLineItem Class](retaildiscountlineitem-class-microsoft-dynamics-commerce-runtime-services-pricingengine-discountdata.md)

[Microsoft.Dynamics.Commerce.Runtime.Services.PricingEngine.DiscountData Namespace](microsoft-dynamics-commerce-runtime-services-pricingengine-discountdata-namespace.md)

