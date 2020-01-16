---
title: DiscountableItemGroup.Add Method  (Microsoft.Dynamics.Commerce.Runtime.Services.PricingEngine.DiscountData)
TOCTitle: Add Method
ms:assetid: M:Microsoft.Dynamics.Commerce.Runtime.Services.PricingEngine.DiscountData.DiscountableItemGroup.Add(Microsoft.Dynamics.Commerce.Runtime.DataModel.SalesLine)
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.services.pricingengine.discountdata.discountableitemgroup.add(v=AX.60)
ms:contentKeyID: 62209829
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.Services.PricingEngine.DiscountData.DiscountableItemGroup.Add
dev_langs:
- CSharp
- C++
- VB
---

# Add Method

Adds the specified SalesLine object to the collection of lines included in this group.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.Services.PricingEngine.DiscountData](microsoft-dynamics-commerce-runtime-services-pricingengine-discountdata-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Services.PricingEngine (in Microsoft.Dynamics.Commerce.Runtime.Services.PricingEngine.dll)

## Syntax

``` vb
'Declaration
Public Sub Add ( _
    line As SalesLine _
)
'Usage
Dim instance As DiscountableItemGroup
Dim line As SalesLine

instance.Add(line)
```

``` csharp
public void Add(
    SalesLine line
)
```

``` c++
public:
void Add(
    SalesLine^ line
)
```

#### Parameters

  - line  
    Type: [Microsoft.Dynamics.Commerce.Runtime.DataModel.SalesLine](salesline-class-microsoft-dynamics-commerce-runtime-datamodel.md)  

## See Also

#### Reference

[DiscountableItemGroup Class](discountableitemgroup-class-microsoft-dynamics-commerce-runtime-services-pricingengine-discountdata.md)

[Microsoft.Dynamics.Commerce.Runtime.Services.PricingEngine.DiscountData Namespace](microsoft-dynamics-commerce-runtime-services-pricingengine-discountdata-namespace.md)

