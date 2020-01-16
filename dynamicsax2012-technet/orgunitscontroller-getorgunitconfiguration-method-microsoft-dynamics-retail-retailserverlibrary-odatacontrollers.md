---
title: OrgUnitsController.GetOrgUnitConfiguration Method  (Microsoft.Dynamics.Retail.RetailServerLibrary.ODataControllers)
TOCTitle: GetOrgUnitConfiguration Method
ms:assetid: M:Microsoft.Dynamics.Retail.RetailServerLibrary.ODataControllers.OrgUnitsController.GetOrgUnitConfiguration
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.retail.retailserverlibrary.odatacontrollers.orgunitscontroller.getorgunitconfiguration(v=AX.60)
ms:contentKeyID: 62202896
author: Khairunj
ms.date: 04/21/2014
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Retail.RetailServerLibrary.ODataControllers.OrgUnitsController.GetOrgUnitConfiguration
dev_langs:
- CSharp
- C++
- VB
---

# GetOrgUnitConfiguration Method

Gets the configuration for the current organization unit.

**Namespace:**  [Microsoft.Dynamics.Retail.RetailServerLibrary.ODataControllers](microsoft-dynamics-retail-retailserverlibrary-odatacontrollers-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Retail.RetailServerLibrary (in Microsoft.Dynamics.Retail.RetailServerLibrary.dll)

## Syntax

``` vb
'Declaration
<HttpPostAttribute> _
Public Function GetOrgUnitConfiguration As ChannelConfiguration
'Usage
Dim instance As OrgUnitsController
Dim returnValue As ChannelConfiguration

returnValue = instance.GetOrgUnitConfiguration()
```

``` csharp
[HttpPostAttribute]
public ChannelConfiguration GetOrgUnitConfiguration()
```

``` c++
[HttpPostAttribute]
public:
ChannelConfiguration^ GetOrgUnitConfiguration()
```

#### Return Value

Type: ChannelConfiguration  
The configuration for the current channel.  

## See Also

#### Reference

[OrgUnitsController Class](orgunitscontroller-class-microsoft-dynamics-retail-retailserverlibrary-odatacontrollers.md)

[Microsoft.Dynamics.Retail.RetailServerLibrary.ODataControllers Namespace](microsoft-dynamics-retail-retailserverlibrary-odatacontrollers-namespace.md)

