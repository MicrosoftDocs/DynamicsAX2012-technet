---
title: ShiftsController.GetZReport Method  (Microsoft.Dynamics.Retail.RetailServerLibrary.ODataControllers)
TOCTitle: GetZReport Method
ms:assetid: M:Microsoft.Dynamics.Retail.RetailServerLibrary.ODataControllers.ShiftsController.GetZReport
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.retail.retailserverlibrary.odatacontrollers.shiftscontroller.getzreport(v=AX.60)
ms:contentKeyID: 62202138
author: tonyafehr
ms.date: 04/21/2014
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Retail.RetailServerLibrary.ODataControllers.ShiftsController.GetZReport
dev_langs:
- CSharp
- C++
- VB
---

# GetZReport Method


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Gets receipt for Z report.

**Namespace:**  [Microsoft.Dynamics.Retail.RetailServerLibrary.ODataControllers](microsoft-dynamics-retail-retailserverlibrary-odatacontrollers-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Retail.RetailServerLibrary (in Microsoft.Dynamics.Retail.RetailServerLibrary.dll)

## Syntax

``` vb
'Declaration
<CommerceAuthorizationAttribute(AllowedRetailRoles := , CheckRetailOperation := True,  _
    RetailOperationId := RetailOperation.PrintZ)> _
<HttpPostAttribute> _
Public Overridable Function GetZReport As Receipt
'Usage
Dim instance As ShiftsController
Dim returnValue As Receipt

returnValue = instance.GetZReport()
```

``` csharp
[CommerceAuthorizationAttribute(AllowedRetailRoles = , CheckRetailOperation = true, 
    RetailOperationId = RetailOperation.PrintZ)]
[HttpPostAttribute]
public virtual Receipt GetZReport()
```

``` c++
[CommerceAuthorizationAttribute(AllowedRetailRoles = , CheckRetailOperation = true, 
    RetailOperationId = RetailOperation::PrintZ)]
[HttpPostAttribute]
public:
virtual Receipt^ GetZReport()
```

#### Return Value

Type: Receipt  
The receipt object.  

## See Also

#### Reference

[ShiftsController Class](shiftscontroller-class-microsoft-dynamics-retail-retailserverlibrary-odatacontrollers.md)

[Microsoft.Dynamics.Retail.RetailServerLibrary.ODataControllers Namespace](microsoft-dynamics-retail-retailserverlibrary-odatacontrollers-namespace.md)

