---
title: ProductVariant.InventoryDimensionId Property  (Microsoft.Dynamics.Commerce.Runtime.DataModel)
TOCTitle: InventoryDimensionId Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.DataModel.ProductVariant.InventoryDimensionId
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.datamodel.productvariant.inventorydimensionid(v=AX.60)
ms:contentKeyID: 62214645
author: tonyafehr
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataModel.ProductVariant.InventoryDimensionId
dev_langs:
- CSharp
- C++
- VB
---

# InventoryDimensionId Property


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Gets or sets the inventory dimenion identifier for this variant.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataModel](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Entities (in Microsoft.Dynamics.Commerce.Runtime.Entities.dll)

## Syntax

``` vb
'Declaration
<DataMemberAttribute> _
<ColumnAttribute("INVENTDIMID")> _
Public Property InventoryDimensionId As String
    Get
    Set
'Usage
Dim instance As ProductVariant
Dim value As String

value = instance.InventoryDimensionId

instance.InventoryDimensionId = value
```

``` csharp
[DataMemberAttribute]
[ColumnAttribute("INVENTDIMID")]
public string InventoryDimensionId { get; set; }
```

``` c++
[DataMemberAttribute]
[ColumnAttribute(L"INVENTDIMID")]
public:
property String^ InventoryDimensionId {
    String^ get ();
    void set (String^ value);
}
```

#### Property Value

Type: [System.String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\))  
Returns [String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\)).  

## See Also

#### Reference

[ProductVariant Class](productvariant-class-microsoft-dynamics-commerce-runtime-datamodel.md)

[Microsoft.Dynamics.Commerce.Runtime.DataModel Namespace](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)

