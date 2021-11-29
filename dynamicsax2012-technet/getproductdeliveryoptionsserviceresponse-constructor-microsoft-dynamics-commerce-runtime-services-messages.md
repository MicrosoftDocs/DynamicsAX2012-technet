---
title: GetProductDeliveryOptionsServiceResponse Constructor  (Microsoft.Dynamics.Commerce.Runtime.Services.Messages)
TOCTitle: GetProductDeliveryOptionsServiceResponse Constructor
ms:assetid: M:Microsoft.Dynamics.Commerce.Runtime.Services.Messages.GetProductDeliveryOptionsServiceResponse.#ctor(System.Collections.Generic.IEnumerable{Microsoft.Dynamics.Commerce.Runtime.DataModel.DeliveryOption})
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.services.messages.getproductdeliveryoptionsserviceresponse.getproductdeliveryoptionsserviceresponse(v=AX.60)
ms:contentKeyID: 49847425
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.Services.Messages.GetProductDeliveryOptionsServiceResponse.#ctor
dev_langs:
- CSharp
- C++
- VB
---

# GetProductDeliveryOptionsServiceResponse Constructor


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Initializes a new instance of the [GetProductDeliveryOptionsServiceResponse](getproductdeliveryoptionsserviceresponse-class-microsoft-dynamics-commerce-runtime-services-messages.md) class.

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

Dim instance As New GetProductDeliveryOptionsServiceResponse(deliveryOptions)
```

``` csharp
public GetProductDeliveryOptionsServiceResponse(
    IEnumerable<DeliveryOption> deliveryOptions
)
```

``` c++
public:
GetProductDeliveryOptionsServiceResponse(
    IEnumerable<DeliveryOption^>^ deliveryOptions
)
```

#### Parameters

  - deliveryOptions  
    Type: [System.Collections.Generic.IEnumerable](https://technet.microsoft.com/library/9eekhta0\(v=ax.60\))\<[DeliveryOption](deliveryoption-class-microsoft-dynamics-commerce-runtime-datamodel.md)\>  

## See Also

#### Reference

[GetProductDeliveryOptionsServiceResponse Class](getproductdeliveryoptionsserviceresponse-class-microsoft-dynamics-commerce-runtime-services-messages.md)

[Microsoft.Dynamics.Commerce.Runtime.Services.Messages Namespace](microsoft-dynamics-commerce-runtime-services-messages-namespace.md)

