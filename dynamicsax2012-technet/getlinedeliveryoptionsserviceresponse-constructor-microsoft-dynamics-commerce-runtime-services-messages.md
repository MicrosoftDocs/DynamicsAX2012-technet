---
title: GetLineDeliveryOptionsServiceResponse Constructor  (Microsoft.Dynamics.Commerce.Runtime.Services.Messages)
TOCTitle: GetLineDeliveryOptionsServiceResponse Constructor
ms:assetid: M:Microsoft.Dynamics.Commerce.Runtime.Services.Messages.GetLineDeliveryOptionsServiceResponse.#ctor(System.Collections.Generic.IEnumerable{Microsoft.Dynamics.Commerce.Runtime.DataModel.SalesLineDeliveryOption})
ms:mtpsurl: https://technet.microsoft.com/en-us/library/microsoft.dynamics.commerce.runtime.services.messages.getlinedeliveryoptionsserviceresponse.getlinedeliveryoptionsserviceresponse(v=AX.60)
ms:contentKeyID: 49836778
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.Services.Messages.GetLineDeliveryOptionsServiceResponse.#ctor
dev_langs:
- CSharp
- C++
- VB
---

# GetLineDeliveryOptionsServiceResponse Constructor

Initializes a new instance of the [GetLineDeliveryOptionsServiceResponse](getlinedeliveryoptionsserviceresponse-class-microsoft-dynamics-commerce-runtime-services-messages.md) class.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.Services.Messages](microsoft-dynamics-commerce-runtime-services-messages-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Services.Messages (in Microsoft.Dynamics.Commerce.Runtime.Services.Messages.dll)

## Syntax

``` vb
'Declaration
Public Sub New ( _
    salesLineDeliveryOption As IEnumerable(Of SalesLineDeliveryOption) _
)
'Usage
Dim salesLineDeliveryOption As IEnumerable(Of SalesLineDeliveryOption)

Dim instance As New GetLineDeliveryOptionsServiceResponse(salesLineDeliveryOption)
```

``` csharp
public GetLineDeliveryOptionsServiceResponse(
    IEnumerable<SalesLineDeliveryOption> salesLineDeliveryOption
)
```

``` c++
public:
GetLineDeliveryOptionsServiceResponse(
    IEnumerable<SalesLineDeliveryOption^>^ salesLineDeliveryOption
)
```

#### Parameters

  - salesLineDeliveryOption  
    Type: [System.Collections.Generic.IEnumerable](https://technet.microsoft.com/en-us/library/9eekhta0\(v=ax.60\))\<[SalesLineDeliveryOption](saleslinedeliveryoption-class-microsoft-dynamics-commerce-runtime-datamodel.md)\>  

## See Also

#### Reference

[GetLineDeliveryOptionsServiceResponse Class](getlinedeliveryoptionsserviceresponse-class-microsoft-dynamics-commerce-runtime-services-messages.md)

[Microsoft.Dynamics.Commerce.Runtime.Services.Messages Namespace](microsoft-dynamics-commerce-runtime-services-messages-namespace.md)

