---
title: GetProductDeliveryOptionsResponse Constructor (IEnumerable(DeliveryOption)) (Microsoft.Dynamics.Commerce.Runtime.Messages)
TOCTitle: GetProductDeliveryOptionsResponse Constructor (IEnumerable(DeliveryOption))
ms:assetid: M:Microsoft.Dynamics.Commerce.Runtime.Messages.GetProductDeliveryOptionsResponse.#ctor(System.Collections.Generic.IEnumerable{Microsoft.Dynamics.Commerce.Runtime.DataModel.DeliveryOption})
ms:mtpsurl: https://technet.microsoft.com/en-us/library/microsoft.dynamics.commerce.runtime.messages.getproductdeliveryoptionsresponse.getproductdeliveryoptionsresponse(v=AX.60)
ms:contentKeyID: 49827258
ms.date: 05/18/2015
mtps_version: v=AX.60
dev_langs:
- vb
- csharp
- c++
---

# GetProductDeliveryOptionsResponse Constructor (IEnumerable(DeliveryOption))

Initializes a new instance of the [GetProductDeliveryOptionsResponse](getproductdeliveryoptionsresponse-class-microsoft-dynamics-commerce-runtime-messages.md) class.

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

Dim instance As New GetProductDeliveryOptionsResponse(deliveryOptions)
```

``` csharp
public GetProductDeliveryOptionsResponse(
    IEnumerable<DeliveryOption> deliveryOptions
)
```

``` c++
public:
GetProductDeliveryOptionsResponse(
    IEnumerable<DeliveryOption^>^ deliveryOptions
)
```

#### Parameters

  - deliveryOptions  
    Type: [System.Collections.Generic.IEnumerable](https://technet.microsoft.com/en-us/library/9eekhta0\(v=ax.60\))\<[DeliveryOption](deliveryoption-class-microsoft-dynamics-commerce-runtime-datamodel.md)\>  

## See Also

#### Reference

[GetProductDeliveryOptionsResponse Class](getproductdeliveryoptionsresponse-class-microsoft-dynamics-commerce-runtime-messages.md)

[GetProductDeliveryOptionsResponse Overload](getproductdeliveryoptionsresponse-constructor-microsoft-dynamics-commerce-runtime-messages.md)

[Microsoft.Dynamics.Commerce.Runtime.Messages Namespace](microsoft-dynamics-commerce-runtime-messages-namespace.md)

