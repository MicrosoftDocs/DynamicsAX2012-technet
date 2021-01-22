---
title: ControllerBase.Configuration Property  (Microsoft.Dynamics.Retail.Ecommerce.Sdk.Core.Controllers)
TOCTitle: Configuration Property
ms:assetid: P:Microsoft.Dynamics.Retail.Ecommerce.Sdk.Core.Controllers.ControllerBase.Configuration
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.retail.ecommerce.sdk.core.controllers.controllerbase.configuration(v=AX.60)
ms:contentKeyID: 65315943
author: Khairunj
ms.author: daxcpft
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Retail.Ecommerce.Sdk.Core.Controllers.ControllerBase.Configuration
dev_langs:
- CSharp
- C++
- VB
---

# Configuration Property

**Namespace:**  [Microsoft.Dynamics.Retail.Ecommerce.Sdk.Core.Controllers](microsoft-dynamics-retail-ecommerce-sdk-core-controllers-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Retail.Ecommerce.Sdk.Core (in Microsoft.Dynamics.Retail.Ecommerce.Sdk.Core.dll)

## Syntax

``` vb
'Declaration
Protected ReadOnly Property Configuration As IConfiguration
    Get
'Usage
Dim value As IConfiguration

value = Me.Configuration
```

``` csharp
protected IConfiguration Configuration { get; }
```

``` c++
protected:
property IConfiguration^ Configuration {
    IConfiguration^ get ();
}
```

#### Property Value

Type: [Microsoft.Dynamics.Retail.Ecommerce.Sdk.Core.Storefront.IConfiguration](iconfiguration-interface-microsoft-dynamics-retail-ecommerce-sdk-core-storefront.md)  

## See Also

#### Reference

[ControllerBase Class](controllerbase-class-microsoft-dynamics-retail-ecommerce-sdk-core-controllers.md)

[Microsoft.Dynamics.Retail.Ecommerce.Sdk.Core.Controllers Namespace](microsoft-dynamics-retail-ecommerce-sdk-core-controllers-namespace.md)

