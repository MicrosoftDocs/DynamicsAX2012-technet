---
title: CartWorkflowHelper.GetTenderLinesForSalesOrder Method  (Microsoft.Dynamics.Commerce.Runtime.Workflow)
TOCTitle: GetTenderLinesForSalesOrder Method
ms:assetid: M:Microsoft.Dynamics.Commerce.Runtime.Workflow.CartWorkflowHelper.GetTenderLinesForSalesOrder(Microsoft.Dynamics.Commerce.Runtime.RequestContext,Microsoft.Dynamics.Commerce.Runtime.Messages.GetReceiptRequest)
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.workflow.cartworkflowhelper.gettenderlinesforsalesorder(v=AX.60)
ms:contentKeyID: 62209348
author: tonyafehr
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.Workflow.CartWorkflowHelper.GetTenderLinesForSalesOrder
dev_langs:
- CSharp
- C++
- VB
---

# GetTenderLinesForSalesOrder Method


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Gets the details of the transactions that are to be present on the receipt.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.Workflow](microsoft-dynamics-commerce-runtime-workflow-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Workflow (in Microsoft.Dynamics.Commerce.Runtime.Workflow.dll)

## Syntax

``` vb
'Declaration
Public Shared Function GetTenderLinesForSalesOrder ( _
    context As RequestContext, _
    request As GetReceiptRequest _
) As ReadOnlyCollection(Of TenderLine)
'Usage
Dim context As RequestContext
Dim request As GetReceiptRequest
Dim returnValue As ReadOnlyCollection(Of TenderLine)

returnValue = CartWorkflowHelper.GetTenderLinesForSalesOrder(context, _
    request)
```

``` csharp
public static ReadOnlyCollection<TenderLine> GetTenderLinesForSalesOrder(
    RequestContext context,
    GetReceiptRequest request
)
```

``` c++
public:
static ReadOnlyCollection<TenderLine^>^ GetTenderLinesForSalesOrder(
    RequestContext^ context, 
    GetReceiptRequest^ request
)
```

#### Parameters

  - context  
    Type: [Microsoft.Dynamics.Commerce.Runtime.RequestContext](requestcontext-class-microsoft-dynamics-commerce-runtime.md)  

<!-- end list -->

  - request  
    Type: [Microsoft.Dynamics.Commerce.Runtime.Messages.GetReceiptRequest](getreceiptrequest-class-microsoft-dynamics-commerce-runtime-messages.md)  

#### Return Value

Type: [System.Collections.ObjectModel.ReadOnlyCollection](https://technet.microsoft.com/library/ms132474\(v=ax.60\))\<[TenderLine](tenderline-class-microsoft-dynamics-commerce-runtime-datamodel.md)\>  
Returns the sales order or the object that contains all the information of the receipt.  

## See Also

#### Reference

[CartWorkflowHelper Class](cartworkflowhelper-class-microsoft-dynamics-commerce-runtime-workflow.md)

[Microsoft.Dynamics.Commerce.Runtime.Workflow Namespace](microsoft-dynamics-commerce-runtime-workflow-namespace.md)

