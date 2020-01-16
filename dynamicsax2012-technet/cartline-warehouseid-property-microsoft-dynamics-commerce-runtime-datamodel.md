---
title: CartLine.WarehouseId Property  (Microsoft.Dynamics.Commerce.Runtime.DataModel)
TOCTitle: WarehouseId Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.DataModel.CartLine.WarehouseId
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.datamodel.cartline.warehouseid(v=AX.60)
ms:contentKeyID: 62214325
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataModel.CartLine.WarehouseId
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
<DataMemberAttribute> _
Public Property WarehouseId As String
    Get
    Set
'Usage
Dim instance As CartLine
Dim value As String

value = instance.WarehouseId

instance.WarehouseId = value
```

``` csharp
[DataMemberAttribute]
public string WarehouseId { get; set; }
```

``` c++
[DataMemberAttribute]
public:
property String^ WarehouseId {
    String^ get ();
    void set (String^ value);
}
```

#### Property Value

Type: [System.String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\))  
Returns [String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\)).  

## See Also

#### Reference

[CartLine Class](cartline-class-microsoft-dynamics-commerce-runtime-datamodel.md)

[Microsoft.Dynamics.Commerce.Runtime.DataModel Namespace](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)

