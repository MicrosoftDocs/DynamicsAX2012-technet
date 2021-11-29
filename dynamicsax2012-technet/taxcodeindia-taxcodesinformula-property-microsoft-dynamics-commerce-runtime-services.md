---
title: TaxCodeIndia.TaxCodesInFormula Property  (Microsoft.Dynamics.Commerce.Runtime.Services)
TOCTitle: TaxCodesInFormula Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.Services.TaxCodeIndia.TaxCodesInFormula
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.services.taxcodeindia.taxcodesinformula(v=AX.60)
ms:contentKeyID: 62207876
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.Services.TaxCodeIndia.TaxCodesInFormula
dev_langs:
- CSharp
- C++
- VB
---

# TaxCodesInFormula Property


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Gets all tax codes in the formula.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.Services](microsoft-dynamics-commerce-runtime-services-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Services (in Microsoft.Dynamics.Commerce.Runtime.Services.dll)

## Syntax

``` vb
'Declaration
Public ReadOnly Property TaxCodesInFormula As IList(Of String)
    Get
'Usage
Dim instance As TaxCodeIndia
Dim value As IList(Of String)

value = instance.TaxCodesInFormula
```

``` csharp
public IList<string> TaxCodesInFormula { get; }
```

``` c++
public:
property IList<String^>^ TaxCodesInFormula {
    IList<String^>^ get ();
}
```

#### Property Value

Type: [System.Collections.Generic.IList](https://technet.microsoft.com/library/5y536ey6\(v=ax.60\))\<[String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\))\>  
Returns [IList\<T\>](https://technet.microsoft.com/library/5y536ey6\(v=ax.60\)).  

## Remarks

For example, if the formula of a tax item is +\[ST-DL\]+\[ST-KA\], the property will be valued as \["ST-DL", "ST-KA"\].

## See Also

#### Reference

[TaxCodeIndia Class](taxcodeindia-class-microsoft-dynamics-commerce-runtime-services.md)

[Microsoft.Dynamics.Commerce.Runtime.Services Namespace](microsoft-dynamics-commerce-runtime-services-namespace.md)

