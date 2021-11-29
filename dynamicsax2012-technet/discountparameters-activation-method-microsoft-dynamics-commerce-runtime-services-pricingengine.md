---
title: DiscountParameters.Activation Method  (Microsoft.Dynamics.Commerce.Runtime.Services.PricingEngine)
TOCTitle: Activation Method
ms:assetid: M:Microsoft.Dynamics.Commerce.Runtime.Services.PricingEngine.DiscountParameters.Activation(Microsoft.Dynamics.Commerce.Runtime.DataModel.PriceDiscountType,Microsoft.Dynamics.Commerce.Runtime.DataModel.PriceDiscountAccountCode,Microsoft.Dynamics.Commerce.Runtime.DataModel.PriceDiscountItemCode)
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.services.pricingengine.discountparameters.activation(v=AX.60)
ms:contentKeyID: 49846414
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.Services.PricingEngine.DiscountParameters.Activation
dev_langs:
- CSharp
- C++
- VB
---

# Activation Method


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Returns true or false, whether a certain relation is active for a discount search.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.Services.PricingEngine](microsoft-dynamics-commerce-runtime-services-pricingengine-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Services.PricingEngine (in Microsoft.Dynamics.Commerce.Runtime.Services.PricingEngine.dll)

## Syntax

``` vb
'Declaration
Public Function Activation ( _
    relation As PriceDiscountType, _
    accountCode As PriceDiscountAccountCode, _
    itemCode As PriceDiscountItemCode _
) As Boolean
'Usage
Dim instance As DiscountParameters
Dim relation As PriceDiscountType
Dim accountCode As PriceDiscountAccountCode
Dim itemCode As PriceDiscountItemCode
Dim returnValue As Boolean

returnValue = instance.Activation(relation, _
    accountCode, itemCode)
```

``` csharp
public bool Activation(
    PriceDiscountType relation,
    PriceDiscountAccountCode accountCode,
    PriceDiscountItemCode itemCode
)
```

``` c++
public:
bool Activation(
    PriceDiscountType relation, 
    PriceDiscountAccountCode accountCode, 
    PriceDiscountItemCode itemCode
)
```

#### Parameters

  - relation  
    Type: [Microsoft.Dynamics.Commerce.Runtime.DataModel.PriceDiscountType](pricediscounttype-enumeration-microsoft-dynamics-commerce-runtime-datamodel.md)  

<!-- end list -->

  - accountCode  
    Type: [Microsoft.Dynamics.Commerce.Runtime.DataModel.PriceDiscountAccountCode](pricediscountaccountcode-enumeration-microsoft-dynamics-commerce-runtime-datamodel.md)  

<!-- end list -->

  - itemCode  
    Type: [Microsoft.Dynamics.Commerce.Runtime.DataModel.PriceDiscountItemCode](pricediscountitemcode-enumeration-microsoft-dynamics-commerce-runtime-datamodel.md)  

#### Return Value

Type: [System.Boolean](https://technet.microsoft.com/library/a28wyd50\(v=ax.60\))  
Returns true if the relation is active, else false.  

## See Also

#### Reference

[DiscountParameters Class](discountparameters-class-microsoft-dynamics-commerce-runtime-services-pricingengine.md)

[Microsoft.Dynamics.Commerce.Runtime.Services.PricingEngine Namespace](microsoft-dynamics-commerce-runtime-services-pricingengine-namespace.md)

