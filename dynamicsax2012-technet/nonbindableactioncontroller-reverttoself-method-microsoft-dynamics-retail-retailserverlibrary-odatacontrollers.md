---
title: NonBindableActionController.RevertToSelf Method  (Microsoft.Dynamics.Retail.RetailServerLibrary.ODataControllers)
TOCTitle: RevertToSelf Method
ms:assetid: M:Microsoft.Dynamics.Retail.RetailServerLibrary.ODataControllers.NonBindableActionController.RevertToSelf(System.Web.Http.OData.ODataActionParameters)
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.retail.retailserverlibrary.odatacontrollers.nonbindableactioncontroller.reverttoself(v=AX.60)
ms:contentKeyID: 62203683
author: tonyafehr
ms.date: 04/21/2014
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Retail.RetailServerLibrary.ODataControllers.NonBindableActionController.RevertToSelf
dev_langs:
- CSharp
- C++
- VB
---

# RevertToSelf Method


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Manager revert.

**Namespace:**  [Microsoft.Dynamics.Retail.RetailServerLibrary.ODataControllers](microsoft-dynamics-retail-retailserverlibrary-odatacontrollers-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Retail.RetailServerLibrary (in Microsoft.Dynamics.Retail.RetailServerLibrary.dll)

## Syntax

``` vb
'Declaration
<HttpPostAttribute> _
<CommerceAuthorizationAttribute(AllowedRetailRoles := , CheckRetailOperation := False)> _
Public Overridable Sub RevertToSelf ( _
    parameters As ODataActionParameters _
)
'Usage
Dim instance As NonBindableActionController
Dim parameters As ODataActionParameters

instance.RevertToSelf(parameters)
```

``` csharp
[HttpPostAttribute]
[CommerceAuthorizationAttribute(AllowedRetailRoles = , CheckRetailOperation = false)]
public virtual void RevertToSelf(
    ODataActionParameters parameters
)
```

``` c++
[HttpPostAttribute]
[CommerceAuthorizationAttribute(AllowedRetailRoles = , CheckRetailOperation = false)]
public:
virtual void RevertToSelf(
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

