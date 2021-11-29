---
title: TaxCode.TaxOnTaxInstance Property  (Microsoft.Dynamics.Commerce.Runtime.Services)
TOCTitle: TaxOnTaxInstance Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.Services.TaxCode.TaxOnTaxInstance
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.services.taxcode.taxontaxinstance(v=AX.60)
ms:contentKeyID: 49855249
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.Services.TaxCode.TaxOnTaxInstance
dev_langs:
- CSharp
- C++
- VB
---

# TaxOnTaxInstance Property


[!INCLUDE[archive-banner](includes/archive-banner.md)]

TaxCode instance referred by TaxOnTax property

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.Services](microsoft-dynamics-commerce-runtime-services-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Services (in Microsoft.Dynamics.Commerce.Runtime.Services.dll)

## Syntax

``` vb
'Declaration
Public Property TaxOnTaxInstance As TaxCode
    Get
    Set
'Usage
Dim instance As TaxCode
Dim value As TaxCode

value = instance.TaxOnTaxInstance

instance.TaxOnTaxInstance = value
```

``` csharp
public TaxCode TaxOnTaxInstance { get; set; }
```

``` c++
public:
property TaxCode^ TaxOnTaxInstance {
    TaxCode^ get ();
    void set (TaxCode^ value);
}
```

#### Property Value

Type: [Microsoft.Dynamics.Commerce.Runtime.Services.TaxCode](taxcode-class-microsoft-dynamics-commerce-runtime-services.md)  
Returns [TaxCode](taxcode-class-microsoft-dynamics-commerce-runtime-services.md).  

## See Also

#### Reference

[TaxCode Class](taxcode-class-microsoft-dynamics-commerce-runtime-services.md)

[Microsoft.Dynamics.Commerce.Runtime.Services Namespace](microsoft-dynamics-commerce-runtime-services-namespace.md)

