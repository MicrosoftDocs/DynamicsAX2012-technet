---
title: CreateAddressServiceRequest Constructor  (Microsoft.Dynamics.Commerce.Runtime.Services.Messages)
TOCTitle: CreateAddressServiceRequest Constructor
ms:assetid: M:Microsoft.Dynamics.Commerce.Runtime.Services.Messages.CreateAddressServiceRequest.#ctor(Microsoft.Dynamics.Commerce.Runtime.DataModel.Customer,Microsoft.Dynamics.Commerce.Runtime.DataModel.Address)
ms:mtpsurl: https://technet.microsoft.com/en-us/library/microsoft.dynamics.commerce.runtime.services.messages.createaddressservicerequest.createaddressservicerequest(v=AX.60)
ms:contentKeyID: 65320989
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.Services.Messages.CreateAddressServiceRequest.#ctor
dev_langs:
- CSharp
- C++
- VB
---

# CreateAddressServiceRequest Constructor

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.Services.Messages](microsoft-dynamics-commerce-runtime-services-messages-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Services.Messages (in Microsoft.Dynamics.Commerce.Runtime.Services.Messages.dll)

## Syntax

``` vb
'Declaration
Public Sub New ( _
    customer As Customer, _
    address As Address _
)
'Usage
Dim customer As Customer
Dim address As Address

Dim instance As New CreateAddressServiceRequest(customer, _
    address)
```

``` csharp
public CreateAddressServiceRequest(
    Customer customer,
    Address address
)
```

``` c++
public:
CreateAddressServiceRequest(
    Customer^ customer, 
    Address^ address
)
```

#### Parameters

  - customer  
    Type: [Microsoft.Dynamics.Commerce.Runtime.DataModel.Customer](customer-class-microsoft-dynamics-commerce-runtime-datamodel.md)  

<!-- end list -->

  - address  
    Type: [Microsoft.Dynamics.Commerce.Runtime.DataModel.Address](address-class-microsoft-dynamics-commerce-runtime-datamodel.md)  

## See Also

#### Reference

[CreateAddressServiceRequest Class](createaddressservicerequest-class-microsoft-dynamics-commerce-runtime-services-messages.md)

[Microsoft.Dynamics.Commerce.Runtime.Services.Messages Namespace](microsoft-dynamics-commerce-runtime-services-messages-namespace.md)

