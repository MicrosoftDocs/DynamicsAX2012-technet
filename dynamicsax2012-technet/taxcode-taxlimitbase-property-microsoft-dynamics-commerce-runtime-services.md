---
title: TaxCode.TaxLimitBase Property  (Microsoft.Dynamics.Commerce.Runtime.Services)
TOCTitle: TaxLimitBase Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.Services.TaxCode.TaxLimitBase
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.services.taxcode.taxlimitbase(v=AX.60)
ms:contentKeyID: 49851070
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.Services.TaxCode.TaxLimitBase
dev_langs:
- CSharp
- C++
- VB
---

# TaxLimitBase Property

Basis of sales tax limits

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.Services](microsoft-dynamics-commerce-runtime-services-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Services (in Microsoft.Dynamics.Commerce.Runtime.Services.dll)

## Syntax

``` vb
'Declaration
Public Property TaxLimitBase As TaxLimitBase
    Get
    Protected Set
'Usage
Dim instance As TaxCode
Dim value As TaxLimitBase

value = instance.TaxLimitBase

instance.TaxLimitBase = value
```

``` csharp
public TaxLimitBase TaxLimitBase { get; protected set; }
```

``` c++
public:
property TaxLimitBase TaxLimitBase {
    TaxLimitBase get ();
    protected: void set (TaxLimitBase value);
}
```

#### Property Value

Type: [Microsoft.Dynamics.Commerce.Runtime.Services.TaxLimitBase](taxlimitbase-enumeration-microsoft-dynamics-commerce-runtime-services.md)  
Returns [TaxLimitBase](taxlimitbase-enumeration-microsoft-dynamics-commerce-runtime-services.md).  

## See Also

#### Reference

[TaxCode Class](taxcode-class-microsoft-dynamics-commerce-runtime-services.md)

[Microsoft.Dynamics.Commerce.Runtime.Services Namespace](microsoft-dynamics-commerce-runtime-services-namespace.md)

