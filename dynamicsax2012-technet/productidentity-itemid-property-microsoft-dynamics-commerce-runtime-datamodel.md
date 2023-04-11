---
title: ProductIdentity.ItemId Property  (Microsoft.Dynamics.Commerce.Runtime.DataModel)
TOCTitle: ItemId Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.DataModel.ProductIdentity.ItemId
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.datamodel.productidentity.itemid(v=AX.60)
ms:contentKeyID: 62210465
author: tonyafehr
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataModel.ProductIdentity.ItemId
dev_langs:
- CSharp
- C++
- VB
---

# ItemId Property


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Gets the item id of the product.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataModel](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Entities (in Microsoft.Dynamics.Commerce.Runtime.Entities.dll)

## Syntax

``` vb
'Declaration
<ColumnAttribute("ITEMID")> _
<DataMemberAttribute> _
Public Property ItemId As String
    Get
    Friend Set
'Usage
Dim instance As ProductIdentity
Dim value As String

value = instance.ItemId
```

``` csharp
[ColumnAttribute("ITEMID")]
[DataMemberAttribute]
public string ItemId { get; internal set; }
```

``` c++
[ColumnAttribute(L"ITEMID")]
[DataMemberAttribute]
public:
property String^ ItemId {
    String^ get ();
    internal: void set (String^ value);
}
```

#### Property Value

Type: [System.String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\))  
Returns [String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\)).  

## See Also

#### Reference

[ProductIdentity Class](productidentity-class-microsoft-dynamics-commerce-runtime-datamodel.md)

[Microsoft.Dynamics.Commerce.Runtime.DataModel Namespace](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)

