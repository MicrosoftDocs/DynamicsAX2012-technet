---
title: TaxCode.CollectLimitMin Property  (Microsoft.Dynamics.Commerce.Runtime.Services)
TOCTitle: CollectLimitMin Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.Services.TaxCode.CollectLimitMin
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.services.taxcode.collectlimitmin(v=AX.60)
ms:contentKeyID: 49844508
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.Services.TaxCode.CollectLimitMin
dev_langs:
- CSharp
- C++
- VB
---

# CollectLimitMin Property


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Collection limits, the minimum tax that can be collected

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.Services](microsoft-dynamics-commerce-runtime-services-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Services (in Microsoft.Dynamics.Commerce.Runtime.Services.dll)

## Syntax

``` vb
'Declaration
Public Property CollectLimitMin As Decimal
    Get
    Protected Set
'Usage
Dim instance As TaxCode
Dim value As Decimal

value = instance.CollectLimitMin

instance.CollectLimitMin = value
```

``` csharp
public decimal CollectLimitMin { get; protected set; }
```

``` c++
public:
property Decimal CollectLimitMin {
    Decimal get ();
    protected: void set (Decimal value);
}
```

#### Property Value

Type: [System.Decimal](https://technet.microsoft.com/library/1k2e8atx\(v=ax.60\))  
Returns [Decimal](https://technet.microsoft.com/library/1k2e8atx\(v=ax.60\)).  

## Remarks

If the calculated tax is less than this, then ZERO tax will be collected

## See Also

#### Reference

[TaxCode Class](taxcode-class-microsoft-dynamics-commerce-runtime-services.md)

[Microsoft.Dynamics.Commerce.Runtime.Services Namespace](microsoft-dynamics-commerce-runtime-services-namespace.md)

