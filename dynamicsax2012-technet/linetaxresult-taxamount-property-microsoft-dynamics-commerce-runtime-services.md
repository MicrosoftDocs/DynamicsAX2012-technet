---
title: LineTaxResult.TaxAmount Property  (Microsoft.Dynamics.Commerce.Runtime.Services)
TOCTitle: TaxAmount Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.Services.LineTaxResult.TaxAmount
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.services.linetaxresult.taxamount(v=AX.60)
ms:contentKeyID: 49819198
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.Services.LineTaxResult.TaxAmount
dev_langs:
- CSharp
- C++
- VB
---

# TaxAmount Property


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Gets or sets the tax amount.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.Services](microsoft-dynamics-commerce-runtime-services-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Services (in Microsoft.Dynamics.Commerce.Runtime.Services.dll)

## Syntax

``` vb
'Declaration
Public Property TaxAmount As Decimal
    Get
    Set
'Usage
Dim instance As LineTaxResult
Dim value As Decimal

value = instance.TaxAmount

instance.TaxAmount = value
```

``` csharp
public decimal TaxAmount { get; set; }
```

``` c++
public:
property Decimal TaxAmount {
    Decimal get ();
    void set (Decimal value);
}
```

#### Property Value

Type: [System.Decimal](https://technet.microsoft.com/library/1k2e8atx\(v=ax.60\))  
The tax amount.  

## See Also

#### Reference

[LineTaxResult Class](linetaxresult-class-microsoft-dynamics-commerce-runtime-services.md)

[Microsoft.Dynamics.Commerce.Runtime.Services Namespace](microsoft-dynamics-commerce-runtime-services-namespace.md)

