---
title: GetLineDeliveryOptionsResponse Constructor (IEnumerable(SalesLineDeliveryOption)) (Microsoft.Dynamics.Commerce.Runtime.Messages)
TOCTitle: GetLineDeliveryOptionsResponse Constructor (IEnumerable(SalesLineDeliveryOption))
ms:assetid: M:Microsoft.Dynamics.Commerce.Runtime.Messages.GetLineDeliveryOptionsResponse.#ctor(System.Collections.Generic.IEnumerable{Microsoft.Dynamics.Commerce.Runtime.DataModel.SalesLineDeliveryOption})
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.messages.getlinedeliveryoptionsresponse.getlinedeliveryoptionsresponse(v=AX.60)
ms:contentKeyID: 62212825
author: tonyafehr
ms.date: 05/18/2015
mtps_version: v=AX.60
dev_langs:
- vb
- csharp
- c++
---

# GetLineDeliveryOptionsResponse Constructor (IEnumerable(SalesLineDeliveryOption))


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Initializes a new instance of the [GetLineDeliveryOptionsResponse](getlinedeliveryoptionsresponse-class-microsoft-dynamics-commerce-runtime-messages.md) class.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.Messages](microsoft-dynamics-commerce-runtime-messages-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Messages (in Microsoft.Dynamics.Commerce.Runtime.Messages.dll)

## Syntax

``` vb
'Declaration
Public Sub New ( _
    salesLineDeliveryOptions As IEnumerable(Of SalesLineDeliveryOption) _
)
'Usage
Dim salesLineDeliveryOptions As IEnumerable(Of SalesLineDeliveryOption)

Dim instance As New GetLineDeliveryOptionsResponse(salesLineDeliveryOptions)
```

``` csharp
public GetLineDeliveryOptionsResponse(
    IEnumerable<SalesLineDeliveryOption> salesLineDeliveryOptions
)
```

``` c++
public:
GetLineDeliveryOptionsResponse(
    IEnumerable<SalesLineDeliveryOption^>^ salesLineDeliveryOptions
)
```

#### Parameters

  - salesLineDeliveryOptions  
    Type: [System.Collections.Generic.IEnumerable](https://technet.microsoft.com/library/9eekhta0\(v=ax.60\))\<[SalesLineDeliveryOption](saleslinedeliveryoption-class-microsoft-dynamics-commerce-runtime-datamodel.md)\>  

## See Also

#### Reference

[GetLineDeliveryOptionsResponse Class](getlinedeliveryoptionsresponse-class-microsoft-dynamics-commerce-runtime-messages.md)

[GetLineDeliveryOptionsResponse Overload](getlinedeliveryoptionsresponse-constructor-microsoft-dynamics-commerce-runtime-messages.md)

[Microsoft.Dynamics.Commerce.Runtime.Messages Namespace](microsoft-dynamics-commerce-runtime-messages-namespace.md)

