---
title: ItemBarcode.InventoryColorId Property  (Microsoft.Dynamics.Commerce.Runtime.DataModel)
TOCTitle: InventoryColorId Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.DataModel.ItemBarcode.InventoryColorId
ms:mtpsurl: https://technet.microsoft.com/en-us/library/microsoft.dynamics.commerce.runtime.datamodel.itembarcode.inventorycolorid(v=AX.60)
ms:contentKeyID: 62215220
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataModel.ItemBarcode.InventoryColorId
dev_langs:
- CSharp
- C++
- VB
---

# InventoryColorId Property

Gets the Invent Color identifier.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataModel](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Entities (in Microsoft.Dynamics.Commerce.Runtime.Entities.dll)

## Syntax

``` vb
'Declaration
<ColumnAttribute("INVENTCOLORID")> _
<DataMemberAttribute> _
Public Property InventoryColorId As String
    Get
    Friend Set
'Usage
Dim instance As ItemBarcode
Dim value As String

value = instance.InventoryColorId
```

``` csharp
[ColumnAttribute("INVENTCOLORID")]
[DataMemberAttribute]
public string InventoryColorId { get; internal set; }
```

``` c++
[ColumnAttribute(L"INVENTCOLORID")]
[DataMemberAttribute]
public:
property String^ InventoryColorId {
    String^ get ();
    internal: void set (String^ value);
}
```

#### Property Value

Type: [System.String](https://technet.microsoft.com/en-us/library/s1wwdcbf\(v=ax.60\))  
Returns [String](https://technet.microsoft.com/en-us/library/s1wwdcbf\(v=ax.60\)).  

## See Also

#### Reference

[ItemBarcode Class](itembarcode-class-microsoft-dynamics-commerce-runtime-datamodel.md)

[Microsoft.Dynamics.Commerce.Runtime.DataModel Namespace](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)

