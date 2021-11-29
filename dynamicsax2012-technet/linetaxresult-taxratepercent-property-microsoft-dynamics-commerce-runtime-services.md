---
title: LineTaxResult.TaxRatePercent Property  (Microsoft.Dynamics.Commerce.Runtime.Services)
TOCTitle: TaxRatePercent Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.Services.LineTaxResult.TaxRatePercent
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.services.linetaxresult.taxratepercent(v=AX.60)
ms:contentKeyID: 49826169
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.Services.LineTaxResult.TaxRatePercent
dev_langs:
- CSharp
- C++
- VB
---

# TaxRatePercent Property


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Gets or sets the tax rate percentage.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.Services](microsoft-dynamics-commerce-runtime-services-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Services (in Microsoft.Dynamics.Commerce.Runtime.Services.dll)

## Syntax

``` vb
'Declaration
Public Property TaxRatePercent As Decimal
    Get
    Set
'Usage
Dim instance As LineTaxResult
Dim value As Decimal

value = instance.TaxRatePercent

instance.TaxRatePercent = value
```

``` csharp
public decimal TaxRatePercent { get; set; }
```

``` c++
public:
property Decimal TaxRatePercent {
    Decimal get ();
    void set (Decimal value);
}
```

#### Property Value

Type: [System.Decimal](https://technet.microsoft.com/library/1k2e8atx\(v=ax.60\))  
The tax rate percentage.  

## See Also

#### Reference

[LineTaxResult Class](linetaxresult-class-microsoft-dynamics-commerce-runtime-services.md)

[Microsoft.Dynamics.Commerce.Runtime.Services Namespace](microsoft-dynamics-commerce-runtime-services-namespace.md)

