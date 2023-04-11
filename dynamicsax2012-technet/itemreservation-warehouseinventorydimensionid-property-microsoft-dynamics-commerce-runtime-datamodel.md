---
title: ItemReservation.WarehouseInventoryDimensionId Property  (Microsoft.Dynamics.Commerce.Runtime.DataModel)
TOCTitle: WarehouseInventoryDimensionId Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.DataModel.ItemReservation.WarehouseInventoryDimensionId
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.datamodel.itemreservation.warehouseinventorydimensionid(v=AX.60)
ms:contentKeyID: 49840433
author: tonyafehr
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataModel.ItemReservation.WarehouseInventoryDimensionId
dev_langs:
- CSharp
- C++
- VB
---

# WarehouseInventoryDimensionId Property


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Gets or sets the warehouse inventory dimension identifier.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataModel](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Entities (in Microsoft.Dynamics.Commerce.Runtime.Entities.dll)

## Syntax

``` vb
'Declaration
<DataMemberAttribute> _
<ColumnAttribute("INVENTDIMID")> _
Public Property WarehouseInventoryDimensionId As String
    Get
    Set
'Usage
Dim instance As ItemReservation
Dim value As String

value = instance.WarehouseInventoryDimensionId

instance.WarehouseInventoryDimensionId = value
```

``` csharp
[DataMemberAttribute]
[ColumnAttribute("INVENTDIMID")]
public string WarehouseInventoryDimensionId { get; set; }
```

``` c++
[DataMemberAttribute]
[ColumnAttribute(L"INVENTDIMID")]
public:
property String^ WarehouseInventoryDimensionId {
    String^ get ();
    void set (String^ value);
}
```

#### Property Value

Type: [System.String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\))  
The warehouse inventory dimension identifier.  

## See Also

#### Reference

[ItemReservation Class](itemreservation-class-microsoft-dynamics-commerce-runtime-datamodel.md)

[Microsoft.Dynamics.Commerce.Runtime.DataModel Namespace](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)

