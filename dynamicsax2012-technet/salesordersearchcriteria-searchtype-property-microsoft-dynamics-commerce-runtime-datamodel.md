---
title: SalesOrderSearchCriteria.SearchType Property  (Microsoft.Dynamics.Commerce.Runtime.DataModel)
TOCTitle: SearchType Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.DataModel.SalesOrderSearchCriteria.SearchType
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.datamodel.salesordersearchcriteria.searchtype(v=AX.60)
ms:contentKeyID: 65316787
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataModel.SalesOrderSearchCriteria.SearchType
dev_langs:
- CSharp
- C++
- VB
---

# SearchType Property


[!INCLUDE[archive-banner](includes/archive-banner.md)]

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataModel](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Entities (in Microsoft.Dynamics.Commerce.Runtime.Entities.dll)

## Syntax

``` vb
'Declaration
<IgnoreDataMemberAttribute> _
Public Property SearchType As OrderSearchType
    Get
    Set
'Usage
Dim instance As SalesOrderSearchCriteria
Dim value As OrderSearchType

value = instance.SearchType

instance.SearchType = value
```

``` csharp
[IgnoreDataMemberAttribute]
public OrderSearchType SearchType { get; set; }
```

``` c++
[IgnoreDataMemberAttribute]
public:
property OrderSearchType SearchType {
    OrderSearchType get ();
    void set (OrderSearchType value);
}
```

#### Property Value

Type: [Microsoft.Dynamics.Commerce.Runtime.DataModel.OrderSearchType](ordersearchtype-enumeration-microsoft-dynamics-commerce-runtime-datamodel.md)  

## See Also

#### Reference

[SalesOrderSearchCriteria Class](salesordersearchcriteria-class-microsoft-dynamics-commerce-runtime-datamodel.md)

[Microsoft.Dynamics.Commerce.Runtime.DataModel Namespace](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)

