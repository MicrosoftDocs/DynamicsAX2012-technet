---
title: NonBindableActionController.LogOn Method  (Microsoft.Dynamics.Retail.RetailServerLibrary.ODataControllers)
TOCTitle: LogOn Method
ms:assetid: M:Microsoft.Dynamics.Retail.RetailServerLibrary.ODataControllers.NonBindableActionController.LogOn(System.Web.Http.OData.ODataActionParameters)
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.retail.retailserverlibrary.odatacontrollers.nonbindableactioncontroller.logon(v=AX.60)
ms:contentKeyID: 62202471
author: tonyafehr
ms.date: 04/21/2014
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Retail.RetailServerLibrary.ODataControllers.NonBindableActionController.LogOn
dev_langs:
- CSharp
- C++
- VB
---

# LogOn Method


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Logs on a retail server user.

**Namespace:**  [Microsoft.Dynamics.Retail.RetailServerLibrary.ODataControllers](microsoft-dynamics-retail-retailserverlibrary-odatacontrollers-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Retail.RetailServerLibrary (in Microsoft.Dynamics.Retail.RetailServerLibrary.dll)

## Syntax

``` vb
'Declaration
<HttpPostAttribute> _
<CommerceAuthorizationAttribute(DeviceTokenRequired := False, AllowedRetailRoles := ,  _
    CheckRetailOperation := False)> _
Public Overridable Function LogOn ( _
    parameters As ODataActionParameters _
) As Employee
'Usage
Dim instance As NonBindableActionController
Dim parameters As ODataActionParameters
Dim returnValue As Employee

returnValue = instance.LogOn(parameters)
```

``` csharp
[HttpPostAttribute]
[CommerceAuthorizationAttribute(DeviceTokenRequired = false, AllowedRetailRoles = , 
    CheckRetailOperation = false)]
public virtual Employee LogOn(
    ODataActionParameters parameters
)
```

``` c++
[HttpPostAttribute]
[CommerceAuthorizationAttribute(DeviceTokenRequired = false, AllowedRetailRoles = , 
    CheckRetailOperation = false)]
public:
virtual Employee^ LogOn(
    ODataActionParameters^ parameters
)
```

#### Parameters

  - parameters  
    Type: ODataActionParameters  

#### Return Value

Type: Employee  
An employee object.  

## See Also

#### Reference

[NonBindableActionController Class](nonbindableactioncontroller-class-microsoft-dynamics-retail-retailserverlibrary-odatacontrollers.md)

[Microsoft.Dynamics.Retail.RetailServerLibrary.ODataControllers Namespace](microsoft-dynamics-retail-retailserverlibrary-odatacontrollers-namespace.md)

