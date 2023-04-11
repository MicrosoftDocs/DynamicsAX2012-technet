---
title: TaxCode.CalculateTaxExcluded Method  (Microsoft.Dynamics.Commerce.Runtime.Services)
TOCTitle: CalculateTaxExcluded Method
ms:assetid: M:Microsoft.Dynamics.Commerce.Runtime.Services.TaxCode.CalculateTaxExcluded(System.Collections.ObjectModel.ReadOnlyCollection{Microsoft.Dynamics.Commerce.Runtime.Services.TaxCode})
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.services.taxcode.calculatetaxexcluded(v=AX.60)
ms:contentKeyID: 49853982
author: tonyafehr
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.Services.TaxCode.CalculateTaxExcluded
dev_langs:
- CSharp
- C++
- VB
---

# CalculateTaxExcluded Method


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Calculate TaxExclusive amounts for a single tax code

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.Services](microsoft-dynamics-commerce-runtime-services-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Services (in Microsoft.Dynamics.Commerce.Runtime.Services.dll)

## Syntax

``` vb
'Declaration
Public Function CalculateTaxExcluded ( _
    codes As ReadOnlyCollection(Of TaxCode) _
) As Decimal
'Usage
Dim instance As TaxCode
Dim codes As ReadOnlyCollection(Of TaxCode)
Dim returnValue As Decimal

returnValue = instance.CalculateTaxExcluded(codes)
```

``` csharp
public decimal CalculateTaxExcluded(
    ReadOnlyCollection<TaxCode> codes
)
```

``` c++
public:
Decimal CalculateTaxExcluded(
    ReadOnlyCollection<TaxCode^>^ codes
)
```

#### Parameters

  - codes  
    Type: [System.Collections.ObjectModel.ReadOnlyCollection](https://technet.microsoft.com/library/ms132474\(v=ax.60\))\<[TaxCode](taxcode-class-microsoft-dynamics-commerce-runtime-services.md)\>  

#### Return Value

Type: [System.Decimal](https://technet.microsoft.com/library/1k2e8atx\(v=ax.60\))  
The tax exclusive amount.  

## See Also

#### Reference

[TaxCode Class](taxcode-class-microsoft-dynamics-commerce-runtime-services.md)

[Microsoft.Dynamics.Commerce.Runtime.Services Namespace](microsoft-dynamics-commerce-runtime-services-namespace.md)

