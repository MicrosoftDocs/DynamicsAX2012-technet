---
title: PriceContextHelper.GetCatalogIds Method (IEnumerable(SalesLine)) (Microsoft.Dynamics.Commerce.Runtime.Services.PricingEngine)
TOCTitle: GetCatalogIds Method (IEnumerable(SalesLine))
ms:assetid: M:Microsoft.Dynamics.Commerce.Runtime.Services.PricingEngine.PriceContextHelper.GetCatalogIds(System.Collections.Generic.IEnumerable{Microsoft.Dynamics.Commerce.Runtime.DataModel.SalesLine})
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.services.pricingengine.pricecontexthelper.getcatalogids(v=AX.60)
ms:contentKeyID: 62209749
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
dev_langs:
- vb
- csharp
- c++
---

# GetCatalogIds Method (IEnumerable(SalesLine))


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Get catalog identifiers.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.Services.PricingEngine](microsoft-dynamics-commerce-runtime-services-pricingengine-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Services.PricingEngine (in Microsoft.Dynamics.Commerce.Runtime.Services.PricingEngine.dll)

## Syntax

``` vb
'Declaration
Public Shared Function GetCatalogIds ( _
    salesLines As IEnumerable(Of SalesLine) _
) As ISet(Of Long)
'Usage
Dim salesLines As IEnumerable(Of SalesLine)
Dim returnValue As ISet(Of Long)

returnValue = PriceContextHelper.GetCatalogIds(salesLines)
```

``` csharp
public static ISet<long> GetCatalogIds(
    IEnumerable<SalesLine> salesLines
)
```

``` c++
public:
static ISet<long long>^ GetCatalogIds(
    IEnumerable<SalesLine^>^ salesLines
)
```

#### Parameters

  - salesLines  
    Type: [System.Collections.Generic.IEnumerable](https://technet.microsoft.com/library/9eekhta0\(v=ax.60\))\<[SalesLine](salesline-class-microsoft-dynamics-commerce-runtime-datamodel.md)\>  

#### Return Value

Type: [System.Collections.Generic.ISet](https://technet.microsoft.com/library/dd412081\(v=ax.60\))\<[Int64](https://technet.microsoft.com/library/6yy583ek\(v=ax.60\))\>  
Set of catalog Ids.  

## See Also

#### Reference

[PriceContextHelper Class](pricecontexthelper-class-microsoft-dynamics-commerce-runtime-services-pricingengine.md)

[GetCatalogIds Overload](pricecontexthelper-getcatalogids-method-microsoft-dynamics-commerce-runtime-services-pricingengine.md)

[Microsoft.Dynamics.Commerce.Runtime.Services.PricingEngine Namespace](microsoft-dynamics-commerce-runtime-services-pricingengine-namespace.md)

