---
title: CartLineData.QuantityInvoiced Property  (Microsoft.Dynamics.Commerce.Runtime.DataModel)
TOCTitle: QuantityInvoiced Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.DataModel.CartLineData.QuantityInvoiced
ms:mtpsurl: https://technet.microsoft.com/en-us/library/microsoft.dynamics.commerce.runtime.datamodel.cartlinedata.quantityinvoiced(v=AX.60)
ms:contentKeyID: 62208671
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataModel.CartLineData.QuantityInvoiced
dev_langs:
- CSharp
- C++
- VB
---

# QuantityInvoiced Property

Gets or sets the quantity that was previously invoiced (pciked up or shipped) for the cartline (customer order).

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataModel](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Entities (in Microsoft.Dynamics.Commerce.Runtime.Entities.dll)

## Syntax

``` vb
'Declaration
<ColumnAttribute("QTYINVOICED")> _
<ReadOnlyAttribute("QTYINVOICED")> _
<DataMemberAttribute> _
Public Property QuantityInvoiced As Nullable(Of Decimal)
    Get
    Set
'Usage
Dim instance As CartLineData
Dim value As Nullable(Of Decimal)

value = instance.QuantityInvoiced

instance.QuantityInvoiced = value
```

``` csharp
[ColumnAttribute("QTYINVOICED")]
[ReadOnlyAttribute("QTYINVOICED")]
[DataMemberAttribute]
public Nullable<decimal> QuantityInvoiced { get; set; }
```

``` c++
[ColumnAttribute(L"QTYINVOICED")]
[ReadOnlyAttribute(L"QTYINVOICED")]
[DataMemberAttribute]
public:
property Nullable<Decimal> QuantityInvoiced {
    Nullable<Decimal> get ();
    void set (Nullable<Decimal> value);
}
```

#### Property Value

Type: [System.Nullable](https://technet.microsoft.com/en-us/library/b3h38hb0\(v=ax.60\))\<[Decimal](https://technet.microsoft.com/en-us/library/1k2e8atx\(v=ax.60\))\>  
Returns [Decimal](https://technet.microsoft.com/en-us/library/1k2e8atx\(v=ax.60\)).  

## See Also

#### Reference

[CartLineData Class](cartlinedata-class-microsoft-dynamics-commerce-runtime-datamodel.md)

[Microsoft.Dynamics.Commerce.Runtime.DataModel Namespace](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)

