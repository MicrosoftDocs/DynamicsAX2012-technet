---
title: IRoundingV3.GetMinimumCurrencyUnit Method  (Microsoft.Dynamics.Retail.Pos.Contracts.Services)
TOCTitle: GetMinimumCurrencyUnit Method
ms:assetid: M:Microsoft.Dynamics.Retail.Pos.Contracts.Services.IRoundingV3.GetMinimumCurrencyUnit(System.String)
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.retail.pos.contracts.services.iroundingv3.getminimumcurrencyunit(v=AX.60)
ms:contentKeyID: 51677228
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Retail.Pos.Contracts.Services.IRoundingV3.GetMinimumCurrencyUnit
dev_langs:
- CSharp
- C++
- VB
---

# GetMinimumCurrencyUnit Method


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Gets the lowest currency unit that will be rounded to for a given currency code using either Sales or Amount rounding.

**Namespace:**  [Microsoft.Dynamics.Retail.Pos.Contracts.Services](microsoft-dynamics-retail-pos-contracts-services-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Retail.Pos.Contracts (in Microsoft.Dynamics.Retail.Pos.Contracts.dll)

## Syntax

``` vb
'Declaration
Function GetMinimumCurrencyUnit ( _
    currencyCode As String _
) As Decimal
'Usage
Dim instance As IRoundingV3
Dim currencyCode As String
Dim returnValue As Decimal

returnValue = instance.GetMinimumCurrencyUnit(currencyCode)
```

``` csharp
decimal GetMinimumCurrencyUnit(
    string currencyCode
)
```

``` c++
Decimal GetMinimumCurrencyUnit(
    String^ currencyCode
)
```

#### Parameters

  - currencyCode  
    Type: [System.String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\))  

#### Return Value

Type: [System.Decimal](https://technet.microsoft.com/library/1k2e8atx\(v=ax.60\))  
Lowest currency unit  

## Remarks

For example, 0.01

## See Also

#### Reference

[IRoundingV3 Interface](iroundingv3-interface-microsoft-dynamics-retail-pos-contracts-services.md)

[Microsoft.Dynamics.Retail.Pos.Contracts.Services Namespace](microsoft-dynamics-retail-pos-contracts-services-namespace.md)

