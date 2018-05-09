---
title: Item.ItemTaxGroupId Property  (Microsoft.Dynamics.Commerce.Runtime.DataModel)
TOCTitle: ItemTaxGroupId Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.DataModel.Item.ItemTaxGroupId
ms:mtpsurl: https://technet.microsoft.com/en-us/library/microsoft.dynamics.commerce.runtime.datamodel.item.itemtaxgroupid(v=AX.60)
ms:contentKeyID: 49830226
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataModel.Item.ItemTaxGroupId
dev_langs:
- CSharp
- C++
- VB
---

# ItemTaxGroupId Property

Gets the item tax group identifier.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataModel](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Entities (in Microsoft.Dynamics.Commerce.Runtime.Entities.dll)

## Syntax

``` vb
'Declaration
<ColumnAttribute("ITEMTAXGROUPID")> _
<DataMemberAttribute> _
Public Property ItemTaxGroupId As String
    Get
    Friend Set
'Usage
Dim instance As Item
Dim value As String

value = instance.ItemTaxGroupId
```

``` csharp
[ColumnAttribute("ITEMTAXGROUPID")]
[DataMemberAttribute]
public string ItemTaxGroupId { get; internal set; }
```

``` c++
[ColumnAttribute(L"ITEMTAXGROUPID")]
[DataMemberAttribute]
public:
property String^ ItemTaxGroupId {
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

