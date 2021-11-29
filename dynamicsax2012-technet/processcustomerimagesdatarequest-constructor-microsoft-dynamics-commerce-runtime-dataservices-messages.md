---
title: ProcessCustomerImagesDataRequest Constructor  (Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages)
TOCTitle: ProcessCustomerImagesDataRequest Constructor
ms:assetid: M:Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages.ProcessCustomerImagesDataRequest.#ctor(System.Collections.Generic.ICollection{Microsoft.Dynamics.Commerce.Runtime.DataModel.Customer})
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.dataservices.messages.processcustomerimagesdatarequest.processcustomerimagesdatarequest(v=AX.60)
ms:contentKeyID: 65321532
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages.ProcessCustomerImagesDataRequest.#ctor
dev_langs:
- CSharp
- C++
- VB
---

# ProcessCustomerImagesDataRequest Constructor


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Initializes a new instance of the [ProcessCustomerImagesDataRequest](processcustomerimagesdatarequest-class-microsoft-dynamics-commerce-runtime-dataservices-messages.md) class.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages](microsoft-dynamics-commerce-runtime-dataservices-messages-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages (in Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages.dll)

## Syntax

``` vb
'Declaration
Public Sub New ( _
    customers As ICollection(Of Customer) _
)
'Usage
Dim customers As ICollection(Of Customer)

Dim instance As New ProcessCustomerImagesDataRequest(customers)
```

``` csharp
public ProcessCustomerImagesDataRequest(
    ICollection<Customer> customers
)
```

``` c++
public:
ProcessCustomerImagesDataRequest(
    ICollection<Customer^>^ customers
)
```

#### Parameters

  - customers  
    Type: [System.Collections.Generic.ICollection](https://technet.microsoft.com/library/92t2ye13\(v=ax.60\))\<[Customer](customer-class-microsoft-dynamics-commerce-runtime-datamodel.md)\>  

## See Also

#### Reference

[ProcessCustomerImagesDataRequest Class](processcustomerimagesdatarequest-class-microsoft-dynamics-commerce-runtime-dataservices-messages.md)

[Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages Namespace](microsoft-dynamics-commerce-runtime-dataservices-messages-namespace.md)

