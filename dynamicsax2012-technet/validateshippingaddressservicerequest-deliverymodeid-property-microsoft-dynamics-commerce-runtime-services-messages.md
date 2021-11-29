---
title: ValidateShippingAddressServiceRequest.DeliveryModeId Property  (Microsoft.Dynamics.Commerce.Runtime.Services.Messages)
TOCTitle: DeliveryModeId Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.Services.Messages.ValidateShippingAddressServiceRequest.DeliveryModeId
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.services.messages.validateshippingaddressservicerequest.deliverymodeid(v=AX.60)
ms:contentKeyID: 49835378
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.Services.Messages.ValidateShippingAddressServiceRequest.DeliveryModeId
dev_langs:
- CSharp
- C++
- VB
---

# DeliveryModeId Property


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Gets the delivery mode identifier to service this request.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.Services.Messages](microsoft-dynamics-commerce-runtime-services-messages-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Services.Messages (in Microsoft.Dynamics.Commerce.Runtime.Services.Messages.dll)

## Syntax

``` vb
'Declaration
<DataMemberAttribute> _
Public Property DeliveryModeId As String
    Get
    Private Set
'Usage
Dim instance As ValidateShippingAddressServiceRequest
Dim value As String

value = instance.DeliveryModeId
```

``` csharp
[DataMemberAttribute]
public string DeliveryModeId { get; private set; }
```

``` c++
[DataMemberAttribute]
public:
property String^ DeliveryModeId {
    String^ get ();
    private: void set (String^ value);
}
```

#### Property Value

Type: [System.String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\))  
Returns [String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\)).  

## See Also

#### Reference

[ValidateShippingAddressServiceRequest Class](validateshippingaddressservicerequest-class-microsoft-dynamics-commerce-runtime-services-messages.md)

[Microsoft.Dynamics.Commerce.Runtime.Services.Messages Namespace](microsoft-dynamics-commerce-runtime-services-messages-namespace.md)

