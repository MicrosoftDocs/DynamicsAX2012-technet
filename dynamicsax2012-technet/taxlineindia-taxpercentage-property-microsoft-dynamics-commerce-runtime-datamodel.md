---
title: TaxLineIndia.TaxPercentage Property  (Microsoft.Dynamics.Commerce.Runtime.DataModel)
TOCTitle: TaxPercentage Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.DataModel.TaxLineIndia.TaxPercentage
ms:mtpsurl: https://technet.microsoft.com/en-us/library/microsoft.dynamics.commerce.runtime.datamodel.taxlineindia.taxpercentage(v=AX.60)
ms:contentKeyID: 62207763
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataModel.TaxLineIndia.TaxPercentage
dev_langs:
- CSharp
- C++
- VB
---

# TaxPercentage Property

Gets or sets tax percentage.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataModel](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Entities (in Microsoft.Dynamics.Commerce.Runtime.Entities.dll)

## Syntax

``` vb
'Declaration
<ColumnAttribute("TAXPERCENTAGE")> _
<DataMemberAttribute> _
Public Property TaxPercentage As Decimal
    Get
    Set
'Usage
Dim instance As TaxLineIndia
Dim value As Decimal

value = instance.TaxPercentage

instance.TaxPercentage = value
```

``` csharp
[ColumnAttribute("TAXPERCENTAGE")]
[DataMemberAttribute]
public decimal TaxPercentage { get; set; }
```

``` c++
[ColumnAttribute(L"TAXPERCENTAGE")]
[DataMemberAttribute]
public:
property Decimal TaxPercentage {
    Decimal get ();
    void set (Decimal value);
}
```

#### Property Value

Type: [System.Decimal](https://technet.microsoft.com/en-us/library/1k2e8atx\(v=ax.60\))  
Returns [Decimal](https://technet.microsoft.com/en-us/library/1k2e8atx\(v=ax.60\)).  

## See Also

#### Reference

[TaxLineIndia Class](taxlineindia-class-microsoft-dynamics-commerce-runtime-datamodel.md)

[Microsoft.Dynamics.Commerce.Runtime.DataModel Namespace](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)

