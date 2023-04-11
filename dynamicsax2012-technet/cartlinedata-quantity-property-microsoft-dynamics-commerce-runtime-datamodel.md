---
title: CartLineData.Quantity Property  (Microsoft.Dynamics.Commerce.Runtime.DataModel)
TOCTitle: Quantity Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.DataModel.CartLineData.Quantity
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.datamodel.cartlinedata.quantity(v=AX.60)
ms:contentKeyID: 49832726
author: tonyafehr
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataModel.CartLineData.Quantity
dev_langs:
- CSharp
- C++
- VB
---

# Quantity Property


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Gets or sets the item quantity on the sales line.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataModel](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Entities (in Microsoft.Dynamics.Commerce.Runtime.Entities.dll)

## Syntax

``` vb
'Declaration
<DataMemberAttribute> _
<ColumnAttribute("QUANTITY")> _
Public Property Quantity As Decimal
    Get
    Set
'Usage
Dim instance As CartLineData
Dim value As Decimal

value = instance.Quantity

instance.Quantity = value
```

``` csharp
[DataMemberAttribute]
[ColumnAttribute("QUANTITY")]
public decimal Quantity { get; set; }
```

``` c++
[DataMemberAttribute]
[ColumnAttribute(L"QUANTITY")]
public:
property Decimal Quantity {
    Decimal get ();
    void set (Decimal value);
}
```

#### Property Value

Type: [System.Decimal](https://technet.microsoft.com/library/1k2e8atx\(v=ax.60\))  
The quantity.  

## See Also

#### Reference

[CartLineData Class](cartlinedata-class-microsoft-dynamics-commerce-runtime-datamodel.md)

[Microsoft.Dynamics.Commerce.Runtime.DataModel Namespace](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)

