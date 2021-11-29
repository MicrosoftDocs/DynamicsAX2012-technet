---
title: CartWorkflowHelper.LogAuditEntry Method  (Microsoft.Dynamics.Commerce.Runtime.Workflow)
TOCTitle: LogAuditEntry Method
ms:assetid: M:Microsoft.Dynamics.Commerce.Runtime.Workflow.CartWorkflowHelper.LogAuditEntry(Microsoft.Dynamics.Commerce.Runtime.RequestContext,System.String,System.String)
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.workflow.cartworkflowhelper.logauditentry(v=AX.60)
ms:contentKeyID: 65322009
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.Workflow.CartWorkflowHelper.LogAuditEntry
dev_langs:
- CSharp
- C++
- VB
---

# LogAuditEntry Method


[!INCLUDE[archive-banner](includes/archive-banner.md)]

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.Workflow](microsoft-dynamics-commerce-runtime-workflow-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Workflow (in Microsoft.Dynamics.Commerce.Runtime.Workflow.dll)

## Syntax

``` vb
'Declaration
Public Shared Sub LogAuditEntry ( _
    context As RequestContext, _
    source As String, _
    logEntry As String _
)
'Usage
Dim context As RequestContext
Dim source As String
Dim logEntry As String

CartWorkflowHelper.LogAuditEntry(context, source, _
    logEntry)
```

``` csharp
public static void LogAuditEntry(
    RequestContext context,
    string source,
    string logEntry
)
```

``` c++
public:
static void LogAuditEntry(
    RequestContext^ context, 
    String^ source, 
    String^ logEntry
)
```

#### Parameters

  - context  
    Type: [Microsoft.Dynamics.Commerce.Runtime.RequestContext](requestcontext-class-microsoft-dynamics-commerce-runtime.md)  

<!-- end list -->

  - source  
    Type: [System.String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\))  

<!-- end list -->

  - logEntry  
    Type: [System.String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\))  

## See Also

#### Reference

[CartWorkflowHelper Class](cartworkflowhelper-class-microsoft-dynamics-commerce-runtime-workflow.md)

[Microsoft.Dynamics.Commerce.Runtime.Workflow Namespace](microsoft-dynamics-commerce-runtime-workflow-namespace.md)

