---
title: GetInvoiceServiceResponse Constructor  (Microsoft.Dynamics.Commerce.Runtime.Services.Messages)
TOCTitle: GetInvoiceServiceResponse Constructor
ms:assetid: M:Microsoft.Dynamics.Commerce.Runtime.Services.Messages.GetInvoiceServiceResponse.#ctor(System.Collections.Generic.IEnumerable{Microsoft.Dynamics.Commerce.Runtime.DataModel.SalesInvoice},Microsoft.Dynamics.Commerce.Runtime.DataModel.SalesOrder)
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.services.messages.getinvoiceserviceresponse.getinvoiceserviceresponse(v=AX.60)
ms:contentKeyID: 62209732
author: tonyafehr
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.Services.Messages.GetInvoiceServiceResponse.#ctor
dev_langs:
- CSharp
- C++
- VB
---

# GetInvoiceServiceResponse Constructor


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Initializes a new instance of the [GetInvoiceServiceResponse](getinvoiceserviceresponse-class-microsoft-dynamics-commerce-runtime-services-messages.md) class.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.Services.Messages](microsoft-dynamics-commerce-runtime-services-messages-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Services.Messages (in Microsoft.Dynamics.Commerce.Runtime.Services.Messages.dll)

## Syntax

``` vb
'Declaration
Public Sub New ( _
    invoices As IEnumerable(Of SalesInvoice), _
    order As SalesOrder _
)
'Usage
Dim invoices As IEnumerable(Of SalesInvoice)
Dim order As SalesOrder

Dim instance As New GetInvoiceServiceResponse(invoices, _
    order)
```

``` csharp
public GetInvoiceServiceResponse(
    IEnumerable<SalesInvoice> invoices,
    SalesOrder order
)
```

``` c++
public:
GetInvoiceServiceResponse(
    IEnumerable<SalesInvoice^>^ invoices, 
    SalesOrder^ order
)
```

#### Parameters

  - invoices  
    Type: [System.Collections.Generic.IEnumerable](https://technet.microsoft.com/library/9eekhta0\(v=ax.60\))\<[SalesInvoice](salesinvoice-class-microsoft-dynamics-commerce-runtime-datamodel.md)\>  

<!-- end list -->

  - order  
    Type: [Microsoft.Dynamics.Commerce.Runtime.DataModel.SalesOrder](salesorder-class-microsoft-dynamics-commerce-runtime-datamodel.md)  

## See Also

#### Reference

[GetInvoiceServiceResponse Class](getinvoiceserviceresponse-class-microsoft-dynamics-commerce-runtime-services-messages.md)

[Microsoft.Dynamics.Commerce.Runtime.Services.Messages Namespace](microsoft-dynamics-commerce-runtime-services-messages-namespace.md)

