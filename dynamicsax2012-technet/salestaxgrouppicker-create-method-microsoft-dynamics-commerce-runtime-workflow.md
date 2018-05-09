---
title: SalesTaxGroupPicker.Create Method  (Microsoft.Dynamics.Commerce.Runtime.Workflow)
TOCTitle: Create Method
ms:assetid: M:Microsoft.Dynamics.Commerce.Runtime.Workflow.SalesTaxGroupPicker.Create(Microsoft.Dynamics.Commerce.Runtime.DataModel.Channel,Microsoft.Dynamics.Commerce.Runtime.RequestContext,Microsoft.Dynamics.Commerce.Runtime.DataModel.Address,System.String,System.String,System.String)
ms:mtpsurl: https://technet.microsoft.com/en-us/library/microsoft.dynamics.commerce.runtime.workflow.salestaxgrouppicker.create(v=AX.60)
ms:contentKeyID: 65315811
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.Workflow.SalesTaxGroupPicker.Create
dev_langs:
- CSharp
- C++
- VB
---

# Create Method

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.Workflow](microsoft-dynamics-commerce-runtime-workflow-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Workflow (in Microsoft.Dynamics.Commerce.Runtime.Workflow.dll)

## Syntax

``` vb
'Declaration
Public Shared Function Create ( _
    channel As Channel, _
    context As RequestContext, _
    address As Address, _
    deliveryMode As String, _
    fulfillmentStoreId As String, _
    shippingFromInventLocation As String _
) As SalesTaxGroupPicker
'Usage
Dim channel As Channel
Dim context As RequestContext
Dim address As Address
Dim deliveryMode As String
Dim fulfillmentStoreId As String
Dim shippingFromInventLocation As String
Dim returnValue As SalesTaxGroupPicker

returnValue = SalesTaxGroupPicker.Create(channel, _
    context, address, deliveryMode, fulfillmentStoreId, _
    shippingFromInventLocation)
```

``` csharp
public static SalesTaxGroupPicker Create(
    Channel channel,
    RequestContext context,
    Address address,
    string deliveryMode,
    string fulfillmentStoreId,
    string shippingFromInventLocation
)
```

``` c++
public:
static SalesTaxGroupPicker^ Create(
    Channel^ channel, 
    RequestContext^ context, 
    Address^ address, 
    String^ deliveryMode, 
    String^ fulfillmentStoreId, 
    String^ shippingFromInventLocation
)
```

#### Parameters

  - channel  
    Type: [Microsoft.Dynamics.Commerce.Runtime.DataModel.Channel](channel-class-microsoft-dynamics-commerce-runtime-datamodel.md)  

<!-- end list -->

  - context  
    Type: [Microsoft.Dynamics.Commerce.Runtime.RequestContext](requestcontext-class-microsoft-dynamics-commerce-runtime.md)  

<!-- end list -->

  - address  
    Type: [Microsoft.Dynamics.Commerce.Runtime.DataModel.Address](address-class-microsoft-dynamics-commerce-runtime-datamodel.md)  

<!-- end list -->

  - deliveryMode  
    Type: [System.String](https://technet.microsoft.com/en-us/library/s1wwdcbf\(v=ax.60\))  

<!-- end list -->

  - fulfillmentStoreId  
    Type: [System.String](https://technet.microsoft.com/en-us/library/s1wwdcbf\(v=ax.60\))  

<!-- end list -->

  - shippingFromInventLocation  
    Type: [System.String](https://technet.microsoft.com/en-us/library/s1wwdcbf\(v=ax.60\))  

#### Return Value

Type: [Microsoft.Dynamics.Commerce.Runtime.Workflow.SalesTaxGroupPicker](salestaxgrouppicker-class-microsoft-dynamics-commerce-runtime-workflow.md)  

## See Also

#### Reference

[SalesTaxGroupPicker Class](salestaxgrouppicker-class-microsoft-dynamics-commerce-runtime-workflow.md)

[Microsoft.Dynamics.Commerce.Runtime.Workflow Namespace](microsoft-dynamics-commerce-runtime-workflow-namespace.md)

