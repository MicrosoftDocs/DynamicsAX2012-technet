---
title: ValidateShippingAddressCarrierServiceRequest.AddressToValidate Property  (Microsoft.Dynamics.Commerce.Runtime.Services.Messages)
TOCTitle: AddressToValidate Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.Services.Messages.ValidateShippingAddressCarrierServiceRequest.AddressToValidate
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.services.messages.validateshippingaddresscarrierservicerequest.addresstovalidate(v=AX.60)
ms:contentKeyID: 49853272
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.Services.Messages.ValidateShippingAddressCarrierServiceRequest.AddressToValidate
dev_langs:
- CSharp
- C++
- VB
---

# AddressToValidate Property


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Gets the address to validate.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.Services.Messages](microsoft-dynamics-commerce-runtime-services-messages-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Services.Messages (in Microsoft.Dynamics.Commerce.Runtime.Services.Messages.dll)

## Syntax

``` vb
'Declaration
<DataMemberAttribute> _
Public Property AddressToValidate As Address
    Get
    Private Set
'Usage
Dim instance As ValidateShippingAddressCarrierServiceRequest
Dim value As Address

value = instance.AddressToValidate
```

``` csharp
[DataMemberAttribute]
public Address AddressToValidate { get; private set; }
```

``` c++
[DataMemberAttribute]
public:
property Address^ AddressToValidate {
    Address^ get ();
    private: void set (Address^ value);
}
```

#### Property Value

Type: [Microsoft.Dynamics.Commerce.Runtime.DataModel.Address](address-class-microsoft-dynamics-commerce-runtime-datamodel.md)  
Returns [Address](address-class-microsoft-dynamics-commerce-runtime-datamodel.md).  

## See Also

#### Reference

[ValidateShippingAddressCarrierServiceRequest Class](validateshippingaddresscarrierservicerequest-class-microsoft-dynamics-commerce-runtime-services-messages.md)

[Microsoft.Dynamics.Commerce.Runtime.Services.Messages Namespace](microsoft-dynamics-commerce-runtime-services-messages-namespace.md)

