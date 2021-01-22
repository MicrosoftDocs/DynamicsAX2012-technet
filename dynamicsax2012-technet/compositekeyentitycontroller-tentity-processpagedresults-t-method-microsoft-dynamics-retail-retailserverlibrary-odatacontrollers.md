---
title: CompositeKeyEntityController(TEntity).ProcessPagedResults(T) Method  (Microsoft.Dynamics.Retail.RetailServerLibrary.ODataControllers)
TOCTitle: ProcessPagedResults(T) Method
ms:assetid: M:Microsoft.Dynamics.Retail.RetailServerLibrary.ODataControllers.CompositeKeyEntityController`1.ProcessPagedResults``1(Microsoft.Dynamics.Commerce.Runtime.PagedResult{``0},System.Int32)
ms:mtpsurl: https://technet.microsoft.com/library/Dn684276(v=AX.60)
ms:contentKeyID: 62203416
author: Khairunj
ms.author: daxcpft
ms.date: 04/21/2014
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Retail.RetailServerLibrary.ODataControllers.CompositeKeyEntityController`1.ProcessPagedResults``1
dev_langs:
- CSharp
- C++
- VB
---

# ProcessPagedResults(T) Method

Processes the paged results.

**Namespace:**  [Microsoft.Dynamics.Retail.RetailServerLibrary.ODataControllers](microsoft-dynamics-retail-retailserverlibrary-odatacontrollers-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Retail.RetailServerLibrary (in Microsoft.Dynamics.Retail.RetailServerLibrary.dll)

## Syntax

``` vb
'Declaration
Protected Sub ProcessPagedResults(Of T As Class) ( _
    entities As PagedResult(Of T), _
    pageSize As Integer _
)
'Usage
Dim entities As PagedResult(Of T)
Dim pageSize As Integer

Me.ProcessPagedResults(entities, _
    pageSize)
```

``` csharp
protected void ProcessPagedResults<T>(
    PagedResult<T> entities,
    int pageSize
)
where T : class
```

``` c++
protected:
generic<typename T>
where T : ref class
void ProcessPagedResults(
    PagedResult<T>^ entities, 
    int pageSize
)
```

#### Type Parameters

  - T

#### Parameters

  - entities  
    Type: PagedResult\<T\>  

<!-- end list -->

  - pageSize  
    Type: [System.Int32](https://technet.microsoft.com/library/td2s409d\(v=ax.60\))  

## See Also

#### Reference

[CompositeKeyEntityController\<TEntity\> Class](compositekeyentitycontroller-tentity-class-microsoft-dynamics-retail-retailserverlibrary-odatacontrollers.md)

[Microsoft.Dynamics.Retail.RetailServerLibrary.ODataControllers Namespace](microsoft-dynamics-retail-retailserverlibrary-odatacontrollers-namespace.md)

