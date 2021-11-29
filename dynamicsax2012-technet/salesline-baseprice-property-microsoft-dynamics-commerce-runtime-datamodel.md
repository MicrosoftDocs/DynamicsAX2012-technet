---
title: SalesLine.BasePrice Property  (Microsoft.Dynamics.Commerce.Runtime.DataModel)
TOCTitle: BasePrice Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.DataModel.SalesLine.BasePrice
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.datamodel.salesline.baseprice(v=AX.60)
ms:contentKeyID: 62213817
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataModel.SalesLine.BasePrice
dev_langs:
- CSharp
- C++
- VB
---

# BasePrice Property


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Gets or sets the base price of the item on this sales line.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataModel](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Entities (in Microsoft.Dynamics.Commerce.Runtime.Entities.dll)

## Syntax

``` vb
'Declaration
<DataMemberAttribute> _
<ColumnAttribute("BASEPRICE")> _
Public Property BasePrice As Decimal
    Get
    Set
'Usage
Dim instance As SalesLine
Dim value As Decimal

value = instance.BasePrice

instance.BasePrice = value
```

``` csharp
[DataMemberAttribute]
[ColumnAttribute("BASEPRICE")]
public decimal BasePrice { get; set; }
```

``` c++
[DataMemberAttribute]
[ColumnAttribute(L"BASEPRICE")]
public:
property Decimal BasePrice {
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

