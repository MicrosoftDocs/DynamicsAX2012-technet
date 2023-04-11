---
title: VerifyProductExistenceRequestHandler Class (Microsoft.Dynamics.Commerce.Runtime.Workflow)
TOCTitle: VerifyProductExistenceRequestHandler Class
ms:assetid: T:Microsoft.Dynamics.Commerce.Runtime.Workflow.VerifyProductExistenceRequestHandler
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.workflow.verifyproductexistencerequesthandler(v=AX.60)
ms:contentKeyID: 62210992
author: tonyafehr
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.Workflow.VerifyProductExistenceRequestHandler
dev_langs:
- CSharp
- C++
- VB
---

# VerifyProductExistenceRequestHandler Class


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Handles request to verify products existence.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.Workflow](microsoft-dynamics-commerce-runtime-workflow-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Workflow (in Microsoft.Dynamics.Commerce.Runtime.Workflow.dll)

## Syntax

``` vb
'Declaration
Public Class VerifyProductExistenceRequestHandler _
    Inherits WorkflowRequestHandler(Of VerifyProductExistenceRequest, VerifyProductExistenceResponse)
'Usage
Dim instance As VerifyProductExistenceRequestHandler
```

``` csharp
public class VerifyProductExistenceRequestHandler : WorkflowRequestHandler<VerifyProductExistenceRequest, VerifyProductExistenceResponse>
```

``` c++
public ref class VerifyProductExistenceRequestHandler : public WorkflowRequestHandler<VerifyProductExistenceRequest^, VerifyProductExistenceResponse^>
```

## Inheritance Hierarchy

[System.Object](https://technet.microsoft.com/library/e5kfa45b\(v=ax.60\))  
  [Microsoft.Dynamics.Commerce.Runtime.Workflow.WorkflowRequestHandler](workflowrequesthandler-trequest-tresponse-class-microsoft-dynamics-commerce-runtime-workflow.md)\<[VerifyProductExistenceRequest](verifyproductexistencerequest-class-microsoft-dynamics-commerce-runtime-messages.md), [VerifyProductExistenceResponse](verifyproductexistenceresponse-class-microsoft-dynamics-commerce-runtime-messages.md)\>  
    Microsoft.Dynamics.Commerce.Runtime.Workflow.VerifyProductExistenceRequestHandler  

## Thread Safety

Any public static (Shared in Visual Basic) members of this type are thread safe. Any instance members are not guaranteed to be thread safe.

## See Also

#### Reference

[Microsoft.Dynamics.Commerce.Runtime.Workflow Namespace](microsoft-dynamics-commerce-runtime-workflow-namespace.md)

