---
title: PickingListLine.ItemName Property  (Microsoft.Dynamics.Commerce.Runtime.DataModel)
TOCTitle: ItemName Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.DataModel.PickingListLine.ItemName
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.datamodel.pickinglistline.itemname(v=AX.60)
ms:contentKeyID: 62213637
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataModel.PickingListLine.ItemName
dev_langs:
- CSharp
- C++
- VB
---

# ItemName Property


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Gets or sets the item name.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataModel](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Entities (in Microsoft.Dynamics.Commerce.Runtime.Entities.dll)

## Syntax

``` vb
'Declaration
<DataMemberAttribute> _
<ColumnAttribute("ITEMNAME")> _
Public Property ItemName As String
    Get
    Set
'Usage
Dim instance As PickingListLine
Dim value As String

value = instance.ItemName

instance.ItemName = value
```

``` csharp
[DataMemberAttribute]
[ColumnAttribute("ITEMNAME")]
public string ItemName { get; set; }
```

``` c++
[DataMemberAttribute]
[ColumnAttribute(L"ITEMNAME")]
public:
property String^ ItemName {
    String^ get ();
    void set (String^ value);
}
```

#### Property Value

Type: [System.String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\))  
Returns [String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\)).  

## See Also

#### Reference

[PickingListLine Class](pickinglistline-class-microsoft-dynamics-commerce-runtime-datamodel.md)

[Microsoft.Dynamics.Commerce.Runtime.DataModel Namespace](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)

