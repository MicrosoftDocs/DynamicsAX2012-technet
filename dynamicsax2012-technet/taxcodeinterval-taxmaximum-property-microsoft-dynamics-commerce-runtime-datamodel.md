---
title: TaxCodeInterval.TaxMaximum Property  (Microsoft.Dynamics.Commerce.Runtime.DataModel)
TOCTitle: TaxMaximum Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.DataModel.TaxCodeInterval.TaxMaximum
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.datamodel.taxcodeinterval.taxmaximum(v=AX.60)
ms:contentKeyID: 62203159
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataModel.TaxCodeInterval.TaxMaximum
dev_langs:
- CSharp
- C++
- VB
---

# TaxMaximum Property

Gets the tax maximum.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataModel](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Entities (in Microsoft.Dynamics.Commerce.Runtime.Entities.dll)

## Syntax

``` vb
'Declaration
<ColumnAttribute("TAXMAX")> _
<DataMemberAttribute> _
Public Property TaxMaximum As Decimal
    Get
    Friend Set
'Usage
Dim instance As TaxCodeInterval
Dim value As Decimal

value = instance.TaxMaximum
```

``` csharp
[ColumnAttribute("TAXMAX")]
[DataMemberAttribute]
public decimal TaxMaximum { get; internal set; }
```

``` c++
[ColumnAttribute(L"TAXMAX")]
[DataMemberAttribute]
public:
property Decimal TaxMaximum {
    Decimal get ();
    internal: void set (Decimal value);
}
```

#### Property Value

Type: [System.Decimal](https://technet.microsoft.com/library/1k2e8atx\(v=ax.60\))  
Returns [Decimal](https://technet.microsoft.com/library/1k2e8atx\(v=ax.60\)).  

## See Also

#### Reference

[TaxCodeInterval Class](taxcodeinterval-class-microsoft-dynamics-commerce-runtime-datamodel.md)

[Microsoft.Dynamics.Commerce.Runtime.DataModel Namespace](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)

