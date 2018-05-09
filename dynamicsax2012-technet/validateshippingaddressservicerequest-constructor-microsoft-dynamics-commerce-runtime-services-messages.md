---
title: ValidateShippingAddressServiceRequest Constructor  (Microsoft.Dynamics.Commerce.Runtime.Services.Messages)
TOCTitle: ValidateShippingAddressServiceRequest Constructor
ms:assetid: M:Microsoft.Dynamics.Commerce.Runtime.Services.Messages.ValidateShippingAddressServiceRequest.#ctor(Microsoft.Dynamics.Commerce.Runtime.DataModel.Address,System.Boolean,System.String)
ms:mtpsurl: https://technet.microsoft.com/en-us/library/microsoft.dynamics.commerce.runtime.services.messages.validateshippingaddressservicerequest.validateshippingaddressservicerequest(v=AX.60)
ms:contentKeyID: 65318501
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.Services.Messages.ValidateShippingAddressServiceRequest.#ctor
dev_langs:
- CSharp
- C++
- VB
---

# ValidateShippingAddressServiceRequest Constructor

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.Services.Messages](microsoft-dynamics-commerce-runtime-services-messages-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Services.Messages (in Microsoft.Dynamics.Commerce.Runtime.Services.Messages.dll)

## Syntax

``` vb
'Declaration
Public Sub New ( _
    addressToValidate As Address, _
    suggestAddresses As Boolean, _
    deliveryModeId As String _
)
'Usage
Dim addressToValidate As Address
Dim suggestAddresses As Boolean
Dim deliveryModeId As String

Dim instance As New ValidateShippingAddressServiceRequest(addressToValidate, _
    suggestAddresses, deliveryModeId)
```

``` csharp
public ValidateShippingAddressServiceRequest(
    Address addressToValidate,
    bool suggestAddresses,
    string deliveryModeId
)
```

``` c++
public:
ValidateShippingAddressServiceRequest(
    Address^ addressToValidate, 
    bool suggestAddresses, 
    String^ deliveryModeId
)
```

#### Parameters

  - addressToValidate  
    Type: [Microsoft.Dynamics.Commerce.Runtime.DataModel.Address](address-class-microsoft-dynamics-commerce-runtime-datamodel.md)  

<!-- end list -->

  - suggestAddresses  
    Type: [System.Boolean](https://technet.microsoft.com/en-us/library/a28wyd50\(v=ax.60\))  

<!-- end list -->

  - deliveryModeId  
    Type: [System.String](https://technet.microsoft.com/en-us/library/s1wwdcbf\(v=ax.60\))  

## See Also

#### Reference

[ValidateShippingAddressServiceRequest Class](validateshippingaddressservicerequest-class-microsoft-dynamics-commerce-runtime-services-messages.md)

[Microsoft.Dynamics.Commerce.Runtime.Services.Messages Namespace](microsoft-dynamics-commerce-runtime-services-messages-namespace.md)

