---
title: TaxableItem.ItemTaxGroupId Property  (Microsoft.Dynamics.Commerce.Runtime.DataModel)
TOCTitle: ItemTaxGroupId Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.DataModel.TaxableItem.ItemTaxGroupId
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.datamodel.taxableitem.itemtaxgroupid(v=AX.60)
ms:contentKeyID: 49847040
author: tonyafehr
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataModel.TaxableItem.ItemTaxGroupId
dev_langs:
- CSharp
- C++
- VB
---

# ItemTaxGroupId Property


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Gets or sets the tax group id for this sales line.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataModel](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Entities (in Microsoft.Dynamics.Commerce.Runtime.Entities.dll)

## Syntax

``` vb
'Declaration
<DataMemberAttribute> _
<ColumnAttribute("ITEMTAXGROUPID")> _
Public Property ItemTaxGroupId As String
    Get
    Set
'Usage
Dim instance As TaxableItem
Dim value As String

value = instance.ItemTaxGroupId

instance.ItemTaxGroupId = value
```

``` csharp
[DataMemberAttribute]
[ColumnAttribute("ITEMTAXGROUPID")]
public string ItemTaxGroupId { get; set; }
```

``` c++
[DataMemberAttribute]
[ColumnAttribute(L"ITEMTAXGROUPID")]
public:
property String^ ItemTaxGroupId {
    String^ get ();
    void set (String^ value);
}
```

#### Property Value

Type: [System.String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\))  
Returns [String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\)).  

## See Also

#### Reference

[TaxableItem Class](taxableitem-class-microsoft-dynamics-commerce-runtime-datamodel.md)

[Microsoft.Dynamics.Commerce.Runtime.DataModel Namespace](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)

