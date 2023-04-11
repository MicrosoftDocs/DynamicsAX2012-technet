---
title: NonBindableActionController.GetDeviceConfiguration Method  (Microsoft.Dynamics.Retail.RetailServerLibrary.ODataControllers)
TOCTitle: GetDeviceConfiguration Method
ms:assetid: M:Microsoft.Dynamics.Retail.RetailServerLibrary.ODataControllers.NonBindableActionController.GetDeviceConfiguration(System.Web.Http.OData.Query.ODataQueryOptions{Microsoft.Dynamics.Commerce.Runtime.DataModel.DeviceConfiguration})
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.retail.retailserverlibrary.odatacontrollers.nonbindableactioncontroller.getdeviceconfiguration(v=AX.60)
ms:contentKeyID: 62202137
author: tonyafehr
ms.date: 04/21/2014
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Retail.RetailServerLibrary.ODataControllers.NonBindableActionController.GetDeviceConfiguration
dev_langs:
- CSharp
- C++
- VB
---

# GetDeviceConfiguration Method


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Gets a single device configuration.

**Namespace:**  [Microsoft.Dynamics.Retail.RetailServerLibrary.ODataControllers](microsoft-dynamics-retail-retailserverlibrary-odatacontrollers-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Retail.RetailServerLibrary (in Microsoft.Dynamics.Retail.RetailServerLibrary.dll)

## Syntax

``` vb
'Declaration
<HttpPostAttribute> _
<CommerceAuthorizationAttribute(AllowedRetailRoles := , CheckRetailOperation := False)> _
Public Overridable Function GetDeviceConfiguration ( _
    queryOptions As ODataQueryOptions(Of DeviceConfiguration) _
) As DeviceConfiguration
'Usage
Dim instance As NonBindableActionController
Dim queryOptions As ODataQueryOptions(Of DeviceConfiguration)
Dim returnValue As DeviceConfiguration

returnValue = instance.GetDeviceConfiguration(queryOptions)
```

``` csharp
[HttpPostAttribute]
[CommerceAuthorizationAttribute(AllowedRetailRoles = , CheckRetailOperation = false)]
public virtual DeviceConfiguration GetDeviceConfiguration(
    ODataQueryOptions<DeviceConfiguration> queryOptions
)
```

``` c++
[HttpPostAttribute]
[CommerceAuthorizationAttribute(AllowedRetailRoles = , CheckRetailOperation = false)]
public:
virtual DeviceConfiguration^ GetDeviceConfiguration(
    ODataQueryOptions<DeviceConfiguration^>^ queryOptions
)
```

#### Parameters

  - queryOptions  
    Type: ODataQueryOptions\<DeviceConfiguration\>  

#### Return Value

Type: DeviceConfiguration  
The device configuration object.  

## See Also

#### Reference

[NonBindableActionController Class](nonbindableactioncontroller-class-microsoft-dynamics-retail-retailserverlibrary-odatacontrollers.md)

[Microsoft.Dynamics.Retail.RetailServerLibrary.ODataControllers Namespace](microsoft-dynamics-retail-retailserverlibrary-odatacontrollers-namespace.md)

