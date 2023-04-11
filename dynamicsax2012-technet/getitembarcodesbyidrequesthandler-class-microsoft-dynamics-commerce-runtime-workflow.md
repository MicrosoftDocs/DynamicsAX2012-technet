---
title: GetItemBarcodesByIdRequestHandler Class (Microsoft.Dynamics.Commerce.Runtime.Workflow)
TOCTitle: GetItemBarcodesByIdRequestHandler Class
ms:assetid: T:Microsoft.Dynamics.Commerce.Runtime.Workflow.GetItemBarcodesByIdRequestHandler
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.workflow.getitembarcodesbyidrequesthandler(v=AX.60)
ms:contentKeyID: 62205131
author: tonyafehr
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.Workflow.GetItemBarcodesByIdRequestHandler
dev_langs:
- CSharp
- C++
- VB
---

# GetItemBarcodesByIdRequestHandler Class


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Handles workflow for GetBarcodesById.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.Workflow](microsoft-dynamics-commerce-runtime-workflow-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Workflow (in Microsoft.Dynamics.Commerce.Runtime.Workflow.dll)

## Syntax

``` vb
'Declaration
Public Class GetItemBarcodesByIdRequestHandler _
    Inherits WorkflowRequestHandler(Of GetItemBarcodesByIdRequest, GetItemBarcodesByIdResponse)
'Usage
Dim instance As GetItemBarcodesByIdRequestHandler
```

``` csharp
public class GetItemBarcodesByIdRequestHandler : WorkflowRequestHandler<GetItemBarcodesByIdRequest, GetItemBarcodesByIdResponse>
```

``` c++
public ref class GetItemBarcodesByIdRequestHandler : public WorkflowRequestHandler<GetItemBarcodesByIdRequest^, GetItemBarcodesByIdResponse^>
```

## Inheritance Hierarchy

[System.Object](https://technet.microsoft.com/library/e5kfa45b\(v=ax.60\))  
  [Microsoft.Dynamics.Commerce.Runtime.Workflow.WorkflowRequestHandler](workflowrequesthandler-trequest-tresponse-class-microsoft-dynamics-commerce-runtime-workflow.md)\<[GetItemBarcodesByIdRequest](getitembarcodesbyidrequest-class-microsoft-dynamics-commerce-runtime-messages.md), [GetItemBarcodesByIdResponse](getitembarcodesbyidresponse-class-microsoft-dynamics-commerce-runtime-messages.md)\>  
    Microsoft.Dynamics.Commerce.Runtime.Workflow.GetItemBarcodesByIdRequestHandler  

## Thread Safety

Any public static (Shared in Visual Basic) members of this type are thread safe. Any instance members are not guaranteed to be thread safe.

## See Also

#### Reference

[Microsoft.Dynamics.Commerce.Runtime.Workflow Namespace](microsoft-dynamics-commerce-runtime-workflow-namespace.md)

