---
title: TaxLineIndia.TaxCodesInFormula Property  (Microsoft.Dynamics.Commerce.Runtime.DataModel)
TOCTitle: TaxCodesInFormula Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.DataModel.TaxLineIndia.TaxCodesInFormula
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.datamodel.taxlineindia.taxcodesinformula(v=AX.60)
ms:contentKeyID: 62207453
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataModel.TaxLineIndia.TaxCodesInFormula
dev_langs:
- CSharp
- C++
- VB
---

# TaxCodesInFormula Property

Gets Tax codes in the formula.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataModel](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Entities (in Microsoft.Dynamics.Commerce.Runtime.Entities.dll)

## Syntax

``` vb
'Declaration
Public ReadOnly Property TaxCodesInFormula As IList(Of String)
    Get
'Usage
Dim instance As TaxLineIndia
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

[TaxLineIndia Class](taxlineindia-class-microsoft-dynamics-commerce-runtime-datamodel.md)

[Microsoft.Dynamics.Commerce.Runtime.DataModel Namespace](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)

