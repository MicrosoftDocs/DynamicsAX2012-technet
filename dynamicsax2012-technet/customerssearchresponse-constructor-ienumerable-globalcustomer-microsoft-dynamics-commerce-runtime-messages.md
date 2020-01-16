---
title: CustomersSearchResponse Constructor (IEnumerable(GlobalCustomer)) (Microsoft.Dynamics.Commerce.Runtime.Messages)
TOCTitle: CustomersSearchResponse Constructor (IEnumerable(GlobalCustomer))
ms:assetid: M:Microsoft.Dynamics.Commerce.Runtime.Messages.CustomersSearchResponse.#ctor(System.Collections.Generic.IEnumerable{Microsoft.Dynamics.Commerce.Runtime.DataModel.GlobalCustomer})
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.messages.customerssearchresponse.customerssearchresponse(v=AX.60)
ms:contentKeyID: 62207990
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
dev_langs:
- vb
- csharp
- c++
---

# CustomersSearchResponse Constructor (IEnumerable(GlobalCustomer))

Initializes a new instance of the [CustomersSearchResponse](customerssearchresponse-class-microsoft-dynamics-commerce-runtime-messages.md) class.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.Messages](microsoft-dynamics-commerce-runtime-messages-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Messages (in Microsoft.Dynamics.Commerce.Runtime.Messages.dll)

## Syntax

``` vb
'Declaration
Public Sub New ( _
    customers As IEnumerable(Of GlobalCustomer) _
)
'Usage
Dim customers As IEnumerable(Of GlobalCustomer)

Dim instance As New CustomersSearchResponse(customers)
```

``` csharp
public CustomersSearchResponse(
    IEnumerable<GlobalCustomer> customers
)
```

``` c++
public:
CustomersSearchResponse(
    IEnumerable<GlobalCustomer^>^ customers
)
```

#### Parameters

  - customers  
    Type: [System.Collections.Generic.IEnumerable](https://technet.microsoft.com/library/9eekhta0\(v=ax.60\))\<[GlobalCustomer](globalcustomer-class-microsoft-dynamics-commerce-runtime-datamodel.md)\>  

## See Also

#### Reference

[CustomersSearchResponse Class](customerssearchresponse-class-microsoft-dynamics-commerce-runtime-messages.md)

[CustomersSearchResponse Overload](customerssearchresponse-constructor-microsoft-dynamics-commerce-runtime-messages.md)

[Microsoft.Dynamics.Commerce.Runtime.Messages Namespace](microsoft-dynamics-commerce-runtime-messages-namespace.md)

