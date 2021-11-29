---
title: PickingList.OrderLines Property  (Microsoft.Dynamics.Commerce.Runtime.DataModel)
TOCTitle: OrderLines Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.DataModel.PickingList.OrderLines
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.datamodel.pickinglist.orderlines(v=AX.60)
ms:contentKeyID: 62204243
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataModel.PickingList.OrderLines
dev_langs:
- CSharp
- C++
- VB
---

# OrderLines Property


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Gets or sets the picking list lines.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataModel](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Entities (in Microsoft.Dynamics.Commerce.Runtime.Entities.dll)

## Syntax

``` vb
'Declaration
<DataMemberAttribute> _
Public Property OrderLines As ICollection(Of PickingListLine)
    Get
    Set
'Usage
Dim instance As PickingList
Dim value As ICollection(Of PickingListLine)

value = instance.OrderLines

instance.OrderLines = value
```

``` csharp
[DataMemberAttribute]
public ICollection<PickingListLine> OrderLines { get; set; }
```

``` c++
[DataMemberAttribute]
public:
property ICollection<PickingListLine^>^ OrderLines {
    ICollection<PickingListLine^>^ get ();
    void set (ICollection<PickingListLine^>^ value);
}
```

#### Property Value

Type: [System.Collections.Generic.ICollection](https://technet.microsoft.com/library/92t2ye13\(v=ax.60\))\<[PickingListLine](pickinglistline-class-microsoft-dynamics-commerce-runtime-datamodel.md)\>  
Returns [ICollection\<T\>](https://technet.microsoft.com/library/92t2ye13\(v=ax.60\)).  

## See Also

#### Reference

[PickingList Class](pickinglist-class-microsoft-dynamics-commerce-runtime-datamodel.md)

[Microsoft.Dynamics.Commerce.Runtime.DataModel Namespace](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)

