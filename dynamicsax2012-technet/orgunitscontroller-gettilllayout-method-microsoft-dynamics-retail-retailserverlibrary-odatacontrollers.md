---
title: OrgUnitsController.GetTillLayout Method  (Microsoft.Dynamics.Retail.RetailServerLibrary.ODataControllers)
TOCTitle: GetTillLayout Method
ms:assetid: M:Microsoft.Dynamics.Retail.RetailServerLibrary.ODataControllers.OrgUnitsController.GetTillLayout
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.retail.retailserverlibrary.odatacontrollers.orgunitscontroller.gettilllayout(v=AX.60)
ms:contentKeyID: 62203799
author: Khairunj
ms.date: 04/21/2014
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Retail.RetailServerLibrary.ODataControllers.OrgUnitsController.GetTillLayout
dev_langs:
- CSharp
- C++
- VB
---

# GetTillLayout Method

Gets a single till layout.

**Namespace:**  [Microsoft.Dynamics.Retail.RetailServerLibrary.ODataControllers](microsoft-dynamics-retail-retailserverlibrary-odatacontrollers-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Retail.RetailServerLibrary (in Microsoft.Dynamics.Retail.RetailServerLibrary.dll)

## Syntax

``` vb
'Declaration
<HttpPostAttribute> _
Public Overridable Function GetTillLayout As TillLayout
'Usage
Dim instance As OrgUnitsController
Dim returnValue As TillLayout

returnValue = instance.GetTillLayout()
```

``` csharp
[HttpPostAttribute]
public virtual TillLayout GetTillLayout()
```

``` c++
[HttpPostAttribute]
public:
virtual TillLayout^ GetTillLayout()
```

#### Return Value

Type: TillLayout  
The till layout object.  

## See Also

#### Reference

[OrgUnitsController Class](orgunitscontroller-class-microsoft-dynamics-retail-retailserverlibrary-odatacontrollers.md)

[Microsoft.Dynamics.Retail.RetailServerLibrary.ODataControllers Namespace](microsoft-dynamics-retail-retailserverlibrary-odatacontrollers-namespace.md)

