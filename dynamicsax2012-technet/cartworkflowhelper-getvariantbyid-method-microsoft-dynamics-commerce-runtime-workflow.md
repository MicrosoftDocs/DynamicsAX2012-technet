---
title: CartWorkflowHelper.GetVariantById Method  (Microsoft.Dynamics.Commerce.Runtime.Workflow)
TOCTitle: GetVariantById Method
ms:assetid: M:Microsoft.Dynamics.Commerce.Runtime.Workflow.CartWorkflowHelper.GetVariantById(Microsoft.Dynamics.Commerce.Runtime.RequestContext,System.String)
ms:mtpsurl: https://technet.microsoft.com/en-us/library/microsoft.dynamics.commerce.runtime.workflow.cartworkflowhelper.getvariantbyid(v=AX.60)
ms:contentKeyID: 62211271
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.Workflow.CartWorkflowHelper.GetVariantById
dev_langs:
- CSharp
- C++
- VB
---

# GetVariantById Method

Gets the variant details by variant id.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.Workflow](microsoft-dynamics-commerce-runtime-workflow-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Workflow (in Microsoft.Dynamics.Commerce.Runtime.Workflow.dll)

## Syntax

``` vb
'Declaration
Public Shared Function GetVariantById ( _
    context As RequestContext, _
    variantId As String _
) As ProductVariant
'Usage
Dim context As RequestContext
Dim variantId As String
Dim returnValue As ProductVariant

returnValue = CartWorkflowHelper.GetVariantById(context, _
    variantId)
```

``` csharp
public static ProductVariant GetVariantById(
    RequestContext context,
    string variantId
)
```

``` c++
public:
static ProductVariant^ GetVariantById(
    RequestContext^ context, 
    String^ variantId
)
```

#### Parameters

  - context  
    Type: [Microsoft.Dynamics.Commerce.Runtime.RequestContext](requestcontext-class-microsoft-dynamics-commerce-runtime.md)  

<!-- end list -->

  - variantId  
    Type: [System.String](https://technet.microsoft.com/en-us/library/s1wwdcbf\(v=ax.60\))  

#### Return Value

Type: [Microsoft.Dynamics.Commerce.Runtime.DataModel.ProductVariant](productvariant-class-microsoft-dynamics-commerce-runtime-datamodel.md)  
Returns the variant object.  

## See Also

#### Reference

[CartWorkflowHelper Class](cartworkflowhelper-class-microsoft-dynamics-commerce-runtime-workflow.md)

[Microsoft.Dynamics.Commerce.Runtime.Workflow Namespace](microsoft-dynamics-commerce-runtime-workflow-namespace.md)

