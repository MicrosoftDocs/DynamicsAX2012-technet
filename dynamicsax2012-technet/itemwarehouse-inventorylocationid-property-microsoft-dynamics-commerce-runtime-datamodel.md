---
title: ItemWarehouse.InventoryLocationId Property  (Microsoft.Dynamics.Commerce.Runtime.DataModel)
TOCTitle: InventoryLocationId Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.DataModel.ItemWarehouse.InventoryLocationId
ms:mtpsurl: https://technet.microsoft.com/en-us/library/microsoft.dynamics.commerce.runtime.datamodel.itemwarehouse.inventorylocationid(v=AX.60)
ms:contentKeyID: 49837456
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataModel.ItemWarehouse.InventoryLocationId
dev_langs:
- CSharp
- C++
- VB
---

# InventoryLocationId Property

Gets or sets the inventory location identifier.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataModel](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Entities (in Microsoft.Dynamics.Commerce.Runtime.Entities.dll)

## Syntax

``` vb
'Declaration
<DataMemberAttribute> _
Public Property InventoryLocationId As String
    Get
    Set
'Usage
Dim instance As ItemWarehouse
Dim value As String

value = instance.InventoryLocationId

instance.InventoryLocationId = value
```

``` csharp
[DataMemberAttribute]
public string InventoryLocationId { get; set; }
```

``` c++
[DataMemberAttribute]
public:
property String^ InventoryLocationId {
    String^ get ();
    void set (String^ value);
}
```

#### Property Value

Type: [System.String](https://technet.microsoft.com/en-us/library/s1wwdcbf\(v=ax.60\))  
The inventory location identifier.  

## See Also

#### Reference

[ItemWarehouse Class](itemwarehouse-class-microsoft-dynamics-commerce-runtime-datamodel.md)

[Microsoft.Dynamics.Commerce.Runtime.DataModel Namespace](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)

