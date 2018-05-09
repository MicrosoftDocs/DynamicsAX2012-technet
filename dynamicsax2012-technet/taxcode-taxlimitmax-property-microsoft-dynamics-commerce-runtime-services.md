---
title: TaxCode.TaxLimitMax Property  (Microsoft.Dynamics.Commerce.Runtime.Services)
TOCTitle: TaxLimitMax Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.Services.TaxCode.TaxLimitMax
ms:mtpsurl: https://technet.microsoft.com/en-us/library/microsoft.dynamics.commerce.runtime.services.taxcode.taxlimitmax(v=AX.60)
ms:contentKeyID: 49842658
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.Services.TaxCode.TaxLimitMax
dev_langs:
- CSharp
- C++
- VB
---

# TaxLimitMax Property

Maximum amount required to calculate this tax

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.Services](microsoft-dynamics-commerce-runtime-services-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Services (in Microsoft.Dynamics.Commerce.Runtime.Services.dll)

## Syntax

``` vb
'Declaration
Public Property TaxLimitMax As Decimal
    Get
    Private Set
'Usage
Dim instance As TaxCode
Dim value As Decimal

value = instance.TaxLimitMax
```

``` csharp
public decimal TaxLimitMax { get; private set; }
```

``` c++
public:
property Decimal TaxLimitMax {
    Decimal get ();
    private: void set (Decimal value);
}
```

#### Property Value

Type: [System.Decimal](https://technet.microsoft.com/en-us/library/1k2e8atx\(v=ax.60\))  
Returns [Decimal](https://technet.microsoft.com/en-us/library/1k2e8atx\(v=ax.60\)).  

## Remarks

REMOVE in favor of TaxIntervals collection. If the price is more than this, then the tax will not be calculated

## See Also

#### Reference

[TaxCode Class](taxcode-class-microsoft-dynamics-commerce-runtime-services.md)

[Microsoft.Dynamics.Commerce.Runtime.Services Namespace](microsoft-dynamics-commerce-runtime-services-namespace.md)

