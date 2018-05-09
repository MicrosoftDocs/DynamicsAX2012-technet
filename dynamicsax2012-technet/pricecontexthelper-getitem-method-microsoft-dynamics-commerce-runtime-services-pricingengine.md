---
title: PriceContextHelper.GetItem Method  (Microsoft.Dynamics.Commerce.Runtime.Services.PricingEngine)
TOCTitle: GetItem Method
ms:assetid: M:Microsoft.Dynamics.Commerce.Runtime.Services.PricingEngine.PriceContextHelper.GetItem(Microsoft.Dynamics.Commerce.Runtime.Services.PricingEngine.PriceContext,System.String)
ms:mtpsurl: https://technet.microsoft.com/en-us/library/microsoft.dynamics.commerce.runtime.services.pricingengine.pricecontexthelper.getitem(v=AX.60)
ms:contentKeyID: 62213968
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.Services.PricingEngine.PriceContextHelper.GetItem
dev_langs:
- CSharp
- C++
- VB
---

# GetItem Method

Get item by item identifier.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.Services.PricingEngine](microsoft-dynamics-commerce-runtime-services-pricingengine-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Services.PricingEngine (in Microsoft.Dynamics.Commerce.Runtime.Services.PricingEngine.dll)

## Syntax

``` vb
'Declaration
Public Shared Function GetItem ( _
    priceContext As PriceContext, _
    itemId As String _
) As Item
'Usage
Dim priceContext As PriceContext
Dim itemId As String
Dim returnValue As Item

returnValue = PriceContextHelper.GetItem(priceContext, _
    itemId)
```

``` csharp
public static Item GetItem(
    PriceContext priceContext,
    string itemId
)
```

``` c++
public:
static Item^ GetItem(
    PriceContext^ priceContext, 
    String^ itemId
)
```

#### Parameters

  - priceContext  
    Type: [Microsoft.Dynamics.Commerce.Runtime.Services.PricingEngine.PriceContext](pricecontext-class-microsoft-dynamics-commerce-runtime-services-pricingengine.md)  

<!-- end list -->

  - itemId  
    Type: [System.String](https://technet.microsoft.com/en-us/library/s1wwdcbf\(v=ax.60\))  

#### Return Value

Type: [Microsoft.Dynamics.Commerce.Runtime.DataModel.Item](item-class-microsoft-dynamics-commerce-runtime-datamodel.md)  
The item.  

## See Also

#### Reference

[PriceContextHelper Class](pricecontexthelper-class-microsoft-dynamics-commerce-runtime-services-pricingengine.md)

[Microsoft.Dynamics.Commerce.Runtime.Services.PricingEngine Namespace](microsoft-dynamics-commerce-runtime-services-pricingengine-namespace.md)

