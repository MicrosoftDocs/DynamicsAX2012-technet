---
title: ChargeLine.SaleLineNumber Property  (Microsoft.Dynamics.Commerce.Runtime.DataModel)
TOCTitle: SaleLineNumber Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.DataModel.ChargeLine.SaleLineNumber
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.datamodel.chargeline.salelinenumber(v=AX.60)
ms:contentKeyID: 62202680
author: Khairunj
ms.author: daxcpft
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataModel.ChargeLine.SaleLineNumber
dev_langs:
- CSharp
- C++
- VB
---

# SaleLineNumber Property

Gets or sets the sale line number.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataModel](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Entities (in Microsoft.Dynamics.Commerce.Runtime.Entities.dll)

## Syntax

``` vb
'Declaration
<DataMemberAttribute> _
<ColumnAttribute("SALELINENUM")> _
<ReadOnlyAttribute("SALELINENUM")> _
Public Property SaleLineNumber As Decimal
    Get
    Set
'Usage
Dim instance As ChargeLine
Dim value As Decimal

value = instance.SaleLineNumber

instance.SaleLineNumber = value
```

``` csharp
[DataMemberAttribute]
[ColumnAttribute("SALELINENUM")]
[ReadOnlyAttribute("SALELINENUM")]
public decimal SaleLineNumber { get; set; }
```

``` c++
[DataMemberAttribute]
[ColumnAttribute(L"SALELINENUM")]
[ReadOnlyAttribute(L"SALELINENUM")]
public:
property Decimal SaleLineNumber {
    Decimal get ();
    void set (Decimal value);
}
```

#### Property Value

Type: [System.Decimal](https://technet.microsoft.com/library/1k2e8atx\(v=ax.60\))  
The sale line number.  

## See Also

#### Reference

[ChargeLine Class](chargeline-class-microsoft-dynamics-commerce-runtime-datamodel.md)

[Microsoft.Dynamics.Commerce.Runtime.DataModel Namespace](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)

