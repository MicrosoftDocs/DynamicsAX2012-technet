---
title: Item.PriceQuantity Property  (Microsoft.Dynamics.Commerce.Runtime.DataModel)
TOCTitle: PriceQuantity Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.DataModel.Item.PriceQuantity
ms:mtpsurl: https://technet.microsoft.com/en-us/library/microsoft.dynamics.commerce.runtime.datamodel.item.pricequantity(v=AX.60)
ms:contentKeyID: 49820757
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataModel.Item.PriceQuantity
dev_langs:
- CSharp
- C++
- VB
---

# PriceQuantity Property

Gets the item price quantity.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataModel](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Entities (in Microsoft.Dynamics.Commerce.Runtime.Entities.dll)

## Syntax

``` vb
'Declaration
<ColumnAttribute("PRICEQTY")> _
<DataMemberAttribute> _
Public Property PriceQuantity As Nullable(Of Decimal)
    Get
    Friend Set
'Usage
Dim instance As Item
Dim value As Nullable(Of Decimal)

value = instance.PriceQuantity
```

``` csharp
[ColumnAttribute("PRICEQTY")]
[DataMemberAttribute]
public Nullable<decimal> PriceQuantity { get; internal set; }
```

``` c++
[ColumnAttribute(L"PRICEQTY")]
[DataMemberAttribute]
public:
property Nullable<Decimal> PriceQuantity {
    Nullable<Decimal> get ();
    internal: void set (Nullable<Decimal> value);
}
```

#### Property Value

Type: [System.Nullable](https://technet.microsoft.com/en-us/library/b3h38hb0\(v=ax.60\))\<[Decimal](https://technet.microsoft.com/en-us/library/1k2e8atx\(v=ax.60\))\>  
Returns [Nullable\<T\>](https://technet.microsoft.com/en-us/library/b3h38hb0\(v=ax.60\)).  

## See Also

#### Reference

[Item Class](item-class-microsoft-dynamics-commerce-runtime-datamodel.md)

[Microsoft.Dynamics.Commerce.Runtime.DataModel Namespace](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)

