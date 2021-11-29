---
title: GetCustomersResponse Constructor (IEnumerable(Customer)) (Microsoft.Dynamics.Commerce.Runtime.Messages)
TOCTitle: GetCustomersResponse Constructor (IEnumerable(Customer))
ms:assetid: M:Microsoft.Dynamics.Commerce.Runtime.Messages.GetCustomersResponse.#ctor(System.Collections.Generic.IEnumerable{Microsoft.Dynamics.Commerce.Runtime.DataModel.Customer})
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.messages.getcustomersresponse.getcustomersresponse(v=AX.60)
ms:contentKeyID: 49832766
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
dev_langs:
- vb
- csharp
- c++
---

# GetCustomersResponse Constructor (IEnumerable(Customer))


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Initializes a new instance of the [GetCustomersResponse](getcustomersresponse-class-microsoft-dynamics-commerce-runtime-messages.md) class.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.Messages](microsoft-dynamics-commerce-runtime-messages-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Messages (in Microsoft.Dynamics.Commerce.Runtime.Messages.dll)

## Syntax

``` vb
'Declaration
Public Sub New ( _
    customers As IEnumerable(Of Customer) _
)
'Usage
Dim customers As IEnumerable(Of Customer)

Dim instance As New GetCustomersResponse(customers)
```

``` csharp
public GetCustomersResponse(
    IEnumerable<Customer> customers
)
```

``` c++
public:
GetCustomersResponse(
    IEnumerable<Customer^>^ customers
)
```

#### Parameters

  - customers  
    Type: [System.Collections.Generic.IEnumerable](https://technet.microsoft.com/library/9eekhta0\(v=ax.60\))\<[Customer](customer-class-microsoft-dynamics-commerce-runtime-datamodel.md)\>  

## See Also

#### Reference

[GetCustomersResponse Class](getcustomersresponse-class-microsoft-dynamics-commerce-runtime-messages.md)

[GetCustomersResponse Overload](getcustomersresponse-constructor-microsoft-dynamics-commerce-runtime-messages.md)

[Microsoft.Dynamics.Commerce.Runtime.Messages Namespace](microsoft-dynamics-commerce-runtime-messages-namespace.md)

