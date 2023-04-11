---
title: TaxCode.TaxCalculationMethod Property  (Microsoft.Dynamics.Commerce.Runtime.Services)
TOCTitle: TaxCalculationMethod Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.Services.TaxCode.TaxCalculationMethod
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.services.taxcode.taxcalculationmethod(v=AX.60)
ms:contentKeyID: 49846708
author: tonyafehr
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.Services.TaxCode.TaxCalculationMethod
dev_langs:
- CSharp
- C++
- VB
---

# TaxCalculationMethod Property


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Whether tax is calculated for entire amounts or for intervals

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.Services](microsoft-dynamics-commerce-runtime-services-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Services (in Microsoft.Dynamics.Commerce.Runtime.Services.dll)

## Syntax

``` vb
'Declaration
Public Property TaxCalculationMethod As TaxCalculationMode
    Get
    Protected Set
'Usage
Dim instance As TaxCode
Dim value As TaxCalculationMode

value = instance.TaxCalculationMethod

instance.TaxCalculationMethod = value
```

``` csharp
public TaxCalculationMode TaxCalculationMethod { get; protected set; }
```

``` c++
public:
property TaxCalculationMode TaxCalculationMethod {
    TaxCalculationMode get ();
    protected: void set (TaxCalculationMode value);
}
```

#### Property Value

Type: [Microsoft.Dynamics.Commerce.Runtime.Services.TaxCalculationMode](taxcalculationmode-enumeration-microsoft-dynamics-commerce-runtime-services.md)  
Returns [TaxCalculationMode](taxcalculationmode-enumeration-microsoft-dynamics-commerce-runtime-services.md).  

## See Also

#### Reference

[TaxCode Class](taxcode-class-microsoft-dynamics-commerce-runtime-services.md)

[Microsoft.Dynamics.Commerce.Runtime.Services Namespace](microsoft-dynamics-commerce-runtime-services-namespace.md)

