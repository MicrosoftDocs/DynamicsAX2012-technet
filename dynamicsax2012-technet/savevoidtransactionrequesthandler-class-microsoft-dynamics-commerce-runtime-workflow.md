---
title: SaveVoidTransactionRequestHandler Class (Microsoft.Dynamics.Commerce.Runtime.Workflow)
TOCTitle: SaveVoidTransactionRequestHandler Class
ms:assetid: T:Microsoft.Dynamics.Commerce.Runtime.Workflow.SaveVoidTransactionRequestHandler
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.workflow.savevoidtransactionrequesthandler(v=AX.60)
ms:contentKeyID: 62208563
author: tonyafehr
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.Workflow.SaveVoidTransactionRequestHandler
dev_langs:
- CSharp
- C++
- VB
---

# SaveVoidTransactionRequestHandler Class


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Handler for submit sales transaction request.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.Workflow](microsoft-dynamics-commerce-runtime-workflow-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Workflow (in Microsoft.Dynamics.Commerce.Runtime.Workflow.dll)

## Syntax

``` vb
'Declaration
Public NotInheritable Class SaveVoidTransactionRequestHandler _
    Inherits WorkflowRequestHandler(Of SaveVoidTransactionRequest, SaveVoidTransactionResponse)
'Usage
Dim instance As SaveVoidTransactionRequestHandler
```

``` csharp
public sealed class SaveVoidTransactionRequestHandler : WorkflowRequestHandler<SaveVoidTransactionRequest, SaveVoidTransactionResponse>
```

``` c++
public ref class SaveVoidTransactionRequestHandler sealed : public WorkflowRequestHandler<SaveVoidTransactionRequest^, SaveVoidTransactionResponse^>
```

## Inheritance Hierarchy

[System.Object](https://technet.microsoft.com/library/e5kfa45b\(v=ax.60\))  
  [Microsoft.Dynamics.Commerce.Runtime.Workflow.WorkflowRequestHandler](workflowrequesthandler-trequest-tresponse-class-microsoft-dynamics-commerce-runtime-workflow.md)\<[SaveVoidTransactionRequest](savevoidtransactionrequest-class-microsoft-dynamics-commerce-runtime-messages.md), [SaveVoidTransactionResponse](savevoidtransactionresponse-class-microsoft-dynamics-commerce-runtime-messages.md)\>  
    Microsoft.Dynamics.Commerce.Runtime.Workflow.SaveVoidTransactionRequestHandler  

## Thread Safety

Any public static (Shared in Visual Basic) members of this type are thread safe. Any instance members are not guaranteed to be thread safe.

## See Also

#### Reference

[Microsoft.Dynamics.Commerce.Runtime.Workflow Namespace](microsoft-dynamics-commerce-runtime-workflow-namespace.md)

