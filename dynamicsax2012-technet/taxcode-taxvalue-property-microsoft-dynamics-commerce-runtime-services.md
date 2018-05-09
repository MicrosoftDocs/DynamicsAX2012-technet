---
title: TaxCode.TaxValue Property  (Microsoft.Dynamics.Commerce.Runtime.Services)
TOCTitle: TaxValue Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.Services.TaxCode.TaxValue
ms:mtpsurl: https://technet.microsoft.com/en-us/library/microsoft.dynamics.commerce.runtime.services.taxcode.taxvalue(v=AX.60)
ms:contentKeyID: 49843015
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.Services.TaxCode.TaxValue
dev_langs:
- CSharp
- C++
- VB
---

# TaxValue Property

Gets or sets the tax value.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.Services](microsoft-dynamics-commerce-runtime-services-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Services (in Microsoft.Dynamics.Commerce.Runtime.Services.dll)

## Syntax

``` vb
'Declaration
Public Property TaxValue As Decimal
    Get
    Set
'Usage
Dim instance As TaxCode
Dim value As Decimal

value = instance.TaxValue

instance.TaxValue = value
```

``` csharp
public decimal TaxValue { get; set; }
```

``` c++
public:
property Decimal TaxValue {
    Decimal get ();
    void set (Decimal value);
}
```

#### Property Value

Type: [System.Decimal](https://technet.microsoft.com/en-us/library/1k2e8atx\(v=ax.60\))  
The tax value.  

## See Also

#### Reference

[TaxCode Class](taxcode-class-microsoft-dynamics-commerce-runtime-services.md)

[Microsoft.Dynamics.Commerce.Runtime.Services Namespace](microsoft-dynamics-commerce-runtime-services-namespace.md)

