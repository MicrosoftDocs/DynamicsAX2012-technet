---
title: TaxCode.PercentPerTax Method  (Microsoft.Dynamics.Commerce.Runtime.Services)
TOCTitle: PercentPerTax Method
ms:assetid: M:Microsoft.Dynamics.Commerce.Runtime.Services.TaxCode.PercentPerTax
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.services.taxcode.percentpertax(v=AX.60)
ms:contentKeyID: 49829719
author: tonyafehr
ms.date: 05/18/2015
mtps_version: v=AX.60
dev_langs:
- vb
- csharp
- c++
---

# PercentPerTax Method


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Return the basic rate for this tax

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.Services](microsoft-dynamics-commerce-runtime-services-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Services (in Microsoft.Dynamics.Commerce.Runtime.Services.dll)

## Syntax

``` vb
'Declaration
Public Function PercentPerTax As Decimal
'Usage
Dim instance As TaxCode
Dim returnValue As Decimal

returnValue = instance.PercentPerTax()
```

``` csharp
public decimal PercentPerTax()
```

``` c++
public:
Decimal PercentPerTax()
```

#### Return Value

Type: [System.Decimal](https://technet.microsoft.com/library/1k2e8atx\(v=ax.60\))  
The basic rate for this tax.  

## See Also

#### Reference

[TaxCode Class](taxcode-class-microsoft-dynamics-commerce-runtime-services.md)

[PercentPerTax Overload](taxcode-percentpertax-method-microsoft-dynamics-commerce-runtime-services.md)

[Microsoft.Dynamics.Commerce.Runtime.Services Namespace](microsoft-dynamics-commerce-runtime-services-namespace.md)

