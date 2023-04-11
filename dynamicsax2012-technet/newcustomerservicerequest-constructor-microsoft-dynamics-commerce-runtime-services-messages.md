---
title: NewCustomerServiceRequest Constructor  (Microsoft.Dynamics.Commerce.Runtime.Services.Messages)
TOCTitle: NewCustomerServiceRequest Constructor
ms:assetid: M:Microsoft.Dynamics.Commerce.Runtime.Services.Messages.NewCustomerServiceRequest.#ctor(Microsoft.Dynamics.Commerce.Runtime.DataModel.Customer,System.Int64)
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.services.messages.newcustomerservicerequest.newcustomerservicerequest(v=AX.60)
ms:contentKeyID: 65320700
author: tonyafehr
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.Services.Messages.NewCustomerServiceRequest.#ctor
dev_langs:
- CSharp
- C++
- VB
---

# NewCustomerServiceRequest Constructor


[!INCLUDE[archive-banner](includes/archive-banner.md)]

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.Services.Messages](microsoft-dynamics-commerce-runtime-services-messages-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Services.Messages (in Microsoft.Dynamics.Commerce.Runtime.Services.Messages.dll)

## Syntax

``` vb
'Declaration
Public Sub New ( _
    customer As Customer, _
    channelId As Long _
)
'Usage
Dim customer As Customer
Dim channelId As Long

Dim instance As New NewCustomerServiceRequest(customer, _
    channelId)
```

``` csharp
public NewCustomerServiceRequest(
    Customer customer,
    long channelId
)
```

``` c++
public:
NewCustomerServiceRequest(
    Customer^ customer, 
    long long channelId
)
```

#### Parameters

  - customer  
    Type: [Microsoft.Dynamics.Commerce.Runtime.DataModel.Customer](customer-class-microsoft-dynamics-commerce-runtime-datamodel.md)  

<!-- end list -->

  - channelId  
    Type: [System.Int64](https://technet.microsoft.com/library/6yy583ek\(v=ax.60\))  

## See Also

#### Reference

[NewCustomerServiceRequest Class](newcustomerservicerequest-class-microsoft-dynamics-commerce-runtime-services-messages.md)

[Microsoft.Dynamics.Commerce.Runtime.Services.Messages Namespace](microsoft-dynamics-commerce-runtime-services-messages-namespace.md)

