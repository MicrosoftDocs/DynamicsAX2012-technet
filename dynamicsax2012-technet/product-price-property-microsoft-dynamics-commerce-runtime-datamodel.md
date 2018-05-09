---
title: Product.Price Property  (Microsoft.Dynamics.Commerce.Runtime.DataModel)
TOCTitle: Price Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.DataModel.Product.Price
ms:mtpsurl: https://technet.microsoft.com/en-us/library/microsoft.dynamics.commerce.runtime.datamodel.product.price(v=AX.60)
ms:contentKeyID: 62215238
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataModel.Product.Price
dev_langs:
- CSharp
- C++
- VB
---

# Price Property

Gets or sets the price after trade agreements have been applied.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataModel](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Entities (in Microsoft.Dynamics.Commerce.Runtime.Entities.dll)

## Syntax

``` vb
'Declaration
<DataMemberAttribute> _
<ColumnAttribute("PRICE")> _
Public Property Price As Decimal
    Get
    Set
'Usage
Dim instance As Product
Dim value As Decimal

value = instance.Price

instance.Price = value
```

``` csharp
[DataMemberAttribute]
[ColumnAttribute("PRICE")]
public decimal Price { get; set; }
```

``` c++
[DataMemberAttribute]
[ColumnAttribute(L"PRICE")]
public:
property Decimal Price {
    Decimal get ();
    void set (Decimal value);
}
```

#### Property Value

Type: [System.Decimal](https://technet.microsoft.com/en-us/library/1k2e8atx\(v=ax.60\))  
Returns [Decimal](https://technet.microsoft.com/en-us/library/1k2e8atx\(v=ax.60\)).  

## See Also

#### Reference

[Product Class](product-class-microsoft-dynamics-commerce-runtime-datamodel.md)

[Microsoft.Dynamics.Commerce.Runtime.DataModel Namespace](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)

