---
title: PickingList.TotalItems Property  (Microsoft.Dynamics.Commerce.Runtime.DataModel)
TOCTitle: TotalItems Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.DataModel.PickingList.TotalItems
ms:mtpsurl: https://technet.microsoft.com/en-us/library/microsoft.dynamics.commerce.runtime.datamodel.pickinglist.totalitems(v=AX.60)
ms:contentKeyID: 62201842
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataModel.PickingList.TotalItems
dev_langs:
- CSharp
- C++
- VB
---

# TotalItems Property

Gets or sets the total number of items that must be counted.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataModel](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Entities (in Microsoft.Dynamics.Commerce.Runtime.Entities.dll)

## Syntax

``` vb
'Declaration
<DataMemberAttribute> _
Public Property TotalItems As Decimal
    Get
    Set
'Usage
Dim instance As PickingList
Dim value As Decimal

value = instance.TotalItems

instance.TotalItems = value
```

``` csharp
[DataMemberAttribute]
public decimal TotalItems { get; set; }
```

``` c++
[DataMemberAttribute]
public:
property Decimal TotalItems {
    Decimal get ();
    void set (Decimal value);
}
```

#### Property Value

Type: [System.Decimal](https://technet.microsoft.com/en-us/library/1k2e8atx\(v=ax.60\))  
Returns [Decimal](https://technet.microsoft.com/en-us/library/1k2e8atx\(v=ax.60\)).  

## See Also

#### Reference

[PickingList Class](pickinglist-class-microsoft-dynamics-commerce-runtime-datamodel.md)

[Microsoft.Dynamics.Commerce.Runtime.DataModel Namespace](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)

