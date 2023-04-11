---
title: ProductPrice.InventoryDimensionId Property  (Microsoft.Dynamics.Commerce.Runtime.DataModel)
TOCTitle: InventoryDimensionId Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.DataModel.ProductPrice.InventoryDimensionId
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.datamodel.productprice.inventorydimensionid(v=AX.60)
ms:contentKeyID: 62208141
author: tonyafehr
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataModel.ProductPrice.InventoryDimensionId
dev_langs:
- CSharp
- C++
- VB
---

# InventoryDimensionId Property


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Gets or sets the optional dimension identifier (for variant) that this product price applies to.

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
Dim instance As ProductPrice
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

[ProductPrice Class](productprice-class-microsoft-dynamics-commerce-runtime-datamodel.md)

[Microsoft.Dynamics.Commerce.Runtime.DataModel Namespace](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)

