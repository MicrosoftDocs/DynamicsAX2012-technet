---
title: DiscountLine.GetCompoundedPercentage Method  (Microsoft.Dynamics.Commerce.Runtime.DataModel)
TOCTitle: GetCompoundedPercentage Method
ms:assetid: M:Microsoft.Dynamics.Commerce.Runtime.DataModel.DiscountLine.GetCompoundedPercentage(System.Decimal,System.Decimal)
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.datamodel.discountline.getcompoundedpercentage(v=AX.60)
ms:contentKeyID: 62213774
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataModel.DiscountLine.GetCompoundedPercentage
dev_langs:
- CSharp
- C++
- VB
---

# GetCompoundedPercentage Method


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Get compounded percentage.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataModel](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Entities (in Microsoft.Dynamics.Commerce.Runtime.Entities.dll)

## Syntax

``` vb
'Declaration
Public Shared Function GetCompoundedPercentage ( _
    percentageOne As Decimal, _
    percentageTwo As Decimal _
) As Decimal
'Usage
Dim percentageOne As Decimal
Dim percentageTwo As Decimal
Dim returnValue As Decimal

returnValue = DiscountLine.GetCompoundedPercentage(percentageOne, _
    percentageTwo)
```

``` csharp
public static decimal GetCompoundedPercentage(
    decimal percentageOne,
    decimal percentageTwo
)
```

``` c++
public:
static Decimal GetCompoundedPercentage(
    Decimal percentageOne, 
    Decimal percentageTwo
)
```

#### Parameters

  - percentageOne  
    Type: [System.Decimal](https://technet.microsoft.com/library/1k2e8atx\(v=ax.60\))  

<!-- end list -->

  - percentageTwo  
    Type: [System.Decimal](https://technet.microsoft.com/library/1k2e8atx\(v=ax.60\))  

#### Return Value

Type: [System.Decimal](https://technet.microsoft.com/library/1k2e8atx\(v=ax.60\))  
Compounded percentage.  

## See Also

#### Reference

[DiscountLine Class](discountline-class-microsoft-dynamics-commerce-runtime-datamodel.md)

[Microsoft.Dynamics.Commerce.Runtime.DataModel Namespace](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)

