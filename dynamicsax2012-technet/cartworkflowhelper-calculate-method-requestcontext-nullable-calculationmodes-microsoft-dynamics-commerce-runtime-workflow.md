---
title: CartWorkflowHelper.Calculate Method (RequestContext, Nullable(CalculationModes)) (Microsoft.Dynamics.Commerce.Runtime.Workflow)
TOCTitle: Calculate Method (RequestContext, Nullable(CalculationModes))
ms:assetid: M:Microsoft.Dynamics.Commerce.Runtime.Workflow.CartWorkflowHelper.Calculate(Microsoft.Dynamics.Commerce.Runtime.RequestContext,System.Nullable{Microsoft.Dynamics.Commerce.Runtime.DataModel.CalculationModes})
ms:mtpsurl: https://technet.microsoft.com/en-us/library/microsoft.dynamics.commerce.runtime.workflow.cartworkflowhelper.calculate(v=AX.60)
ms:contentKeyID: 62206910
ms.date: 05/18/2015
mtps_version: v=AX.60
dev_langs:
- vb
- csharp
- c++
---

# Calculate Method (RequestContext, Nullable(CalculationModes))

Calculates the various totals depending on the specified calculation mode.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.Workflow](microsoft-dynamics-commerce-runtime-workflow-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Workflow (in Microsoft.Dynamics.Commerce.Runtime.Workflow.dll)

## Syntax

``` vb
'Declaration
Public Shared Sub Calculate ( _
    context As RequestContext, _
    requestedMode As Nullable(Of CalculationModes) _
)
'Usage
Dim context As RequestContext
Dim requestedMode As Nullable(Of CalculationModes)

CartWorkflowHelper.Calculate(context, requestedMode)
```

``` csharp
public static void Calculate(
    RequestContext context,
    Nullable<CalculationModes> requestedMode
)
```

``` c++
public:
static void Calculate(
    RequestContext^ context, 
    Nullable<CalculationModes> requestedMode
)
```

#### Parameters

  - context  
    Type: [Microsoft.Dynamics.Commerce.Runtime.RequestContext](requestcontext-class-microsoft-dynamics-commerce-runtime.md)  

<!-- end list -->

  - requestedMode  
    Type: [System.Nullable](https://technet.microsoft.com/en-us/library/b3h38hb0\(v=ax.60\))\<[CalculationModes](calculationmodes-enumeration-microsoft-dynamics-commerce-runtime-datamodel.md)\>  

## See Also

#### Reference

[CartWorkflowHelper Class](cartworkflowhelper-class-microsoft-dynamics-commerce-runtime-workflow.md)

[Calculate Overload](cartworkflowhelper-calculate-method-microsoft-dynamics-commerce-runtime-workflow.md)

[Microsoft.Dynamics.Commerce.Runtime.Workflow Namespace](microsoft-dynamics-commerce-runtime-workflow-namespace.md)

