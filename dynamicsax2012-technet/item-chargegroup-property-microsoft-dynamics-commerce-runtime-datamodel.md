---
title: Item.ChargeGroup Property  (Microsoft.Dynamics.Commerce.Runtime.DataModel)
TOCTitle: ChargeGroup Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.DataModel.Item.ChargeGroup
ms:mtpsurl: https://technet.microsoft.com/en-us/library/microsoft.dynamics.commerce.runtime.datamodel.item.chargegroup(v=AX.60)
ms:contentKeyID: 49825277
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataModel.Item.ChargeGroup
dev_langs:
- CSharp
- C++
- VB
---

# ChargeGroup Property

Gets the item's charge (markup) group identifier.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataModel](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Entities (in Microsoft.Dynamics.Commerce.Runtime.Entities.dll)

## Syntax

``` vb
'Declaration
<DataMemberAttribute> _
<ColumnAttribute("MARKUPGROUPID")> _
Public Property ChargeGroup As String
    Get
    Friend Set
'Usage
Dim instance As Item
Dim value As String

value = instance.ChargeGroup
```

``` csharp
[DataMemberAttribute]
[ColumnAttribute("MARKUPGROUPID")]
public string ChargeGroup { get; internal set; }
```

``` c++
[DataMemberAttribute]
[ColumnAttribute(L"MARKUPGROUPID")]
public:
property String^ ChargeGroup {
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

