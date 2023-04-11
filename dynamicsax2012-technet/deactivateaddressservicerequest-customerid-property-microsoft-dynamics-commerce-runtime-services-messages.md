---
title: DeactivateAddressServiceRequest.CustomerId Property  (Microsoft.Dynamics.Commerce.Runtime.Services.Messages)
TOCTitle: CustomerId Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.Services.Messages.DeactivateAddressServiceRequest.CustomerId
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.services.messages.deactivateaddressservicerequest.customerid(v=AX.60)
ms:contentKeyID: 65317565
author: tonyafehr
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.Services.Messages.DeactivateAddressServiceRequest.CustomerId
dev_langs:
- CSharp
- C++
- VB
---

# CustomerId Property


[!INCLUDE[archive-banner](includes/archive-banner.md)]

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.Services.Messages](microsoft-dynamics-commerce-runtime-services-messages-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Services.Messages (in Microsoft.Dynamics.Commerce.Runtime.Services.Messages.dll)

## Syntax

``` vb
'Declaration
<DataMemberAttribute> _
Public Property CustomerId As Long
    Get
    Protected Set
'Usage
Dim instance As DeactivateAddressServiceRequest
Dim value As Long

value = instance.CustomerId

instance.CustomerId = value
```

``` csharp
[DataMemberAttribute]
public long CustomerId { get; protected set; }
```

``` c++
[DataMemberAttribute]
public:
property long long CustomerId {
    long long get ();
    protected: void set (long long value);
}
```

#### Property Value

Type: [System.Int64](https://technet.microsoft.com/library/6yy583ek\(v=ax.60\))  

## See Also

#### Reference

[DeactivateAddressServiceRequest Class](deactivateaddressservicerequest-class-microsoft-dynamics-commerce-runtime-services-messages.md)

[Microsoft.Dynamics.Commerce.Runtime.Services.Messages Namespace](microsoft-dynamics-commerce-runtime-services-messages-namespace.md)

