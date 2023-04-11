---
title: ITaxCodeV1.TaxCalculationMethod Property  (Microsoft.Dynamics.Retail.Pos.Contracts.BusinessObjects)
TOCTitle: TaxCalculationMethod Property
ms:assetid: P:Microsoft.Dynamics.Retail.Pos.Contracts.BusinessObjects.ITaxCodeV1.TaxCalculationMethod
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.retail.pos.contracts.businessobjects.itaxcodev1.taxcalculationmethod(v=AX.60)
ms:contentKeyID: 47129046
author: tonyafehr
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Retail.Pos.Contracts.BusinessObjects.ITaxCodeV1.TaxCalculationMethod
dev_langs:
- CSharp
- C++
- VB
---

# TaxCalculationMethod Property


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Indicates whether the tax is calculated for entire amounts or for intervals.

**Namespace:**  [Microsoft.Dynamics.Retail.Pos.Contracts.BusinessObjects](microsoft-dynamics-retail-pos-contracts-businessobjects-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Retail.Pos.Contracts (in Microsoft.Dynamics.Retail.Pos.Contracts.dll)

## Syntax

``` vb
'Declaration
ReadOnly Property TaxCalculationMethod As TaxCalculationMode
    Get
'Usage
Dim instance As ITaxCodeV1
Dim value As TaxCalculationMode

value = instance.TaxCalculationMethod
```

``` csharp
TaxCalculationMode TaxCalculationMethod { get; }
```

``` c++
property TaxCalculationMode TaxCalculationMethod {
    TaxCalculationMode get ();
}
```

#### Property Value

Type: [Microsoft.Dynamics.Retail.Pos.Contracts.BusinessObjects.TaxCalculationMode](taxcalculationmode-enumeration-microsoft-dynamics-retail-pos-contracts-businessobjects.md)  
The [Microsoft.Dynamics.Retail.Pos.Contracts.BusinessObjects.TaxCalculationMode](taxcalculationmode-enumeration-microsoft-dynamics-retail-pos-contracts-businessobjects.md) value.  

## See Also

#### Reference

[ITaxCodeV1 Interface](itaxcodev1-interface-microsoft-dynamics-retail-pos-contracts-businessobjects.md)

[Microsoft.Dynamics.Retail.Pos.Contracts.BusinessObjects Namespace](microsoft-dynamics-retail-pos-contracts-businessobjects-namespace.md)

