---
title: SaveKitTransactionRequestHandler Class (Microsoft.Dynamics.Commerce.Runtime.Workflow)
TOCTitle: SaveKitTransactionRequestHandler Class
ms:assetid: T:Microsoft.Dynamics.Commerce.Runtime.Workflow.SaveKitTransactionRequestHandler
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.workflow.savekittransactionrequesthandler(v=AX.60)
ms:contentKeyID: 62202317
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.Workflow.SaveKitTransactionRequestHandler
dev_langs:
- CSharp
- C++
- VB
---

# SaveKitTransactionRequestHandler Class


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Save all incoming kit (disassembly) operation transactions.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.Workflow](microsoft-dynamics-commerce-runtime-workflow-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Workflow (in Microsoft.Dynamics.Commerce.Runtime.Workflow.dll)

## Syntax

``` vb
'Declaration
Public Class SaveKitTransactionRequestHandler _
    Inherits WorkflowRequestHandler(Of SaveKitTransactionRequest, SaveKitTransactionResponse)
'Usage
Dim instance As SaveKitTransactionRequestHandler
```

``` csharp
public class SaveKitTransactionRequestHandler : WorkflowRequestHandler<SaveKitTransactionRequest, SaveKitTransactionResponse>
```

``` c++
public ref class SaveKitTransactionRequestHandler : public WorkflowRequestHandler<SaveKitTransactionRequest^, SaveKitTransactionResponse^>
```

## Inheritance Hierarchy

[System.Object](https://technet.microsoft.com/library/e5kfa45b\(v=ax.60\))  
  [Microsoft.Dynamics.Commerce.Runtime.Workflow.WorkflowRequestHandler](workflowrequesthandler-trequest-tresponse-class-microsoft-dynamics-commerce-runtime-workflow.md)\<[SaveKitTransactionRequest](savekittransactionrequest-class-microsoft-dynamics-commerce-runtime-messages.md), [SaveKitTransactionResponse](savekittransactionresponse-class-microsoft-dynamics-commerce-runtime-messages.md)\>  
    Microsoft.Dynamics.Commerce.Runtime.Workflow.SaveKitTransactionRequestHandler  

## Thread Safety

Any public static (Shared in Visual Basic) members of this type are thread safe. Any instance members are not guaranteed to be thread safe.

## See Also

#### Reference

[Microsoft.Dynamics.Commerce.Runtime.Workflow Namespace](microsoft-dynamics-commerce-runtime-workflow-namespace.md)

