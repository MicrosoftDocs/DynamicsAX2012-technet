---
title: TaxCodeUnit.TaxRoundOff Property  (Microsoft.Dynamics.Commerce.Runtime.DataModel)
TOCTitle: TaxRoundOff Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.DataModel.TaxCodeUnit.TaxRoundOff
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.datamodel.taxcodeunit.taxroundoff(v=AX.60)
ms:contentKeyID: 62211798
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataModel.TaxCodeUnit.TaxRoundOff
dev_langs:
- CSharp
- C++
- VB
---

# TaxRoundOff Property

Gets the tax round off.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataModel](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Entities (in Microsoft.Dynamics.Commerce.Runtime.Entities.dll)

## Syntax

``` vb
'Declaration
<DataMemberAttribute> _
<ColumnAttribute("TAXROUNDOFF")> _
Public Property TaxRoundOff As Decimal
    Get
    Friend Set
'Usage
Dim instance As TaxCodeUnit
Dim value As Decimal

value = instance.TaxRoundOff
```

``` csharp
[DataMemberAttribute]
[ColumnAttribute("TAXROUNDOFF")]
public decimal TaxRoundOff { get; internal set; }
```

``` c++
[DataMemberAttribute]
[ColumnAttribute(L"TAXROUNDOFF")]
public:
property Decimal TaxRoundOff {
    Decimal get ();
    internal: void set (Decimal value);
}
```

#### Property Value

Type: [System.Decimal](https://technet.microsoft.com/library/1k2e8atx\(v=ax.60\))  
Returns [Decimal](https://technet.microsoft.com/library/1k2e8atx\(v=ax.60\)).  

## See Also

#### Reference

[TaxCodeUnit Class](taxcodeunit-class-microsoft-dynamics-commerce-runtime-datamodel.md)

[Microsoft.Dynamics.Commerce.Runtime.DataModel Namespace](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)

