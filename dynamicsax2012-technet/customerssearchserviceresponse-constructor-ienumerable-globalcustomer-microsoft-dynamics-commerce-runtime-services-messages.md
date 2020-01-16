---
title: CustomersSearchServiceResponse Constructor (IEnumerable(GlobalCustomer)) (Microsoft.Dynamics.Commerce.Runtime.Services.Messages)
TOCTitle: CustomersSearchServiceResponse Constructor (IEnumerable(GlobalCustomer))
ms:assetid: M:Microsoft.Dynamics.Commerce.Runtime.Services.Messages.CustomersSearchServiceResponse.#ctor(System.Collections.Generic.IEnumerable{Microsoft.Dynamics.Commerce.Runtime.DataModel.GlobalCustomer})
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.services.messages.customerssearchserviceresponse.customerssearchserviceresponse(v=AX.60)
ms:contentKeyID: 62206297
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
dev_langs:
- vb
- csharp
- c++
---

# CustomersSearchServiceResponse Constructor (IEnumerable(GlobalCustomer))

Initializes a new instance of the [CustomersSearchServiceResponse](customerssearchserviceresponse-class-microsoft-dynamics-commerce-runtime-services-messages.md) class.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.Services.Messages](microsoft-dynamics-commerce-runtime-services-messages-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Services.Messages (in Microsoft.Dynamics.Commerce.Runtime.Services.Messages.dll)

## Syntax

``` vb
'Declaration
Public Sub New ( _
    customers As IEnumerable(Of GlobalCustomer) _
)
'Usage
Dim customers As IEnumerable(Of GlobalCustomer)

Dim instance As New CustomersSearchServiceResponse(customers)
```

``` csharp
public CustomersSearchServiceResponse(
    IEnumerable<GlobalCustomer> customers
)
```

``` c++
public:
CustomersSearchServiceResponse(
    IEnumerable<GlobalCustomer^>^ customers
)
```

#### Parameters

  - customers  
    Type: [System.Collections.Generic.IEnumerable](https://technet.microsoft.com/library/9eekhta0\(v=ax.60\))\<[GlobalCustomer](globalcustomer-class-microsoft-dynamics-commerce-runtime-datamodel.md)\>  

## See Also

#### Reference

[CustomersSearchServiceResponse Class](customerssearchserviceresponse-class-microsoft-dynamics-commerce-runtime-services-messages.md)

[CustomersSearchServiceResponse Overload](customerssearchserviceresponse-constructor-microsoft-dynamics-commerce-runtime-services-messages.md)

[Microsoft.Dynamics.Commerce.Runtime.Services.Messages Namespace](microsoft-dynamics-commerce-runtime-services-messages-namespace.md)

