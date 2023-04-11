---
title: CompositeKeyEntityController(TEntity).ProcessPagedResults Method  (Microsoft.Dynamics.Retail.RetailServerLibrary.ODataControllers)
TOCTitle: ProcessPagedResults Method
ms:assetid: M:Microsoft.Dynamics.Retail.RetailServerLibrary.ODataControllers.CompositeKeyEntityController`1.ProcessPagedResults(Microsoft.Dynamics.Commerce.Runtime.PagedResult{`0},System.Int32)
ms:mtpsurl: https://technet.microsoft.com/library/Dn716541(v=AX.60)
ms:contentKeyID: 62203058
author: tonyafehr
ms.date: 04/21/2014
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Retail.RetailServerLibrary.ODataControllers.CompositeKeyEntityController`1.ProcessPagedResults
dev_langs:
- CSharp
- C++
- VB
---

# ProcessPagedResults Method


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Processes the paged results.

**Namespace:**  [Microsoft.Dynamics.Retail.RetailServerLibrary.ODataControllers](microsoft-dynamics-retail-retailserverlibrary-odatacontrollers-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Retail.RetailServerLibrary (in Microsoft.Dynamics.Retail.RetailServerLibrary.dll)

## Syntax

``` vb
'Declaration
Protected Sub ProcessPagedResults ( _
    entities As PagedResult(Of TEntity), _
    pageSize As Integer _
)
'Usage
Dim entities As PagedResult(Of TEntity)
Dim pageSize As Integer

Me.ProcessPagedResults(entities, _
    pageSize)
```

``` csharp
protected void ProcessPagedResults(
    PagedResult<TEntity> entities,
    int pageSize
)
```

``` c++
protected:
void ProcessPagedResults(
    PagedResult<TEntity>^ entities, 
    int pageSize
)
```

#### Parameters

  - entities  
    Type: PagedResult\<[TEntity](compositekeyentitycontroller-tentity-class-microsoft-dynamics-retail-retailserverlibrary-odatacontrollers.md)\>  

<!-- end list -->

  - pageSize  
    Type: [System.Int32](https://technet.microsoft.com/library/td2s409d\(v=ax.60\))  

## See Also

#### Reference

[CompositeKeyEntityController\<TEntity\> Class](compositekeyentitycontroller-tentity-class-microsoft-dynamics-retail-retailserverlibrary-odatacontrollers.md)

[Microsoft.Dynamics.Retail.RetailServerLibrary.ODataControllers Namespace](microsoft-dynamics-retail-retailserverlibrary-odatacontrollers-namespace.md)

