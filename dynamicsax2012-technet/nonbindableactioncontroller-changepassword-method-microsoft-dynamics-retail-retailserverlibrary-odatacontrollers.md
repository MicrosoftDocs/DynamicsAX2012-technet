---
title: NonBindableActionController.ChangePassword Method  (Microsoft.Dynamics.Retail.RetailServerLibrary.ODataControllers)
TOCTitle: ChangePassword Method
ms:assetid: M:Microsoft.Dynamics.Retail.RetailServerLibrary.ODataControllers.NonBindableActionController.ChangePassword(System.Web.Http.OData.ODataActionParameters)
ms:mtpsurl: https://technet.microsoft.com/en-us/library/microsoft.dynamics.retail.retailserverlibrary.odatacontrollers.nonbindableactioncontroller.changepassword(v=AX.60)
ms:contentKeyID: 62203369
ms.date: 04/21/2014
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Retail.RetailServerLibrary.ODataControllers.NonBindableActionController.ChangePassword
dev_langs:
- CSharp
- C++
- VB
---

# ChangePassword Method

Change password for a user.

**Namespace:**  [Microsoft.Dynamics.Retail.RetailServerLibrary.ODataControllers](microsoft-dynamics-retail-retailserverlibrary-odatacontrollers-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Retail.RetailServerLibrary (in Microsoft.Dynamics.Retail.RetailServerLibrary.dll)

## Syntax

``` vb
'Declaration
<HttpPostAttribute> _
<CommerceAuthorizationAttribute(DeviceTokenRequired := True, AllowedRetailRoles := ,  _
    CheckRetailOperation := True, RetailOperationId := RetailOperation.ChangePassword)> _
Public Overridable Sub ChangePassword ( _
    parameters As ODataActionParameters _
)
'Usage
Dim instance As NonBindableActionController
Dim parameters As ODataActionParameters

instance.ChangePassword(parameters)
```

``` csharp
[HttpPostAttribute]
[CommerceAuthorizationAttribute(DeviceTokenRequired = true, AllowedRetailRoles = , 
    CheckRetailOperation = true, RetailOperationId = RetailOperation.ChangePassword)]
public virtual void ChangePassword(
    ODataActionParameters parameters
)
```

``` c++
[HttpPostAttribute]
[CommerceAuthorizationAttribute(DeviceTokenRequired = true, AllowedRetailRoles = , 
    CheckRetailOperation = true, RetailOperationId = RetailOperation::ChangePassword)]
public:
virtual void ChangePassword(
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

