---
title: DeliveryOptionsResponse.SetDeliveryOptions Method  (Microsoft.Dynamics.Retail.Ecommerce.Sdk.Services)
TOCTitle: SetDeliveryOptions Method
ms:assetid: M:Microsoft.Dynamics.Retail.Ecommerce.Sdk.Services.DeliveryOptionsResponse.SetDeliveryOptions(System.Collections.ObjectModel.Collection{Microsoft.Dynamics.Retail.Ecommerce.Sdk.Core.Models.DeliveryOption})
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.retail.ecommerce.sdk.services.deliveryoptionsresponse.setdeliveryoptions(v=AX.60)
ms:contentKeyID: 65317415
author: tonyafehr
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Retail.Ecommerce.Sdk.Services.DeliveryOptionsResponse.SetDeliveryOptions
dev_langs:
- CSharp
- C++
- VB
---

# SetDeliveryOptions Method


[!INCLUDE[archive-banner](includes/archive-banner.md)]

**Namespace:**  [Microsoft.Dynamics.Retail.Ecommerce.Sdk.Services](microsoft-dynamics-retail-ecommerce-sdk-services-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Retail.Ecommerce.Sdk.Services (in Microsoft.Dynamics.Retail.Ecommerce.Sdk.Services.dll)

## Syntax

``` vb
'Declaration
Public Sub SetDeliveryOptions ( _
    deliveryMethods As Collection(Of DeliveryOption) _
)
'Usage
Dim instance As DeliveryOptionsResponse
Dim deliveryMethods As Collection(Of DeliveryOption)

instance.SetDeliveryOptions(deliveryMethods)
```

``` csharp
public void SetDeliveryOptions(
    Collection<DeliveryOption> deliveryMethods
)
```

``` c++
public:
void SetDeliveryOptions(
    Collection<DeliveryOption^>^ deliveryMethods
)
```

#### Parameters

  - deliveryMethods  
    Type: [System.Collections.ObjectModel.Collection](https://technet.microsoft.com/library/ms132397\(v=ax.60\))\<[DeliveryOption](deliveryoption-class-microsoft-dynamics-retail-ecommerce-sdk-core-models.md)\>  

## See Also

#### Reference

[DeliveryOptionsResponse Class](deliveryoptionsresponse-class-microsoft-dynamics-retail-ecommerce-sdk-services.md)

[Microsoft.Dynamics.Retail.Ecommerce.Sdk.Services Namespace](microsoft-dynamics-retail-ecommerce-sdk-services-namespace.md)

