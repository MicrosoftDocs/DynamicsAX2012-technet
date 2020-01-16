---
title: DiscountBase.GetProductOrVariantIdToRetailDiscountLinesMap Method  (Microsoft.Dynamics.Commerce.Runtime.Services.PricingEngine.DiscountData)
TOCTitle: GetProductOrVariantIdToRetailDiscountLinesMap Method
ms:assetid: M:Microsoft.Dynamics.Commerce.Runtime.Services.PricingEngine.DiscountData.DiscountBase.GetProductOrVariantIdToRetailDiscountLinesMap
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.services.pricingengine.discountdata.discountbase.getproductorvariantidtoretaildiscountlinesmap(v=AX.60)
ms:contentKeyID: 62214434
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.Services.PricingEngine.DiscountData.DiscountBase.GetProductOrVariantIdToRetailDiscountLinesMap
dev_langs:
- CSharp
- C++
- VB
---

# GetProductOrVariantIdToRetailDiscountLinesMap Method

Gets product or variant Id to retail discount lines map.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.Services.PricingEngine.DiscountData](microsoft-dynamics-commerce-runtime-services-pricingengine-discountdata-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Services.PricingEngine (in Microsoft.Dynamics.Commerce.Runtime.Services.PricingEngine.dll)

## Syntax

``` vb
'Declaration
Public Function GetProductOrVariantIdToRetailDiscountLinesMap As IDictionary(Of Long, IList(Of RetailDiscountLine))
'Usage
Dim instance As DiscountBase
Dim returnValue As IDictionary(Of Long, IList(Of RetailDiscountLine))

returnValue = instance.GetProductOrVariantIdToRetailDiscountLinesMap()
```

``` csharp
public IDictionary<long, IList<RetailDiscountLine>> GetProductOrVariantIdToRetailDiscountLinesMap()
```

``` c++
public:
IDictionary<long long, IList<RetailDiscountLine^>^>^ GetProductOrVariantIdToRetailDiscountLinesMap()
```

#### Return Value

Type: [System.Collections.Generic.IDictionary](https://technet.microsoft.com/library/s4ys34ea\(v=ax.60\))\<[Int64](https://technet.microsoft.com/library/6yy583ek\(v=ax.60\)), [IList](https://technet.microsoft.com/library/5y536ey6\(v=ax.60\))\<[RetailDiscountLine](retaildiscountline-class-microsoft-dynamics-commerce-runtime-datamodel.md)\>\>  
Product or variant Id to retail discount lines map.  

## See Also

#### Reference

[DiscountBase Class](discountbase-class-microsoft-dynamics-commerce-runtime-services-pricingengine-discountdata.md)

[Microsoft.Dynamics.Commerce.Runtime.Services.PricingEngine.DiscountData Namespace](microsoft-dynamics-commerce-runtime-services-pricingengine-discountdata-namespace.md)

