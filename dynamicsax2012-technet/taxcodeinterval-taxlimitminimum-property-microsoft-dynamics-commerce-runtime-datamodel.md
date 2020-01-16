---
title: TaxCodeInterval.TaxLimitMinimum Property  (Microsoft.Dynamics.Commerce.Runtime.DataModel)
TOCTitle: TaxLimitMinimum Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.DataModel.TaxCodeInterval.TaxLimitMinimum
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.datamodel.taxcodeinterval.taxlimitminimum(v=AX.60)
ms:contentKeyID: 62210055
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataModel.TaxCodeInterval.TaxLimitMinimum
dev_langs:
- CSharp
- C++
- VB
---

# TaxLimitMinimum Property

Gets the tax limit minimum.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataModel](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Entities (in Microsoft.Dynamics.Commerce.Runtime.Entities.dll)

## Syntax

``` vb
'Declaration
<ColumnAttribute("TAXLIMITMIN")> _
<DataMemberAttribute> _
Public Property TaxLimitMinimum As Decimal
    Get
    Friend Set
'Usage
Dim instance As TaxCodeInterval
Dim value As Decimal

value = instance.TaxLimitMinimum
```

``` csharp
[ColumnAttribute("TAXLIMITMIN")]
[DataMemberAttribute]
public decimal TaxLimitMinimum { get; internal set; }
```

``` c++
[ColumnAttribute(L"TAXLIMITMIN")]
[DataMemberAttribute]
public:
property Decimal TaxLimitMinimum {
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

