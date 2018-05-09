---
title: GetOrderDeliveryOptionsServiceResponse Constructor  (Microsoft.Dynamics.Commerce.Runtime.Services.Messages)
TOCTitle: GetOrderDeliveryOptionsServiceResponse Constructor
ms:assetid: M:Microsoft.Dynamics.Commerce.Runtime.Services.Messages.GetOrderDeliveryOptionsServiceResponse.#ctor(System.Collections.Generic.IEnumerable{Microsoft.Dynamics.Commerce.Runtime.DataModel.DeliveryOption})
ms:mtpsurl: https://technet.microsoft.com/en-us/library/microsoft.dynamics.commerce.runtime.services.messages.getorderdeliveryoptionsserviceresponse.getorderdeliveryoptionsserviceresponse(v=AX.60)
ms:contentKeyID: 49842195
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.Services.Messages.GetOrderDeliveryOptionsServiceResponse.#ctor
dev_langs:
- CSharp
- C++
- VB
---

# GetOrderDeliveryOptionsServiceResponse Constructor

Initializes a new instance of the [GetOrderDeliveryOptionsServiceResponse](getorderdeliveryoptionsserviceresponse-class-microsoft-dynamics-commerce-runtime-services-messages.md) class.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.Services.Messages](microsoft-dynamics-commerce-runtime-services-messages-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Services.Messages (in Microsoft.Dynamics.Commerce.Runtime.Services.Messages.dll)

## Syntax

``` vb
'Declaration
Public Sub New ( _
    deliveryOptions As IEnumerable(Of DeliveryOption) _
)
'Usage
Dim deliveryOptions As IEnumerable(Of DeliveryOption)

Dim instance As New GetOrderDeliveryOptionsServiceResponse(deliveryOptions)
```

``` csharp
public GetOrderDeliveryOptionsServiceResponse(
    IEnumerable<DeliveryOption> deliveryOptions
)
```

``` c++
public:
GetOrderDeliveryOptionsServiceResponse(
    IEnumerable<DeliveryOption^>^ deliveryOptions
)
```

#### Parameters

  - deliveryOptions  
    Type: [System.Collections.Generic.IEnumerable](https://technet.microsoft.com/en-us/library/9eekhta0\(v=ax.60\))\<[DeliveryOption](deliveryoption-class-microsoft-dynamics-commerce-runtime-datamodel.md)\>  

## See Also

#### Reference

[GetOrderDeliveryOptionsServiceResponse Class](getorderdeliveryoptionsserviceresponse-class-microsoft-dynamics-commerce-runtime-services-messages.md)

[Microsoft.Dynamics.Commerce.Runtime.Services.Messages Namespace](microsoft-dynamics-commerce-runtime-services-messages-namespace.md)

