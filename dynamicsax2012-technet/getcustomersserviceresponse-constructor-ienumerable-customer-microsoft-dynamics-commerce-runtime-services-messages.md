---
title: GetCustomersServiceResponse Constructor (IEnumerable(Customer)) (Microsoft.Dynamics.Commerce.Runtime.Services.Messages)
TOCTitle: GetCustomersServiceResponse Constructor (IEnumerable(Customer))
ms:assetid: M:Microsoft.Dynamics.Commerce.Runtime.Services.Messages.GetCustomersServiceResponse.#ctor(System.Collections.Generic.IEnumerable{Microsoft.Dynamics.Commerce.Runtime.DataModel.Customer})
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.services.messages.getcustomersserviceresponse.getcustomersserviceresponse(v=AX.60)
ms:contentKeyID: 49840714
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
dev_langs:
- vb
- csharp
- c++
---

# GetCustomersServiceResponse Constructor (IEnumerable(Customer))


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Initializes a new instance of the [GetCustomersServiceResponse](getcustomersserviceresponse-class-microsoft-dynamics-commerce-runtime-services-messages.md) class.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.Services.Messages](microsoft-dynamics-commerce-runtime-services-messages-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Services.Messages (in Microsoft.Dynamics.Commerce.Runtime.Services.Messages.dll)

## Syntax

``` vb
'Declaration
Public Sub New ( _
    customers As IEnumerable(Of Customer) _
)
'Usage
Dim customers As IEnumerable(Of Customer)

Dim instance As New GetCustomersServiceResponse(customers)
```

``` csharp
public GetCustomersServiceResponse(
    IEnumerable<Customer> customers
)
```

``` c++
public:
GetCustomersServiceResponse(
    IEnumerable<Customer^>^ customers
)
```

#### Parameters

  - customers  
    Type: [System.Collections.Generic.IEnumerable](https://technet.microsoft.com/library/9eekhta0\(v=ax.60\))\<[Customer](customer-class-microsoft-dynamics-commerce-runtime-datamodel.md)\>  

## See Also

#### Reference

[GetCustomersServiceResponse Class](getcustomersserviceresponse-class-microsoft-dynamics-commerce-runtime-services-messages.md)

[GetCustomersServiceResponse Overload](getcustomersserviceresponse-constructor-microsoft-dynamics-commerce-runtime-services-messages.md)

[Microsoft.Dynamics.Commerce.Runtime.Services.Messages Namespace](microsoft-dynamics-commerce-runtime-services-messages-namespace.md)

