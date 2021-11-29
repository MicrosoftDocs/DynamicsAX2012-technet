---
title: IndiaGetInterStateTaxRegimeServiceRequest.ShippingToAddress Property  (Microsoft.Dynamics.Commerce.Runtime.Services.Messages)
TOCTitle: ShippingToAddress Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.Services.Messages.IndiaGetInterStateTaxRegimeServiceRequest.ShippingToAddress
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.services.messages.indiagetinterstatetaxregimeservicerequest.shippingtoaddress(v=AX.60)
ms:contentKeyID: 65320648
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.Services.Messages.IndiaGetInterStateTaxRegimeServiceRequest.ShippingToAddress
dev_langs:
- CSharp
- C++
- VB
---

# ShippingToAddress Property


[!INCLUDE[archive-banner](includes/archive-banner.md)]

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.Services.Messages](microsoft-dynamics-commerce-runtime-services-messages-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Services.Messages (in Microsoft.Dynamics.Commerce.Runtime.Services.Messages.dll)

## Syntax

``` vb
'Declaration
<DataMemberAttribute> _
Public Property ShippingToAddress As Address
    Get
    Private Set
'Usage
Dim instance As IndiaGetInterStateTaxRegimeServiceRequest
Dim value As Address

value = instance.ShippingToAddress
```

``` csharp
[DataMemberAttribute]
public Address ShippingToAddress { get; private set; }
```

``` c++
[DataMemberAttribute]
public:
property Address^ ShippingToAddress {
    Address^ get ();
    private: void set (Address^ value);
}
```

#### Property Value

Type: [Microsoft.Dynamics.Commerce.Runtime.DataModel.Address](address-class-microsoft-dynamics-commerce-runtime-datamodel.md)  

## See Also

#### Reference

[IndiaGetInterStateTaxRegimeServiceRequest Class](indiagetinterstatetaxregimeservicerequest-class-microsoft-dynamics-commerce-runtime-services-messages.md)

[Microsoft.Dynamics.Commerce.Runtime.Services.Messages Namespace](microsoft-dynamics-commerce-runtime-services-messages-namespace.md)

