---
title: IEdmModelFactory.CreateModel Method  (Microsoft.Dynamics.Retail.RetailServerLibrary)
TOCTitle: CreateModel Method
ms:assetid: M:Microsoft.Dynamics.Retail.RetailServerLibrary.IEdmModelFactory.CreateModel
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.retail.retailserverlibrary.iedmmodelfactory.createmodel(v=AX.60)
ms:contentKeyID: 62202207
author: tonyafehr
ms.date: 04/21/2014
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Retail.RetailServerLibrary.IEdmModelFactory.CreateModel
dev_langs:
- CSharp
- C++
- VB
---

# CreateModel Method


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Creates OData edm model.

**Namespace:**  [Microsoft.Dynamics.Retail.RetailServerLibrary](microsoft-dynamics-retail-retailserverlibrary-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Retail.RetailServerLibrary (in Microsoft.Dynamics.Retail.RetailServerLibrary.dll)

## Syntax

``` vb
'Declaration
Function CreateModel As IEdmModel
'Usage
Dim instance As IEdmModelFactory
Dim returnValue As IEdmModel

returnValue = instance.CreateModel()
```

``` csharp
IEdmModel CreateModel()
```

``` c++
IEdmModel^ CreateModel()
```

#### Return Value

Type: IEdmModel  
The IEdmModel.  

## See Also

#### Reference

[IEdmModelFactory Interface](iedmmodelfactory-interface-microsoft-dynamics-retail-retailserverlibrary.md)

[Microsoft.Dynamics.Retail.RetailServerLibrary Namespace](microsoft-dynamics-retail-retailserverlibrary-namespace.md)

