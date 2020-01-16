---
title: GetLineDeliveryOptionsServiceRequest.ShippingAddress Property  (Microsoft.Dynamics.Commerce.Runtime.Services.Messages)
TOCTitle: ShippingAddress Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.Services.Messages.GetLineDeliveryOptionsServiceRequest.ShippingAddress
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.services.messages.getlinedeliveryoptionsservicerequest.shippingaddress(v=AX.60)
ms:contentKeyID: 62212255
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.Services.Messages.GetLineDeliveryOptionsServiceRequest.ShippingAddress
dev_langs:
- CSharp
- C++
- VB
---

# ShippingAddress Property

Gets the shipping address used for the request.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.Services.Messages](microsoft-dynamics-commerce-runtime-services-messages-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Services.Messages (in Microsoft.Dynamics.Commerce.Runtime.Services.Messages.dll)

## Syntax

``` vb
'Declaration
<DataMemberAttribute> _
Public Property ShippingAddress As Address
    Get
    Private Set
'Usage
Dim instance As GetLineDeliveryOptionsServiceRequest
Dim value As Address

value = instance.ShippingAddress
```

``` csharp
[DataMemberAttribute]
public Address ShippingAddress { get; private set; }
```

``` c++
[DataMemberAttribute]
public:
property Address^ ShippingAddress {
    Address^ get ();
    private: void set (Address^ value);
}
```

#### Property Value

Type: [Microsoft.Dynamics.Commerce.Runtime.DataModel.Address](address-class-microsoft-dynamics-commerce-runtime-datamodel.md)  
Returns [Address](address-class-microsoft-dynamics-commerce-runtime-datamodel.md).  

## Remarks

If not provided, the addresses set in the lines will be used.

## See Also

#### Reference

[GetLineDeliveryOptionsServiceRequest Class](getlinedeliveryoptionsservicerequest-class-microsoft-dynamics-commerce-runtime-services-messages.md)

[Microsoft.Dynamics.Commerce.Runtime.Services.Messages Namespace](microsoft-dynamics-commerce-runtime-services-messages-namespace.md)

