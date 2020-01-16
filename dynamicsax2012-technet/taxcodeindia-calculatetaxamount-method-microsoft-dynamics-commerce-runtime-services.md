---
title: TaxCodeIndia.CalculateTaxAmount Method  (Microsoft.Dynamics.Commerce.Runtime.Services)
TOCTitle: CalculateTaxAmount Method
ms:assetid: M:Microsoft.Dynamics.Commerce.Runtime.Services.TaxCodeIndia.CalculateTaxAmount(System.Collections.ObjectModel.ReadOnlyCollection{Microsoft.Dynamics.Commerce.Runtime.Services.TaxCode})
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.services.taxcodeindia.calculatetaxamount(v=AX.60)
ms:contentKeyID: 62210178
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.Services.TaxCodeIndia.CalculateTaxAmount
dev_langs:
- CSharp
- C++
- VB
---

# CalculateTaxAmount Method

Calculates tax for this code for the line item.

Updates the line item by adding a new Tax Item.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.Services](microsoft-dynamics-commerce-runtime-services-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Services (in Microsoft.Dynamics.Commerce.Runtime.Services.dll)

## Syntax

``` vb
'Declaration
Public Overrides Function CalculateTaxAmount ( _
    codes As ReadOnlyCollection(Of TaxCode) _
) As Decimal
'Usage
Dim instance As TaxCodeIndia
Dim codes As ReadOnlyCollection(Of TaxCode)
Dim returnValue As Decimal

returnValue = instance.CalculateTaxAmount(codes)
```

``` csharp
public override decimal CalculateTaxAmount(
    ReadOnlyCollection<TaxCode> codes
)
```

``` c++
public:
virtual Decimal CalculateTaxAmount(
    ReadOnlyCollection<TaxCode^>^ codes
) override
```

#### Parameters

  - codes  
    Type: [System.Collections.ObjectModel.ReadOnlyCollection](https://technet.microsoft.com/library/ms132474\(v=ax.60\))\<[TaxCode](taxcode-class-microsoft-dynamics-commerce-runtime-services.md)\>  

#### Return Value

Type: [System.Decimal](https://technet.microsoft.com/library/1k2e8atx\(v=ax.60\))  
The calculated amount of tax.  

## See Also

#### Reference

[TaxCodeIndia Class](taxcodeindia-class-microsoft-dynamics-commerce-runtime-services.md)

[Microsoft.Dynamics.Commerce.Runtime.Services Namespace](microsoft-dynamics-commerce-runtime-services-namespace.md)

