---
title: CustomerOrderWorkflowHelper.HandlePayments Method (RequestContext, SalesTransaction, TokenizedPaymentCard, String) (Microsoft.Dynamics.Commerce.Runtime.Workflow)
TOCTitle: HandlePayments Method (RequestContext, SalesTransaction, TokenizedPaymentCard, String)
ms:assetid: M:Microsoft.Dynamics.Commerce.Runtime.Workflow.CustomerOrderWorkflowHelper.HandlePayments(Microsoft.Dynamics.Commerce.Runtime.RequestContext,Microsoft.Dynamics.Commerce.Runtime.DataModel.SalesTransaction,Microsoft.Dynamics.Commerce.Runtime.DataModel.TokenizedPaymentCard,System.String)
ms:mtpsurl: https://technet.microsoft.com/en-us/library/microsoft.dynamics.commerce.runtime.workflow.customerorderworkflowhelper.handlepayments(v=AX.60)
ms:contentKeyID: 65319063
ms.date: 05/18/2015
mtps_version: v=AX.60
dev_langs:
- vb
- csharp
- c++
---

# HandlePayments Method (RequestContext, SalesTransaction, TokenizedPaymentCard, String)

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.Workflow](microsoft-dynamics-commerce-runtime-workflow-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Workflow (in Microsoft.Dynamics.Commerce.Runtime.Workflow.dll)

## Syntax

``` vb
'Declaration
Public Shared Function HandlePayments ( _
    context As RequestContext, _
    salesTransaction As SalesTransaction, _
    tokenizedPaymentCard As TokenizedPaymentCard, _
    cardTypeId As String _
) As SalesTransaction
'Usage
Dim context As RequestContext
Dim salesTransaction As SalesTransaction
Dim tokenizedPaymentCard As TokenizedPaymentCard
Dim cardTypeId As String
Dim returnValue As SalesTransaction

returnValue = CustomerOrderWorkflowHelper.HandlePayments(context, _
    salesTransaction, tokenizedPaymentCard, _
    cardTypeId)
```

``` csharp
public static SalesTransaction HandlePayments(
    RequestContext context,
    SalesTransaction salesTransaction,
    TokenizedPaymentCard tokenizedPaymentCard,
    string cardTypeId
)
```

``` c++
public:
static SalesTransaction^ HandlePayments(
    RequestContext^ context, 
    SalesTransaction^ salesTransaction, 
    TokenizedPaymentCard^ tokenizedPaymentCard, 
    String^ cardTypeId
)
```

#### Parameters

  - context  
    Type: [Microsoft.Dynamics.Commerce.Runtime.RequestContext](requestcontext-class-microsoft-dynamics-commerce-runtime.md)  

<!-- end list -->

  - salesTransaction  
    Type: [Microsoft.Dynamics.Commerce.Runtime.DataModel.SalesTransaction](salestransaction-class-microsoft-dynamics-commerce-runtime-datamodel.md)  

<!-- end list -->

  - tokenizedPaymentCard  
    Type: [Microsoft.Dynamics.Commerce.Runtime.DataModel.TokenizedPaymentCard](tokenizedpaymentcard-class-microsoft-dynamics-commerce-runtime-datamodel.md)  

<!-- end list -->

  - cardTypeId  
    Type: [System.String](https://technet.microsoft.com/en-us/library/s1wwdcbf\(v=ax.60\))  

#### Return Value

Type: [Microsoft.Dynamics.Commerce.Runtime.DataModel.SalesTransaction](salestransaction-class-microsoft-dynamics-commerce-runtime-datamodel.md)  

## See Also

#### Reference

[CustomerOrderWorkflowHelper Class](customerorderworkflowhelper-class-microsoft-dynamics-commerce-runtime-workflow.md)

[HandlePayments Overload](customerorderworkflowhelper-handlepayments-method-microsoft-dynamics-commerce-runtime-workflow.md)

[Microsoft.Dynamics.Commerce.Runtime.Workflow Namespace](microsoft-dynamics-commerce-runtime-workflow-namespace.md)

