---
title: RetailServerQueryableAttribute.ApplyQuery Method (IQueryable, ) (Microsoft.Dynamics.Retail.RetailServerLibrary)
TOCTitle: ApplyQuery Method (IQueryable, )
ms:assetid: M:Microsoft.Dynamics.Retail.RetailServerLibrary.RetailServerQueryableAttribute.ApplyQuery(System.Linq.IQueryable,System.Web.Http.OData.Query.ODataQueryOptions)
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.retail.retailserverlibrary.retailserverqueryableattribute.applyquery(v=AX.60)
ms:contentKeyID: 62202209
author: Khairunj
ms.date: 04/21/2014
mtps_version: v=AX.60
dev_langs:
- vb
- csharp
- c++
---

# ApplyQuery Method (IQueryable, )

Overrides the base method for the purpose of removing of the applied skip query option on the results.

The reason is that the lower layers already considered the skip parameter.

**Namespace:**  [Microsoft.Dynamics.Retail.RetailServerLibrary](microsoft-dynamics-retail-retailserverlibrary-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Retail.RetailServerLibrary (in Microsoft.Dynamics.Retail.RetailServerLibrary.dll)

## Syntax

``` vb
'Declaration
Public Overrides Function ApplyQuery ( _
    queryable As IQueryable, _
    queryOptions As ODataQueryOptions _
) As IQueryable
'Usage
Dim instance As RetailServerQueryableAttribute
Dim queryable As IQueryable
Dim queryOptions As ODataQueryOptions
Dim returnValue As IQueryable

returnValue = instance.ApplyQuery(queryable, _
    queryOptions)
```

``` csharp
public override IQueryable ApplyQuery(
    IQueryable queryable,
    ODataQueryOptions queryOptions
)
```

``` c++
public:
virtual IQueryable^ ApplyQuery(
    IQueryable^ queryable, 
    ODataQueryOptions^ queryOptions
) override
```

#### Parameters

  - queryable  
    Type: [System.Linq.IQueryable](https://technet.microsoft.com/library/bb495796\(v=ax.60\))  

<!-- end list -->

  - queryOptions  
    Type: ODataQueryOptions  

#### Return Value

Type: [System.Linq.IQueryable](https://technet.microsoft.com/library/bb495796\(v=ax.60\))  
Well formed query.  

## See Also

#### Reference

[RetailServerQueryableAttribute Class](retailserverqueryableattribute-class-microsoft-dynamics-retail-retailserverlibrary.md)

[ApplyQuery Overload](retailserverqueryableattribute-applyquery-method-microsoft-dynamics-retail-retailserverlibrary.md)

[Microsoft.Dynamics.Retail.RetailServerLibrary Namespace](microsoft-dynamics-retail-retailserverlibrary-namespace.md)

