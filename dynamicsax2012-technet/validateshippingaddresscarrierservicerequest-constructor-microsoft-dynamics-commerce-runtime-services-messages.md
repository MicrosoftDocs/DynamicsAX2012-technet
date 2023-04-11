---
title: ValidateShippingAddressCarrierServiceRequest Constructor  (Microsoft.Dynamics.Commerce.Runtime.Services.Messages)
TOCTitle: ValidateShippingAddressCarrierServiceRequest Constructor
ms:assetid: M:Microsoft.Dynamics.Commerce.Runtime.Services.Messages.ValidateShippingAddressCarrierServiceRequest.#ctor(Microsoft.Dynamics.Commerce.Runtime.ParameterSet,Microsoft.Dynamics.Commerce.Runtime.DataModel.Address,System.Boolean)
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.services.messages.validateshippingaddresscarrierservicerequest.validateshippingaddresscarrierservicerequest(v=AX.60)
ms:contentKeyID: 65318939
author: tonyafehr
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.Services.Messages.ValidateShippingAddressCarrierServiceRequest.#ctor
dev_langs:
- CSharp
- C++
- VB
---

# ValidateShippingAddressCarrierServiceRequest Constructor


[!INCLUDE[archive-banner](includes/archive-banner.md)]

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.Services.Messages](microsoft-dynamics-commerce-runtime-services-messages-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Services.Messages (in Microsoft.Dynamics.Commerce.Runtime.Services.Messages.dll)

## Syntax

``` vb
'Declaration
Public Sub New ( _
    adapterConfig As ParameterSet, _
    addressToValidate As Address, _
    suggestAddresses As Boolean _
)
'Usage
Dim adapterConfig As ParameterSet
Dim addressToValidate As Address
Dim suggestAddresses As Boolean

Dim instance As New ValidateShippingAddressCarrierServiceRequest(adapterConfig, _
    addressToValidate, suggestAddresses)
```

``` csharp
public ValidateShippingAddressCarrierServiceRequest(
    ParameterSet adapterConfig,
    Address addressToValidate,
    bool suggestAddresses
)
```

``` c++
public:
ValidateShippingAddressCarrierServiceRequest(
    ParameterSet^ adapterConfig, 
    Address^ addressToValidate, 
    bool suggestAddresses
)
```

#### Parameters

  - adapterConfig  
    Type: [Microsoft.Dynamics.Commerce.Runtime.ParameterSet](parameterset-class-microsoft-dynamics-commerce-runtime.md)  

<!-- end list -->

  - addressToValidate  
    Type: [Microsoft.Dynamics.Commerce.Runtime.DataModel.Address](address-class-microsoft-dynamics-commerce-runtime-datamodel.md)  

<!-- end list -->

  - suggestAddresses  
    Type: [System.Boolean](https://technet.microsoft.com/library/a28wyd50\(v=ax.60\))  

## See Also

#### Reference

[ValidateShippingAddressCarrierServiceRequest Class](validateshippingaddresscarrierservicerequest-class-microsoft-dynamics-commerce-runtime-services-messages.md)

[Microsoft.Dynamics.Commerce.Runtime.Services.Messages Namespace](microsoft-dynamics-commerce-runtime-services-messages-namespace.md)

