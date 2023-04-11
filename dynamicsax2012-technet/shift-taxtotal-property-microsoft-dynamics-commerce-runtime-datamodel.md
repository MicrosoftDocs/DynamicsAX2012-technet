---
title: Shift.TaxTotal Property  (Microsoft.Dynamics.Commerce.Runtime.DataModel)
TOCTitle: TaxTotal Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.DataModel.Shift.TaxTotal
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.datamodel.shift.taxtotal(v=AX.60)
ms:contentKeyID: 62208292
author: tonyafehr
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataModel.Shift.TaxTotal
dev_langs:
- CSharp
- C++
- VB
---

# TaxTotal Property


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Gets or sets total of tax.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataModel](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Entities (in Microsoft.Dynamics.Commerce.Runtime.Entities.dll)

## Syntax

``` vb
'Declaration
<DataMemberAttribute> _
<ColumnAttribute("TAXTOTAL")> _
Public Property TaxTotal As Decimal
    Get
    Set
'Usage
Dim instance As Shift
Dim value As Decimal

value = instance.TaxTotal

instance.TaxTotal = value
```

``` csharp
[DataMemberAttribute]
[ColumnAttribute("TAXTOTAL")]
public decimal TaxTotal { get; set; }
```

``` c++
[DataMemberAttribute]
[ColumnAttribute(L"TAXTOTAL")]
public:
property Decimal TaxTotal {
    Decimal get ();
    void set (Decimal value);
}
```

#### Property Value

Type: [System.Decimal](https://technet.microsoft.com/library/1k2e8atx\(v=ax.60\))  
Returns [Decimal](https://technet.microsoft.com/library/1k2e8atx\(v=ax.60\)).  

## See Also

#### Reference

[Shift Class](shift-class-microsoft-dynamics-commerce-runtime-datamodel.md)

[Microsoft.Dynamics.Commerce.Runtime.DataModel Namespace](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)

