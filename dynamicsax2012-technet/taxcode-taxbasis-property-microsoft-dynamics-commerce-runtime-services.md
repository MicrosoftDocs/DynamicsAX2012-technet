---
title: TaxCode.TaxBasis Property  (Microsoft.Dynamics.Commerce.Runtime.Services)
TOCTitle: TaxBasis Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.Services.TaxCode.TaxBasis
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.services.taxcode.taxbasis(v=AX.60)
ms:contentKeyID: 49822257
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.Services.TaxCode.TaxBasis
dev_langs:
- CSharp
- C++
- VB
---

# TaxBasis Property

Get tax basis. A value used as starting point for tax formula.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.Services](microsoft-dynamics-commerce-runtime-services-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Services (in Microsoft.Dynamics.Commerce.Runtime.Services.dll)

## Syntax

``` vb
'Declaration
Public Property TaxBasis As Decimal
    Get
    Protected Set
'Usage
Dim instance As TaxCode
Dim value As Decimal

value = instance.TaxBasis

instance.TaxBasis = value
```

``` csharp
public decimal TaxBasis { get; protected set; }
```

``` c++
public:
property Decimal TaxBasis {
    Decimal get ();
    protected: void set (Decimal value);
}
```

#### Property Value

Type: [System.Decimal](https://technet.microsoft.com/library/1k2e8atx\(v=ax.60\))  
Returns [Decimal](https://technet.microsoft.com/library/1k2e8atx\(v=ax.60\)).  

## See Also

#### Reference

[TaxCode Class](taxcode-class-microsoft-dynamics-commerce-runtime-services.md)

[Microsoft.Dynamics.Commerce.Runtime.Services Namespace](microsoft-dynamics-commerce-runtime-services-namespace.md)

