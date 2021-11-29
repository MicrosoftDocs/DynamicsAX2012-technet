---
title: NonBindableActionController.LogOff Method  (Microsoft.Dynamics.Retail.RetailServerLibrary.ODataControllers)
TOCTitle: LogOff Method
ms:assetid: M:Microsoft.Dynamics.Retail.RetailServerLibrary.ODataControllers.NonBindableActionController.LogOff
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.retail.retailserverlibrary.odatacontrollers.nonbindableactioncontroller.logoff(v=AX.60)
ms:contentKeyID: 62202787
author: Khairunj
ms.date: 04/21/2014
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Retail.RetailServerLibrary.ODataControllers.NonBindableActionController.LogOff
dev_langs:
- CSharp
- C++
- VB
---

# LogOff Method


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Logs off a retail server user.

**Namespace:**  [Microsoft.Dynamics.Retail.RetailServerLibrary.ODataControllers](microsoft-dynamics-retail-retailserverlibrary-odatacontrollers-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Retail.RetailServerLibrary (in Microsoft.Dynamics.Retail.RetailServerLibrary.dll)

## Syntax

``` vb
'Declaration
<HttpPostAttribute> _
<CommerceAuthorizationAttribute(DeviceTokenRequired := False, AllowedRetailRoles := ,  _
    CheckRetailOperation := False)> _
Public Overridable Sub LogOff
'Usage
Dim instance As NonBindableActionController

instance.LogOff()
```

``` csharp
[HttpPostAttribute]
[CommerceAuthorizationAttribute(DeviceTokenRequired = false, AllowedRetailRoles = , 
    CheckRetailOperation = false)]
public virtual void LogOff()
```

``` c++
[HttpPostAttribute]
[CommerceAuthorizationAttribute(DeviceTokenRequired = false, AllowedRetailRoles = , 
    CheckRetailOperation = false)]
public:
virtual void LogOff()
```

## See Also

#### Reference

[NonBindableActionController Class](nonbindableactioncontroller-class-microsoft-dynamics-retail-retailserverlibrary-odatacontrollers.md)

[Microsoft.Dynamics.Retail.RetailServerLibrary.ODataControllers Namespace](microsoft-dynamics-retail-retailserverlibrary-odatacontrollers-namespace.md)

