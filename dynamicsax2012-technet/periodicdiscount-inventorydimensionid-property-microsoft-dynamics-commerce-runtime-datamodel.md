---
title: PeriodicDiscount.InventoryDimensionId Property  (Microsoft.Dynamics.Commerce.Runtime.DataModel)
TOCTitle: InventoryDimensionId Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.DataModel.PeriodicDiscount.InventoryDimensionId
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.datamodel.periodicdiscount.inventorydimensionid(v=AX.60)
ms:contentKeyID: 62210711
author: tonyafehr
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataModel.PeriodicDiscount.InventoryDimensionId
dev_langs:
- CSharp
- C++
- VB
---

# InventoryDimensionId Property


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Gets the identifier of the variant dimensions of the item with which this price adjustment is associated.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataModel](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Entities (in Microsoft.Dynamics.Commerce.Runtime.Entities.dll)

## Syntax

``` vb
'Declaration
<ColumnAttribute("INVENTDIMID")> _
<DataMemberAttribute> _
Public Property InventoryDimensionId As String
    Get
    Friend Set
'Usage
Dim instance As PeriodicDiscount
Dim value As String

value = instance.InventoryDimensionId
```

``` csharp
[ColumnAttribute("INVENTDIMID")]
[DataMemberAttribute]
public string InventoryDimensionId { get; internal set; }
```

``` c++
[ColumnAttribute(L"INVENTDIMID")]
[DataMemberAttribute]
public:
property String^ InventoryDimensionId {
    String^ get ();
    internal: void set (String^ value);
}
```

#### Property Value

Type: [System.String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\))  
Returns [String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\)).  

## See Also

#### Reference

[PeriodicDiscount Class](periodicdiscount-class-microsoft-dynamics-commerce-runtime-datamodel.md)

[Microsoft.Dynamics.Commerce.Runtime.DataModel Namespace](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)

