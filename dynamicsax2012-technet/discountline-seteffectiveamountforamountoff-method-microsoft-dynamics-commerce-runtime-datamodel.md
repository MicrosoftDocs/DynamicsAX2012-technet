---
title: DiscountLine.SetEffectiveAmountForAmountOff Method  (Microsoft.Dynamics.Commerce.Runtime.DataModel)
TOCTitle: SetEffectiveAmountForAmountOff Method
ms:assetid: M:Microsoft.Dynamics.Commerce.Runtime.DataModel.DiscountLine.SetEffectiveAmountForAmountOff(System.Decimal,System.Decimal,Microsoft.Dynamics.Commerce.Runtime.DataModel.RoundingRule)
ms:mtpsurl: https://technet.microsoft.com/en-us/library/microsoft.dynamics.commerce.runtime.datamodel.discountline.seteffectiveamountforamountoff(v=AX.60)
ms:contentKeyID: 65319776
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataModel.DiscountLine.SetEffectiveAmountForAmountOff
dev_langs:
- CSharp
- C++
- VB
---

# SetEffectiveAmountForAmountOff Method

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataModel](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Entities (in Microsoft.Dynamics.Commerce.Runtime.Entities.dll)

## Syntax

``` vb
'Declaration
Public Function SetEffectiveAmountForAmountOff ( _
    grossAmountDiscountable As Decimal, _
    quantity As Decimal, _
    roundingRule As RoundingRule _
) As Decimal
'Usage
Dim instance As DiscountLine
Dim grossAmountDiscountable As Decimal
Dim quantity As Decimal
Dim roundingRule As RoundingRule
Dim returnValue As Decimal

returnValue = instance.SetEffectiveAmountForAmountOff(grossAmountDiscountable, _
    quantity, roundingRule)
```

``` csharp
public decimal SetEffectiveAmountForAmountOff(
    decimal grossAmountDiscountable,
    decimal quantity,
    RoundingRule roundingRule
)
```

``` c++
public:
Decimal SetEffectiveAmountForAmountOff(
    Decimal grossAmountDiscountable, 
    Decimal quantity, 
    RoundingRule^ roundingRule
)
```

#### Parameters

  - grossAmountDiscountable  
    Type: [System.Decimal](https://technet.microsoft.com/en-us/library/1k2e8atx\(v=ax.60\))  

<!-- end list -->

  - quantity  
    Type: [System.Decimal](https://technet.microsoft.com/en-us/library/1k2e8atx\(v=ax.60\))  

<!-- end list -->

  - roundingRule  
    Type: [Microsoft.Dynamics.Commerce.Runtime.DataModel.RoundingRule](roundingrule-delegate-microsoft-dynamics-commerce-runtime-datamodel.md)  

#### Return Value

Type: [System.Decimal](https://technet.microsoft.com/en-us/library/1k2e8atx\(v=ax.60\))  

## See Also

#### Reference

[DiscountLine Class](discountline-class-microsoft-dynamics-commerce-runtime-datamodel.md)

[Microsoft.Dynamics.Commerce.Runtime.DataModel Namespace](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)

