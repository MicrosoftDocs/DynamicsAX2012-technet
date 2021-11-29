---
title: SalesLine.LineManualDiscountPercentage Property  (Microsoft.Dynamics.Commerce.Runtime.DataModel)
TOCTitle: LineManualDiscountPercentage Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.DataModel.SalesLine.LineManualDiscountPercentage
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.datamodel.salesline.linemanualdiscountpercentage(v=AX.60)
ms:contentKeyID: 62213151
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataModel.SalesLine.LineManualDiscountPercentage
dev_langs:
- CSharp
- C++
- VB
---

# LineManualDiscountPercentage Property


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Gets or sets the manual line percent off value.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataModel](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Entities (in Microsoft.Dynamics.Commerce.Runtime.Entities.dll)

## Syntax

``` vb
'Declaration
<ColumnAttribute("LINEMANUALDISCOUNTPERCENTAGE")> _
<DataMemberAttribute> _
Public Property LineManualDiscountPercentage As Decimal
    Get
    Set
'Usage
Dim instance As SalesLine
Dim value As Decimal

value = instance.LineManualDiscountPercentage

instance.LineManualDiscountPercentage = value
```

``` csharp
[ColumnAttribute("LINEMANUALDISCOUNTPERCENTAGE")]
[DataMemberAttribute]
public decimal LineManualDiscountPercentage { get; set; }
```

``` c++
[ColumnAttribute(L"LINEMANUALDISCOUNTPERCENTAGE")]
[DataMemberAttribute]
public:
property Decimal LineManualDiscountPercentage {
    Decimal get ();
    void set (Decimal value);
}
```

#### Property Value

Type: [System.Decimal](https://technet.microsoft.com/library/1k2e8atx\(v=ax.60\))  
Returns [Decimal](https://technet.microsoft.com/library/1k2e8atx\(v=ax.60\)).  

## See Also

#### Reference

[SalesLine Class](salesline-class-microsoft-dynamics-commerce-runtime-datamodel.md)

[Microsoft.Dynamics.Commerce.Runtime.DataModel Namespace](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)

