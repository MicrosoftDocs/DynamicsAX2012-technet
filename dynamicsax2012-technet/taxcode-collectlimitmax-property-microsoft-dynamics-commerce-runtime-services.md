---
title: TaxCode.CollectLimitMax Property  (Microsoft.Dynamics.Commerce.Runtime.Services)
TOCTitle: CollectLimitMax Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.Services.TaxCode.CollectLimitMax
ms:mtpsurl: https://technet.microsoft.com/en-us/library/microsoft.dynamics.commerce.runtime.services.taxcode.collectlimitmax(v=AX.60)
ms:contentKeyID: 49834802
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.Services.TaxCode.CollectLimitMax
dev_langs:
- CSharp
- C++
- VB
---

# CollectLimitMax Property

Collection limits, the maximum tax that can be collected

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.Services](microsoft-dynamics-commerce-runtime-services-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Services (in Microsoft.Dynamics.Commerce.Runtime.Services.dll)

## Syntax

``` vb
'Declaration
Public Property CollectLimitMax As Decimal
    Get
    Protected Set
'Usage
Dim instance As TaxCode
Dim value As Decimal

value = instance.CollectLimitMax

instance.CollectLimitMax = value
```

``` csharp
public decimal CollectLimitMax { get; protected set; }
```

``` c++
public:
property Decimal CollectLimitMax {
    Decimal get ();
    protected: void set (Decimal value);
}
```

#### Property Value

Type: [System.Decimal](https://technet.microsoft.com/en-us/library/1k2e8atx\(v=ax.60\))  
Returns [Decimal](https://technet.microsoft.com/en-us/library/1k2e8atx\(v=ax.60\)).  

## Remarks

If the calculated tax is more than this, then THIS will be the tax amount collected

## See Also

#### Reference

[TaxCode Class](taxcode-class-microsoft-dynamics-commerce-runtime-services.md)

[Microsoft.Dynamics.Commerce.Runtime.Services Namespace](microsoft-dynamics-commerce-runtime-services-namespace.md)

