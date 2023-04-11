---
title: PickingListLine.OrderId Property  (Microsoft.Dynamics.Commerce.Runtime.DataModel)
TOCTitle: OrderId Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.DataModel.PickingListLine.OrderId
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.datamodel.pickinglistline.orderid(v=AX.60)
ms:contentKeyID: 62213378
author: tonyafehr
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataModel.PickingListLine.OrderId
dev_langs:
- CSharp
- C++
- VB
---

# OrderId Property


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Gets or sets the order identifier.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataModel](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Entities (in Microsoft.Dynamics.Commerce.Runtime.Entities.dll)

## Syntax

``` vb
'Declaration
<ColumnAttribute("ORDERID")> _
<DataMemberAttribute> _
Public Property OrderId As String
    Get
    Set
'Usage
Dim instance As PickingListLine
Dim value As String

value = instance.OrderId

instance.OrderId = value
```

``` csharp
[ColumnAttribute("ORDERID")]
[DataMemberAttribute]
public string OrderId { get; set; }
```

``` c++
[ColumnAttribute(L"ORDERID")]
[DataMemberAttribute]
public:
property String^ OrderId {
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

