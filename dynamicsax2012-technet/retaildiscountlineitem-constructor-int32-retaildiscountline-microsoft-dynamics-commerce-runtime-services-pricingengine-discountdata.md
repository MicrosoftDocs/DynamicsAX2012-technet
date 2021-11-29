---
title: RetailDiscountLineItem Constructor (Int32, RetailDiscountLine) (Microsoft.Dynamics.Commerce.Runtime.Services.PricingEngine.DiscountData)
TOCTitle: RetailDiscountLineItem Constructor (Int32, RetailDiscountLine)
ms:assetid: M:Microsoft.Dynamics.Commerce.Runtime.Services.PricingEngine.DiscountData.RetailDiscountLineItem.#ctor(System.Int32,Microsoft.Dynamics.Commerce.Runtime.DataModel.RetailDiscountLine)
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.services.pricingengine.discountdata.retaildiscountlineitem.retaildiscountlineitem(v=AX.60)
ms:contentKeyID: 62211378
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
dev_langs:
- vb
- csharp
- c++
---

# RetailDiscountLineItem Constructor (Int32, RetailDiscountLine)


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Initializes a new instance of the RetailDiscountLineItem class, with the values set to the specified parameters.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.Services.PricingEngine.DiscountData](microsoft-dynamics-commerce-runtime-services-pricingengine-discountdata-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Services.PricingEngine (in Microsoft.Dynamics.Commerce.Runtime.Services.PricingEngine.dll)

## Syntax

``` vb
'Declaration
Public Sub New ( _
    itemIndex As Integer, _
    discountLine As RetailDiscountLine _
)
'Usage
Dim itemIndex As Integer
Dim discountLine As RetailDiscountLine

Dim instance As New RetailDiscountLineItem(itemIndex, _
    discountLine)
```

``` csharp
public RetailDiscountLineItem(
    int itemIndex,
    RetailDiscountLine discountLine
)
```

``` c++
public:
RetailDiscountLineItem(
    int itemIndex, 
    RetailDiscountLine^ discountLine
)
```

#### Parameters

  - itemIndex  
    Type: [System.Int32](https://technet.microsoft.com/library/td2s409d\(v=ax.60\))  

<!-- end list -->

  - discountLine  
    Type: [Microsoft.Dynamics.Commerce.Runtime.DataModel.RetailDiscountLine](retaildiscountline-class-microsoft-dynamics-commerce-runtime-datamodel.md)  

## See Also

#### Reference

[RetailDiscountLineItem Class](retaildiscountlineitem-class-microsoft-dynamics-commerce-runtime-services-pricingengine-discountdata.md)

[RetailDiscountLineItem Overload](retaildiscountlineitem-constructor-microsoft-dynamics-commerce-runtime-services-pricingengine-discountdata.md)

[Microsoft.Dynamics.Commerce.Runtime.Services.PricingEngine.DiscountData Namespace](microsoft-dynamics-commerce-runtime-services-pricingengine-discountdata-namespace.md)

