---
title: CartWorkflowHelper.CreateCartLineData Method  (Microsoft.Dynamics.Commerce.Runtime.Workflow)
TOCTitle: CreateCartLineData Method
ms:assetid: M:Microsoft.Dynamics.Commerce.Runtime.Workflow.CartWorkflowHelper.CreateCartLineData(Microsoft.Dynamics.Commerce.Runtime.RequestContext,System.String,System.String,System.Int64,System.String,System.String,System.Decimal,System.Decimal)
ms:mtpsurl: https://technet.microsoft.com/en-us/library/microsoft.dynamics.commerce.runtime.workflow.cartworkflowhelper.createcartlinedata(v=AX.60)
ms:contentKeyID: 62209879
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.Workflow.CartWorkflowHelper.CreateCartLineData
dev_langs:
- CSharp
- C++
- VB
---

# CreateCartLineData Method

Creates the cart line data.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.Workflow](microsoft-dynamics-commerce-runtime-workflow-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Workflow (in Microsoft.Dynamics.Commerce.Runtime.Workflow.dll)

## Syntax

``` vb
'Declaration
Public Shared Function CreateCartLineData ( _
    context As RequestContext, _
    itemId As String, _
    barcode As String, _
    productId As Long, _
    inventDimId As String, _
    unitOfMeasureSymbol As String, _
    quantity As Decimal, _
    barcodePrice As Decimal _
) As CartLineData
'Usage
Dim context As RequestContext
Dim itemId As String
Dim barcode As String
Dim productId As Long
Dim inventDimId As String
Dim unitOfMeasureSymbol As String
Dim quantity As Decimal
Dim barcodePrice As Decimal
Dim returnValue As CartLineData

returnValue = CartWorkflowHelper.CreateCartLineData(context, _
    itemId, barcode, productId, inventDimId, _
    unitOfMeasureSymbol, quantity, barcodePrice)
```

``` csharp
public static CartLineData CreateCartLineData(
    RequestContext context,
    string itemId,
    string barcode,
    long productId,
    string inventDimId,
    string unitOfMeasureSymbol,
    decimal quantity,
    decimal barcodePrice
)
```

``` c++
public:
static CartLineData^ CreateCartLineData(
    RequestContext^ context, 
    String^ itemId, 
    String^ barcode, 
    long long productId, 
    String^ inventDimId, 
    String^ unitOfMeasureSymbol, 
    Decimal quantity, 
    Decimal barcodePrice
)
```

#### Parameters

  - context  
    Type: [Microsoft.Dynamics.Commerce.Runtime.RequestContext](requestcontext-class-microsoft-dynamics-commerce-runtime.md)  

<!-- end list -->

  - itemId  
    Type: [System.String](https://technet.microsoft.com/en-us/library/s1wwdcbf\(v=ax.60\))  

<!-- end list -->

  - barcode  
    Type: [System.String](https://technet.microsoft.com/en-us/library/s1wwdcbf\(v=ax.60\))  

<!-- end list -->

  - productId  
    Type: [System.Int64](https://technet.microsoft.com/en-us/library/6yy583ek\(v=ax.60\))  

<!-- end list -->

  - inventDimId  
    Type: [System.String](https://technet.microsoft.com/en-us/library/s1wwdcbf\(v=ax.60\))  

<!-- end list -->

  - unitOfMeasureSymbol  
    Type: [System.String](https://technet.microsoft.com/en-us/library/s1wwdcbf\(v=ax.60\))  

<!-- end list -->

  - quantity  
    Type: [System.Decimal](https://technet.microsoft.com/en-us/library/1k2e8atx\(v=ax.60\))  

<!-- end list -->

  - barcodePrice  
    Type: [System.Decimal](https://technet.microsoft.com/en-us/library/1k2e8atx\(v=ax.60\))  

#### Return Value

Type: [Microsoft.Dynamics.Commerce.Runtime.DataModel.CartLineData](cartlinedata-class-microsoft-dynamics-commerce-runtime-datamodel.md)  
Returns the cartline data.  

## See Also

#### Reference

[CartWorkflowHelper Class](cartworkflowhelper-class-microsoft-dynamics-commerce-runtime-workflow.md)

[Microsoft.Dynamics.Commerce.Runtime.Workflow Namespace](microsoft-dynamics-commerce-runtime-workflow-namespace.md)

