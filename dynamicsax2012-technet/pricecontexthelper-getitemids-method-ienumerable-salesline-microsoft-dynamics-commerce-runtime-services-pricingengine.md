---
title: PriceContextHelper.GetItemIds Method (IEnumerable(SalesLine)) (Microsoft.Dynamics.Commerce.Runtime.Services.PricingEngine)
TOCTitle: GetItemIds Method (IEnumerable(SalesLine))
ms:assetid: M:Microsoft.Dynamics.Commerce.Runtime.Services.PricingEngine.PriceContextHelper.GetItemIds(System.Collections.Generic.IEnumerable{Microsoft.Dynamics.Commerce.Runtime.DataModel.SalesLine})
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.services.pricingengine.pricecontexthelper.getitemids(v=AX.60)
ms:contentKeyID: 62209041
author: tonyafehr
ms.date: 05/18/2015
mtps_version: v=AX.60
dev_langs:
- vb
- csharp
- c++
---

# GetItemIds Method (IEnumerable(SalesLine))


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Get item identifiers.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.Services.PricingEngine](microsoft-dynamics-commerce-runtime-services-pricingengine-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Services.PricingEngine (in Microsoft.Dynamics.Commerce.Runtime.Services.PricingEngine.dll)

## Syntax

``` vb
'Declaration
Public Shared Function GetItemIds ( _
    salesLines As IEnumerable(Of SalesLine) _
) As ISet(Of String)
'Usage
Dim salesLines As IEnumerable(Of SalesLine)
Dim returnValue As ISet(Of String)

returnValue = PriceContextHelper.GetItemIds(salesLines)
```

``` csharp
public static ISet<string> GetItemIds(
    IEnumerable<SalesLine> salesLines
)
```

``` c++
public:
static ISet<String^>^ GetItemIds(
    IEnumerable<SalesLine^>^ salesLines
)
```

#### Parameters

  - salesLines  
    Type: [System.Collections.Generic.IEnumerable](https://technet.microsoft.com/library/9eekhta0\(v=ax.60\))\<[SalesLine](salesline-class-microsoft-dynamics-commerce-runtime-datamodel.md)\>  

#### Return Value

Type: [System.Collections.Generic.ISet](https://technet.microsoft.com/library/dd412081\(v=ax.60\))\<[String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\))\>  
Set of item Ids.  

## See Also

#### Reference

[PriceContextHelper Class](pricecontexthelper-class-microsoft-dynamics-commerce-runtime-services-pricingengine.md)

[GetItemIds Overload](pricecontexthelper-getitemids-method-microsoft-dynamics-commerce-runtime-services-pricingengine.md)

[Microsoft.Dynamics.Commerce.Runtime.Services.PricingEngine Namespace](microsoft-dynamics-commerce-runtime-services-pricingengine-namespace.md)

