---
title: GetBarcodeRequestHandler Class (Microsoft.Dynamics.Commerce.Runtime.Workflow)
TOCTitle: GetBarcodeRequestHandler Class
ms:assetid: T:Microsoft.Dynamics.Commerce.Runtime.Workflow.GetBarcodeRequestHandler
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.workflow.getbarcoderequesthandler(v=AX.60)
ms:contentKeyID: 62213886
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.Workflow.GetBarcodeRequestHandler
dev_langs:
- CSharp
- C++
- VB
---

# GetBarcodeRequestHandler Class


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Workflow class helps to retrieve the Barcode details.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.Workflow](microsoft-dynamics-commerce-runtime-workflow-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Workflow (in Microsoft.Dynamics.Commerce.Runtime.Workflow.dll)

## Syntax

``` vb
'Declaration
Public Class GetBarcodeRequestHandler _
    Inherits WorkflowRequestHandler(Of GetBarcodeRequest, GetBarcodeResponse)
'Usage
Dim instance As GetBarcodeRequestHandler
```

``` csharp
public class GetBarcodeRequestHandler : WorkflowRequestHandler<GetBarcodeRequest, GetBarcodeResponse>
```

``` c++
public ref class GetBarcodeRequestHandler : public WorkflowRequestHandler<GetBarcodeRequest^, GetBarcodeResponse^>
```

## Inheritance Hierarchy

[System.Object](https://technet.microsoft.com/library/e5kfa45b\(v=ax.60\))  
  [Microsoft.Dynamics.Commerce.Runtime.Workflow.WorkflowRequestHandler](workflowrequesthandler-trequest-tresponse-class-microsoft-dynamics-commerce-runtime-workflow.md)\<[GetBarcodeRequest](getbarcoderequest-class-microsoft-dynamics-commerce-runtime-messages.md), [GetBarcodeResponse](getbarcoderesponse-class-microsoft-dynamics-commerce-runtime-messages.md)\>  
    Microsoft.Dynamics.Commerce.Runtime.Workflow.GetBarcodeRequestHandler  

## Thread Safety

Any public static (Shared in Visual Basic) members of this type are thread safe. Any instance members are not guaranteed to be thread safe.

## See Also

#### Reference

[Microsoft.Dynamics.Commerce.Runtime.Workflow Namespace](microsoft-dynamics-commerce-runtime-workflow-namespace.md)

