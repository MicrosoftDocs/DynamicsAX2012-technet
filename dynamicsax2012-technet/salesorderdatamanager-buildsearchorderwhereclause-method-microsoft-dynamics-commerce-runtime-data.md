---
title: SalesOrderDataManager.BuildSearchOrderWhereClause Method  (Microsoft.Dynamics.Commerce.Runtime.Data)
TOCTitle: BuildSearchOrderWhereClause Method
ms:assetid: M:Microsoft.Dynamics.Commerce.Runtime.Data.SalesOrderDataManager.BuildSearchOrderWhereClause(Microsoft.Dynamics.Commerce.Runtime.DataModel.SalesOrderSearchCriteria,Microsoft.Dynamics.Commerce.Runtime.Data.SqlPagedQuery,System.Collections.Generic.IList{System.String})
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.data.salesorderdatamanager.buildsearchorderwhereclause(v=AX.60)
ms:contentKeyID: 65317666
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.Data.SalesOrderDataManager.BuildSearchOrderWhereClause
dev_langs:
- CSharp
- C++
- VB
---

# BuildSearchOrderWhereClause Method

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.Data](microsoft-dynamics-commerce-runtime-data-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.DataManagers (in Microsoft.Dynamics.Commerce.Runtime.DataManagers.dll)

## Syntax

``` vb
'Declaration
Public Shared Sub BuildSearchOrderWhereClause ( _
    criteria As SalesOrderSearchCriteria, _
    query As SqlPagedQuery, _
    whereClauses As IList(Of String) _
)
'Usage
Dim criteria As SalesOrderSearchCriteria
Dim query As SqlPagedQuery
Dim whereClauses As IList(Of String)

SalesOrderDataManager.BuildSearchOrderWhereClause(criteria, _
    query, whereClauses)
```

``` csharp
public static void BuildSearchOrderWhereClause(
    SalesOrderSearchCriteria criteria,
    SqlPagedQuery query,
    IList<string> whereClauses
)
```

``` c++
public:
static void BuildSearchOrderWhereClause(
    SalesOrderSearchCriteria^ criteria, 
    SqlPagedQuery^ query, 
    IList<String^>^ whereClauses
)
```

#### Parameters

  - criteria  
    Type: [Microsoft.Dynamics.Commerce.Runtime.DataModel.SalesOrderSearchCriteria](salesordersearchcriteria-class-microsoft-dynamics-commerce-runtime-datamodel.md)  

<!-- end list -->

  - query  
    Type: [Microsoft.Dynamics.Commerce.Runtime.Data.SqlPagedQuery](sqlpagedquery-class-microsoft-dynamics-commerce-runtime-data.md)  

<!-- end list -->

  - whereClauses  
    Type: [System.Collections.Generic.IList](https://technet.microsoft.com/library/5y536ey6\(v=ax.60\))\<[String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\))\>  

## See Also

#### Reference

[SalesOrderDataManager Class](salesorderdatamanager-class-microsoft-dynamics-commerce-runtime-data.md)

[Microsoft.Dynamics.Commerce.Runtime.Data Namespace](microsoft-dynamics-commerce-runtime-data-namespace.md)

