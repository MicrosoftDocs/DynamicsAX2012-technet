---
title: TaxCode.TaxOnTax Property  (Microsoft.Dynamics.Commerce.Runtime.Services)
TOCTitle: TaxOnTax Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.Services.TaxCode.TaxOnTax
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.services.taxcode.taxontax(v=AX.60)
ms:contentKeyID: 49853972
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.Services.TaxCode.TaxOnTax
dev_langs:
- CSharp
- C++
- VB
---

# TaxOnTax Property

TaxCode of the other sales tax that this tax is based on.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.Services](microsoft-dynamics-commerce-runtime-services-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Services (in Microsoft.Dynamics.Commerce.Runtime.Services.dll)

## Syntax

``` vb
'Declaration
Public Property TaxOnTax As String
    Get
    Protected Set
'Usage
Dim instance As TaxCode
Dim value As String

value = instance.TaxOnTax

instance.TaxOnTax = value
```

``` csharp
public string TaxOnTax { get; protected set; }
```

``` c++
public:
property String^ TaxOnTax {
    String^ get ();
    protected: void set (String^ value);
}
```

#### Property Value

Type: [System.String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\))  
Returns [String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\)).  

## See Also

#### Reference

[TaxCode Class](taxcode-class-microsoft-dynamics-commerce-runtime-services.md)

[Microsoft.Dynamics.Commerce.Runtime.Services Namespace](microsoft-dynamics-commerce-runtime-services-namespace.md)

