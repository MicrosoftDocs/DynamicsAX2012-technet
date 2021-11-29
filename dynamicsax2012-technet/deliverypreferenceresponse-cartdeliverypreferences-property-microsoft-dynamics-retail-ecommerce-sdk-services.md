---
title: DeliveryPreferenceResponse.CartDeliveryPreferences Property  (Microsoft.Dynamics.Retail.Ecommerce.Sdk.Services)
TOCTitle: CartDeliveryPreferences Property
ms:assetid: P:Microsoft.Dynamics.Retail.Ecommerce.Sdk.Services.DeliveryPreferenceResponse.CartDeliveryPreferences
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.retail.ecommerce.sdk.services.deliverypreferenceresponse.cartdeliverypreferences(v=AX.60)
ms:contentKeyID: 65317259
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Retail.Ecommerce.Sdk.Services.DeliveryPreferenceResponse.CartDeliveryPreferences
dev_langs:
- CSharp
- C++
- VB
---

# CartDeliveryPreferences Property


[!INCLUDE[archive-banner](includes/archive-banner.md)]

**Namespace:**  [Microsoft.Dynamics.Retail.Ecommerce.Sdk.Services](microsoft-dynamics-retail-ecommerce-sdk-services-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Retail.Ecommerce.Sdk.Services (in Microsoft.Dynamics.Retail.Ecommerce.Sdk.Services.dll)

## Syntax

``` vb
'Declaration
<DataMemberAttribute> _
Public Property CartDeliveryPreferences As CartDeliveryPreferences
    Get
    Set
'Usage
Dim instance As DeliveryPreferenceResponse
Dim value As CartDeliveryPreferences

value = instance.CartDeliveryPreferences

instance.CartDeliveryPreferences = value
```

``` csharp
[DataMemberAttribute]
public CartDeliveryPreferences CartDeliveryPreferences { get; set; }
```

``` c++
[DataMemberAttribute]
public:
property CartDeliveryPreferences^ CartDeliveryPreferences {
    CartDeliveryPreferences^ get ();
    void set (CartDeliveryPreferences^ value);
}
```

#### Property Value

Type: [Microsoft.Dynamics.Retail.Ecommerce.Sdk.Core.Models.CartDeliveryPreferences](cartdeliverypreferences-class-microsoft-dynamics-retail-ecommerce-sdk-core-models.md)  

## See Also

#### Reference

[DeliveryPreferenceResponse Class](deliverypreferenceresponse-class-microsoft-dynamics-retail-ecommerce-sdk-services.md)

[Microsoft.Dynamics.Retail.Ecommerce.Sdk.Services Namespace](microsoft-dynamics-retail-ecommerce-sdk-services-namespace.md)

