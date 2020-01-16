---
title: KitTransactionLine.InventoryDimensionId Property  (Microsoft.Dynamics.Commerce.Runtime.DataModel)
TOCTitle: InventoryDimensionId Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.DataModel.KitTransactionLine.InventoryDimensionId
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.datamodel.kittransactionline.inventorydimensionid(v=AX.60)
ms:contentKeyID: 62205762
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataModel.KitTransactionLine.InventoryDimensionId
dev_langs:
- CSharp
- C++
- VB
---

# InventoryDimensionId Property

Gets or sets the retail variant Id of the kit variant.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataModel](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Entities (in Microsoft.Dynamics.Commerce.Runtime.Entities.dll)

## Syntax

``` vb
'Declaration
<ColumnAttribute("INVENTDIMID")> _
<DataMemberAttribute> _
Public Property InventoryDimensionId As String
    Get
    Set
'Usage
Dim instance As KitTransactionLine
Dim value As String

value = instance.InventoryDimensionId

instance.InventoryDimensionId = value
```

``` csharp
[ColumnAttribute("INVENTDIMID")]
[DataMemberAttribute]
public string InventoryDimensionId { get; set; }
```

``` c++
[ColumnAttribute(L"INVENTDIMID")]
[DataMemberAttribute]
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

[KitTransactionLine Class](kittransactionline-class-microsoft-dynamics-commerce-runtime-datamodel.md)

[Microsoft.Dynamics.Commerce.Runtime.DataModel Namespace](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)

