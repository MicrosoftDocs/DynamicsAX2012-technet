---
title: SalesLine.LineMultilineDiscOnItem Property  (Microsoft.Dynamics.Commerce.Runtime.DataModel)
TOCTitle: LineMultilineDiscOnItem Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.DataModel.SalesLine.LineMultilineDiscOnItem
ms:mtpsurl: https://technet.microsoft.com/en-us/library/microsoft.dynamics.commerce.runtime.datamodel.salesline.linemultilinedisconitem(v=AX.60)
ms:contentKeyID: 49851432
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataModel.SalesLine.LineMultilineDiscOnItem
dev_langs:
- CSharp
- C++
- VB
---

# LineMultilineDiscOnItem Property

Gets or sets whether the item has customer line and/or multiline discount item on it.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataModel](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Entities (in Microsoft.Dynamics.Commerce.Runtime.Entities.dll)

## Syntax

``` vb
'Declaration
<DataMemberAttribute> _
Public Property LineMultilineDiscOnItem As LineMultilineDiscountOnItem
    Get
    Set
'Usage
Dim instance As SalesLine
Dim value As LineMultilineDiscountOnItem

value = instance.LineMultilineDiscOnItem

instance.LineMultilineDiscOnItem = value
```

``` csharp
[DataMemberAttribute]
public LineMultilineDiscountOnItem LineMultilineDiscOnItem { get; set; }
```

``` c++
[DataMemberAttribute]
public:
property LineMultilineDiscountOnItem LineMultilineDiscOnItem {
    LineMultilineDiscountOnItem get ();
    void set (LineMultilineDiscountOnItem value);
}
```

#### Property Value

Type: [Microsoft.Dynamics.Commerce.Runtime.DataModel.LineMultilineDiscountOnItem](linemultilinediscountonitem-enumeration-microsoft-dynamics-commerce-runtime-datamodel.md)  
Returns [LineMultilineDiscountOnItem](linemultilinediscountonitem-enumeration-microsoft-dynamics-commerce-runtime-datamodel.md).  

## See Also

#### Reference

[SalesLine Class](salesline-class-microsoft-dynamics-commerce-runtime-datamodel.md)

[Microsoft.Dynamics.Commerce.Runtime.DataModel Namespace](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)

