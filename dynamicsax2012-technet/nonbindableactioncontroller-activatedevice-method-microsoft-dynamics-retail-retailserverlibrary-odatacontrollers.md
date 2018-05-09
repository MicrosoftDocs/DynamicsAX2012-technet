---
title: NonBindableActionController.ActivateDevice Method  (Microsoft.Dynamics.Retail.RetailServerLibrary.ODataControllers)
TOCTitle: ActivateDevice Method
ms:assetid: M:Microsoft.Dynamics.Retail.RetailServerLibrary.ODataControllers.NonBindableActionController.ActivateDevice(System.Web.Http.OData.ODataActionParameters)
ms:mtpsurl: https://technet.microsoft.com/en-us/library/microsoft.dynamics.retail.retailserverlibrary.odatacontrollers.nonbindableactioncontroller.activatedevice(v=AX.60)
ms:contentKeyID: 62202311
ms.date: 04/21/2014
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Retail.RetailServerLibrary.ODataControllers.NonBindableActionController.ActivateDevice
dev_langs:
- CSharp
- C++
- VB
---

# ActivateDevice Method

Activiate device.

**Namespace:**  [Microsoft.Dynamics.Retail.RetailServerLibrary.ODataControllers](microsoft-dynamics-retail-retailserverlibrary-odatacontrollers-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Retail.RetailServerLibrary (in Microsoft.Dynamics.Retail.RetailServerLibrary.dll)

## Syntax

``` vb
'Declaration
<CommerceAuthorizationAttribute(DeviceTokenRequired := False, AllowedRetailRoles := ,  _
    CheckRetailOperation := True, RetailOperationId := RetailOperation.ActivateDevice)> _
<HttpPostAttribute> _
Public Overridable Function ActivateDevice ( _
    parameters As ODataActionParameters _
) As Device
'Usage
Dim instance As NonBindableActionController
Dim parameters As ODataActionParameters
Dim returnValue As Device

returnValue = instance.ActivateDevice(parameters)
```

``` csharp
[CommerceAuthorizationAttribute(DeviceTokenRequired = false, AllowedRetailRoles = , 
    CheckRetailOperation = true, RetailOperationId = RetailOperation.ActivateDevice)]
[HttpPostAttribute]
public virtual Device ActivateDevice(
    ODataActionParameters parameters
)
```

``` c++
[CommerceAuthorizationAttribute(DeviceTokenRequired = false, AllowedRetailRoles = , 
    CheckRetailOperation = true, RetailOperationId = RetailOperation::ActivateDevice)]
[HttpPostAttribute]
public:
virtual Device^ ActivateDevice(
    ODataActionParameters^ parameters
)
```

#### Parameters

  - parameters  
    Type: ODataActionParameters  

#### Return Value

Type: Device  
The device object.  

## See Also

#### Reference

[NonBindableActionController Class](nonbindableactioncontroller-class-microsoft-dynamics-retail-retailserverlibrary-odatacontrollers.md)

[Microsoft.Dynamics.Retail.RetailServerLibrary.ODataControllers Namespace](microsoft-dynamics-retail-retailserverlibrary-odatacontrollers-namespace.md)

