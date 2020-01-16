---
title: CartWorkflowHelper.GetProductsInCartLines Method  (Microsoft.Dynamics.Commerce.Runtime.Workflow)
TOCTitle: GetProductsInCartLines Method
ms:assetid: M:Microsoft.Dynamics.Commerce.Runtime.Workflow.CartWorkflowHelper.GetProductsInCartLines(Microsoft.Dynamics.Commerce.Runtime.RequestContext,System.Collections.Generic.IEnumerable{Microsoft.Dynamics.Commerce.Runtime.DataModel.CartLine})
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.workflow.cartworkflowhelper.getproductsincartlines(v=AX.60)
ms:contentKeyID: 62203675
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.Workflow.CartWorkflowHelper.GetProductsInCartLines
dev_langs:
- CSharp
- C++
- VB
---

# GetProductsInCartLines Method

Gets the listings in cart lines.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.Workflow](microsoft-dynamics-commerce-runtime-workflow-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Workflow (in Microsoft.Dynamics.Commerce.Runtime.Workflow.dll)

## Syntax

``` vb
'Declaration
Public Shared Function GetProductsInCartLines ( _
    context As RequestContext, _
    cartLines As IEnumerable(Of CartLine) _
) As Dictionary(Of Long, Product)
'Usage
Dim context As RequestContext
Dim cartLines As IEnumerable(Of CartLine)
Dim returnValue As Dictionary(Of Long, Product)

returnValue = CartWorkflowHelper.GetProductsInCartLines(context, _
    cartLines)
```

``` csharp
public static Dictionary<long, Product> GetProductsInCartLines(
    RequestContext context,
    IEnumerable<CartLine> cartLines
)
```

``` c++
public:
static Dictionary<long long, Product^>^ GetProductsInCartLines(
    RequestContext^ context, 
    IEnumerable<CartLine^>^ cartLines
)
```

#### Parameters

  - context  
    Type: [Microsoft.Dynamics.Commerce.Runtime.RequestContext](requestcontext-class-microsoft-dynamics-commerce-runtime.md)  

<!-- end list -->

  - cartLines  
    Type: [System.Collections.Generic.IEnumerable](https://technet.microsoft.com/library/9eekhta0\(v=ax.60\))\<[CartLine](cartline-class-microsoft-dynamics-commerce-runtime-datamodel.md)\>  

#### Return Value

Type: [System.Collections.Generic.Dictionary](https://technet.microsoft.com/library/xfhwa508\(v=ax.60\))\<[Int64](https://technet.microsoft.com/library/6yy583ek\(v=ax.60\)), [Product](product-class-microsoft-dynamics-commerce-runtime-datamodel.md)\>  
A dictionary of listing id to listings mapping.  

## See Also

#### Reference

[CartWorkflowHelper Class](cartworkflowhelper-class-microsoft-dynamics-commerce-runtime-workflow.md)

[Microsoft.Dynamics.Commerce.Runtime.Workflow Namespace](microsoft-dynamics-commerce-runtime-workflow-namespace.md)

