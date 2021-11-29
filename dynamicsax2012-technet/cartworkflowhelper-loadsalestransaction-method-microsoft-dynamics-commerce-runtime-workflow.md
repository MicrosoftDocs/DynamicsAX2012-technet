---
title: CartWorkflowHelper.LoadSalesTransaction Method  (Microsoft.Dynamics.Commerce.Runtime.Workflow)
TOCTitle: LoadSalesTransaction Method
ms:assetid: M:Microsoft.Dynamics.Commerce.Runtime.Workflow.CartWorkflowHelper.LoadSalesTransaction(Microsoft.Dynamics.Commerce.Runtime.RequestContext,System.String)
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.workflow.cartworkflowhelper.loadsalestransaction(v=AX.60)
ms:contentKeyID: 62209627
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.Workflow.CartWorkflowHelper.LoadSalesTransaction
dev_langs:
- CSharp
- C++
- VB
---

# LoadSalesTransaction Method


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Loads the sales transactions given the customer identifier.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.Workflow](microsoft-dynamics-commerce-runtime-workflow-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Workflow (in Microsoft.Dynamics.Commerce.Runtime.Workflow.dll)

## Syntax

``` vb
'Declaration
Public Shared Function LoadSalesTransaction ( _
    context As RequestContext, _
    cartId As String _
) As SalesTransaction
'Usage
Dim context As RequestContext
Dim cartId As String
Dim returnValue As SalesTransaction

returnValue = CartWorkflowHelper.LoadSalesTransaction(context, _
    cartId)
```

``` csharp
public static SalesTransaction LoadSalesTransaction(
    RequestContext context,
    string cartId
)
```

``` c++
public:
static SalesTransaction^ LoadSalesTransaction(
    RequestContext^ context, 
    String^ cartId
)
```

#### Parameters

  - context  
    Type: [Microsoft.Dynamics.Commerce.Runtime.RequestContext](requestcontext-class-microsoft-dynamics-commerce-runtime.md)  

<!-- end list -->

  - cartId  
    Type: [System.String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\))  

#### Return Value

Type: [Microsoft.Dynamics.Commerce.Runtime.DataModel.SalesTransaction](salestransaction-class-microsoft-dynamics-commerce-runtime-datamodel.md)  
The loaded sales transaction.  

## See Also

#### Reference

[CartWorkflowHelper Class](cartworkflowhelper-class-microsoft-dynamics-commerce-runtime-workflow.md)

[Microsoft.Dynamics.Commerce.Runtime.Workflow Namespace](microsoft-dynamics-commerce-runtime-workflow-namespace.md)

