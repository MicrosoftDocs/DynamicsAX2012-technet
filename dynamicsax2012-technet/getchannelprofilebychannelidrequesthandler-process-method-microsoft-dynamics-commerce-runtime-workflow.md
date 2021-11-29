---
title: GetChannelProfileByChannelIdRequestHandler.Process Method  (Microsoft.Dynamics.Commerce.Runtime.Workflow)
TOCTitle: Process Method
ms:assetid: M:Microsoft.Dynamics.Commerce.Runtime.Workflow.GetChannelProfileByChannelIdRequestHandler.Process(Microsoft.Dynamics.Commerce.Runtime.Messages.GetChannelProfileByChannelIdRequest)
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.workflow.getchannelprofilebychannelidrequesthandler.process(v=AX.60)
ms:contentKeyID: 62208127
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.Workflow.GetChannelProfileByChannelIdRequestHandler.Process
dev_langs:
- CSharp
- C++
- VB
---

# Process Method


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Executes the workflow to retrieve the channel's profile..

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.Workflow](microsoft-dynamics-commerce-runtime-workflow-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Workflow (in Microsoft.Dynamics.Commerce.Runtime.Workflow.dll)

## Syntax

``` vb
'Declaration
Protected Overrides Function Process ( _
    request As GetChannelProfileByChannelIdRequest _
) As GetChannelProfileByChannelIdResponse
'Usage
Dim request As GetChannelProfileByChannelIdRequest
Dim returnValue As GetChannelProfileByChannelIdResponse

returnValue = Me.Process(request)
```

``` csharp
protected override GetChannelProfileByChannelIdResponse Process(
    GetChannelProfileByChannelIdRequest request
)
```

``` c++
protected:
virtual GetChannelProfileByChannelIdResponse^ Process(
    GetChannelProfileByChannelIdRequest^ request
) override
```

#### Parameters

  - request  
    Type: [Microsoft.Dynamics.Commerce.Runtime.Messages.GetChannelProfileByChannelIdRequest](getchannelprofilebychannelidrequest-class-microsoft-dynamics-commerce-runtime-messages.md)  

#### Return Value

Type: [Microsoft.Dynamics.Commerce.Runtime.Messages.GetChannelProfileByChannelIdResponse](getchannelprofilebychannelidresponse-class-microsoft-dynamics-commerce-runtime-messages.md)  
The response.  

## See Also

#### Reference

[GetChannelProfileByChannelIdRequestHandler Class](getchannelprofilebychannelidrequesthandler-class-microsoft-dynamics-commerce-runtime-workflow.md)

[Microsoft.Dynamics.Commerce.Runtime.Workflow Namespace](microsoft-dynamics-commerce-runtime-workflow-namespace.md)

