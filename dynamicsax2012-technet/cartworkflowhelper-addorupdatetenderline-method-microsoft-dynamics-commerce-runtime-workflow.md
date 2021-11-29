---
title: CartWorkflowHelper.AddOrUpdateTenderLine Method  (Microsoft.Dynamics.Commerce.Runtime.Workflow)
TOCTitle: AddOrUpdateTenderLine Method
ms:assetid: M:Microsoft.Dynamics.Commerce.Runtime.Workflow.CartWorkflowHelper.AddOrUpdateTenderLine(Microsoft.Dynamics.Commerce.Runtime.RequestContext,Microsoft.Dynamics.Commerce.Runtime.DataModel.TenderLineBase)
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.workflow.cartworkflowhelper.addorupdatetenderline(v=AX.60)
ms:contentKeyID: 65321269
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.Workflow.CartWorkflowHelper.AddOrUpdateTenderLine
dev_langs:
- CSharp
- C++
- VB
---

# AddOrUpdateTenderLine Method


[!INCLUDE[archive-banner](includes/archive-banner.md)]

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.Workflow](microsoft-dynamics-commerce-runtime-workflow-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Workflow (in Microsoft.Dynamics.Commerce.Runtime.Workflow.dll)

## Syntax

``` vb
'Declaration
Public Shared Sub AddOrUpdateTenderLine ( _
    context As RequestContext, _
    updatedTenderLine As TenderLineBase _
)
'Usage
Dim context As RequestContext
Dim updatedTenderLine As TenderLineBase

CartWorkflowHelper.AddOrUpdateTenderLine(context, _
    updatedTenderLine)
```

``` csharp
public static void AddOrUpdateTenderLine(
    RequestContext context,
    TenderLineBase updatedTenderLine
)
```

``` c++
public:
static void AddOrUpdateTenderLine(
    RequestContext^ context, 
    TenderLineBase^ updatedTenderLine
)
```

#### Parameters

  - context  
    Type: [Microsoft.Dynamics.Commerce.Runtime.RequestContext](requestcontext-class-microsoft-dynamics-commerce-runtime.md)  

<!-- end list -->

  - updatedTenderLine  
    Type: [Microsoft.Dynamics.Commerce.Runtime.DataModel.TenderLineBase](tenderlinebase-class-microsoft-dynamics-commerce-runtime-datamodel.md)  

## See Also

#### Reference

[CartWorkflowHelper Class](cartworkflowhelper-class-microsoft-dynamics-commerce-runtime-workflow.md)

[Microsoft.Dynamics.Commerce.Runtime.Workflow Namespace](microsoft-dynamics-commerce-runtime-workflow-namespace.md)

