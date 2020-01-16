---
title: NonBindableActionController.ValidateHardwareStationToken Method  (Microsoft.Dynamics.Retail.RetailServerLibrary.ODataControllers)
TOCTitle: ValidateHardwareStationToken Method
ms:assetid: M:Microsoft.Dynamics.Retail.RetailServerLibrary.ODataControllers.NonBindableActionController.ValidateHardwareStationToken(System.Web.Http.OData.ODataActionParameters)
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.retail.retailserverlibrary.odatacontrollers.nonbindableactioncontroller.validatehardwarestationtoken(v=AX.60)
ms:contentKeyID: 62202175
author: Khairunj
ms.date: 04/21/2014
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Retail.RetailServerLibrary.ODataControllers.NonBindableActionController.ValidateHardwareStationToken
dev_langs:
- CSharp
- C++
- VB
---

# ValidateHardwareStationToken Method

Validate a hardware station token.

**Namespace:**  [Microsoft.Dynamics.Retail.RetailServerLibrary.ODataControllers](microsoft-dynamics-retail-retailserverlibrary-odatacontrollers-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Retail.RetailServerLibrary (in Microsoft.Dynamics.Retail.RetailServerLibrary.dll)

## Syntax

``` vb
'Declaration
<HttpPostAttribute> _
<CommerceAuthorizationAttribute(DeviceTokenRequired := False, AllowedRetailRoles := ,  _
    CheckRetailOperation := False)> _
Public Overridable Sub ValidateHardwareStationToken ( _
    parameters As ODataActionParameters _
)
'Usage
Dim instance As NonBindableActionController
Dim parameters As ODataActionParameters

instance.ValidateHardwareStationToken(parameters)
```

``` csharp
[HttpPostAttribute]
[CommerceAuthorizationAttribute(DeviceTokenRequired = false, AllowedRetailRoles = , 
    CheckRetailOperation = false)]
public virtual void ValidateHardwareStationToken(
    ODataActionParameters parameters
)
```

``` c++
[HttpPostAttribute]
[CommerceAuthorizationAttribute(DeviceTokenRequired = false, AllowedRetailRoles = , 
    CheckRetailOperation = false)]
public:
virtual void ValidateHardwareStationToken(
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

