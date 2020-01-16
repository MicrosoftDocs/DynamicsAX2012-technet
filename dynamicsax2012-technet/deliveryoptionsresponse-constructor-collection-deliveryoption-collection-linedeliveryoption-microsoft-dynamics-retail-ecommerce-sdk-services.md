---
title: DeliveryOptionsResponse Constructor (Collection(DeliveryOption), Collection(LineDeliveryOption)) (Microsoft.Dynamics.Retail.Ecommerce.Sdk.Services)
TOCTitle: DeliveryOptionsResponse Constructor (Collection(DeliveryOption), Collection(LineDeliveryOption))
ms:assetid: M:Microsoft.Dynamics.Retail.Ecommerce.Sdk.Services.DeliveryOptionsResponse.#ctor(System.Collections.ObjectModel.Collection{Microsoft.Dynamics.Retail.Ecommerce.Sdk.Core.Models.DeliveryOption},System.Collections.ObjectModel.Collection{Microsoft.Dynamics.Retail.Ecommerce.Sdk.Core.Models.LineDeliveryOption})
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.retail.ecommerce.sdk.services.deliveryoptionsresponse.deliveryoptionsresponse(v=AX.60)
ms:contentKeyID: 65316138
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
dev_langs:
- vb
- csharp
- c++
---

# DeliveryOptionsResponse Constructor (Collection(DeliveryOption), Collection(LineDeliveryOption))

**Namespace:**  [Microsoft.Dynamics.Retail.Ecommerce.Sdk.Services](microsoft-dynamics-retail-ecommerce-sdk-services-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Retail.Ecommerce.Sdk.Services (in Microsoft.Dynamics.Retail.Ecommerce.Sdk.Services.dll)

## Syntax

``` vb
'Declaration
Public Sub New ( _
    deliveryOptions As Collection(Of DeliveryOption), _
    lineDeliveryOptions As Collection(Of LineDeliveryOption) _
)
'Usage
Dim deliveryOptions As Collection(Of DeliveryOption)
Dim lineDeliveryOptions As Collection(Of LineDeliveryOption)

Dim instance As New DeliveryOptionsResponse(deliveryOptions, _
    lineDeliveryOptions)
```

``` csharp
public DeliveryOptionsResponse(
    Collection<DeliveryOption> deliveryOptions,
    Collection<LineDeliveryOption> lineDeliveryOptions
)
```

``` c++
public:
DeliveryOptionsResponse(
    Collection<DeliveryOption^>^ deliveryOptions, 
    Collection<LineDeliveryOption^>^ lineDeliveryOptions
)
```

#### Parameters

  - deliveryOptions  
    Type: [System.Collections.ObjectModel.Collection](https://technet.microsoft.com/library/ms132397\(v=ax.60\))\<[DeliveryOption](deliveryoption-class-microsoft-dynamics-retail-ecommerce-sdk-core-models.md)\>  

<!-- end list -->

  - lineDeliveryOptions  
    Type: [System.Collections.ObjectModel.Collection](https://technet.microsoft.com/library/ms132397\(v=ax.60\))\<[LineDeliveryOption](linedeliveryoption-class-microsoft-dynamics-retail-ecommerce-sdk-core-models.md)\>  

## See Also

#### Reference

[DeliveryOptionsResponse Class](deliveryoptionsresponse-class-microsoft-dynamics-retail-ecommerce-sdk-services.md)

[DeliveryOptionsResponse Overload](deliveryoptionsresponse-constructor-microsoft-dynamics-retail-ecommerce-sdk-services.md)

[Microsoft.Dynamics.Retail.Ecommerce.Sdk.Services Namespace](microsoft-dynamics-retail-ecommerce-sdk-services-namespace.md)

