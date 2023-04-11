---
title: TaxCode.Value Property  (Microsoft.Dynamics.Commerce.Runtime.Services)
TOCTitle: Value Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.Services.TaxCode.Value
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.services.taxcode.value(v=AX.60)
ms:contentKeyID: 49852609
author: tonyafehr
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.Services.TaxCode.Value
dev_langs:
- CSharp
- C++
- VB
---

# Value Property


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Value/Rate of the tax

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.Services](microsoft-dynamics-commerce-runtime-services-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Services (in Microsoft.Dynamics.Commerce.Runtime.Services.dll)

## Syntax

``` vb
'Declaration
Public Property Value As Decimal
    Get
    Private Set
'Usage
Dim instance As TaxCode
Dim value As Decimal

value = instance.Value
```

``` csharp
public decimal Value { get; private set; }
```

``` c++
public:
property Decimal Value {
    Decimal get ();
    private: void set (Decimal value);
}
```

#### Property Value

Type: [System.Decimal](https://technet.microsoft.com/library/1k2e8atx\(v=ax.60\))  
Returns [Decimal](https://technet.microsoft.com/library/1k2e8atx\(v=ax.60\)).  

## Remarks

REMOVE in favor of TaxIntervals

## See Also

#### Reference

[TaxCode Class](taxcode-class-microsoft-dynamics-commerce-runtime-services.md)

[Microsoft.Dynamics.Commerce.Runtime.Services Namespace](microsoft-dynamics-commerce-runtime-services-namespace.md)

