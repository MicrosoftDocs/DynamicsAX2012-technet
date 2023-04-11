---
title: CommerceModelFactory.CreateModel Method  (Microsoft.Dynamics.Retail.RetailServerLibrary)
TOCTitle: CreateModel Method
ms:assetid: M:Microsoft.Dynamics.Retail.RetailServerLibrary.CommerceModelFactory.CreateModel
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.retail.retailserverlibrary.commercemodelfactory.createmodel(v=AX.60)
ms:contentKeyID: 62202446
author: tonyafehr
ms.date: 04/21/2014
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Retail.RetailServerLibrary.CommerceModelFactory.CreateModel
dev_langs:
- CSharp
- C++
- VB
---

# CreateModel Method


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Creates the commerce EDM model.

**Namespace:**  [Microsoft.Dynamics.Retail.RetailServerLibrary](microsoft-dynamics-retail-retailserverlibrary-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Retail.RetailServerLibrary (in Microsoft.Dynamics.Retail.RetailServerLibrary.dll)

## Syntax

``` vb
'Declaration
Public Function CreateModel As IEdmModel
'Usage
Dim instance As CommerceModelFactory
Dim returnValue As IEdmModel

returnValue = instance.CreateModel()
```

``` csharp
public IEdmModel CreateModel()
```

``` c++
public:
virtual IEdmModel^ CreateModel() sealed
```

#### Return Value

Type: IEdmModel  
The IEdmModel new model.  

#### Implements

[IEdmModelFactory.CreateModel()](iedmmodelfactory-createmodel-method-microsoft-dynamics-retail-retailserverlibrary.md)  

## See Also

#### Reference

[CommerceModelFactory Class](commercemodelfactory-class-microsoft-dynamics-retail-retailserverlibrary.md)

[Microsoft.Dynamics.Retail.RetailServerLibrary Namespace](microsoft-dynamics-retail-retailserverlibrary-namespace.md)

