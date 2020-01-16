---
title: SalesOrder.Status Property  (Microsoft.Dynamics.Commerce.Runtime.DataModel)
TOCTitle: Status Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.DataModel.SalesOrder.Status
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.datamodel.salesorder.status(v=AX.60)
ms:contentKeyID: 49850228
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataModel.SalesOrder.Status
dev_langs:
- CSharp
- C++
- VB
---

# Status Property

Gets or sets the order status.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataModel](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Entities (in Microsoft.Dynamics.Commerce.Runtime.Entities.dll)

## Syntax

``` vb
'Declaration
<ColumnAttribute("STATUS")> _
<IgnoreDataMemberAttribute> _
Public Property Status As SalesStatus
    Get
    Set
'Usage
Dim instance As SalesOrder
Dim value As SalesStatus

value = instance.Status

instance.Status = value
```

``` csharp
[ColumnAttribute("STATUS")]
[IgnoreDataMemberAttribute]
public SalesStatus Status { get; set; }
```

``` c++
[ColumnAttribute(L"STATUS")]
[IgnoreDataMemberAttribute]
public:
property SalesStatus Status {
    SalesStatus get ();
    void set (SalesStatus value);
}
```

#### Property Value

Type: [Microsoft.Dynamics.Commerce.Runtime.DataModel.SalesStatus](salesstatus-enumeration-microsoft-dynamics-commerce-runtime-datamodel.md)  
Returns [SalesStatus](salesstatus-enumeration-microsoft-dynamics-commerce-runtime-datamodel.md).  

## See Also

#### Reference

[SalesOrder Class](salesorder-class-microsoft-dynamics-commerce-runtime-datamodel.md)

[Microsoft.Dynamics.Commerce.Runtime.DataModel Namespace](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)

