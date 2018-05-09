---
title: DiscountBase.NewDiscountLine Method  (Microsoft.Dynamics.Commerce.Runtime.Services.PricingEngine.DiscountData)
TOCTitle: NewDiscountLine Method
ms:assetid: M:Microsoft.Dynamics.Commerce.Runtime.Services.PricingEngine.DiscountData.DiscountBase.NewDiscountLine(System.String,System.String)
ms:mtpsurl: https://technet.microsoft.com/en-us/library/microsoft.dynamics.commerce.runtime.services.pricingengine.discountdata.discountbase.newdiscountline(v=AX.60)
ms:contentKeyID: 62213976
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.Services.PricingEngine.DiscountData.DiscountBase.NewDiscountLine
dev_langs:
- CSharp
- C++
- VB
---

# NewDiscountLine Method

Create a new discount line.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.Services.PricingEngine.DiscountData](microsoft-dynamics-commerce-runtime-services-pricingengine-discountdata-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Services.PricingEngine (in Microsoft.Dynamics.Commerce.Runtime.Services.PricingEngine.dll)

## Syntax

``` vb
'Declaration
Protected Function NewDiscountLine ( _
    discountCode As String, _
    itemId As String _
) As DiscountLine
'Usage
Dim discountCode As String
Dim itemId As String
Dim returnValue As DiscountLine

returnValue = Me.NewDiscountLine(discountCode, _
    itemId)
```

``` csharp
protected DiscountLine NewDiscountLine(
    string discountCode,
    string itemId
)
```

``` c++
protected:
DiscountLine^ NewDiscountLine(
    String^ discountCode, 
    String^ itemId
)
```

#### Parameters

  - discountCode  
    Type: [System.String](https://technet.microsoft.com/en-us/library/s1wwdcbf\(v=ax.60\))  

<!-- end list -->

  - itemId  
    Type: [System.String](https://technet.microsoft.com/en-us/library/s1wwdcbf\(v=ax.60\))  

#### Return Value

Type: [Microsoft.Dynamics.Commerce.Runtime.DataModel.DiscountLine](discountline-class-microsoft-dynamics-commerce-runtime-datamodel.md)  
A new discount line.  

## See Also

#### Reference

[DiscountBase Class](discountbase-class-microsoft-dynamics-commerce-runtime-services-pricingengine-discountdata.md)

[Microsoft.Dynamics.Commerce.Runtime.Services.PricingEngine.DiscountData Namespace](microsoft-dynamics-commerce-runtime-services-pricingengine-discountdata-namespace.md)

