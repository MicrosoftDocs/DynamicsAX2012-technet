---
title: DiscountBase.TryGetRetailDiscountLines Method  (Microsoft.Dynamics.Commerce.Runtime.Services.PricingEngine.DiscountData)
TOCTitle: TryGetRetailDiscountLines Method
ms:assetid: M:Microsoft.Dynamics.Commerce.Runtime.Services.PricingEngine.DiscountData.DiscountBase.TryGetRetailDiscountLines(System.Int64,System.Int64,System.String,System.Collections.Generic.IList{Microsoft.Dynamics.Commerce.Runtime.DataModel.RetailDiscountLine}@)
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.services.pricingengine.discountdata.discountbase.trygetretaildiscountlines(v=AX.60)
ms:contentKeyID: 62203282
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.Services.PricingEngine.DiscountData.DiscountBase.TryGetRetailDiscountLines
dev_langs:
- CSharp
- C++
- VB
---

# TryGetRetailDiscountLines Method


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Try getting retail discount lines by variant Id or product Id.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.Services.PricingEngine.DiscountData](microsoft-dynamics-commerce-runtime-services-pricingengine-discountdata-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Services.PricingEngine (in Microsoft.Dynamics.Commerce.Runtime.Services.PricingEngine.dll)

## Syntax

``` vb
'Declaration
Protected Function TryGetRetailDiscountLines ( _
    productOrVariantId As Long, _
    masterProductId As Long, _
    unitOfMeasure As String, _
    <OutAttribute> ByRef lines As IList(Of RetailDiscountLine) _
) As Boolean
'Usage
Dim productOrVariantId As Long
Dim masterProductId As Long
Dim unitOfMeasure As String
Dim lines As IList(Of RetailDiscountLine)
Dim returnValue As Boolean

returnValue = Me.TryGetRetailDiscountLines(productOrVariantId, _
    masterProductId, unitOfMeasure, _
    lines)
```

``` csharp
protected bool TryGetRetailDiscountLines(
    long productOrVariantId,
    long masterProductId,
    string unitOfMeasure,
    out IList<RetailDiscountLine> lines
)
```

``` c++
protected:
bool TryGetRetailDiscountLines(
    long long productOrVariantId, 
    long long masterProductId, 
    String^ unitOfMeasure, 
    [OutAttribute] IList<RetailDiscountLine^>^% lines
)
```

#### Parameters

  - productOrVariantId  
    Type: [System.Int64](https://technet.microsoft.com/library/6yy583ek\(v=ax.60\))  

<!-- end list -->

  - masterProductId  
    Type: [System.Int64](https://technet.microsoft.com/library/6yy583ek\(v=ax.60\))  

<!-- end list -->

  - unitOfMeasure  
    Type: [System.String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\))  

<!-- end list -->

  - lines  
    Type: [System.Collections.Generic.IList](https://technet.microsoft.com/library/5y536ey6\(v=ax.60\))\<[RetailDiscountLine](retaildiscountline-class-microsoft-dynamics-commerce-runtime-datamodel.md)\>  

#### Return Value

Type: [System.Boolean](https://technet.microsoft.com/library/a28wyd50\(v=ax.60\))  
True if found.  

## Remarks

The key of triggering product dictionary is one of variant Id, product Id or master product Id.

## See Also

#### Reference

[DiscountBase Class](discountbase-class-microsoft-dynamics-commerce-runtime-services-pricingengine-discountdata.md)

[Microsoft.Dynamics.Commerce.Runtime.Services.PricingEngine.DiscountData Namespace](microsoft-dynamics-commerce-runtime-services-pricingengine-discountdata-namespace.md)

