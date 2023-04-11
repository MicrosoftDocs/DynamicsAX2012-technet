---
title: DiscountLine.AddEffectiveAmountForPercentOff Method  (Microsoft.Dynamics.Commerce.Runtime.DataModel)
TOCTitle: AddEffectiveAmountForPercentOff Method
ms:assetid: M:Microsoft.Dynamics.Commerce.Runtime.DataModel.DiscountLine.AddEffectiveAmountForPercentOff(System.Decimal,System.Decimal,Microsoft.Dynamics.Commerce.Runtime.DataModel.RoundingRule)
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.datamodel.discountline.addeffectiveamountforpercentoff(v=AX.60)
ms:contentKeyID: 65322905
author: tonyafehr
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataModel.DiscountLine.AddEffectiveAmountForPercentOff
dev_langs:
- CSharp
- C++
- VB
---

# AddEffectiveAmountForPercentOff Method


[!INCLUDE[archive-banner](includes/archive-banner.md)]

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataModel](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Entities (in Microsoft.Dynamics.Commerce.Runtime.Entities.dll)

## Syntax

``` vb
'Declaration
Public Function AddEffectiveAmountForPercentOff ( _
    grossAmountDiscountable As Decimal, _
    maxDiscountAmount As Decimal, _
    roundingRule As RoundingRule _
) As Decimal
'Usage
Dim instance As DiscountLine
Dim grossAmountDiscountable As Decimal
Dim maxDiscountAmount As Decimal
Dim roundingRule As RoundingRule
Dim returnValue As Decimal

returnValue = instance.AddEffectiveAmountForPercentOff(grossAmountDiscountable, _
    maxDiscountAmount, roundingRule)
```

``` csharp
public decimal AddEffectiveAmountForPercentOff(
    decimal grossAmountDiscountable,
    decimal maxDiscountAmount,
    RoundingRule roundingRule
)
```

``` c++
public:
Decimal AddEffectiveAmountForPercentOff(
    Decimal grossAmountDiscountable, 
    Decimal maxDiscountAmount, 
    RoundingRule^ roundingRule
)
```

#### Parameters

  - grossAmountDiscountable  
    Type: [System.Decimal](https://technet.microsoft.com/library/1k2e8atx\(v=ax.60\))  

<!-- end list -->

  - maxDiscountAmount  
    Type: [System.Decimal](https://technet.microsoft.com/library/1k2e8atx\(v=ax.60\))  

<!-- end list -->

  - roundingRule  
    Type: [Microsoft.Dynamics.Commerce.Runtime.DataModel.RoundingRule](roundingrule-delegate-microsoft-dynamics-commerce-runtime-datamodel.md)  

#### Return Value

Type: [System.Decimal](https://technet.microsoft.com/library/1k2e8atx\(v=ax.60\))  

## See Also

#### Reference

[DiscountLine Class](discountline-class-microsoft-dynamics-commerce-runtime-datamodel.md)

[Microsoft.Dynamics.Commerce.Runtime.DataModel Namespace](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)

