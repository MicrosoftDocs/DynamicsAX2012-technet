---
title: CustomerOrderWorkflowHelper.FillAddressInformation Method  (Microsoft.Dynamics.Commerce.Runtime.Workflow)
TOCTitle: FillAddressInformation Method
ms:assetid: M:Microsoft.Dynamics.Commerce.Runtime.Workflow.CustomerOrderWorkflowHelper.FillAddressInformation(Microsoft.Dynamics.Commerce.Runtime.RequestContext,Microsoft.Dynamics.Commerce.Runtime.DataModel.SalesTransaction,Microsoft.Dynamics.Commerce.Runtime.DataModel.Cart,System.Collections.Generic.Dictionary{System.String,Microsoft.Dynamics.Commerce.Runtime.DataModel.SalesLine})
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.workflow.customerorderworkflowhelper.filladdressinformation(v=AX.60)
ms:contentKeyID: 62210929
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.Workflow.CustomerOrderWorkflowHelper.FillAddressInformation
dev_langs:
- CSharp
- C++
- VB
---

# FillAddressInformation Method

Fills cart with address information that is not present on the request (cart).

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.Workflow](microsoft-dynamics-commerce-runtime-workflow-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Workflow (in Microsoft.Dynamics.Commerce.Runtime.Workflow.dll)

## Syntax

``` vb
'Declaration
Public Shared Sub FillAddressInformation ( _
    context As RequestContext, _
    salesTransaction As SalesTransaction, _
    cart As Cart, _
    salesLineByLineId As Dictionary(Of String, SalesLine) _
)
'Usage
Dim context As RequestContext
Dim salesTransaction As SalesTransaction
Dim cart As Cart
Dim salesLineByLineId As Dictionary(Of String, SalesLine)

CustomerOrderWorkflowHelper.FillAddressInformation(context, _
    salesTransaction, cart, salesLineByLineId)
```

``` csharp
public static void FillAddressInformation(
    RequestContext context,
    SalesTransaction salesTransaction,
    Cart cart,
    Dictionary<string, SalesLine> salesLineByLineId
)
```

``` c++
public:
static void FillAddressInformation(
    RequestContext^ context, 
    SalesTransaction^ salesTransaction, 
    Cart^ cart, 
    Dictionary<String^, SalesLine^>^ salesLineByLineId
)
```

#### Parameters

  - context  
    Type: [Microsoft.Dynamics.Commerce.Runtime.RequestContext](requestcontext-class-microsoft-dynamics-commerce-runtime.md)  

<!-- end list -->

  - salesTransaction  
    Type: [Microsoft.Dynamics.Commerce.Runtime.DataModel.SalesTransaction](salestransaction-class-microsoft-dynamics-commerce-runtime-datamodel.md)  

<!-- end list -->

  - cart  
    Type: [Microsoft.Dynamics.Commerce.Runtime.DataModel.Cart](cart-class-microsoft-dynamics-commerce-runtime-datamodel.md)  

<!-- end list -->

  - salesLineByLineId  
    Type: [System.Collections.Generic.Dictionary](https://technet.microsoft.com/library/xfhwa508\(v=ax.60\))\<[String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\)), [SalesLine](salesline-class-microsoft-dynamics-commerce-runtime-datamodel.md)\>  

## Remarks

When we receive a cart request the Shipping address might be incomplete, so it needs to be fetched from the DB based on its record id.

This method will compare the existing address on the transaction header / lines with the correspondent address on the cart header / lines. Only when the address is changed, added or remove that it will fetch the addresses from the DB.

## See Also

#### Reference

[CustomerOrderWorkflowHelper Class](customerorderworkflowhelper-class-microsoft-dynamics-commerce-runtime-workflow.md)

[Microsoft.Dynamics.Commerce.Runtime.Workflow Namespace](microsoft-dynamics-commerce-runtime-workflow-namespace.md)

