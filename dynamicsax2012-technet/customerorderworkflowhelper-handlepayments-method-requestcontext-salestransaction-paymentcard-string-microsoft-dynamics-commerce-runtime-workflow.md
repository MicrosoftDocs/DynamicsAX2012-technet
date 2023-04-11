---
title: CustomerOrderWorkflowHelper.HandlePayments Method (RequestContext, SalesTransaction, PaymentCard, String) (Microsoft.Dynamics.Commerce.Runtime.Workflow)
TOCTitle: HandlePayments Method (RequestContext, SalesTransaction, PaymentCard, String)
ms:assetid: M:Microsoft.Dynamics.Commerce.Runtime.Workflow.CustomerOrderWorkflowHelper.HandlePayments(Microsoft.Dynamics.Commerce.Runtime.RequestContext,Microsoft.Dynamics.Commerce.Runtime.DataModel.SalesTransaction,Microsoft.Dynamics.Commerce.Runtime.DataModel.PaymentCard,System.String)
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.workflow.customerorderworkflowhelper.handlepayments(v=AX.60)
ms:contentKeyID: 62213002
author: tonyafehr
ms.date: 05/18/2015
mtps_version: v=AX.60
dev_langs:
- vb
- csharp
- c++
---

# HandlePayments Method (RequestContext, SalesTransaction, PaymentCard, String)


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Handles payments for customer orders, it includes: \* Capturing deposit.

\* Creating token for shipped items.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.Workflow](microsoft-dynamics-commerce-runtime-workflow-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Workflow (in Microsoft.Dynamics.Commerce.Runtime.Workflow.dll)

## Syntax

``` vb
'Declaration
Public Shared Function HandlePayments ( _
    context As RequestContext, _
    salesTransaction As SalesTransaction, _
    paymentCard As PaymentCard, _
    cardTypeId As String _
) As SalesTransaction
'Usage
Dim context As RequestContext
Dim salesTransaction As SalesTransaction
Dim paymentCard As PaymentCard
Dim cardTypeId As String
Dim returnValue As SalesTransaction

returnValue = CustomerOrderWorkflowHelper.HandlePayments(context, _
    salesTransaction, paymentCard, cardTypeId)
```

``` csharp
public static SalesTransaction HandlePayments(
    RequestContext context,
    SalesTransaction salesTransaction,
    PaymentCard paymentCard,
    string cardTypeId
)
```

``` c++
public:
static SalesTransaction^ HandlePayments(
    RequestContext^ context, 
    SalesTransaction^ salesTransaction, 
    PaymentCard^ paymentCard, 
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

  - paymentCard  
    Type: [Microsoft.Dynamics.Commerce.Runtime.DataModel.PaymentCard](paymentcard-class-microsoft-dynamics-commerce-runtime-datamodel.md)  

<!-- end list -->

  - cardTypeId  
    Type: [System.String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\))  

#### Return Value

Type: [Microsoft.Dynamics.Commerce.Runtime.DataModel.SalesTransaction](salestransaction-class-microsoft-dynamics-commerce-runtime-datamodel.md)  
Updated sales transaction.  

## See Also

#### Reference

[CustomerOrderWorkflowHelper Class](customerorderworkflowhelper-class-microsoft-dynamics-commerce-runtime-workflow.md)

[HandlePayments Overload](customerorderworkflowhelper-handlepayments-method-microsoft-dynamics-commerce-runtime-workflow.md)

[Microsoft.Dynamics.Commerce.Runtime.Workflow Namespace](microsoft-dynamics-commerce-runtime-workflow-namespace.md)

