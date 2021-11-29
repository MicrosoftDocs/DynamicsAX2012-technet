---
title: CartWorkflowHelper.GetReceiptTypes Method  (Microsoft.Dynamics.Commerce.Runtime.Workflow)
TOCTitle: GetReceiptTypes Method
ms:assetid: M:Microsoft.Dynamics.Commerce.Runtime.Workflow.CartWorkflowHelper.GetReceiptTypes(Microsoft.Dynamics.Commerce.Runtime.DataModel.SalesTransaction,Microsoft.Dynamics.Commerce.Runtime.RequestContext,Microsoft.Dynamics.Commerce.Runtime.Messages.GetReceiptRequest)
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.workflow.cartworkflowhelper.getreceipttypes(v=AX.60)
ms:contentKeyID: 62214554
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.Workflow.CartWorkflowHelper.GetReceiptTypes
dev_langs:
- CSharp
- C++
- VB
---

# GetReceiptTypes Method


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Gets the types of receipts that are to be printed for a transaction.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.Workflow](microsoft-dynamics-commerce-runtime-workflow-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Workflow (in Microsoft.Dynamics.Commerce.Runtime.Workflow.dll)

## Syntax

``` vb
'Declaration
Public Shared Function GetReceiptTypes ( _
    salesOrder As SalesTransaction, _
    context As RequestContext, _
    request As GetReceiptRequest _
) As ReadOnlyCollection(Of ReceiptType)
'Usage
Dim salesOrder As SalesTransaction
Dim context As RequestContext
Dim request As GetReceiptRequest
Dim returnValue As ReadOnlyCollection(Of ReceiptType)

returnValue = CartWorkflowHelper.GetReceiptTypes(salesOrder, _
    context, request)
```

``` csharp
public static ReadOnlyCollection<ReceiptType> GetReceiptTypes(
    SalesTransaction salesOrder,
    RequestContext context,
    GetReceiptRequest request
)
```

``` c++
public:
static ReadOnlyCollection<ReceiptType>^ GetReceiptTypes(
    SalesTransaction^ salesOrder, 
    RequestContext^ context, 
    GetReceiptRequest^ request
)
```

#### Parameters

  - salesOrder  
    Type: [Microsoft.Dynamics.Commerce.Runtime.DataModel.SalesTransaction](salestransaction-class-microsoft-dynamics-commerce-runtime-datamodel.md)  

<!-- end list -->

  - context  
    Type: [Microsoft.Dynamics.Commerce.Runtime.RequestContext](requestcontext-class-microsoft-dynamics-commerce-runtime.md)  

<!-- end list -->

  - request  
    Type: [Microsoft.Dynamics.Commerce.Runtime.Messages.GetReceiptRequest](getreceiptrequest-class-microsoft-dynamics-commerce-runtime-messages.md)  

#### Return Value

Type: [System.Collections.ObjectModel.ReadOnlyCollection](https://technet.microsoft.com/library/ms132474\(v=ax.60\))\<[ReceiptType](receipttype-enumeration-microsoft-dynamics-commerce-runtime-datamodel.md)\>  
Returns the receipt types are will be printed.  

## See Also

#### Reference

[CartWorkflowHelper Class](cartworkflowhelper-class-microsoft-dynamics-commerce-runtime-workflow.md)

[Microsoft.Dynamics.Commerce.Runtime.Workflow Namespace](microsoft-dynamics-commerce-runtime-workflow-namespace.md)

