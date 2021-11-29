---
title: CartWorkflowHelper.Calculate Method (RequestContext, Nullable(CalculationModes), Boolean) (Microsoft.Dynamics.Commerce.Runtime.Workflow)
TOCTitle: Calculate Method (RequestContext, Nullable(CalculationModes), Boolean)
ms:assetid: M:Microsoft.Dynamics.Commerce.Runtime.Workflow.CartWorkflowHelper.Calculate(Microsoft.Dynamics.Commerce.Runtime.RequestContext,System.Nullable{Microsoft.Dynamics.Commerce.Runtime.DataModel.CalculationModes},System.Boolean)
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.workflow.cartworkflowhelper.calculate(v=AX.60)
ms:contentKeyID: 62211146
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
dev_langs:
- vb
- csharp
- c++
---

# Calculate Method (RequestContext, Nullable(CalculationModes), Boolean)


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Calculates the various totals depending on the specified calculation mode.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.Workflow](microsoft-dynamics-commerce-runtime-workflow-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Workflow (in Microsoft.Dynamics.Commerce.Runtime.Workflow.dll)

## Syntax

``` vb
'Declaration
Public Shared Sub Calculate ( _
    context As RequestContext, _
    requestedMode As Nullable(Of CalculationModes), _
    restoreItemPrices As Boolean _
)
'Usage
Dim context As RequestContext
Dim requestedMode As Nullable(Of CalculationModes)
Dim restoreItemPrices As Boolean

CartWorkflowHelper.Calculate(context, requestedMode, _
    restoreItemPrices)
```

``` csharp
public static void Calculate(
    RequestContext context,
    Nullable<CalculationModes> requestedMode,
    bool restoreItemPrices
)
```

``` c++
public:
static void Calculate(
    RequestContext^ context, 
    Nullable<CalculationModes> requestedMode, 
    bool restoreItemPrices
)
```

#### Parameters

  - context  
    Type: [Microsoft.Dynamics.Commerce.Runtime.RequestContext](requestcontext-class-microsoft-dynamics-commerce-runtime.md)  

<!-- end list -->

  - requestedMode  
    Type: [System.Nullable](https://technet.microsoft.com/library/b3h38hb0\(v=ax.60\))\<[CalculationModes](calculationmodes-enumeration-microsoft-dynamics-commerce-runtime-datamodel.md)\>  

<!-- end list -->

  - restoreItemPrices  
    Type: [System.Boolean](https://technet.microsoft.com/library/a28wyd50\(v=ax.60\))  

## See Also

#### Reference

[CartWorkflowHelper Class](cartworkflowhelper-class-microsoft-dynamics-commerce-runtime-workflow.md)

[Calculate Overload](cartworkflowhelper-calculate-method-microsoft-dynamics-commerce-runtime-workflow.md)

[Microsoft.Dynamics.Commerce.Runtime.Workflow Namespace](microsoft-dynamics-commerce-runtime-workflow-namespace.md)

