---
title: CommerceModelFactory.BindEntityAction(TEntity) Method  (Microsoft.Dynamics.Retail.RetailServerLibrary)
TOCTitle: BindEntityAction(TEntity) Method
ms:assetid: M:Microsoft.Dynamics.Retail.RetailServerLibrary.CommerceModelFactory.BindEntityAction``1(System.String)
ms:mtpsurl: https://technet.microsoft.com/en-us/library/Dn716131(v=AX.60)
ms:contentKeyID: 62202397
ms.date: 04/21/2014
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Retail.RetailServerLibrary.CommerceModelFactory.BindEntityAction``1
dev_langs:
- CSharp
- C++
- VB
---

# BindEntityAction(TEntity) Method

Binds entity action of the model.

**Namespace:**  [Microsoft.Dynamics.Retail.RetailServerLibrary](microsoft-dynamics-retail-retailserverlibrary-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Retail.RetailServerLibrary (in Microsoft.Dynamics.Retail.RetailServerLibrary.dll)

## Syntax

``` vb
'Declaration
Protected Shared Function BindEntityAction(Of TEntity As Class) ( _
    actionName As String _
) As ActionConfiguration
'Usage
Dim actionName As String
Dim returnValue As ActionConfiguration

returnValue = CommerceModelFactory.BindEntityAction(actionName)
```

``` csharp
protected static ActionConfiguration BindEntityAction<TEntity>(
    string actionName
)
where TEntity : class
```

``` c++
protected:
generic<typename TEntity>
where TEntity : ref class
static ActionConfiguration^ BindEntityAction(
    String^ actionName
)
```

#### Type Parameters

  - TEntity

#### Parameters

  - actionName  
    Type: [System.String](https://technet.microsoft.com/en-us/library/s1wwdcbf\(v=ax.60\))  

#### Return Value

Type: ActionConfiguration  
The ActionConfiguration of the OData object.  

## See Also

#### Reference

[CommerceModelFactory Class](commercemodelfactory-class-microsoft-dynamics-retail-retailserverlibrary.md)

[Microsoft.Dynamics.Retail.RetailServerLibrary Namespace](microsoft-dynamics-retail-retailserverlibrary-namespace.md)

