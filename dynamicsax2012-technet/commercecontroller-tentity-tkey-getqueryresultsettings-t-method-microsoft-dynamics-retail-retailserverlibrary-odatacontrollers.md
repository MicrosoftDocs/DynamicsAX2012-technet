---
title: CommerceController(TEntity, TKey).GetQueryResultSettings(T) Method  (Microsoft.Dynamics.Retail.RetailServerLibrary.ODataControllers)
TOCTitle: GetQueryResultSettings(T) Method
ms:assetid: M:Microsoft.Dynamics.Retail.RetailServerLibrary.ODataControllers.CommerceController`2.GetQueryResultSettings``1(System.Web.Http.OData.Query.ODataQueryOptions{``0})
ms:mtpsurl: https://technet.microsoft.com/library/Dn716121(v=AX.60)
ms:contentKeyID: 62202387
author: Khairunj
ms.date: 04/21/2014
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Retail.RetailServerLibrary.ODataControllers.CommerceController`2.GetQueryResultSettings``1
dev_langs:
- CSharp
- C++
- VB
---

# GetQueryResultSettings(T) Method

Gets the query result settings based on the current query options.

**Namespace:**  [Microsoft.Dynamics.Retail.RetailServerLibrary.ODataControllers](microsoft-dynamics-retail-retailserverlibrary-odatacontrollers-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Retail.RetailServerLibrary (in Microsoft.Dynamics.Retail.RetailServerLibrary.dll)

## Syntax

``` vb
'Declaration
Protected Function GetQueryResultSettings(Of T As Class) ( _
    queryOptions As ODataQueryOptions(Of T) _
) As QueryResultSettings
'Usage
Dim queryOptions As ODataQueryOptions(Of T)
Dim returnValue As QueryResultSettings

returnValue = Me.GetQueryResultSettings(queryOptions)
```

``` csharp
protected QueryResultSettings GetQueryResultSettings<T>(
    ODataQueryOptions<T> queryOptions
)
where T : class
```

``` c++
protected:
generic<typename T>
where T : ref class
QueryResultSettings^ GetQueryResultSettings(
    ODataQueryOptions<T>^ queryOptions
)
```

#### Type Parameters

  - T

#### Parameters

  - queryOptions  
    Type: ODataQueryOptions\<T\>  

#### Return Value

Type: QueryResultSettings  
The query result settings.  

## See Also

#### Reference

[CommerceController\<TEntity, TKey\> Class](commercecontroller-tentity-tkey-class-microsoft-dynamics-retail-retailserverlibrary-odatacontrollers.md)

[Microsoft.Dynamics.Retail.RetailServerLibrary.ODataControllers Namespace](microsoft-dynamics-retail-retailserverlibrary-odatacontrollers-namespace.md)

