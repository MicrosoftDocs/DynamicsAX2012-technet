---
title: PriceContextHelper.GetCatalogIds Method (SalesTransaction) (Microsoft.Dynamics.Commerce.Runtime.Services.PricingEngine)
TOCTitle: GetCatalogIds Method (SalesTransaction)
ms:assetid: M:Microsoft.Dynamics.Commerce.Runtime.Services.PricingEngine.PriceContextHelper.GetCatalogIds(Microsoft.Dynamics.Commerce.Runtime.DataModel.SalesTransaction)
ms:mtpsurl: https://technet.microsoft.com/en-us/library/microsoft.dynamics.commerce.runtime.services.pricingengine.pricecontexthelper.getcatalogids(v=AX.60)
ms:contentKeyID: 62211783
ms.date: 05/18/2015
mtps_version: v=AX.60
dev_langs:
- vb
- csharp
- c++
---

# GetCatalogIds Method (SalesTransaction)

Get catalog identifiers.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.Services.PricingEngine](microsoft-dynamics-commerce-runtime-services-pricingengine-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Services.PricingEngine (in Microsoft.Dynamics.Commerce.Runtime.Services.PricingEngine.dll)

## Syntax

``` vb
'Declaration
Public Shared Function GetCatalogIds ( _
    transaction As SalesTransaction _
) As ISet(Of Long)
'Usage
Dim transaction As SalesTransaction
Dim returnValue As ISet(Of Long)

returnValue = PriceContextHelper.GetCatalogIds(transaction)
```

``` csharp
public static ISet<long> GetCatalogIds(
    SalesTransaction transaction
)
```

``` c++
public:
static ISet<long long>^ GetCatalogIds(
    SalesTransaction^ transaction
)
```

#### Parameters

  - transaction  
    Type: [Microsoft.Dynamics.Commerce.Runtime.DataModel.SalesTransaction](salestransaction-class-microsoft-dynamics-commerce-runtime-datamodel.md)  

#### Return Value

Type: [System.Collections.Generic.ISet](https://technet.microsoft.com/en-us/library/dd412081\(v=ax.60\))\<[Int64](https://technet.microsoft.com/en-us/library/6yy583ek\(v=ax.60\))\>  
Set of catalog Ids.  

## See Also

#### Reference

[PriceContextHelper Class](pricecontexthelper-class-microsoft-dynamics-commerce-runtime-services-pricingengine.md)

[GetCatalogIds Overload](pricecontexthelper-getcatalogids-method-microsoft-dynamics-commerce-runtime-services-pricingengine.md)

[Microsoft.Dynamics.Commerce.Runtime.Services.PricingEngine Namespace](microsoft-dynamics-commerce-runtime-services-pricingengine-namespace.md)

