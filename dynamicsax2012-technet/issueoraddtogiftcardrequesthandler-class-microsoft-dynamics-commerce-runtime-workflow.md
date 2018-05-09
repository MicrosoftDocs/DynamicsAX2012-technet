---
title: IssueOrAddToGiftCardRequestHandler Class (Microsoft.Dynamics.Commerce.Runtime.Workflow)
TOCTitle: IssueOrAddToGiftCardRequestHandler Class
ms:assetid: T:Microsoft.Dynamics.Commerce.Runtime.Workflow.IssueOrAddToGiftCardRequestHandler
ms:mtpsurl: https://technet.microsoft.com/en-us/library/microsoft.dynamics.commerce.runtime.workflow.issueoraddtogiftcardrequesthandler(v=AX.60)
ms:contentKeyID: 62212065
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.Workflow.IssueOrAddToGiftCardRequestHandler
dev_langs:
- CSharp
- C++
- VB
---

# IssueOrAddToGiftCardRequestHandler Class

Handles workflow to issue or add balance to gift card.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.Workflow](microsoft-dynamics-commerce-runtime-workflow-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Workflow (in Microsoft.Dynamics.Commerce.Runtime.Workflow.dll)

## Syntax

``` vb
'Declaration
Public NotInheritable Class IssueOrAddToGiftCardRequestHandler _
    Inherits WorkflowRequestHandler(Of IssueOrAddToGiftCardRequest, IssueOrAddToGiftCardResponse)
'Usage
Dim instance As IssueOrAddToGiftCardRequestHandler
```

``` csharp
public sealed class IssueOrAddToGiftCardRequestHandler : WorkflowRequestHandler<IssueOrAddToGiftCardRequest, IssueOrAddToGiftCardResponse>
```

``` c++
public ref class IssueOrAddToGiftCardRequestHandler sealed : public WorkflowRequestHandler<IssueOrAddToGiftCardRequest^, IssueOrAddToGiftCardResponse^>
```

## Inheritance Hierarchy

[System.Object](https://technet.microsoft.com/en-us/library/e5kfa45b\(v=ax.60\))  
  [Microsoft.Dynamics.Commerce.Runtime.Workflow.WorkflowRequestHandler](workflowrequesthandler-trequest-tresponse-class-microsoft-dynamics-commerce-runtime-workflow.md)\<[IssueOrAddToGiftCardRequest](issueoraddtogiftcardrequest-class-microsoft-dynamics-commerce-runtime-messages.md), [IssueOrAddToGiftCardResponse](issueoraddtogiftcardresponse-class-microsoft-dynamics-commerce-runtime-messages.md)\>  
    Microsoft.Dynamics.Commerce.Runtime.Workflow.IssueOrAddToGiftCardRequestHandler  

## Thread Safety

Any public static (Shared in Visual Basic) members of this type are thread safe. Any instance members are not guaranteed to be thread safe.

## See Also

#### Reference

[Microsoft.Dynamics.Commerce.Runtime.Workflow Namespace](microsoft-dynamics-commerce-runtime-workflow-namespace.md)

