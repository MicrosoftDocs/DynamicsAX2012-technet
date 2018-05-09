---
title: DeliveryOptionsResponse.SetLineDeliveryOptions Method  (Microsoft.Dynamics.Retail.Ecommerce.Sdk.Services)
TOCTitle: SetLineDeliveryOptions Method
ms:assetid: M:Microsoft.Dynamics.Retail.Ecommerce.Sdk.Services.DeliveryOptionsResponse.SetLineDeliveryOptions(System.Collections.ObjectModel.Collection{Microsoft.Dynamics.Retail.Ecommerce.Sdk.Core.Models.LineDeliveryOption})
ms:mtpsurl: https://technet.microsoft.com/en-us/library/microsoft.dynamics.retail.ecommerce.sdk.services.deliveryoptionsresponse.setlinedeliveryoptions(v=AX.60)
ms:contentKeyID: 65318716
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Retail.Ecommerce.Sdk.Services.DeliveryOptionsResponse.SetLineDeliveryOptions
dev_langs:
- CSharp
- C++
- VB
---

# SetLineDeliveryOptions Method

**Namespace:**  [Microsoft.Dynamics.Retail.Ecommerce.Sdk.Services](microsoft-dynamics-retail-ecommerce-sdk-services-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Retail.Ecommerce.Sdk.Services (in Microsoft.Dynamics.Retail.Ecommerce.Sdk.Services.dll)

## Syntax

``` vb
'Declaration
Public Sub SetLineDeliveryOptions ( _
    itemDeliveryMethods As Collection(Of LineDeliveryOption) _
)
'Usage
Dim instance As DeliveryOptionsResponse
Dim itemDeliveryMethods As Collection(Of LineDeliveryOption)

instance.SetLineDeliveryOptions(itemDeliveryMethods)
```

``` csharp
public void SetLineDeliveryOptions(
    Collection<LineDeliveryOption> itemDeliveryMethods
)
```

``` c++
public:
void SetLineDeliveryOptions(
    Collection<LineDeliveryOption^>^ itemDeliveryMethods
)
```

#### Parameters

  - itemDeliveryMethods  
    Type: [System.Collections.ObjectModel.Collection](https://technet.microsoft.com/en-us/library/ms132397\(v=ax.60\))\<[LineDeliveryOption](linedeliveryoption-class-microsoft-dynamics-retail-ecommerce-sdk-core-models.md)\>  

## See Also

#### Reference

[DeliveryOptionsResponse Class](deliveryoptionsresponse-class-microsoft-dynamics-retail-ecommerce-sdk-services.md)

[Microsoft.Dynamics.Retail.Ecommerce.Sdk.Services Namespace](microsoft-dynamics-retail-ecommerce-sdk-services-namespace.md)

