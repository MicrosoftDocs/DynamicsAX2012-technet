---
title: GetAllDeliveryOptionsResponse Constructor (IEnumerable(DeliveryOption)) (Microsoft.Dynamics.Commerce.Runtime.Messages)
TOCTitle: GetAllDeliveryOptionsResponse Constructor (IEnumerable(DeliveryOption))
ms:assetid: M:Microsoft.Dynamics.Commerce.Runtime.Messages.GetAllDeliveryOptionsResponse.#ctor(System.Collections.Generic.IEnumerable{Microsoft.Dynamics.Commerce.Runtime.DataModel.DeliveryOption})
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.messages.getalldeliveryoptionsresponse.getalldeliveryoptionsresponse(v=AX.60)
ms:contentKeyID: 62206078
author: tonyafehr
ms.date: 05/18/2015
mtps_version: v=AX.60
dev_langs:
- vb
- csharp
- c++
---

# GetAllDeliveryOptionsResponse Constructor (IEnumerable(DeliveryOption))


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Initializes a new instance of the [GetAllDeliveryOptionsResponse](getalldeliveryoptionsresponse-class-microsoft-dynamics-commerce-runtime-messages.md) class.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.Messages](microsoft-dynamics-commerce-runtime-messages-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Messages (in Microsoft.Dynamics.Commerce.Runtime.Messages.dll)

## Syntax

``` vb
'Declaration
Public Sub New ( _
    deliveryOptions As IEnumerable(Of DeliveryOption) _
)
'Usage
Dim deliveryOptions As IEnumerable(Of DeliveryOption)

Dim instance As New GetAllDeliveryOptionsResponse(deliveryOptions)
```

``` csharp
public GetAllDeliveryOptionsResponse(
    IEnumerable<DeliveryOption> deliveryOptions
)
```

``` c++
public:
GetAllDeliveryOptionsResponse(
    IEnumerable<DeliveryOption^>^ deliveryOptions
)
```

#### Parameters

  - deliveryOptions  
    Type: [System.Collections.Generic.IEnumerable](https://technet.microsoft.com/library/9eekhta0\(v=ax.60\))\<[DeliveryOption](deliveryoption-class-microsoft-dynamics-commerce-runtime-datamodel.md)\>  

## See Also

#### Reference

[GetAllDeliveryOptionsResponse Class](getalldeliveryoptionsresponse-class-microsoft-dynamics-commerce-runtime-messages.md)

[GetAllDeliveryOptionsResponse Overload](getalldeliveryoptionsresponse-constructor-microsoft-dynamics-commerce-runtime-messages.md)

[Microsoft.Dynamics.Commerce.Runtime.Messages Namespace](microsoft-dynamics-commerce-runtime-messages-namespace.md)

