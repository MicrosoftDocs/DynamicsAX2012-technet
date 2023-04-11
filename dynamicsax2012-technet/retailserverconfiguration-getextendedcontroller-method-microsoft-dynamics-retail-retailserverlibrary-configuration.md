---
title: RetailServerConfiguration.GetExtendedController Method  (Microsoft.Dynamics.Retail.RetailServerLibrary.Configuration)
TOCTitle: GetExtendedController Method
ms:assetid: M:Microsoft.Dynamics.Retail.RetailServerLibrary.Configuration.RetailServerConfiguration.GetExtendedController(System.String)
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.retail.retailserverlibrary.configuration.retailserverconfiguration.getextendedcontroller(v=AX.60)
ms:contentKeyID: 62202814
author: tonyafehr
ms.date: 04/21/2014
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Retail.RetailServerLibrary.Configuration.RetailServerConfiguration.GetExtendedController
dev_langs:
- CSharp
- C++
- VB
---

# GetExtendedController Method


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Gets the extended controller by name.

**Namespace:**  [Microsoft.Dynamics.Retail.RetailServerLibrary.Configuration](microsoft-dynamics-retail-retailserverlibrary-configuration-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Retail.RetailServerLibrary (in Microsoft.Dynamics.Retail.RetailServerLibrary.dll)

## Syntax

``` vb
'Declaration
Public Shared Function GetExtendedController ( _
    controllerName As String _
) As IHttpController
'Usage
Dim controllerName As String
Dim returnValue As IHttpController

returnValue = RetailServerConfiguration.GetExtendedController(controllerName)
```

``` csharp
public static IHttpController GetExtendedController(
    string controllerName
)
```

``` c++
public:
static IHttpController^ GetExtendedController(
    String^ controllerName
)
```

#### Parameters

  - controllerName  
    Type: [System.String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\))  

#### Return Value

Type: IHttpController  
The extended controller from MEF composition.  

## See Also

#### Reference

[RetailServerConfiguration Class](retailserverconfiguration-class-microsoft-dynamics-retail-retailserverlibrary-configuration.md)

[Microsoft.Dynamics.Retail.RetailServerLibrary.Configuration Namespace](microsoft-dynamics-retail-retailserverlibrary-configuration-namespace.md)

