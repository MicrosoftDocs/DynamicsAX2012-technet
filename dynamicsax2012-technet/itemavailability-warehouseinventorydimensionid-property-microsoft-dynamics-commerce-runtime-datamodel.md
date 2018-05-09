---
title: ItemAvailability.WarehouseInventoryDimensionId Property  (Microsoft.Dynamics.Commerce.Runtime.DataModel)
TOCTitle: WarehouseInventoryDimensionId Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.DataModel.ItemAvailability.WarehouseInventoryDimensionId
ms:mtpsurl: https://technet.microsoft.com/en-us/library/microsoft.dynamics.commerce.runtime.datamodel.itemavailability.warehouseinventorydimensionid(v=AX.60)
ms:contentKeyID: 49856255
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataModel.ItemAvailability.WarehouseInventoryDimensionId
dev_langs:
- CSharp
- C++
- VB
---

# WarehouseInventoryDimensionId Property

Gets the warehouse inventory dimension identifier.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataModel](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Entities (in Microsoft.Dynamics.Commerce.Runtime.Entities.dll)

## Syntax

``` vb
'Declaration
<DataMemberAttribute> _
<ColumnAttribute("WAREHOUSEINVENTDIMID")> _
Public Property WarehouseInventoryDimensionId As String
    Get
    Friend Set
'Usage
Dim instance As ItemAvailability
Dim value As String

value = instance.WarehouseInventoryDimensionId
```

``` csharp
[DataMemberAttribute]
[ColumnAttribute("WAREHOUSEINVENTDIMID")]
public string WarehouseInventoryDimensionId { get; internal set; }
```

``` c++
[DataMemberAttribute]
[ColumnAttribute(L"WAREHOUSEINVENTDIMID")]
public:
property String^ WarehouseInventoryDimensionId {
    String^ get ();
    internal: void set (String^ value);
}
```

#### Property Value

Type: [System.String](https://technet.microsoft.com/en-us/library/s1wwdcbf\(v=ax.60\))  
Returns [String](https://technet.microsoft.com/en-us/library/s1wwdcbf\(v=ax.60\)).  

## See Also

#### Reference

[ItemAvailability Class](itemavailability-class-microsoft-dynamics-commerce-runtime-datamodel.md)

[Microsoft.Dynamics.Commerce.Runtime.DataModel Namespace](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)

