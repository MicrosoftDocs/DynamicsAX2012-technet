---
title: GetExternalShippingRateServiceRequest Constructor  (Microsoft.Dynamics.Commerce.Runtime.Services.Messages)
TOCTitle: GetExternalShippingRateServiceRequest Constructor
ms:assetid: M:Microsoft.Dynamics.Commerce.Runtime.Services.Messages.GetExternalShippingRateServiceRequest.#ctor(System.Collections.Generic.IEnumerable{Microsoft.Dynamics.Commerce.Runtime.DataModel.SalesLine})
ms:mtpsurl: https://technet.microsoft.com/en-us/library/microsoft.dynamics.commerce.runtime.services.messages.getexternalshippingrateservicerequest.getexternalshippingrateservicerequest(v=AX.60)
ms:contentKeyID: 65318946
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.Services.Messages.GetExternalShippingRateServiceRequest.#ctor
dev_langs:
- CSharp
- C++
- VB
---

# GetExternalShippingRateServiceRequest Constructor

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.Services.Messages](microsoft-dynamics-commerce-runtime-services-messages-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Services.Messages (in Microsoft.Dynamics.Commerce.Runtime.Services.Messages.dll)

## Syntax

``` vb
'Declaration
Public Sub New ( _
    salesLines As IEnumerable(Of SalesLine) _
)
'Usage
Dim salesLines As IEnumerable(Of SalesLine)

Dim instance As New GetExternalShippingRateServiceRequest(salesLines)
```

``` csharp
public GetExternalShippingRateServiceRequest(
    IEnumerable<SalesLine> salesLines
)
```

``` c++
public:
GetExternalShippingRateServiceRequest(
    IEnumerable<SalesLine^>^ salesLines
)
```

#### Parameters

  - salesLines  
    Type: [System.Collections.Generic.IEnumerable](https://technet.microsoft.com/en-us/library/9eekhta0\(v=ax.60\))\<[SalesLine](salesline-class-microsoft-dynamics-commerce-runtime-datamodel.md)\>  

## See Also

#### Reference

[GetExternalShippingRateServiceRequest Class](getexternalshippingrateservicerequest-class-microsoft-dynamics-commerce-runtime-services-messages.md)

[Microsoft.Dynamics.Commerce.Runtime.Services.Messages Namespace](microsoft-dynamics-commerce-runtime-services-messages-namespace.md)

