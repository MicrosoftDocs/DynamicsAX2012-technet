---
title: FeatureNotSupportedRequestHandler.Execute Method  (Microsoft.Dynamics.Commerce.Runtime.Services.WindowsPhone)
TOCTitle: Execute Method
ms:assetid: M:Microsoft.Dynamics.Commerce.Runtime.Services.WindowsPhone.FeatureNotSupportedRequestHandler.Execute(Microsoft.Dynamics.Commerce.Runtime.Messages.Request)
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.services.windowsphone.featurenotsupportedrequesthandler.execute(v=AX.60)
ms:contentKeyID: 65320105
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.Services.WindowsPhone.FeatureNotSupportedRequestHandler.Execute
dev_langs:
- CSharp
- C++
- VB
---

# Execute Method


[!INCLUDE[archive-banner](includes/archive-banner.md)]

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.Services.WindowsPhone](microsoft-dynamics-commerce-runtime-services-windowsphone-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Services.WindowsPhone (in Microsoft.Dynamics.Commerce.Runtime.Services.WindowsPhone.dll)

## Syntax

``` vb
'Declaration
Public Function Execute ( _
    request As Request _
) As Response
'Usage
Dim instance As FeatureNotSupportedRequestHandler
Dim request As Request
Dim returnValue As Response

returnValue = instance.Execute(request)
```

``` csharp
public Response Execute(
    Request request
)
```

``` c++
public:
virtual Response^ Execute(
    Request^ request
) sealed
```

#### Parameters

  - request  
    Type: [Microsoft.Dynamics.Commerce.Runtime.Messages.Request](request-class-microsoft-dynamics-commerce-runtime-messages.md)  

#### Return Value

Type: [Microsoft.Dynamics.Commerce.Runtime.Messages.Response](response-class-microsoft-dynamics-commerce-runtime-messages.md)  

#### Implements

[IRequestHandler.Execute(Request)](irequesthandler-execute-method-microsoft-dynamics-commerce-runtime-workflow.md)  

## See Also

#### Reference

[FeatureNotSupportedRequestHandler Class](featurenotsupportedrequesthandler-class-microsoft-dynamics-commerce-runtime-services-windowsphone.md)

[Microsoft.Dynamics.Commerce.Runtime.Services.WindowsPhone Namespace](microsoft-dynamics-commerce-runtime-services-windowsphone-namespace.md)

