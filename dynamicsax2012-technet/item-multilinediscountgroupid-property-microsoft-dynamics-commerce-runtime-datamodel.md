---
title: Item.MultilineDiscountGroupId Property  (Microsoft.Dynamics.Commerce.Runtime.DataModel)
TOCTitle: MultilineDiscountGroupId Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.DataModel.Item.MultilineDiscountGroupId
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.datamodel.item.multilinediscountgroupid(v=AX.60)
ms:contentKeyID: 49851944
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataModel.Item.MultilineDiscountGroupId
dev_langs:
- CSharp
- C++
- VB
---

# MultilineDiscountGroupId Property

Gets the optional multiline disount group assigned to this item.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataModel](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Entities (in Microsoft.Dynamics.Commerce.Runtime.Entities.dll)

## Syntax

``` vb
'Declaration
<ColumnAttribute("MULTILINEDISC")> _
<DataMemberAttribute> _
Public Property MultilineDiscountGroupId As String
    Get
    Friend Set
'Usage
Dim instance As Item
Dim value As String

value = instance.MultilineDiscountGroupId
```

``` csharp
[ColumnAttribute("MULTILINEDISC")]
[DataMemberAttribute]
public string MultilineDiscountGroupId { get; internal set; }
```

``` c++
[ColumnAttribute(L"MULTILINEDISC")]
[DataMemberAttribute]
public:
property String^ MultilineDiscountGroupId {
    String^ get ();
    internal: void set (String^ value);
}
```

#### Property Value

Type: [System.String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\))  
Returns [String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\)).  

## See Also

#### Reference

[Item Class](item-class-microsoft-dynamics-commerce-runtime-datamodel.md)

[Microsoft.Dynamics.Commerce.Runtime.DataModel Namespace](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)

