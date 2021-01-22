---
title: CartWorkflowHelper.GeneratePermanentTransactionId Method  (Microsoft.Dynamics.Commerce.Runtime.Workflow)
TOCTitle: GeneratePermanentTransactionId Method
ms:assetid: M:Microsoft.Dynamics.Commerce.Runtime.Workflow.CartWorkflowHelper.GeneratePermanentTransactionId(Microsoft.Dynamics.Commerce.Runtime.DataModel.SalesTransaction,Microsoft.Dynamics.Commerce.Runtime.RequestContext)
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.workflow.cartworkflowhelper.generatepermanenttransactionid(v=AX.60)
ms:contentKeyID: 62212514
author: Khairunj
ms.author: daxcpft
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.Workflow.CartWorkflowHelper.GeneratePermanentTransactionId
dev_langs:
- CSharp
- C++
- VB
---

# GeneratePermanentTransactionId Method

Generates a new permanent transaction id formatted as "StoreId-TerminalId-SequenceNumber".

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.Workflow](microsoft-dynamics-commerce-runtime-workflow-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Workflow (in Microsoft.Dynamics.Commerce.Runtime.Workflow.dll)

## Syntax

``` vb
'Declaration
Public Shared Function GeneratePermanentTransactionId ( _
    transaction As SalesTransaction, _
    context As RequestContext _
) As String
'Usage
Dim transaction As SalesTransaction
Dim context As RequestContext
Dim returnValue As String

returnValue = CartWorkflowHelper.GeneratePermanentTransactionId(transaction, _
    context)
```

``` csharp
public static string GeneratePermanentTransactionId(
    SalesTransaction transaction,
    RequestContext context
)
```

``` c++
public:
static String^ GeneratePermanentTransactionId(
    SalesTransaction^ transaction, 
    RequestContext^ context
)
```

#### Parameters

  - transaction  
    Type: [Microsoft.Dynamics.Commerce.Runtime.DataModel.SalesTransaction](salestransaction-class-microsoft-dynamics-commerce-runtime-datamodel.md)  

<!-- end list -->

  - context  
    Type: [Microsoft.Dynamics.Commerce.Runtime.RequestContext](requestcontext-class-microsoft-dynamics-commerce-runtime.md)  

#### Return Value

Type: [System.String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\))  
If the current channel type is retail store, returns a generated transaction id formatted as "StoreId-TerminalId-SequenceNumber"; otherwise, returns the existing transaction id.  

## See Also

#### Reference

[CartWorkflowHelper Class](cartworkflowhelper-class-microsoft-dynamics-commerce-runtime-workflow.md)

[Microsoft.Dynamics.Commerce.Runtime.Workflow Namespace](microsoft-dynamics-commerce-runtime-workflow-namespace.md)

