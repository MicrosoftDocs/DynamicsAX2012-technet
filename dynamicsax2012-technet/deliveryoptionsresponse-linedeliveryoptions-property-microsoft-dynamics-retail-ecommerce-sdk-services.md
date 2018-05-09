---
title: DeliveryOptionsResponse.LineDeliveryOptions Property  (Microsoft.Dynamics.Retail.Ecommerce.Sdk.Services)
TOCTitle: LineDeliveryOptions Property
ms:assetid: P:Microsoft.Dynamics.Retail.Ecommerce.Sdk.Services.DeliveryOptionsResponse.LineDeliveryOptions
ms:mtpsurl: https://technet.microsoft.com/en-us/library/microsoft.dynamics.retail.ecommerce.sdk.services.deliveryoptionsresponse.linedeliveryoptions(v=AX.60)
ms:contentKeyID: 65315775
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Retail.Ecommerce.Sdk.Services.DeliveryOptionsResponse.LineDeliveryOptions
dev_langs:
- CSharp
- C++
- VB
---

# LineDeliveryOptions Property

**Namespace:**  [Microsoft.Dynamics.Retail.Ecommerce.Sdk.Services](microsoft-dynamics-retail-ecommerce-sdk-services-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Retail.Ecommerce.Sdk.Services (in Microsoft.Dynamics.Retail.Ecommerce.Sdk.Services.dll)

## Syntax

``` vb
'Declaration
<DataMemberAttribute> _
Public Property LineDeliveryOptions As Collection(Of LineDeliveryOption)
    Get
    Private Set
'Usage
Dim instance As DeliveryOptionsResponse
Dim value As Collection(Of LineDeliveryOption)

value = instance.LineDeliveryOptions
```

``` csharp
[DataMemberAttribute]
public Collection<LineDeliveryOption> LineDeliveryOptions { get; private set; }
```

``` c++
[DataMemberAttribute]
public:
property Collection<LineDeliveryOption^>^ LineDeliveryOptions {
    Collection<LineDeliveryOption^>^ get ();
    private: void set (Collection<LineDeliveryOption^>^ value);
}
```

#### Property Value

Type: [System.Collections.ObjectModel.Collection](https://technet.microsoft.com/en-us/library/ms132397\(v=ax.60\))\<[LineDeliveryOption](linedeliveryoption-class-microsoft-dynamics-retail-ecommerce-sdk-core-models.md)\>  

## See Also

#### Reference

[DeliveryOptionsResponse Class](deliveryoptionsresponse-class-microsoft-dynamics-retail-ecommerce-sdk-services.md)

[Microsoft.Dynamics.Retail.Ecommerce.Sdk.Services Namespace](microsoft-dynamics-retail-ecommerce-sdk-services-namespace.md)

