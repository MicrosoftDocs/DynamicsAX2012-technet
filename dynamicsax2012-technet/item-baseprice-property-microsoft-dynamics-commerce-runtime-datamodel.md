---
title: Item.BasePrice Property  (Microsoft.Dynamics.Commerce.Runtime.DataModel)
TOCTitle: BasePrice Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.DataModel.Item.BasePrice
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.datamodel.item.baseprice(v=AX.60)
ms:contentKeyID: 49848180
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataModel.Item.BasePrice
dev_langs:
- CSharp
- C++
- VB
---

# BasePrice Property

Gets the item base price.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataModel](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Entities (in Microsoft.Dynamics.Commerce.Runtime.Entities.dll)

## Syntax

``` vb
'Declaration
<ColumnAttribute("PRICE")> _
<DataMemberAttribute> _
Public Property BasePrice As Decimal
    Get
    Friend Set
'Usage
Dim instance As Item
Dim value As Decimal

value = instance.BasePrice
```

``` csharp
[ColumnAttribute("PRICE")]
[DataMemberAttribute]
public decimal BasePrice { get; internal set; }
```

``` c++
[ColumnAttribute(L"PRICE")]
[DataMemberAttribute]
public:
property Decimal BasePrice {
    Decimal get ();
    internal: void set (Decimal value);
}
```

#### Property Value

Type: [System.Decimal](https://technet.microsoft.com/library/1k2e8atx\(v=ax.60\))  
Returns [Decimal](https://technet.microsoft.com/library/1k2e8atx\(v=ax.60\)).  

## See Also

#### Reference

[Item Class](item-class-microsoft-dynamics-commerce-runtime-datamodel.md)

[Microsoft.Dynamics.Commerce.Runtime.DataModel Namespace](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)

