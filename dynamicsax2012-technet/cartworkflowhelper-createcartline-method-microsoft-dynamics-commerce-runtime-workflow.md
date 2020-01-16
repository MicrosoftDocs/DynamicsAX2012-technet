---
title: CartWorkflowHelper.CreateCartLine Method  (Microsoft.Dynamics.Commerce.Runtime.Workflow)
TOCTitle: CreateCartLine Method
ms:assetid: M:Microsoft.Dynamics.Commerce.Runtime.Workflow.CartWorkflowHelper.CreateCartLine(Microsoft.Dynamics.Commerce.Runtime.RequestContext,System.String,System.String,System.String,System.String,System.Decimal,System.Decimal)
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.workflow.cartworkflowhelper.createcartline(v=AX.60)
ms:contentKeyID: 62208936
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.Workflow.CartWorkflowHelper.CreateCartLine
dev_langs:
- CSharp
- C++
- VB
---

# CreateCartLine Method

Creates the cart line.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.Workflow](microsoft-dynamics-commerce-runtime-workflow-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Workflow (in Microsoft.Dynamics.Commerce.Runtime.Workflow.dll)

## Syntax

``` vb
'Declaration
Public Shared Function CreateCartLine ( _
    context As RequestContext, _
    barcode As String, _
    itemId As String, _
    variantId As String, _
    unitOfMeasureSymbol As String, _
    quantity As Decimal, _
    barcodePrice As Decimal _
) As CartLine
'Usage
Dim context As RequestContext
Dim barcode As String
Dim itemId As String
Dim variantId As String
Dim unitOfMeasureSymbol As String
Dim quantity As Decimal
Dim barcodePrice As Decimal
Dim returnValue As CartLine

returnValue = CartWorkflowHelper.CreateCartLine(context, _
    barcode, itemId, variantId, unitOfMeasureSymbol, _
    quantity, barcodePrice)
```

``` csharp
public static CartLine CreateCartLine(
    RequestContext context,
    string barcode,
    string itemId,
    string variantId,
    string unitOfMeasureSymbol,
    decimal quantity,
    decimal barcodePrice
)
```

``` c++
public:
static CartLine^ CreateCartLine(
    RequestContext^ context, 
    String^ barcode, 
    String^ itemId, 
    String^ variantId, 
    String^ unitOfMeasureSymbol, 
    Decimal quantity, 
    Decimal barcodePrice
)
```

#### Parameters

  - context  
    Type: [Microsoft.Dynamics.Commerce.Runtime.RequestContext](requestcontext-class-microsoft-dynamics-commerce-runtime.md)  

<!-- end list -->

  - barcode  
    Type: [System.String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\))  

<!-- end list -->

  - itemId  
    Type: [System.String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\))  

<!-- end list -->

  - variantId  
    Type: [System.String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\))  

<!-- end list -->

  - unitOfMeasureSymbol  
    Type: [System.String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\))  

<!-- end list -->

  - quantity  
    Type: [System.Decimal](https://technet.microsoft.com/library/1k2e8atx\(v=ax.60\))  

<!-- end list -->

  - barcodePrice  
    Type: [System.Decimal](https://technet.microsoft.com/library/1k2e8atx\(v=ax.60\))  

#### Return Value

Type: [Microsoft.Dynamics.Commerce.Runtime.DataModel.CartLine](cartline-class-microsoft-dynamics-commerce-runtime-datamodel.md)  
Returns the cartline object.  

## See Also

#### Reference

[CartWorkflowHelper Class](cartworkflowhelper-class-microsoft-dynamics-commerce-runtime-workflow.md)

[Microsoft.Dynamics.Commerce.Runtime.Workflow Namespace](microsoft-dynamics-commerce-runtime-workflow-namespace.md)

