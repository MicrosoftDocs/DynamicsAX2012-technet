---
title: DiscountParameters.ValidRelation Method (PriceDiscountAccountCode, String) (Microsoft.Dynamics.Commerce.Runtime.Services.PricingEngine)
TOCTitle: ValidRelation Method (PriceDiscountAccountCode, String)
ms:assetid: M:Microsoft.Dynamics.Commerce.Runtime.Services.PricingEngine.DiscountParameters.ValidRelation(Microsoft.Dynamics.Commerce.Runtime.DataModel.PriceDiscountAccountCode,System.String)
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.services.pricingengine.discountparameters.validrelation(v=AX.60)
ms:contentKeyID: 49825224
author: tonyafehr
ms.date: 05/18/2015
mtps_version: v=AX.60
dev_langs:
- vb
- csharp
- c++
---

# ValidRelation Method (PriceDiscountAccountCode, String)


[!INCLUDE[archive-banner](includes/archive-banner.md)]

True if there is a valid relation between the accountcode and relation.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.Services.PricingEngine](microsoft-dynamics-commerce-runtime-services-pricingengine-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Services.PricingEngine (in Microsoft.Dynamics.Commerce.Runtime.Services.PricingEngine.dll)

## Syntax

``` vb
'Declaration
Public Shared Function ValidRelation ( _
    accountCode As PriceDiscountAccountCode, _
    relation As String _
) As Boolean
'Usage
Dim accountCode As PriceDiscountAccountCode
Dim relation As String
Dim returnValue As Boolean

returnValue = DiscountParameters.ValidRelation(accountCode, _
    relation)
```

``` csharp
public static bool ValidRelation(
    PriceDiscountAccountCode accountCode,
    string relation
)
```

``` c++
public:
static bool ValidRelation(
    PriceDiscountAccountCode accountCode, 
    String^ relation
)
```

#### Parameters

  - accountCode  
    Type: [Microsoft.Dynamics.Commerce.Runtime.DataModel.PriceDiscountAccountCode](pricediscountaccountcode-enumeration-microsoft-dynamics-commerce-runtime-datamodel.md)  

<!-- end list -->

  - relation  
    Type: [System.String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\))  

#### Return Value

Type: [System.Boolean](https://technet.microsoft.com/library/a28wyd50\(v=ax.60\))  
True if the account code allows the given relation.  

## See Also

#### Reference

[DiscountParameters Class](discountparameters-class-microsoft-dynamics-commerce-runtime-services-pricingengine.md)

[ValidRelation Overload](discountparameters-validrelation-method-microsoft-dynamics-commerce-runtime-services-pricingengine.md)

[Microsoft.Dynamics.Commerce.Runtime.Services.PricingEngine Namespace](microsoft-dynamics-commerce-runtime-services-pricingengine-namespace.md)

