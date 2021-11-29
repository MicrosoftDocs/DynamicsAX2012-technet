---
title: SalesOrderSearchCriteria.SearchLocationType Property  (Microsoft.Dynamics.Commerce.Runtime.DataModel)
TOCTitle: SearchLocationType Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.DataModel.SalesOrderSearchCriteria.SearchLocationType
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.datamodel.salesordersearchcriteria.searchlocationtype(v=AX.60)
ms:contentKeyID: 62206709
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataModel.SalesOrderSearchCriteria.SearchLocationType
dev_langs:
- CSharp
- C++
- VB
---

# SearchLocationType Property


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Gets or sets the search location type.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataModel](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Entities (in Microsoft.Dynamics.Commerce.Runtime.Entities.dll)

## Syntax

``` vb
'Declaration
<IgnoreDataMemberAttribute> _
Public Property SearchLocationType As SearchLocation
    Get
    Set
'Usage
Dim instance As SalesOrderSearchCriteria
Dim value As SearchLocation

value = instance.SearchLocationType

instance.SearchLocationType = value
```

``` csharp
[IgnoreDataMemberAttribute]
public SearchLocation SearchLocationType { get; set; }
```

``` c++
[IgnoreDataMemberAttribute]
public:
property SearchLocation SearchLocationType {
    SearchLocation get ();
    void set (SearchLocation value);
}
```

#### Property Value

Type: [Microsoft.Dynamics.Commerce.Runtime.DataModel.SearchLocation](searchlocation-enumeration-microsoft-dynamics-commerce-runtime-datamodel.md)  
Returns [SearchLocation](searchlocation-enumeration-microsoft-dynamics-commerce-runtime-datamodel.md).  

## See Also

#### Reference

[SalesOrderSearchCriteria Class](salesordersearchcriteria-class-microsoft-dynamics-commerce-runtime-datamodel.md)

[Microsoft.Dynamics.Commerce.Runtime.DataModel Namespace](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)

