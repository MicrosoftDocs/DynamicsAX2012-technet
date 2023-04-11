---
title: TaxCodeIndia.AbatementPercent Property  (Microsoft.Dynamics.Commerce.Runtime.Services)
TOCTitle: AbatementPercent Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.Services.TaxCodeIndia.AbatementPercent
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.services.taxcodeindia.abatementpercent(v=AX.60)
ms:contentKeyID: 62210977
author: tonyafehr
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.Services.TaxCodeIndia.AbatementPercent
dev_langs:
- CSharp
- C++
- VB
---

# AbatementPercent Property


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Gets or sets the percentage off item tax basis.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.Services](microsoft-dynamics-commerce-runtime-services-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Services (in Microsoft.Dynamics.Commerce.Runtime.Services.dll)

## Syntax

``` vb
'Declaration
Public Property AbatementPercent As Decimal
    Get
    Set
'Usage
Dim instance As TaxCodeIndia
Dim value As Decimal

value = instance.AbatementPercent

instance.AbatementPercent = value
```

``` csharp
public decimal AbatementPercent { get; set; }
```

``` c++
public:
property Decimal AbatementPercent {
    Decimal get ();
    void set (Decimal value);
}
```

#### Property Value

Type: [System.Decimal](https://technet.microsoft.com/library/1k2e8atx\(v=ax.60\))  
Returns [Decimal](https://technet.microsoft.com/library/1k2e8atx\(v=ax.60\)).  

## See Also

#### Reference

[TaxCodeIndia Class](taxcodeindia-class-microsoft-dynamics-commerce-runtime-services.md)

[Microsoft.Dynamics.Commerce.Runtime.Services Namespace](microsoft-dynamics-commerce-runtime-services-namespace.md)

