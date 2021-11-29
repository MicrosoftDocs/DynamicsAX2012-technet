---
title: TaxCode.AmountPerUnitCalculationBase Property  (Microsoft.Dynamics.Commerce.Runtime.Services)
TOCTitle: AmountPerUnitCalculationBase Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.Services.TaxCode.AmountPerUnitCalculationBase
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.services.taxcode.amountperunitcalculationbase(v=AX.60)
ms:contentKeyID: 49844562
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.Services.TaxCode.AmountPerUnitCalculationBase
dev_langs:
- CSharp
- C++
- VB
---

# AmountPerUnitCalculationBase Property


[!INCLUDE[archive-banner](includes/archive-banner.md)]

returns the calculation base for AmountPerUnit tax calculations

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.Services](microsoft-dynamics-commerce-runtime-services-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Services (in Microsoft.Dynamics.Commerce.Runtime.Services.dll)

## Syntax

``` vb
'Declaration
Public ReadOnly Property AmountPerUnitCalculationBase As Decimal
    Get
'Usage
Dim instance As TaxCode
Dim value As Decimal

value = instance.AmountPerUnitCalculationBase
```

``` csharp
public decimal AmountPerUnitCalculationBase { get; }
```

``` c++
public:
property Decimal AmountPerUnitCalculationBase {
    Decimal get ();
}
```

#### Property Value

Type: [System.Decimal](https://technet.microsoft.com/library/1k2e8atx\(v=ax.60\))  
Returns [Decimal](https://technet.microsoft.com/library/1k2e8atx\(v=ax.60\)).  

## See Also

#### Reference

[TaxCode Class](taxcode-class-microsoft-dynamics-commerce-runtime-services.md)

[Microsoft.Dynamics.Commerce.Runtime.Services Namespace](microsoft-dynamics-commerce-runtime-services-namespace.md)

