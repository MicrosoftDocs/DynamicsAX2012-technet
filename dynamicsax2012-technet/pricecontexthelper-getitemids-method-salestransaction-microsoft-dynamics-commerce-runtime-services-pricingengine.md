---
title: PriceContextHelper.GetItemIds Method (SalesTransaction) (Microsoft.Dynamics.Commerce.Runtime.Services.PricingEngine)
TOCTitle: GetItemIds Method (SalesTransaction)
ms:assetid: M:Microsoft.Dynamics.Commerce.Runtime.Services.PricingEngine.PriceContextHelper.GetItemIds(Microsoft.Dynamics.Commerce.Runtime.DataModel.SalesTransaction)
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.services.pricingengine.pricecontexthelper.getitemids(v=AX.60)
ms:contentKeyID: 62214433
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
dev_langs:
- vb
- csharp
- c++
---

# GetItemIds Method (SalesTransaction)


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Get item identifiers.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.Services.PricingEngine](microsoft-dynamics-commerce-runtime-services-pricingengine-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Services.PricingEngine (in Microsoft.Dynamics.Commerce.Runtime.Services.PricingEngine.dll)

## Syntax

``` vb
'Declaration
Public Shared Function GetItemIds ( _
    transaction As SalesTransaction _
) As ISet(Of String)
'Usage
Dim transaction As SalesTransaction
Dim returnValue As ISet(Of String)

returnValue = PriceContextHelper.GetItemIds(transaction)
```

``` csharp
public static ISet<string> GetItemIds(
    SalesTransaction transaction
)
```

``` c++
public:
static ISet<String^>^ GetItemIds(
    SalesTransaction^ transaction
)
```

#### Parameters

  - transaction  
    Type: [Microsoft.Dynamics.Commerce.Runtime.DataModel.SalesTransaction](salestransaction-class-microsoft-dynamics-commerce-runtime-datamodel.md)  

#### Return Value

Type: [System.Collections.Generic.ISet](https://technet.microsoft.com/library/dd412081\(v=ax.60\))\<[String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\))\>  
Set of item Ids.  

## See Also

#### Reference

[PriceContextHelper Class](pricecontexthelper-class-microsoft-dynamics-commerce-runtime-services-pricingengine.md)

[GetItemIds Overload](pricecontexthelper-getitemids-method-microsoft-dynamics-commerce-runtime-services-pricingengine.md)

[Microsoft.Dynamics.Commerce.Runtime.Services.PricingEngine Namespace](microsoft-dynamics-commerce-runtime-services-pricingengine-namespace.md)

