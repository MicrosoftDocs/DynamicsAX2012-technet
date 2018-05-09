---
title: Item.InventoryUnitOfMeasure Property  (Microsoft.Dynamics.Commerce.Runtime.DataModel)
TOCTitle: InventoryUnitOfMeasure Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.DataModel.Item.InventoryUnitOfMeasure
ms:mtpsurl: https://technet.microsoft.com/en-us/library/microsoft.dynamics.commerce.runtime.datamodel.item.inventoryunitofmeasure(v=AX.60)
ms:contentKeyID: 49846377
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataModel.Item.InventoryUnitOfMeasure
dev_langs:
- CSharp
- C++
- VB
---

# InventoryUnitOfMeasure Property

Gets the inventory unit of measure.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataModel](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Entities (in Microsoft.Dynamics.Commerce.Runtime.Entities.dll)

## Syntax

``` vb
'Declaration
<DataMemberAttribute> _
<ColumnAttribute("INVENTUNITID")> _
Public Property InventoryUnitOfMeasure As String
    Get
    Friend Set
'Usage
Dim instance As Item
Dim value As String

value = instance.InventoryUnitOfMeasure
```

``` csharp
[DataMemberAttribute]
[ColumnAttribute("INVENTUNITID")]
public string InventoryUnitOfMeasure { get; internal set; }
```

``` c++
[DataMemberAttribute]
[ColumnAttribute(L"INVENTUNITID")]
public:
property String^ InventoryUnitOfMeasure {
    String^ get ();
    internal: void set (String^ value);
}
```

#### Property Value

Type: [System.String](https://technet.microsoft.com/en-us/library/s1wwdcbf\(v=ax.60\))  
Returns [String](https://technet.microsoft.com/en-us/library/s1wwdcbf\(v=ax.60\)).  

## See Also

#### Reference

[Item Class](item-class-microsoft-dynamics-commerce-runtime-datamodel.md)

[Microsoft.Dynamics.Commerce.Runtime.DataModel Namespace](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)

