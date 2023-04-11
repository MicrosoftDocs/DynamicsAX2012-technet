---
title: TaxableItem.TaxAmountExemptInclusive Property  (Microsoft.Dynamics.Commerce.Runtime.DataModel)
TOCTitle: TaxAmountExemptInclusive Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.DataModel.TaxableItem.TaxAmountExemptInclusive
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.datamodel.taxableitem.taxamountexemptinclusive(v=AX.60)
ms:contentKeyID: 49837521
author: tonyafehr
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataModel.TaxableItem.TaxAmountExemptInclusive
dev_langs:
- CSharp
- C++
- VB
---

# TaxAmountExemptInclusive Property


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Gets or sets the exempt inclusive tax amount for the item.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataModel](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Entities (in Microsoft.Dynamics.Commerce.Runtime.Entities.dll)

## Syntax

``` vb
'Declaration
<ColumnAttribute("TAXAMOUNTEXEMPTINCLUSIVE")> _
<DataMemberAttribute> _
Public Property TaxAmountExemptInclusive As Decimal
    Get
    Set
'Usage
Dim instance As TaxableItem
Dim value As Decimal

value = instance.TaxAmountExemptInclusive

instance.TaxAmountExemptInclusive = value
```

``` csharp
[ColumnAttribute("TAXAMOUNTEXEMPTINCLUSIVE")]
[DataMemberAttribute]
public decimal TaxAmountExemptInclusive { get; set; }
```

``` c++
[ColumnAttribute(L"TAXAMOUNTEXEMPTINCLUSIVE")]
[DataMemberAttribute]
public:
property Decimal TaxAmountExemptInclusive {
    Decimal get ();
    void set (Decimal value);
}
```

#### Property Value

Type: [System.Decimal](https://technet.microsoft.com/library/1k2e8atx\(v=ax.60\))  
Returns [Decimal](https://technet.microsoft.com/library/1k2e8atx\(v=ax.60\)).  

## See Also

#### Reference

[TaxableItem Class](taxableitem-class-microsoft-dynamics-commerce-runtime-datamodel.md)

[Microsoft.Dynamics.Commerce.Runtime.DataModel Namespace](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)

