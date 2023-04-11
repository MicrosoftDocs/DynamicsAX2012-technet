---
title: CustomerOrderWorkflowHelper.UpdateCustomerOrderFieldsOnCheckout Method  (Microsoft.Dynamics.Commerce.Runtime.Workflow)
TOCTitle: UpdateCustomerOrderFieldsOnCheckout Method
ms:assetid: M:Microsoft.Dynamics.Commerce.Runtime.Workflow.CustomerOrderWorkflowHelper.UpdateCustomerOrderFieldsOnCheckout(Microsoft.Dynamics.Commerce.Runtime.DataModel.SalesTransaction)
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.workflow.customerorderworkflowhelper.updatecustomerorderfieldsoncheckout(v=AX.60)
ms:contentKeyID: 62211078
author: tonyafehr
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.Workflow.CustomerOrderWorkflowHelper.UpdateCustomerOrderFieldsOnCheckout
dev_langs:
- CSharp
- C++
- VB
---

# UpdateCustomerOrderFieldsOnCheckout Method


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Updates the customer order fields on checkout.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.Workflow](microsoft-dynamics-commerce-runtime-workflow-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Workflow (in Microsoft.Dynamics.Commerce.Runtime.Workflow.dll)

## Syntax

``` vb
'Declaration
Public Shared Sub UpdateCustomerOrderFieldsOnCheckout ( _
    salesTransaction As SalesTransaction _
)
'Usage
Dim salesTransaction As SalesTransaction

CustomerOrderWorkflowHelper.UpdateCustomerOrderFieldsOnCheckout(salesTransaction)
```

``` csharp
public static void UpdateCustomerOrderFieldsOnCheckout(
    SalesTransaction salesTransaction
)
```

``` c++
public:
static void UpdateCustomerOrderFieldsOnCheckout(
    SalesTransaction^ salesTransaction
)
```

#### Parameters

  - salesTransaction  
    Type: [Microsoft.Dynamics.Commerce.Runtime.DataModel.SalesTransaction](salestransaction-class-microsoft-dynamics-commerce-runtime-datamodel.md)  

## See Also

#### Reference

[CustomerOrderWorkflowHelper Class](customerorderworkflowhelper-class-microsoft-dynamics-commerce-runtime-workflow.md)

[Microsoft.Dynamics.Commerce.Runtime.Workflow Namespace](microsoft-dynamics-commerce-runtime-workflow-namespace.md)

