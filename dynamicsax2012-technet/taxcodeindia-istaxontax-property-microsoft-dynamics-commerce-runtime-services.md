---
title: TaxCodeIndia.IsTaxOnTax Property  (Microsoft.Dynamics.Commerce.Runtime.Services)
TOCTitle: IsTaxOnTax Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.Services.TaxCodeIndia.IsTaxOnTax
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.services.taxcodeindia.istaxontax(v=AX.60)
ms:contentKeyID: 62209018
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.Services.TaxCodeIndia.IsTaxOnTax
dev_langs:
- CSharp
- C++
- VB
---

# IsTaxOnTax Property

Gets or sets a value indicating whether the tax code is a tax-on-tax or not.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.Services](microsoft-dynamics-commerce-runtime-services-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Services (in Microsoft.Dynamics.Commerce.Runtime.Services.dll)

## Syntax

``` vb
'Declaration
Public Property IsTaxOnTax As Boolean
    Get
    Set
'Usage
Dim instance As TaxCodeIndia
Dim value As Boolean

value = instance.IsTaxOnTax

instance.IsTaxOnTax = value
```

``` csharp
public bool IsTaxOnTax { get; set; }
```

``` c++
public:
property bool IsTaxOnTax {
    bool get ();
    void set (bool value);
}
```

#### Property Value

Type: [System.Boolean](https://technet.microsoft.com/library/a28wyd50\(v=ax.60\))  
Returns [Boolean](https://technet.microsoft.com/library/a28wyd50\(v=ax.60\)).  

## See Also

#### Reference

[TaxCodeIndia Class](taxcodeindia-class-microsoft-dynamics-commerce-runtime-services.md)

[Microsoft.Dynamics.Commerce.Runtime.Services Namespace](microsoft-dynamics-commerce-runtime-services-namespace.md)

