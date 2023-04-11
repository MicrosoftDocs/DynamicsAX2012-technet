---
title: GetProductDeliveryOptionsRequest.ShippingAddress Property  (Microsoft.Dynamics.Commerce.Runtime.Messages)
TOCTitle: ShippingAddress Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.Messages.GetProductDeliveryOptionsRequest.ShippingAddress
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.messages.getproductdeliveryoptionsrequest.shippingaddress(v=AX.60)
ms:contentKeyID: 49838560
author: tonyafehr
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.Messages.GetProductDeliveryOptionsRequest.ShippingAddress
dev_langs:
- CSharp
- C++
- VB
---

# ShippingAddress Property


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Gets or sets the shipping address based on which the delivery options are computed.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.Messages](microsoft-dynamics-commerce-runtime-messages-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Messages (in Microsoft.Dynamics.Commerce.Runtime.Messages.dll)

## Syntax

``` vb
'Declaration
<DataMemberAttribute> _
Public Property ShippingAddress As Address
    Get
    Set
'Usage
Dim instance As GetProductDeliveryOptionsRequest
Dim value As Address

value = instance.ShippingAddress

instance.ShippingAddress = value
```

``` csharp
[DataMemberAttribute]
public Address ShippingAddress { get; set; }
```

``` c++
[DataMemberAttribute]
public:
property Address^ ShippingAddress {
    Address^ get ();
    void set (Address^ value);
}
```

#### Property Value

Type: [Microsoft.Dynamics.Commerce.Runtime.DataModel.Address](address-class-microsoft-dynamics-commerce-runtime-datamodel.md)  
Returns [Address](address-class-microsoft-dynamics-commerce-runtime-datamodel.md).  

## See Also

#### Reference

[GetProductDeliveryOptionsRequest Class](getproductdeliveryoptionsrequest-class-microsoft-dynamics-commerce-runtime-messages.md)

[Microsoft.Dynamics.Commerce.Runtime.Messages Namespace](microsoft-dynamics-commerce-runtime-messages-namespace.md)

