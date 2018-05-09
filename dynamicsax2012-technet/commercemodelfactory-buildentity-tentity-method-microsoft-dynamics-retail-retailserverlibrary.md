---
title: CommerceModelFactory.BuildEntity(TEntity) Method  (Microsoft.Dynamics.Retail.RetailServerLibrary)
TOCTitle: BuildEntity(TEntity) Method
ms:assetid: M:Microsoft.Dynamics.Retail.RetailServerLibrary.CommerceModelFactory.BuildEntity``1
ms:mtpsurl: https://technet.microsoft.com/en-us/library/Dn716695(v=AX.60)
ms:contentKeyID: 62203709
ms.date: 04/21/2014
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Retail.RetailServerLibrary.CommerceModelFactory.BuildEntity``1
dev_langs:
- CSharp
- C++
- VB
---

# BuildEntity(TEntity) Method

Builds the entity.

**Namespace:**  [Microsoft.Dynamics.Retail.RetailServerLibrary](microsoft-dynamics-retail-retailserverlibrary-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Retail.RetailServerLibrary (in Microsoft.Dynamics.Retail.RetailServerLibrary.dll)

## Syntax

``` vb
'Declaration
Protected Shared Sub BuildEntity(Of TEntity As Class)
'Usage

CommerceModelFactory.BuildEntity()
```

``` csharp
protected static void BuildEntity<TEntity>()
where TEntity : class
```

``` c++
protected:
generic<typename TEntity>
where TEntity : ref class
static void BuildEntity()
```

#### Type Parameters

  - TEntity

## See Also

#### Reference

[CommerceModelFactory Class](commercemodelfactory-class-microsoft-dynamics-retail-retailserverlibrary.md)

[Microsoft.Dynamics.Retail.RetailServerLibrary Namespace](microsoft-dynamics-retail-retailserverlibrary-namespace.md)

