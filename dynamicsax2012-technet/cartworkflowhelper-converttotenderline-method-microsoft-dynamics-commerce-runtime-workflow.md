---
title: CartWorkflowHelper.ConvertToTenderLine Method  (Microsoft.Dynamics.Commerce.Runtime.Workflow)
TOCTitle: ConvertToTenderLine Method
ms:assetid: M:Microsoft.Dynamics.Commerce.Runtime.Workflow.CartWorkflowHelper.ConvertToTenderLine(Microsoft.Dynamics.Commerce.Runtime.DataModel.CartTenderLine)
ms:mtpsurl: https://technet.microsoft.com/en-us/library/microsoft.dynamics.commerce.runtime.workflow.cartworkflowhelper.converttotenderline(v=AX.60)
ms:contentKeyID: 62207741
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.Workflow.CartWorkflowHelper.ConvertToTenderLine
dev_langs:
- CSharp
- C++
- VB
---

# ConvertToTenderLine Method

Converts CartTenderLine to TenderLine.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.Workflow](microsoft-dynamics-commerce-runtime-workflow-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Workflow (in Microsoft.Dynamics.Commerce.Runtime.Workflow.dll)

## Syntax

``` vb
'Declaration
Public Shared Function ConvertToTenderLine ( _
    cartTenderLine As CartTenderLine _
) As TenderLine
'Usage
Dim cartTenderLine As CartTenderLine
Dim returnValue As TenderLine

returnValue = CartWorkflowHelper.ConvertToTenderLine(cartTenderLine)
```

``` csharp
public static TenderLine ConvertToTenderLine(
    CartTenderLine cartTenderLine
)
```

``` c++
public:
static TenderLine^ ConvertToTenderLine(
    CartTenderLine^ cartTenderLine
)
```

#### Parameters

  - cartTenderLine  
    Type: [Microsoft.Dynamics.Commerce.Runtime.DataModel.CartTenderLine](carttenderline-class-microsoft-dynamics-commerce-runtime-datamodel.md)  

#### Return Value

Type: [Microsoft.Dynamics.Commerce.Runtime.DataModel.TenderLine](tenderline-class-microsoft-dynamics-commerce-runtime-datamodel.md)  
The tender line.  

## See Also

#### Reference

[CartWorkflowHelper Class](cartworkflowhelper-class-microsoft-dynamics-commerce-runtime-workflow.md)

[Microsoft.Dynamics.Commerce.Runtime.Workflow Namespace](microsoft-dynamics-commerce-runtime-workflow-namespace.md)

