---
title: TaxCode.AmountPerUnitValue Property  (Microsoft.Dynamics.Commerce.Runtime.Services)
TOCTitle: AmountPerUnitValue Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.Services.TaxCode.AmountPerUnitValue
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.services.taxcode.amountperunitvalue(v=AX.60)
ms:contentKeyID: 62210256
author: tonyafehr
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.Services.TaxCode.AmountPerUnitValue
dev_langs:
- CSharp
- C++
- VB
---

# AmountPerUnitValue Property


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Gets or sets the amount per unit value.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.Services](microsoft-dynamics-commerce-runtime-services-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Services (in Microsoft.Dynamics.Commerce.Runtime.Services.dll)

## Syntax

``` vb
'Declaration
Public Property AmountPerUnitValue As Decimal
    Get
    Set
'Usage
Dim instance As TaxCode
Dim value As Decimal

value = instance.AmountPerUnitValue

instance.AmountPerUnitValue = value
```

``` csharp
public decimal AmountPerUnitValue { get; set; }
```

``` c++
public:
property Decimal AmountPerUnitValue {
    Decimal get ();
    void set (Decimal value);
}
```

#### Property Value

Type: [System.Decimal](https://technet.microsoft.com/library/1k2e8atx\(v=ax.60\))  
The amount per unit value.  

## See Also

#### Reference

[TaxCode Class](taxcode-class-microsoft-dynamics-commerce-runtime-services.md)

[Microsoft.Dynamics.Commerce.Runtime.Services Namespace](microsoft-dynamics-commerce-runtime-services-namespace.md)

