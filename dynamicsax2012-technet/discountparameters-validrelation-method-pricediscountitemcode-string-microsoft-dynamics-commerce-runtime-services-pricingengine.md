---
title: DiscountParameters.ValidRelation Method (PriceDiscountItemCode, String) (Microsoft.Dynamics.Commerce.Runtime.Services.PricingEngine)
TOCTitle: ValidRelation Method (PriceDiscountItemCode, String)
ms:assetid: M:Microsoft.Dynamics.Commerce.Runtime.Services.PricingEngine.DiscountParameters.ValidRelation(Microsoft.Dynamics.Commerce.Runtime.DataModel.PriceDiscountItemCode,System.String)
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.services.pricingengine.discountparameters.validrelation(v=AX.60)
ms:contentKeyID: 49849352
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
dev_langs:
- vb
- csharp
- c++
---

# ValidRelation Method (PriceDiscountItemCode, String)


[!INCLUDE[archive-banner](includes/archive-banner.md)]

True if there is a valid relation between the itemcode and relation.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.Services.PricingEngine](microsoft-dynamics-commerce-runtime-services-pricingengine-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Services.PricingEngine (in Microsoft.Dynamics.Commerce.Runtime.Services.PricingEngine.dll)

## Syntax

``` vb
'Declaration
Public Shared Function ValidRelation ( _
    itemCode As PriceDiscountItemCode, _
    relation As String _
) As Boolean
'Usage
Dim itemCode As PriceDiscountItemCode
Dim relation As String
Dim returnValue As Boolean

returnValue = DiscountParameters.ValidRelation(itemCode, _
    relation)
```

``` csharp
public static bool ValidRelation(
    PriceDiscountItemCode itemCode,
    string relation
)
```

``` c++
public:
static bool ValidRelation(
    PriceDiscountItemCode itemCode, 
    String^ relation
)
```

#### Parameters

  - itemCode  
    Type: [Microsoft.Dynamics.Commerce.Runtime.DataModel.PriceDiscountItemCode](pricediscountitemcode-enumeration-microsoft-dynamics-commerce-runtime-datamodel.md)  

<!-- end list -->

  - relation  
    Type: [System.String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\))  

#### Return Value

Type: [System.Boolean](https://technet.microsoft.com/library/a28wyd50\(v=ax.60\))  
Returns true if the relation ok, else false.  

## See Also

#### Reference

[DiscountParameters Class](discountparameters-class-microsoft-dynamics-commerce-runtime-services-pricingengine.md)

[ValidRelation Overload](discountparameters-validrelation-method-microsoft-dynamics-commerce-runtime-services-pricingengine.md)

[Microsoft.Dynamics.Commerce.Runtime.Services.PricingEngine Namespace](microsoft-dynamics-commerce-runtime-services-pricingengine-namespace.md)

