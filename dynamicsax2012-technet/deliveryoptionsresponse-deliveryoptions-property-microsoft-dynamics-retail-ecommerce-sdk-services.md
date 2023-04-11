---
title: DeliveryOptionsResponse.DeliveryOptions Property  (Microsoft.Dynamics.Retail.Ecommerce.Sdk.Services)
TOCTitle: DeliveryOptions Property
ms:assetid: P:Microsoft.Dynamics.Retail.Ecommerce.Sdk.Services.DeliveryOptionsResponse.DeliveryOptions
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.retail.ecommerce.sdk.services.deliveryoptionsresponse.deliveryoptions(v=AX.60)
ms:contentKeyID: 65315596
author: tonyafehr
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Retail.Ecommerce.Sdk.Services.DeliveryOptionsResponse.DeliveryOptions
dev_langs:
- CSharp
- C++
- VB
---

# DeliveryOptions Property


[!INCLUDE[archive-banner](includes/archive-banner.md)]

**Namespace:**  [Microsoft.Dynamics.Retail.Ecommerce.Sdk.Services](microsoft-dynamics-retail-ecommerce-sdk-services-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Retail.Ecommerce.Sdk.Services (in Microsoft.Dynamics.Retail.Ecommerce.Sdk.Services.dll)

## Syntax

``` vb
'Declaration
<DataMemberAttribute> _
Public Property DeliveryOptions As Collection(Of DeliveryOption)
    Get
    Private Set
'Usage
Dim instance As DeliveryOptionsResponse
Dim value As Collection(Of DeliveryOption)

value = instance.DeliveryOptions
```

``` csharp
[DataMemberAttribute]
public Collection<DeliveryOption> DeliveryOptions { get; private set; }
```

``` c++
[DataMemberAttribute]
public:
property Collection<DeliveryOption^>^ DeliveryOptions {
    Collection<DeliveryOption^>^ get ();
    private: void set (Collection<DeliveryOption^>^ value);
}
```

#### Property Value

Type: [System.Collections.ObjectModel.Collection](https://technet.microsoft.com/library/ms132397\(v=ax.60\))\<[DeliveryOption](deliveryoption-class-microsoft-dynamics-retail-ecommerce-sdk-core-models.md)\>  

## See Also

#### Reference

[DeliveryOptionsResponse Class](deliveryoptionsresponse-class-microsoft-dynamics-retail-ecommerce-sdk-services.md)

[Microsoft.Dynamics.Retail.Ecommerce.Sdk.Services Namespace](microsoft-dynamics-retail-ecommerce-sdk-services-namespace.md)

