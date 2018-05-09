---
title: TaxCodeInterval.TaxMinimum Property  (Microsoft.Dynamics.Commerce.Runtime.DataModel)
TOCTitle: TaxMinimum Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.DataModel.TaxCodeInterval.TaxMinimum
ms:mtpsurl: https://technet.microsoft.com/en-us/library/microsoft.dynamics.commerce.runtime.datamodel.taxcodeinterval.taxminimum(v=AX.60)
ms:contentKeyID: 62209718
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataModel.TaxCodeInterval.TaxMinimum
dev_langs:
- CSharp
- C++
- VB
---

# TaxMinimum Property

Gets the tax minimum.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataModel](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Entities (in Microsoft.Dynamics.Commerce.Runtime.Entities.dll)

## Syntax

``` vb
'Declaration
<ColumnAttribute("TAXMIN")> _
<DataMemberAttribute> _
Public Property TaxMinimum As Decimal
    Get
    Friend Set
'Usage
Dim instance As TaxCodeInterval
Dim value As Decimal

value = instance.TaxMinimum
```

``` csharp
[ColumnAttribute("TAXMIN")]
[DataMemberAttribute]
public decimal TaxMinimum { get; internal set; }
```

``` c++
[ColumnAttribute(L"TAXMIN")]
[DataMemberAttribute]
public:
property Decimal TaxMinimum {
    Decimal get ();
    internal: void set (Decimal value);
}
```

#### Property Value

Type: [System.Decimal](https://technet.microsoft.com/en-us/library/1k2e8atx\(v=ax.60\))  
Returns [Decimal](https://technet.microsoft.com/en-us/library/1k2e8atx\(v=ax.60\)).  

## See Also

#### Reference

[TaxCodeInterval Class](taxcodeinterval-class-microsoft-dynamics-commerce-runtime-datamodel.md)

[Microsoft.Dynamics.Commerce.Runtime.DataModel Namespace](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)

