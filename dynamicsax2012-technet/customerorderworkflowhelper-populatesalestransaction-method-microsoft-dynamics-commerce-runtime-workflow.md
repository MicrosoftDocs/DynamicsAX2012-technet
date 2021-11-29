---
title: CustomerOrderWorkflowHelper.PopulateSalesTransaction Method  (Microsoft.Dynamics.Commerce.Runtime.Workflow)
TOCTitle: PopulateSalesTransaction Method
ms:assetid: M:Microsoft.Dynamics.Commerce.Runtime.Workflow.CustomerOrderWorkflowHelper.PopulateSalesTransaction(Microsoft.Dynamics.Commerce.Runtime.RequestContext,System.String,System.String)
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.workflow.customerorderworkflowhelper.populatesalestransaction(v=AX.60)
ms:contentKeyID: 62211717
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.Workflow.CustomerOrderWorkflowHelper.PopulateSalesTransaction
dev_langs:
- CSharp
- C++
- VB
---

# PopulateSalesTransaction Method


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Populates the sales transaction.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.Workflow](microsoft-dynamics-commerce-runtime-workflow-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Workflow (in Microsoft.Dynamics.Commerce.Runtime.Workflow.dll)

## Syntax

``` vb
'Declaration
Public Shared Sub PopulateSalesTransaction ( _
    context As RequestContext, _
    cartId As String, _
    email As String _
)
'Usage
Dim context As RequestContext
Dim cartId As String
Dim email As String

CustomerOrderWorkflowHelper.PopulateSalesTransaction(context, _
    cartId, email)
```

``` csharp
public static void PopulateSalesTransaction(
    RequestContext context,
    string cartId,
    string email
)
```

``` c++
public:
static void PopulateSalesTransaction(
    RequestContext^ context, 
    String^ cartId, 
    String^ email
)
```

#### Parameters

  - context  
    Type: [Microsoft.Dynamics.Commerce.Runtime.RequestContext](requestcontext-class-microsoft-dynamics-commerce-runtime.md)  

<!-- end list -->

  - cartId  
    Type: [System.String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\))  

<!-- end list -->

  - email  
    Type: [System.String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\))  

## See Also

#### Reference

[CustomerOrderWorkflowHelper Class](customerorderworkflowhelper-class-microsoft-dynamics-commerce-runtime-workflow.md)

[Microsoft.Dynamics.Commerce.Runtime.Workflow Namespace](microsoft-dynamics-commerce-runtime-workflow-namespace.md)

