---
title: AuthenticateDevicePartialRequestHandler.Process Method  (Microsoft.Dynamics.Commerce.Runtime.Workflow)
TOCTitle: Process Method
ms:assetid: M:Microsoft.Dynamics.Commerce.Runtime.Workflow.AuthenticateDevicePartialRequestHandler.Process(Microsoft.Dynamics.Commerce.Runtime.Messages.AuthenticateDevicePartialRequest)
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.workflow.authenticatedevicepartialrequesthandler.process(v=AX.60)
ms:contentKeyID: 62213313
author: tonyafehr
ms.author: daxcpft
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.Workflow.AuthenticateDevicePartialRequestHandler.Process
dev_langs:
- CSharp
- C++
- VB
---

# Process Method


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Executes the workflow to authenticate the device.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.Workflow](microsoft-dynamics-commerce-runtime-workflow-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Workflow (in Microsoft.Dynamics.Commerce.Runtime.Workflow.dll)

## Syntax

``` vb
'Declaration
Protected Overrides Function Process ( _
    request As AuthenticateDevicePartialRequest _
) As AuthenticateDevicePartialResponse
'Usage
Dim request As AuthenticateDevicePartialRequest
Dim returnValue As AuthenticateDevicePartialResponse

returnValue = Me.Process(request)
```

``` csharp
protected override AuthenticateDevicePartialResponse Process(
    AuthenticateDevicePartialRequest request
)
```

``` c++
protected:
virtual AuthenticateDevicePartialResponse^ Process(
    AuthenticateDevicePartialRequest^ request
) override
```

#### Parameters

  - request  
    Type: [Microsoft.Dynamics.Commerce.Runtime.Messages.AuthenticateDevicePartialRequest](authenticatedevicepartialrequest-class-microsoft-dynamics-commerce-runtime-messages.md)  

#### Return Value

Type: [Microsoft.Dynamics.Commerce.Runtime.Messages.AuthenticateDevicePartialResponse](authenticatedevicepartialresponse-class-microsoft-dynamics-commerce-runtime-messages.md)  
The response.  

## See Also

#### Reference

[AuthenticateDevicePartialRequestHandler Class](authenticatedevicepartialrequesthandler-class-microsoft-dynamics-commerce-runtime-workflow.md)

[Microsoft.Dynamics.Commerce.Runtime.Workflow Namespace](microsoft-dynamics-commerce-runtime-workflow-namespace.md)

