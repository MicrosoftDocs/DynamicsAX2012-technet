---
title: DeactivateAddressServiceRequest Constructor  (Microsoft.Dynamics.Commerce.Runtime.Services.Messages)
TOCTitle: DeactivateAddressServiceRequest Constructor
ms:assetid: M:Microsoft.Dynamics.Commerce.Runtime.Services.Messages.DeactivateAddressServiceRequest.#ctor(System.Int64,System.Int64)
ms:mtpsurl: https://technet.microsoft.com/en-us/library/microsoft.dynamics.commerce.runtime.services.messages.deactivateaddressservicerequest.deactivateaddressservicerequest(v=AX.60)
ms:contentKeyID: 65319966
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.Services.Messages.DeactivateAddressServiceRequest.#ctor
dev_langs:
- CSharp
- C++
- VB
---

# DeactivateAddressServiceRequest Constructor

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.Services.Messages](microsoft-dynamics-commerce-runtime-services-messages-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Services.Messages (in Microsoft.Dynamics.Commerce.Runtime.Services.Messages.dll)

## Syntax

``` vb
'Declaration
Public Sub New ( _
    addressId As Long, _
    customerId As Long _
)
'Usage
Dim addressId As Long
Dim customerId As Long

Dim instance As New DeactivateAddressServiceRequest(addressId, _
    customerId)
```

``` csharp
public DeactivateAddressServiceRequest(
    long addressId,
    long customerId
)
```

``` c++
public:
DeactivateAddressServiceRequest(
    long long addressId, 
    long long customerId
)
```

#### Parameters

  - addressId  
    Type: [System.Int64](https://technet.microsoft.com/en-us/library/6yy583ek\(v=ax.60\))  

<!-- end list -->

  - customerId  
    Type: [System.Int64](https://technet.microsoft.com/en-us/library/6yy583ek\(v=ax.60\))  

## See Also

#### Reference

[DeactivateAddressServiceRequest Class](deactivateaddressservicerequest-class-microsoft-dynamics-commerce-runtime-services-messages.md)

[Microsoft.Dynamics.Commerce.Runtime.Services.Messages Namespace](microsoft-dynamics-commerce-runtime-services-messages-namespace.md)

