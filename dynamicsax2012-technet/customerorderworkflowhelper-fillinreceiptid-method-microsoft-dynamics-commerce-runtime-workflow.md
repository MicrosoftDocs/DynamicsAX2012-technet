---
title: CustomerOrderWorkflowHelper.FillInReceiptId Method  (Microsoft.Dynamics.Commerce.Runtime.Workflow)
TOCTitle: FillInReceiptId Method
ms:assetid: M:Microsoft.Dynamics.Commerce.Runtime.Workflow.CustomerOrderWorkflowHelper.FillInReceiptId(Microsoft.Dynamics.Commerce.Runtime.RequestContext,Microsoft.Dynamics.Commerce.Runtime.DataModel.SalesTransaction,System.String)
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.workflow.customerorderworkflowhelper.fillinreceiptid(v=AX.60)
ms:contentKeyID: 65322392
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.Workflow.CustomerOrderWorkflowHelper.FillInReceiptId
dev_langs:
- CSharp
- C++
- VB
---

# FillInReceiptId Method


[!INCLUDE[archive-banner](includes/archive-banner.md)]

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.Workflow](microsoft-dynamics-commerce-runtime-workflow-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Workflow (in Microsoft.Dynamics.Commerce.Runtime.Workflow.dll)

## Syntax

``` vb
'Declaration
Public Shared Function FillInReceiptId ( _
    context As RequestContext, _
    salesTransaction As SalesTransaction, _
    receiptNumberSequence As String _
) As SalesTransaction
'Usage
Dim context As RequestContext
Dim salesTransaction As SalesTransaction
Dim receiptNumberSequence As String
Dim returnValue As SalesTransaction

returnValue = CustomerOrderWorkflowHelper.FillInReceiptId(context, _
    salesTransaction, receiptNumberSequence)
```

``` csharp
public static SalesTransaction FillInReceiptId(
    RequestContext context,
    SalesTransaction salesTransaction,
    string receiptNumberSequence
)
```

``` c++
public:
static SalesTransaction^ FillInReceiptId(
    RequestContext^ context, 
    SalesTransaction^ salesTransaction, 
    String^ receiptNumberSequence
)
```

#### Parameters

  - context  
    Type: [Microsoft.Dynamics.Commerce.Runtime.RequestContext](requestcontext-class-microsoft-dynamics-commerce-runtime.md)  

<!-- end list -->

  - salesTransaction  
    Type: [Microsoft.Dynamics.Commerce.Runtime.DataModel.SalesTransaction](salestransaction-class-microsoft-dynamics-commerce-runtime-datamodel.md)  

<!-- end list -->

  - receiptNumberSequence  
    Type: [System.String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\))  

#### Return Value

Type: [Microsoft.Dynamics.Commerce.Runtime.DataModel.SalesTransaction](salestransaction-class-microsoft-dynamics-commerce-runtime-datamodel.md)  

## See Also

#### Reference

[CustomerOrderWorkflowHelper Class](customerorderworkflowhelper-class-microsoft-dynamics-commerce-runtime-workflow.md)

[Microsoft.Dynamics.Commerce.Runtime.Workflow Namespace](microsoft-dynamics-commerce-runtime-workflow-namespace.md)

