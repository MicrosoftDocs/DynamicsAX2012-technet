---
title: DiscountApplication.RetailDiscountLines Property  (Microsoft.Dynamics.Commerce.Runtime.Services.PricingEngine.DiscountData)
TOCTitle: RetailDiscountLines Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.Services.PricingEngine.DiscountData.DiscountApplication.RetailDiscountLines
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.services.pricingengine.discountdata.discountapplication.retaildiscountlines(v=AX.60)
ms:contentKeyID: 62213397
author: tonyafehr
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.Services.PricingEngine.DiscountData.DiscountApplication.RetailDiscountLines
dev_langs:
- CSharp
- C++
- VB
---

# RetailDiscountLines Property


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Gets or sets the specific discount lines for the discount associated with this application.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.Services.PricingEngine.DiscountData](microsoft-dynamics-commerce-runtime-services-pricingengine-discountdata-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Services.PricingEngine (in Microsoft.Dynamics.Commerce.Runtime.Services.PricingEngine.dll)

## Syntax

``` vb
'Declaration
Public Property RetailDiscountLines As IEnumerable(Of RetailDiscountLineItem)
    Get
    Set
'Usage
Dim instance As DiscountApplication
Dim value As IEnumerable(Of RetailDiscountLineItem)

value = instance.RetailDiscountLines

instance.RetailDiscountLines = value
```

``` csharp
public IEnumerable<RetailDiscountLineItem> RetailDiscountLines { get; set; }
```

``` c++
public:
property IEnumerable<RetailDiscountLineItem^>^ RetailDiscountLines {
    IEnumerable<RetailDiscountLineItem^>^ get ();
    void set (IEnumerable<RetailDiscountLineItem^>^ value);
}
```

#### Property Value

Type: [System.Collections.Generic.IEnumerable](https://technet.microsoft.com/library/9eekhta0\(v=ax.60\))\<[RetailDiscountLineItem](retaildiscountlineitem-class-microsoft-dynamics-commerce-runtime-services-pricingengine-discountdata.md)\>  
Returns [IEnumerable\<T\>](https://technet.microsoft.com/library/9eekhta0\(v=ax.60\)).  

## See Also

#### Reference

[DiscountApplication Class](discountapplication-class-microsoft-dynamics-commerce-runtime-services-pricingengine-discountdata.md)

[Microsoft.Dynamics.Commerce.Runtime.Services.PricingEngine.DiscountData Namespace](microsoft-dynamics-commerce-runtime-services-pricingengine-discountdata-namespace.md)

