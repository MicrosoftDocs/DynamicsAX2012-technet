---
title: CustomerOrderWorkflowHelper.GetCalculationModes Method  (Microsoft.Dynamics.Commerce.Runtime.Workflow)
TOCTitle: GetCalculationModes Method
ms:assetid: M:Microsoft.Dynamics.Commerce.Runtime.Workflow.CustomerOrderWorkflowHelper.GetCalculationModes(Microsoft.Dynamics.Commerce.Runtime.RequestContext,Microsoft.Dynamics.Commerce.Runtime.DataModel.SalesTransaction)
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.workflow.customerorderworkflowhelper.getcalculationmodes(v=AX.60)
ms:contentKeyID: 62213240
author: tonyafehr
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.Workflow.CustomerOrderWorkflowHelper.GetCalculationModes
dev_langs:
- CSharp
- C++
- VB
---

# GetCalculationModes Method


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Gets the calculation modes based on the operation being performed.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.Workflow](microsoft-dynamics-commerce-runtime-workflow-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Workflow (in Microsoft.Dynamics.Commerce.Runtime.Workflow.dll)

## Syntax

``` vb
'Declaration
Public Shared Function GetCalculationModes ( _
    context As RequestContext, _
    salesTransaction As SalesTransaction _
) As CalculationModes
'Usage
Dim context As RequestContext
Dim salesTransaction As SalesTransaction
Dim returnValue As CalculationModes

returnValue = CustomerOrderWorkflowHelper.GetCalculationModes(context, _
    salesTransaction)
```

``` csharp
public static CalculationModes GetCalculationModes(
    RequestContext context,
    SalesTransaction salesTransaction
)
```

``` c++
public:
static CalculationModes GetCalculationModes(
    RequestContext^ context, 
    SalesTransaction^ salesTransaction
)
```

#### Parameters

  - context  
    Type: [Microsoft.Dynamics.Commerce.Runtime.RequestContext](requestcontext-class-microsoft-dynamics-commerce-runtime.md)  

<!-- end list -->

  - salesTransaction  
    Type: [Microsoft.Dynamics.Commerce.Runtime.DataModel.SalesTransaction](salestransaction-class-microsoft-dynamics-commerce-runtime-datamodel.md)  

#### Return Value

Type: [Microsoft.Dynamics.Commerce.Runtime.DataModel.CalculationModes](calculationmodes-enumeration-microsoft-dynamics-commerce-runtime-datamodel.md)  
The filtered calculation modes.  

## See Also

#### Reference

[CustomerOrderWorkflowHelper Class](customerorderworkflowhelper-class-microsoft-dynamics-commerce-runtime-workflow.md)

[Microsoft.Dynamics.Commerce.Runtime.Workflow Namespace](microsoft-dynamics-commerce-runtime-workflow-namespace.md)

