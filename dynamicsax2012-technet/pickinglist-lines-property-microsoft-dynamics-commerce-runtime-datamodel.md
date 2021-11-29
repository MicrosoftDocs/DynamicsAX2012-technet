---
title: PickingList.Lines Property  (Microsoft.Dynamics.Commerce.Runtime.DataModel)
TOCTitle: Lines Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.DataModel.PickingList.Lines
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.datamodel.pickinglist.lines(v=AX.60)
ms:contentKeyID: 62205736
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataModel.PickingList.Lines
dev_langs:
- CSharp
- C++
- VB
---

# Lines Property


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Gets or sets the number of items in the order.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataModel](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Entities (in Microsoft.Dynamics.Commerce.Runtime.Entities.dll)

## Syntax

``` vb
'Declaration
<DataMemberAttribute> _
Public Property Lines As Decimal
    Get
    Set
'Usage
Dim instance As PickingList
Dim value As Decimal

value = instance.Lines

instance.Lines = value
```

``` csharp
[DataMemberAttribute]
public decimal Lines { get; set; }
```

``` c++
[DataMemberAttribute]
public:
property Decimal Lines {
    Decimal get ();
    void set (Decimal value);
}
```

#### Property Value

Type: [System.Decimal](https://technet.microsoft.com/library/1k2e8atx\(v=ax.60\))  
Returns [Decimal](https://technet.microsoft.com/library/1k2e8atx\(v=ax.60\)).  

## See Also

#### Reference

[PickingList Class](pickinglist-class-microsoft-dynamics-commerce-runtime-datamodel.md)

[Microsoft.Dynamics.Commerce.Runtime.DataModel Namespace](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)

