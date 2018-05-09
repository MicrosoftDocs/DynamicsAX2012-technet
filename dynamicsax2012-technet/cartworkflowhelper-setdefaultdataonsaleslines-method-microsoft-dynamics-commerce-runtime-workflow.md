---
title: CartWorkflowHelper.SetDefaultDataOnSalesLines Method  (Microsoft.Dynamics.Commerce.Runtime.Workflow)
TOCTitle: SetDefaultDataOnSalesLines Method
ms:assetid: M:Microsoft.Dynamics.Commerce.Runtime.Workflow.CartWorkflowHelper.SetDefaultDataOnSalesLines(Microsoft.Dynamics.Commerce.Runtime.RequestContext,System.Collections.Generic.IEnumerable{Microsoft.Dynamics.Commerce.Runtime.DataModel.SalesLine})
ms:mtpsurl: https://technet.microsoft.com/en-us/library/microsoft.dynamics.commerce.runtime.workflow.cartworkflowhelper.setdefaultdataonsaleslines(v=AX.60)
ms:contentKeyID: 62215189
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.Workflow.CartWorkflowHelper.SetDefaultDataOnSalesLines
dev_langs:
- CSharp
- C++
- VB
---

# SetDefaultDataOnSalesLines Method

Sets the default data on sales lines.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.Workflow](microsoft-dynamics-commerce-runtime-workflow-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Workflow (in Microsoft.Dynamics.Commerce.Runtime.Workflow.dll)

## Syntax

``` vb
'Declaration
Public Shared Sub SetDefaultDataOnSalesLines ( _
    context As RequestContext, _
    salesLines As IEnumerable(Of SalesLine) _
)
'Usage
Dim context As RequestContext
Dim salesLines As IEnumerable(Of SalesLine)

CartWorkflowHelper.SetDefaultDataOnSalesLines(context, _
    salesLines)
```

``` csharp
public static void SetDefaultDataOnSalesLines(
    RequestContext context,
    IEnumerable<SalesLine> salesLines
)
```

``` c++
public:
static void SetDefaultDataOnSalesLines(
    RequestContext^ context, 
    IEnumerable<SalesLine^>^ salesLines
)
```

#### Parameters

  - context  
    Type: [Microsoft.Dynamics.Commerce.Runtime.RequestContext](requestcontext-class-microsoft-dynamics-commerce-runtime.md)  

<!-- end list -->

  - salesLines  
    Type: [System.Collections.Generic.IEnumerable](https://technet.microsoft.com/en-us/library/9eekhta0\(v=ax.60\))\<[SalesLine](salesline-class-microsoft-dynamics-commerce-runtime-datamodel.md)\>  

## See Also

#### Reference

[CartWorkflowHelper Class](cartworkflowhelper-class-microsoft-dynamics-commerce-runtime-workflow.md)

[Microsoft.Dynamics.Commerce.Runtime.Workflow Namespace](microsoft-dynamics-commerce-runtime-workflow-namespace.md)

