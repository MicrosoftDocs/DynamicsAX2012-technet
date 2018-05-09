---
title: Cart.WarehouseId Property  (Microsoft.Dynamics.Commerce.Runtime.DataModel)
TOCTitle: WarehouseId Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.DataModel.Cart.WarehouseId
ms:mtpsurl: https://technet.microsoft.com/en-us/library/microsoft.dynamics.commerce.runtime.datamodel.cart.warehouseid(v=AX.60)
ms:contentKeyID: 49831440
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataModel.Cart.WarehouseId
dev_langs:
- CSharp
- C++
- VB
---

# WarehouseId Property

Gets or sets the warehouse identifier.This is the same as inventory location identifier.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataModel](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Entities (in Microsoft.Dynamics.Commerce.Runtime.Entities.dll)

## Syntax

``` vb
'Declaration
<ColumnAttribute("INVENTLOCATIONID")> _
<DataMemberAttribute> _
Public Property WarehouseId As String
    Get
    Set
'Usage
Dim instance As Cart
Dim value As String

value = instance.WarehouseId

instance.WarehouseId = value
```

``` csharp
[ColumnAttribute("INVENTLOCATIONID")]
[DataMemberAttribute]
public string WarehouseId { get; set; }
```

``` c++
[ColumnAttribute(L"INVENTLOCATIONID")]
[DataMemberAttribute]
public:
property String^ WarehouseId {
    String^ get ();
    void set (String^ value);
}
```

#### Property Value

Type: [System.String](https://technet.microsoft.com/en-us/library/s1wwdcbf\(v=ax.60\))  
Returns [String](https://technet.microsoft.com/en-us/library/s1wwdcbf\(v=ax.60\)).  

## See Also

#### Reference

[Cart Class](cart-class-microsoft-dynamics-commerce-runtime-datamodel.md)

[Microsoft.Dynamics.Commerce.Runtime.DataModel Namespace](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)

