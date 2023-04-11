---
title: NonBindableActionController.ResetPassword Method  (Microsoft.Dynamics.Retail.RetailServerLibrary.ODataControllers)
TOCTitle: ResetPassword Method
ms:assetid: M:Microsoft.Dynamics.Retail.RetailServerLibrary.ODataControllers.NonBindableActionController.ResetPassword(System.Web.Http.OData.ODataActionParameters)
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.retail.retailserverlibrary.odatacontrollers.nonbindableactioncontroller.resetpassword(v=AX.60)
ms:contentKeyID: 62203080
author: tonyafehr
ms.date: 04/21/2014
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Retail.RetailServerLibrary.ODataControllers.NonBindableActionController.ResetPassword
dev_langs:
- CSharp
- C++
- VB
---

# ResetPassword Method


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Reset password for a user.

**Namespace:**  [Microsoft.Dynamics.Retail.RetailServerLibrary.ODataControllers](microsoft-dynamics-retail-retailserverlibrary-odatacontrollers-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Retail.RetailServerLibrary (in Microsoft.Dynamics.Retail.RetailServerLibrary.dll)

## Syntax

``` vb
'Declaration
<HttpPostAttribute> _
<CommerceAuthorizationAttribute(DeviceTokenRequired := True, AllowedRetailRoles := ,  _
    CheckRetailOperation := True, RetailOperationId := RetailOperation.ResetPassword)> _
Public Overridable Sub ResetPassword ( _
    parameters As ODataActionParameters _
)
'Usage
Dim instance As NonBindableActionController
Dim parameters As ODataActionParameters

instance.ResetPassword(parameters)
```

``` csharp
[HttpPostAttribute]
[CommerceAuthorizationAttribute(DeviceTokenRequired = true, AllowedRetailRoles = , 
    CheckRetailOperation = true, RetailOperationId = RetailOperation.ResetPassword)]
public virtual void ResetPassword(
    ODataActionParameters parameters
)
```

``` c++
[HttpPostAttribute]
[CommerceAuthorizationAttribute(DeviceTokenRequired = true, AllowedRetailRoles = , 
    CheckRetailOperation = true, RetailOperationId = RetailOperation::ResetPassword)]
public:
virtual void ResetPassword(
    ODataActionParameters^ parameters
)
```

#### Parameters

  - parameters  
    Type: ODataActionParameters  

## See Also

#### Reference

[NonBindableActionController Class](nonbindableactioncontroller-class-microsoft-dynamics-retail-retailserverlibrary-odatacontrollers.md)

[Microsoft.Dynamics.Retail.RetailServerLibrary.ODataControllers Namespace](microsoft-dynamics-retail-retailserverlibrary-odatacontrollers-namespace.md)

