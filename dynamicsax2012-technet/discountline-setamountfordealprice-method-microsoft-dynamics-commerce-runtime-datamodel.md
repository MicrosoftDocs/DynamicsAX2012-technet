---
title: DiscountLine.SetAmountForDealPrice Method  (Microsoft.Dynamics.Commerce.Runtime.DataModel)
TOCTitle: SetAmountForDealPrice Method
ms:assetid: M:Microsoft.Dynamics.Commerce.Runtime.DataModel.DiscountLine.SetAmountForDealPrice(System.Decimal,System.Decimal,Microsoft.Dynamics.Commerce.Runtime.DataModel.RoundingRule)
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.datamodel.discountline.setamountfordealprice(v=AX.60)
ms:contentKeyID: 65323009
author: tonyafehr
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataModel.DiscountLine.SetAmountForDealPrice
dev_langs:
- CSharp
- C++
- VB
---

# SetAmountForDealPrice Method


[!INCLUDE[archive-banner](includes/archive-banner.md)]

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataModel](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Entities (in Microsoft.Dynamics.Commerce.Runtime.Entities.dll)

## Syntax

``` vb
'Declaration
Public Sub SetAmountForDealPrice ( _
    grossAmountDiscountable As Decimal, _
    quantity As Decimal, _
    roundingRule As RoundingRule _
)
'Usage
Dim instance As DiscountLine
Dim grossAmountDiscountable As Decimal
Dim quantity As Decimal
Dim roundingRule As RoundingRule

instance.SetAmountForDealPrice(grossAmountDiscountable, _
    quantity, roundingRule)
```

``` csharp
public void SetAmountForDealPrice(
    decimal grossAmountDiscountable,
    decimal quantity,
    RoundingRule roundingRule
)
```

``` c++
public:
void SetAmountForDealPrice(
    Decimal grossAmountDiscountable, 
    Decimal quantity, 
    RoundingRule^ roundingRule
)
```

#### Parameters

  - grossAmountDiscountable  
    Type: [System.Decimal](https://technet.microsoft.com/library/1k2e8atx\(v=ax.60\))  

<!-- end list -->

  - quantity  
    Type: [System.Decimal](https://technet.microsoft.com/library/1k2e8atx\(v=ax.60\))  

<!-- end list -->

  - roundingRule  
    Type: [Microsoft.Dynamics.Commerce.Runtime.DataModel.RoundingRule](roundingrule-delegate-microsoft-dynamics-commerce-runtime-datamodel.md)  

## See Also

#### Reference

[DiscountLine Class](discountline-class-microsoft-dynamics-commerce-runtime-datamodel.md)

[Microsoft.Dynamics.Commerce.Runtime.DataModel Namespace](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)

