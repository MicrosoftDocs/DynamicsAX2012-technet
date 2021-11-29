---
title: TaxCode.TaxBase Property  (Microsoft.Dynamics.Commerce.Runtime.Services)
TOCTitle: TaxBase Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.Services.TaxCode.TaxBase
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.services.taxcode.taxbase(v=AX.60)
ms:contentKeyID: 49851451
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.Services.TaxCode.TaxBase
dev_langs:
- CSharp
- C++
- VB
---

# TaxBase Property


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Origin from which sales tax is calculated

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.Services](microsoft-dynamics-commerce-runtime-services-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Services (in Microsoft.Dynamics.Commerce.Runtime.Services.dll)

## Syntax

``` vb
'Declaration
Public Property TaxBase As TaxBase
    Get
    Protected Set
'Usage
Dim instance As TaxCode
Dim value As TaxBase

value = instance.TaxBase

instance.TaxBase = value
```

``` csharp
public TaxBase TaxBase { get; protected set; }
```

``` c++
public:
property TaxBase TaxBase {
    TaxBase get ();
    protected: void set (TaxBase value);
}
```

#### Property Value

Type: [Microsoft.Dynamics.Commerce.Runtime.Services.TaxBase](taxbase-enumeration-microsoft-dynamics-commerce-runtime-services.md)  
Returns [TaxBase](taxbase-enumeration-microsoft-dynamics-commerce-runtime-services.md).  

## See Also

#### Reference

[TaxCode Class](taxcode-class-microsoft-dynamics-commerce-runtime-services.md)

[Microsoft.Dynamics.Commerce.Runtime.Services Namespace](microsoft-dynamics-commerce-runtime-services-namespace.md)

