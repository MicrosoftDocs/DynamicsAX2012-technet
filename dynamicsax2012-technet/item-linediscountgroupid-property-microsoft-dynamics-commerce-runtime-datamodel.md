---
title: Item.LineDiscountGroupId Property  (Microsoft.Dynamics.Commerce.Runtime.DataModel)
TOCTitle: LineDiscountGroupId Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.DataModel.Item.LineDiscountGroupId
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.datamodel.item.linediscountgroupid(v=AX.60)
ms:contentKeyID: 49846084
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataModel.Item.LineDiscountGroupId
dev_langs:
- CSharp
- C++
- VB
---

# LineDiscountGroupId Property

Gets the optional line discount group assigned to this item.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataModel](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Entities (in Microsoft.Dynamics.Commerce.Runtime.Entities.dll)

## Syntax

``` vb
'Declaration
<DataMemberAttribute> _
<ColumnAttribute("LINEDISC")> _
Public Property LineDiscountGroupId As String
    Get
    Friend Set
'Usage
Dim instance As Item
Dim value As String

value = instance.LineDiscountGroupId
```

``` csharp
[DataMemberAttribute]
[ColumnAttribute("LINEDISC")]
public string LineDiscountGroupId { get; internal set; }
```

``` c++
[DataMemberAttribute]
[ColumnAttribute(L"LINEDISC")]
public:
property String^ LineDiscountGroupId {
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

