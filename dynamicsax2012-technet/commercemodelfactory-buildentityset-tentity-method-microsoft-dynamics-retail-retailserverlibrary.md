---
title: CommerceModelFactory.BuildEntitySet(TEntity) Method  (Microsoft.Dynamics.Retail.RetailServerLibrary)
TOCTitle: BuildEntitySet(TEntity) Method
ms:assetid: M:Microsoft.Dynamics.Retail.RetailServerLibrary.CommerceModelFactory.BuildEntitySet``1(System.String)
ms:mtpsurl: https://technet.microsoft.com/library/Dn737209(v=AX.60)
ms:contentKeyID: 62201920
author: Khairunj
ms.date: 04/21/2014
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Retail.RetailServerLibrary.CommerceModelFactory.BuildEntitySet``1
dev_langs:
- CSharp
- C++
- VB
---

# BuildEntitySet(TEntity) Method

Builds entity set.

**Namespace:**  [Microsoft.Dynamics.Retail.RetailServerLibrary](microsoft-dynamics-retail-retailserverlibrary-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Retail.RetailServerLibrary (in Microsoft.Dynamics.Retail.RetailServerLibrary.dll)

## Syntax

``` vb
'Declaration
Protected Shared Function BuildEntitySet(Of TEntity As Class) ( _
    entitySetName As String _
) As EntitySetConfiguration(Of TEntity)
'Usage
Dim entitySetName As String
Dim returnValue As EntitySetConfiguration(Of TEntity)

returnValue = CommerceModelFactory.BuildEntitySet(entitySetName)
```

``` csharp
protected static EntitySetConfiguration<TEntity> BuildEntitySet<TEntity>(
    string entitySetName
)
where TEntity : class
```

``` c++
protected:
generic<typename TEntity>
where TEntity : ref class
static EntitySetConfiguration<TEntity>^ BuildEntitySet(
    String^ entitySetName
)
```

#### Type Parameters

  - TEntity

#### Parameters

  - entitySetName  
    Type: [System.String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\))  

#### Return Value

Type: EntitySetConfiguration\<TEntity\>  
The EntitySetConfiguration.  

## See Also

#### Reference

[CommerceModelFactory Class](commercemodelfactory-class-microsoft-dynamics-retail-retailserverlibrary.md)

[Microsoft.Dynamics.Retail.RetailServerLibrary Namespace](microsoft-dynamics-retail-retailserverlibrary-namespace.md)

