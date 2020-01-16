---
title: SalesOrder.OrderPlacedDate Property  (Microsoft.Dynamics.Commerce.Runtime.DataModel)
TOCTitle: OrderPlacedDate Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.DataModel.SalesOrder.OrderPlacedDate
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.datamodel.salesorder.orderplaceddate(v=AX.60)
ms:contentKeyID: 49854867
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataModel.SalesOrder.OrderPlacedDate
dev_langs:
- CSharp
- C++
- VB
---

# OrderPlacedDate Property

Gets or sets the date the order was placed.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataModel](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Entities (in Microsoft.Dynamics.Commerce.Runtime.Entities.dll)

## Syntax

``` vb
'Declaration
<RequiredToBeUtcAttribute(True)> _
<DataMemberAttribute> _
<ColumnAttribute("ORDERPLACEDDATE")> _
Public Property OrderPlacedDate As DateTimeOffset
    Get
    Set
'Usage
Dim instance As SalesOrder
Dim value As DateTimeOffset

value = instance.OrderPlacedDate

instance.OrderPlacedDate = value
```

``` csharp
[RequiredToBeUtcAttribute(true)]
[DataMemberAttribute]
[ColumnAttribute("ORDERPLACEDDATE")]
public DateTimeOffset OrderPlacedDate { get; set; }
```

``` c++
[RequiredToBeUtcAttribute(true)]
[DataMemberAttribute]
[ColumnAttribute(L"ORDERPLACEDDATE")]
public:
property DateTimeOffset OrderPlacedDate {
    DateTimeOffset get ();
    void set (DateTimeOffset value);
}
```

#### Property Value

Type: [System.DateTimeOffset](https://technet.microsoft.com/library/bb341783\(v=ax.60\))  
Returns [DateTime](https://technet.microsoft.com/library/03ybds8y\(v=ax.60\)).  

## See Also

#### Reference

[SalesOrder Class](salesorder-class-microsoft-dynamics-commerce-runtime-datamodel.md)

[Microsoft.Dynamics.Commerce.Runtime.DataModel Namespace](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)

